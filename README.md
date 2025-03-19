# Home

This repository contains the source code for a static homepage built using [Hugo](https://gohugo.io/) and a personally forked version of the [Anatole theme](https://github.com/lxndrblz/anatole).

## Features

- **Hugo**: A fast and flexible static site generator.
- **Anatole Theme**: A minimalistic and elegant theme, customized to suit personal preferences.
- **Custom CSS**: Includes custom CSS for category colors and other small customizations.
- **Deployment Pipeline**: Automated deployment pipeline using GitHub workflows.

## Getting Started

### Prerequisites

- Install [Hugo](https://gohugo.io/getting-started/installing/) on your system.

### Setup

1. Clone this repository:

   ```bash
   git clone <repository-url>
   cd home
   ```

2. Initialize and update the submodule for the forked Anatole theme:

   ```bash
   git submodule update --init --recursive
   ```

3. Run the development server:

   ```bash
   hugo server
   ```

4. Open your browser and navigate to `http://localhost:1313` to view the homepage.

## Customization

The Anatole theme has been forked and customized for this project. You can find the forked theme in the `themes/anatole` directory. Additionally, custom CSS has been added for category colors and other small design tweaks. These styles can be found in the `assets/css` directory.

## Deployment

This project uses a GitHub workflow for automated deployment. On every push to the `main` branch, the workflow builds the site and deploys it to the configured hosting service.

To generate the static files manually for deployment, run:

```bash
hugo server
```

The generated files will be located in the `public` and `resources` directories.

## Acknowledgments

- [Hugo](https://gohugo.io/)
- [Anatole Theme](https://github.com/lxndrblz/anatole)
