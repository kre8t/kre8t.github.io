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