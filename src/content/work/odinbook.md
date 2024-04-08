---
title: OdinBook
publishDate: 2023-03-02 8:00:00
img: /assets/work/odinbook.png
img_alt: Posts on OdinBook
description: |
  Circa 2010 Facebook clone built using Ruby on Rails
tags:
  - Ruby on Rails
  - PostgreSQL
  - Render
  - Hotwire
  - RSpec
url: https://github.com/jp524/odinbook
---

### Overview

Web app clone of circa 2010 Facebook. Authenticated users can write posts, add comments and like posts. Users can also personalize their profile with personal information and a picture.

Users chose to accept or decline friend requests they receive in the notification section of the navigation bar. Once friendships are established users can see each other's posts.

### Features

- Responsive single page application built using Hotwire (Turbo + Stimulus)
- System testing for all features using RSpec and Capybara
- Mobile and desktop styling using Sass and BEM methodology
- Application deployed to Render, with PostgreSQL cloud database and Cloudinary cloud storage
- Authentication of users using Devise