---
title: Github-UiKit Migrated to Miniml
date: 2021-12-03 09:32:13 -08:00
tags:
- github-uikit
- github
- cms
- blog
- jekyll
layout: post
bigimg: "/assets/img/uploads/blocks.png"
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
gem "miniml"
```

Add this line to your Jekyll site's `_config.yml` file:

```yaml
theme: miniml
```

Then run Bundler to install the theme gem and dependencies:

```bash
bundle install
```

***