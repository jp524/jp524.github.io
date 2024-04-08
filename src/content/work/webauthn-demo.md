---
title: WebAuthn Demo
publishDate: 2024-04-08 8:00:00
img: /assets/work/webauthn-demo.png
img_alt: Multi-factor login options for a user
description: |
  Login with multi-factor authentication using WebAuthn 
tags:
  - Ruby on Rails
  - SQLite
  - JavaScript
  - WebAuthn
url: https://github.com/jp524/webauthn-demo
---

### Overview

Demo app prepared a talk I gave at the [WNB.rb meetup](https://www.wnb-rb.dev/meetups) of March 2024.

This Ruby on Rails app demonstrates login with multi-factor authentication using WebAuthn.

It relies on the `webauthn` gem and the `@github/webauthn-json` package.

### Features

- Secure user accounts using WebAuthn authenticators such as security keys, iCloud keychain, fingerprint, etc.
- Lightweight custom authentication built using Rails 7.1
- Stimulus controllers for JavaScript
- Model and system tests using RSpec and Capybara
- Mobile and desktop styling using Sass and BEM methodology