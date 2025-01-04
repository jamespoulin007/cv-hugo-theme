# CV-HUGO-THEME

<!-- [![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fjamespoulin007%2Fcv-hugo-theme%2Fbadge%3Fref%3Dmain&style=flat)](https://actions-badge.atrox.dev/jamespoulin007/cv-hugo-theme/goto?ref=main)
![Repository Size](https://img.shields.io/github/repo-size/jamespoulin007/cv-hugo-theme)
![Lines of Codes](https://img.shields.io/tokei/lines/github.com/jamespoulin007/cv-hugo-theme)
![Contributor](https://img.shields.io/github/contributors/jamespoulin007/cv-hugo-theme)
![Latest Release](https://img.shields.io/github/v/release/jamespoulin007/cv-hugo-theme?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/jamespoulin007/cv-hugo-theme)
![Open Issues](https://img.shields.io/github/issues/jamespoulin007/cv-hugo-theme?color=important)
![Open Pull Requests](https://img.shields.io/github/issues-pr/jamespoulin007/cv-hugo-theme?color=yellowgreen)
![License](https://img.shields.io/github/license/jamespoulin007/cv-hugo-theme)
![Security Headers](https://img.shields.io/security-headers?url=https%3A%2F%2Fjamespoulin007.github.io%2F) -->

A [Hugo](https://gohugo.io/) theme for a personal portfolio with minimalist design and responsiveness.

![Thumbnail](https://raw.githubusercontent.com/jamespoulin007/cv-hugo-theme/refs/heads/main/images/screenshot.png)

## Features

- Minimalist Design
- Fully Responsive
- Multiple Language Support
- Carefully Designed Cards
- Experience Timeline
- Achievement Gallery
- Sidebar to Categorize the Posts
- Short Codes
- Analytics Support
  - GoatCounter
  - counter.dev
  - Google Analytics
  - Matomo/Piwik
  - [Umami](https://umami.is/)
- Comment Support
  - [Disqus](https://disqus.com/)
  - [Valine](https://valine.js.org/)
  - [Uttarances](https://utteranc.es/)
  - [Giscus](https://giscus.app/)


## Requirements

- Hugo Version 0.128.0 (extended) or higher
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later.

## Usage

The easiest way to use this theme is to fork [jamespoulin007.github.io](https://github.com/jamespoulin007/jamespoulin007.github.io) sample repo. Then change the configurations according to your need.

If you want to start from scratch, then follow these steps:

##### 1. Initialize Hugo module on you repo

At first, initialize [Hugo modules](https://gohugo.io/hugo-modules/) in your repo. This will create a `go.mod` file.

```bash
hugo mod init github.com/<your username>/<your repo name>
```

##### 2. Add this theme as your module dependency

Now, in your `hugo.yaml` file, add a `module` section.

```yaml
# Use Hugo modules to add theme
module:
  imports:
  - path: github.com/jamespoulin007/cv-hugo-theme/v4
```

Check this sample [hugo.yaml](https://github.com/jamespoulin007/jamespoulin007.github.io/blob/main/hugo.yaml) for further reference.

##### 3. Update your module

Now, run this command to load this theme as your module.

```bash
hugo mod tidy
```

#### Running Locally

Now, you can run your hugo site locally with the following steps:

##### 1. Generate node dependency configuration

Now run the following command to generate node dependency configuration. This will create the a `package.json` file in you repo.

```bash
hugo mod npm pack
```

##### 2. Install dependencies

Install the node dependencies using following command:
```bash
npm install
```

##### 3. Run your site

Now, run you site locally using following command.

```bash
hugo server -w
```

When you run your site for first time, it will start with the default parameters. It should look similar to the [example site](https://jamespoulin007.github.io). However, it will not have any sections in the homepage as we haven't configured them yet. You can configure your site by following the guides from [here](https://cv-hugo-theme-guides.netlify.app/posts/configuration/).

## Shortcodes

Here, are some handy shortcodes you can use with this theme.

- [Alert](https://cv-hugo-theme-guides.netlify.app/posts/shortcodes/#alert)
- [Image](https://cv-hugo-theme-guides.netlify.app/posts/shortcodes/#image)
- [Split](https://cv-hugo-theme-guides.netlify.app/posts/shortcodes/#split)
- [Vertical Space](https://cv-hugo-theme-guides.netlify.app/posts/shortcodes/#vertical-space)
- [Video](https://cv-hugo-theme-guides.netlify.app/posts/shortcodes/#video)
- [Mermaid](https://jamespoulin007.github.io/posts/shortcodes/#mermaid)

