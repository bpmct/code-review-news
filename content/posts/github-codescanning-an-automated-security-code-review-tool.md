---
title: "GitHub CodeScanning: an automated security code review tool"
subtitle: At GitHub Satellite 2020, GitHub announces their new CodeScanning tool
category:
  - Code Review Tools
author: Ben Potter
date: 2020-05-06T16:40:50.867Z
featureImage: /uploads/chrome_0v3lrsxixo.png
---
Today at GitHub Satellite, the GitHub team announces **CodeScanning**, a code analysis tool that runs on GitHub actions.

CodeScanning works on any code analysis engine, but the demo used CodeQL, GitHub's own security analysis tool. After setting up the action, CodeScanning will run on any push to a configured branch, and will notify developers of any security vulnerabilities in PRs or pushes. It even has the the ability to follow user flows in order to ensure user inputs are sanitized before added to a database.

CodeScanning will be also be FREE for open source projects!

![CodeScanning Example Screenshot](/uploads/chrome_p6e2Ntcp6d.png)

[Watch the video on GitHub Satellite.](https://githubsatellite.com/)