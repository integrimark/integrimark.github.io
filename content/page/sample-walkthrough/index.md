---
title: "Getting Started with IntegriMark"
description: "Walking through an example repository to understand how to setup IntegriMark."
draft: false
tags: ["Featured"]
images: []
# keywords: ["markdown cheat sheet","markdown","cheat sheet", "markdown cheatsheet", "hugo markdown cheat sheet", "goldmark"]
# aliases:
#   - blog/my-third-blog-post
---

# Getting Started with IntegriMark

In this guide, we will walk through an example repository to understand how to setup IntegriMark using [the `integrimark-publish-action` GitHub Action](https://github.com/integrimark/integrimark-publish-action).

Recall that IntegriMark can be run in two different ways:

- Either it can be run manually on a local computer (following the instructions on the [IntegriMark GitHub repository](https://github.com/integrimark/integrimark/)).
  - In this scenario, the `integrimark` command line tool is used to generate the HTML "bundle" files and the `passwords.json` locally, and the bundle can then be published to GitHub Pages.

- Or it can be run automatically from a repository using continuous integration and the `integrimark-publish-action` GitHub Action.
  - In this scenario, all files are uploaded to a private repository, and the `integrimark-publish-action` GitHub Action continuously updates the `passwords.json` file to the private repository, and publishes the HTML "bundle" files to GitHub Pages.

In this guide we will be using the second scenario, and we will walk through the steps to set up a repository to use the `integrimark-publish-action` GitHub Action.

## Step 1: Create a new repository


![Screenshot of the sample](sshot1-integrimark-worflow.png)

![Screenshot of the sample](sshot2-github-token-permissions.png)

![Screenshot of the sample](sshot3-github-pages-deployment.png)

![Screenshot of the sample](sshot4-integrimark-passwords_json.png)

![Screenshot of the sample](sshot5-sample-mailing.png)
