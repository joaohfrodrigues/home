+++
author = "João Fialho Rodrigues"
title = "Building this website: Previous iterations"
date = "2025-03-24"
description = "The story behind this site and how it was built"
tags = [
    "hugo", "website"
]
categories = ["development"]
series = ["building_this_website"]
toc = true
article = true
+++

This is first blog article of my personal website. My writing practice is not what it once was and that is part of what brings me here. I remember the good-old days of writing in SAPO Blogs, a portuguese Blog hosting platform, with my friends in grad school.

Later, while graduating, I thought it would be a good excuse to learn some front-end programming, but the overhead of keeping it updated and running was too high for me.

Recently I was scrolling on Reddit and found [Hugo](https://gohugo.io/), an open source and easy to set-up static website generator written in Go. I decided to give it a chance, and here we are.

The goals I set to myself to reach while building this space were defined since the beginning although the priority of each of them dynamically changed over time. We will go over those in this post, and also the previous iterations that led me here.

## Goals

- Professional showcase: My personal space should be a straightforward way of sharing my professional profile and achievements.
- Personalization: Keeping a personal space gives me freedom to define most aspects of the content and appearance, unlike most platforms. This aspect also allows me to share different aspects of my interests, including some of my personal hobbies.
- Learning: I could just pay to have a ready to go solution but this should be something that makes me learn along the way.
- Cost effectiveness: It shouldn't be expensive to keep up a personal page and costs should be reduced whenever they are not needed.

The version of the website you are seeing now is the fourth iteration of a process that started in 2017 while I was completing my MSc. in Electrical and Computer Engineering. The previous iterations are described in the following sub-sections, alongside its pros and cons.

## Previous iterations

### ReactJS

While completing my Masters degree I looked into [ReactJS](https://react.dev/) to create a CV simple website using GitHub pages. Trying React for the first time allowed me to get a glimpse of front-end development which was not part of my MSc. course.

The main advantage of the ReactJS solution was the high amount of personalization it provided. All aspects of the design were made by me, although choosing for a pre-built theme (not even then I had the courage to do something from 0% when it came to front-end development)

I also became frustratingly aware of all component dependencies and how difficult it was to add an additional page reference without breaking the remaining website content.

In the end, I decided it would be worthwhile to give up part of the personalization and flexibility and go with a more structured and pre-defined approach.

### Wordpress

Afterward I performed a full 180º turn and used Wordpress.com to host a personal blog on their free tier with a free wordpress.com domain. The upside was the incredible amount of features out of the box. However, everything was quite straightforward and for the purpose I wanted, having such a heavy backend was ultimately unnecessary to meet my goals. Additionally, a lot of personalization features of Wordpress are behind a subscription paywall.

*[Wordpress.com](https://wordpress.com/) multiple services and hosting on top of the open-sourced platform [Wordpress.org](https://wordpress.org/).*

I still consider Wordpress, either in its open-source form or the full-fledge feature heavy option from Wordpress.com to be a good option for a project of this sort, specially when one has to consider scalability and for other types of businesses.

### Notion

I have been using [Notion](https://www.notion.com/) with more or less recurrence for two years now, and its simple organization and powerful embedded databases seemed to me like great potential to be used as website pages. Notion supports hosting a website on top of some directory you have on your current space, but most features are behind a paywall, much like wordpress, and the Notion website by default is just like any Notion notebook, which becomes rather dull compared to other options.

I am sure that there are other interesting options to be used, I hope that these few examples can help the reader decide on the best approach.

## Current state

After starting an stopping this project, this is where it is now. I had again gone through a couple of hours of searching on Google, Reddit and now also ChatGPT and Gemini as my project buddies, and decided to go with Hugo as a static website builder, since I found the community to be active, the setup to be simple yet capable of much customization and its themes to be attractive, offering all the requirements I had listed before.

I will give a more in-depth overview of the current implementation of this website in a future post.
