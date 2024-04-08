---
title: KnewHub (KnewPlay)
publishDate: 2024-04-08 9:00:00
img: /assets/work/knewplay-knewhub.png
img_alt: Viewing an article pulled from a GitHub repository
description: |
  Open-learning platform for STEM content
tags:
  - Ruby on Rails
  - PostgreSQL
  - Webhooks
  - GitHub API
  - DevOps
url: https://github.com/knewplay/knewhub
---

### Overview

KnewHub is an open-source project I built for a former employer. Knewhub is a full-stack Ruby on Rails application allowing authors to share content from their GitHub repositories.

Authors write articles using Markdown. They can also use custom syntax for KnewHub to display:
  - Code blocks from external code files or GitHub gists
  - Questions & answers
  - 3D files using Autodesk Viewer

The application is integrated with GitHub to automatically update content if an author's repository is updated. This is done through webhooks set up for the GitHub App integration.

I deployed the application on Google Cloud Platform and documented the process in a [deployment guide](https://github.com/knewplay/knewhub/blob/main/deployment-guide.md).

### Features

- Integration with GitHub through GitHub API and webhooks to automatically update course content from multiple repositories
- WebAuthn authentication standard to secure administrator accounts using physical security keys or face/fingerprint recognition
- Automated tests using RSpec, Capybara and factories for a total test coverage of 91%
- Application deployed using Google Cloud Compute Engine virtual machine and Cloud SQL Postgres database
- Configuration of Linux VM to manage Rails application and required services (Redis, Sidekiq, Caddy, Ops Agent)
