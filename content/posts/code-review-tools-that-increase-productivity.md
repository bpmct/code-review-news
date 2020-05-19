---
title: Code review tools that increase productivity
subtitle: Code reviews can be quite time consuming, here are some tools that
  improve the process
category:
  - Code Review Tools
author: Ben Potter
date: 2020-05-17T21:20:40.947Z
featureImage: /uploads/aerial-photo-of-buildings-and-roads-681335.jpg
---
Code reviews are incredibly important for everything from ensuring application security to reducing technical debt. However, code reviews can be quite time consuming. By using tools, you can reduce toil and automate some manual tasks, speeding up development.


## Analytics
**Code review analytics** is a great place to start. By understanding how your current code reviews perform, you can make decisions to optimize your workflow. 
- ValueStream offers [GitHub PR analytics](https://medium.com/valuestream-by-operational-analytics-inc/valuestream-introducing-github-pull-request-metric-reports-a159e9bef754)
- GitLab recently added [code review analytics as well](https://codereviewnews.com/gitlabs-new-code-review-analytics-tool)
- [SourceLevel](https://sourcelevel.io/) offers PR analytics as well for gaining deeper insights

![Analytics photo](https://i.imgur.com/uI8Wukd.jpg)


## Security
Automated security code reviews can not only improve code review time, but also consistently search your code for known security bugs. This can save a lot of manual time while also ensuring that common bugs are not overlooked.
- GitHub just announced **[CodeScanning](https://codereviewnews.com/github-codescanning-an-automated-security-code-review-tool)**, an automated security code review tool that works for both pushes and PRs.
- [Codacy](https://www.codacy.com/), an automated code review tool, will search search for security flaws in your code.
- Synk.io recently releases a [free cheatsheet](https://codereviewnews.com/8-security-code-review-best-practices) that makes it easy to search for security flaws in code reviews.
- SoftwareSecured.com also has a great [security checklist](https://www.softwaresecured.com/secure-code-review-checklist/) for code reviews!

![Code security stock photo](https://i.imgur.com/3kIwzPR.jpg)

## Code quality/technical debt
Searching for duplicated code, unused functions, and overcomplex code can often be automated. These tools will save you time and do a lot of this for you:
- [Codacy](https://www.codacy.com/) does automated code quality reviews for PRs, including metrics to show how your code quality improves over time.
- [SourceGraph](https://about.sourcegraph.com/) makes it easier to visualize and understand your code in code review time. 
- DeepSource [(now free for private repos)](https://codereviewnews.com/deepsource-is-now-free-for-private-repositories) also offers automated security analysis on code reviews in Python and Go.

![Person coding dual monitors](https://i.imgur.com/HsIqEMN.jpg)

## Improve the manual review process
- [CodeSteam](https://codestream.com) makes it easy to request a code review at any point in the development cycle, right from your IDE.
- [Phabricator](https://www.phacility.com/phabricator/), Facebook's code review tool, adds a lot of features that GitHub PRs are lacking.
- SourceGraph's [GitHub Integration](https://about.sourcegraph.com/product/code-review/) is a bwoeser extension that adds enhanced discussion tools 
- [Github PRs for VS Code](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) makes it easy to "checkout" a PR in VS Code and leave comments.

---

🤔 Are we missing something? [Contact us](https://codereviewnews.com/about)

---

⚠ Disclaimer: I do contract social media work for CodeStream, which is included in this roundup.
