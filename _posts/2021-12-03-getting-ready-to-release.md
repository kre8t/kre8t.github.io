---
layout: post
title: Almost ready to release V 1.0 of Github-UiKit
date: 2021-12-03 10:32:13 -0700
tags:
- github-uikit
- github
- cms
- blog
- jekyll

---
Github-UiKit is available as a [Jekyll theme gem](https://jekyllrb.com/docs/themes/). It has been built with Github Pages in mind. Installing should be fairly simple.

<!--more-->

## Installing the Theme

If you're running Jekyll v3.5+ and self-hosting you can quickly install the theme as a Ruby gem.

**ProTip:** Be sure to remove the folders and files that you don't need. These folders contain documentation and test pages for the theme and you probably don't want them littering up your repo.
{: .uk-alert .uk-padding-small}

### Ruby Gem Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "github-uikit"
```

Add this line to your Jekyll site's `_config.yml` file:

```yaml
theme: github-uikit
```

Then run Bundler to install the theme gem and dependencies:

```bash
bundle install
```

***

Choose from one of the following methods to install into your local drive.

\# Clone the Github repository

First enter the following into your CLI.

\`\`\`

git clone [https://github.com/isaacjosephhorton/github-uikit.git](https://github.com/isaacjosephhorton/github-uikit.git "https://github.com/isaacjosephhorton/github-uikit.git")

\`\`\`

Edit the config file in the root directory to match your site's configuration.

run this command to build the files into the \\_site directory:

\`\`\`

bundle install

\`\`\`

Test the site locally with this command:

\`\`\`

bundle exec jekyll serve

\`\`\`

push the finished site to a github repository

\`\`\`

git push -u origin master

\`\`\`

\# Set up navigation

Navigation titles and links are set in the \\_data/navigation.yml file.

\# Built-in page layouts

You can define different layouts and includes as you see fit.

Use one of the 5 following page layouts or design your own.

\* page

\* over

\* default

\* component

\* home

Built in \[UiKit\]([https://getuikit.com/](https://getuikit.com/ "https://getuikit.com/")){:target="_ blank"}, with an elegant homepage, blog and archive pages. Build a simple and beautiful website or blog in a few hours or less.

\[!\[GitHub forks\]([https://img.shields.io/github/forks/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Fork](https://img.shields.io/github/forks/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Fork "https://img.shields.io/github/forks/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Fork"))\]([https://github.com/isaacjosephhorton/github-uikit/fork/](https://github.com/isaacjosephhorton/github-uikit/fork/ "https://github.com/isaacjosephhorton/github-uikit/fork/"))

\[!\[GitHub stars\]([https://img.shields.io/github/stars/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Stars](https://img.shields.io/github/stars/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Stars "https://img.shields.io/github/stars/isaacjosephhorton/github-uikit.svg?style=for-the-badge&label=Stars"))\]([https://github.com/isaacjosephhorton/github-uikit/stargazers](https://github.com/isaacjosephhorton/github-uikit/stargazers "https://github.com/isaacjosephhorton/github-uikit/stargazers"))

\[!\[GitHub last commit\]([https://img.shields.io/github/last-commit/isaacjosephhorton/github-uikit.svg?style=for-the-badge](https://img.shields.io/github/last-commit/isaacjosephhorton/github-uikit.svg?style=for-the-badge "https://img.shields.io/github/last-commit/isaacjosephhorton/github-uikit.svg?style=for-the-badge"))\]([https://github.com/isaacjosephhorton/github-uikit/commits/master](https://github.com/isaacjosephhorton/github-uikit/commits/master "https://github.com/isaacjosephhorton/github-uikit/commits/master"))

\[!\[GitHub issues\]([https://img.shields.io/github/issues-raw/isaacjosephhorton/github-uikit.svg?style=for-the-badge](https://img.shields.io/github/issues-raw/isaacjosephhorton/github-uikit.svg?style=for-the-badge "https://img.shields.io/github/issues-raw/isaacjosephhorton/github-uikit.svg?style=for-the-badge"))\]([https://github.com/isaacjosephhorton/github-uikit/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc](https://github.com/isaacjosephhorton/github-uikit/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc "https://github.com/isaacjosephhorton/github-uikit/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc"))

\[!\[Gem\]([https://img.shields.io/gem/dt/github-uikit?label=Gem&style=for-the-badge](https://img.shields.io/gem/dt/github-uikit?label=Gem&style=for-the-badge "https://img.shields.io/gem/dt/github-uikit?label=Gem&style=for-the-badge"))\]([https://rubygems.org/gems/github-uikit](https://rubygems.org/gems/github-uikit "https://rubygems.org/gems/github-uikit"))

\[!\[GitHub contributors\]([https://img.shields.io/github/contributors/isaacjosephhorton/github-uikit.svg?style=for-the-badge](https://img.shields.io/github/contributors/isaacjosephhorton/github-uikit.svg?style=for-the-badge "https://img.shields.io/github/contributors/isaacjosephhorton/github-uikit.svg?style=for-the-badge"))\]([https://github.com/isaacjosephhorton/github-uikit/graphs/contributors](https://github.com/isaacjosephhorton/github-uikit/graphs/contributors "https://github.com/isaacjosephhorton/github-uikit/graphs/contributors"))

\[!\[Open Source Helpers\]([https://www.codetriage.com/isaacjosephhorton/github-uikit/badges/users.svg](https://www.codetriage.com/isaacjosephhorton/github-uikit/badges/users.svg "https://www.codetriage.com/isaacjosephhorton/github-uikit/badges/users.svg"))\]([https://www.codetriage.com/isaacjosephhorton/github-uikit](https://www.codetriage.com/isaacjosephhorton/github-uikit "https://www.codetriage.com/isaacjosephhorton/github-uikit"))