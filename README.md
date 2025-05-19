# Hackboat 2025

This is the github repo for the [Hackboat website](https://hackboat.org) - the unconference that floats.

Join us for a one-day infosec unconference on a boat in Portland, OR on June 6th, 2025.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (version 2.5.0 or higher recommended)
- [RubyGems](https://rubygems.org/pages/download)
- [Bundler](https://bundler.io/)

## Installation

1. Clone this repository to your local machine

   ```bash
   git clone <repository-url>
   cd hackboat2025
   ```

2. Install the required gems

   ```bash
   bundle install
   ```

## Running Locally

To start the site locally:

```bash
bundle exec jekyll serve
```

This will start a local server, typically at `http://localhost:4000`. You can view the site by opening this URL in your web browser.

If you want to see draft posts and make the server watch for changes:

```bash
bundle exec jekyll serve --drafts --livereload
```

## Project Structure

- `_config.yml`: Configuration settings for the Jekyll site
- `_layouts/`: HTML templates for different page types
- `_sass/`: SCSS stylesheets
- `assets/`: Static files like images, CSS, and JavaScript
- `index.html`: The main landing page

## Making Changes

After making changes to the site:

1. Test your changes locally using the instructions above
2. Commit your changes to the repository
3. Create a pull request
