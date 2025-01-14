# Contribution Guidelines

First of all, thanks for thinking of contributing to this project! 👏

Following these guidelines helps to communicate that you respect the time of the maintainer and developing this open
source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping
you finalize your pull requests.

This project has a [Contributor Covenant Code of Conduct](./CODE_OF_CONDUCT.md). By participating in this project you
agree to abide by its terms.

## ❤️ Ways to Contribute

- Blog or tweet about the project
- Improve documentation
- Fix a bug
- Implement a new feature
- Discuss potential ways to improve project
- Improve existing implementation, performance, etc.

## 🛎 Questions & Feature Requests

Feel free to [open a ticket](https://github.com/release-it/release-it/issues/new) with your question. Feature requests
are also welcome. Describe the feature, why you need it, and how it should work. Please provide as much detail and
context as possible.

## 🐛 File a Bug

In case you've encountered a bug, please make sure:

- You are using the [latest version](https://github.com/release-it/release-it/releases).
- You have read the [documentation](https://github.com/release-it/release-it/blob/master/README.md) first, and
  double-checked your configuration.
- You have acknowledged from [Troubleshooting & debugging](README.md#troubleshooting--debugging) the errors are likely a
  bug in this project, and not coming from e.g. your environment or custom scripts/commands.
- In your issue description, please include:
  - What you expected to see, and what happened instead.
  - Your operating system and other environment information.
  - As much information as possible, such as the command and configuration used.
  - Interesting logs from a verbose and/or debug run.
  - All steps to reproduce the issue.

## 🎁 Pull Requests

Pull requests are welcome! If you never created a pull request before, here are some tutorials:

- [Creating a pull request](https://help.github.com/articles/creating-a-pull-request/)
- [How to Contribute to an Open Source Project on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

Please keep the following in mind:

- To match the existing code styling, use `npm run format` before committing code.
- Make sure the tests pass (run `npm test`). Your changes probably deserve new tests as well.
- Remember that this project is cross-platform compatible (macOS, Windows, Linux), and that it runs in different
  versions of Node. On PR submission, a [GitHub Action](https://github.com/release-it/release-it/actions) will run the
  tests in multiple supported platforms and Node.js versions.

Unsure about whether you should open a pull request? Feel free to discuss it first in a ticket.

[Fork](https://help.github.com/articles/fork-a-repo/) the repository to get started, and set it up on your machine:

```bash
git clone https://github.com/<your-github-username>/release-it
cd release-it
npm install
```

Verify the tests are passing:

```bash
npm test
```

To use your modified version of release-it in your project, [npm-link](https://docs.npmjs.com/cli/link.html) it:

```bash
# From your release-it clone:
npm link

# From your project that uses release-it:
npm link release-it
```
