# Contributing to the Antti Kivi’s Projects

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

There are many ways in which you can contribute to Antti Kivi’s projects, beyond writing code. The goal of this document is to provide a high-level overview of how you can get involved.

The following is a set of guidelines for contributing to the projects. These are mostly guidelines, not rules. Use your best judgment and feel free to propose changes to this document in a pull request.

#### Table of Contents

[Code of Conduct](#code-of-conduct)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Style Guides](#style-guides)
  * [Git Commit Messages](#git-commit-messages)

## Code of Conduct

Antti Kivi’s projects and everyone participating in them are governed by the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you’re expected to uphold this code. Please report unacceptable behaviour to antti.kivi@visiosto.fi.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for a project. Following these guidelines helps the maintainers and the community understand your report :pencil:, reproduce the behaviour :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don’t need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](.github/ISSUE_TEMPLATE/bug_report.md) because the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it’s the same thing that you’re experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting a Bug Report

* **Check the [debugging guide](#).** You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem in the latest version of the project in question. <!-- TODO There is no debugging guide -->
* **Check the [FAQ](#)** for a list of common questions and problems. <!-- TODO There is no FAQ -->
* **Perform a [cursory search](https://github.com/issues?q=is%3Aissue+user%anttikivi)** to see if the problem has already been reported. If it has and the issue is still open, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit a (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues). Just create an issue on the repository and provide the following information by filling in [the template](.github/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include additional details to help the maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started the project, e.g. which command exactly you used in the terminal or how you started the project otherwise. When listing steps, **don’t just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or a command, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copiable snippets, which you use in those examples. If you’re providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics#multiple-lines).
* **Describe the behaviour you observed after following the steps** and point out what exactly is the problem with that behaviour.
* **Explain which behaviour you expected to see instead and why.**
* **Include screenshots, animated GIFs, and video captures** which show you following the described steps and demonstrate the problem. You can use [this tool](http://www.cockos.com/licecap) to record GIFs on macOS and Windows and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux. <!-- TODO include instructions for including the input recording here. -->
* **If you’re reporting that the project crashed**, include a crash report from the operating system. On macOS, the crash report will be available in `Console.app` under ‘Diagnostic and usage information’ > ‘User diagnostic reports’. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests), or put it in a [gist](https://gist.github.com) and provide a link to that gist.
* **If the problem is related to performance or memory**, include a [CPU profile capture](#) with your report. <!-- TODO Include link -->
* **If the problem wasn’t triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of the project) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of the project?** What’s the most recent version in which the problem doesn’t happen? You can download older versions of the projects from their Releases pages on GitHub.
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of the project are you using?** You can get the exact version of some projects by running `project -v` in your terminal where `project` is the name of the project.
* **What’s the name and version of the OS you’re using**?
* **Are you running the project in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
* **Which keyboard layout are you using?** Are you using a US layout or some other layout?
<!-- TODO Add information about Node, Python, or some other environment and their versions -->

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for a project, including completely new features and minor improvements to existing functionality. Following these guidelines helps the maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don’t need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](.github/ISSUE_TEMPLATE/feature_request.md), including the steps that you imagine you would take if the feature you’re requesting existed.

#### Before Submitting an Enhancement Suggestion

* **Check the [debugging guide](#)** for tips — you might discover that the enhancement is already available. Most importantly, check if you’re using the latest version of the project and if you can get the desired behaviour by changing the settings of the project. <!-- TODO There is no debugging guide -->
* **Perform a [cursory search](https://github.com/issues?q=is%3Aissue+user%anttikivi)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit a (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues). Just create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copiable snippets which you use in those examples as [Markdown code blocks](https://help.github.com/articles/markdown-basics#multiple-lines).
* **Describe the current behaviour** and **explain which behaviour you expected to see instead** and why.
* **Include screenshots, animated GIFs, and video captures** which help you demonstrate the steps or point out the part of the project which the suggestion is related to. You can use [this tool](http://www.cockos.com/licecap) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux. <!-- TODO include instructions for including the input recording here. -->
* **Specify which version of the project you’re using.** You can get the exact version of some projects by running `project -v` in your terminal where `project` is the name of the project.
* **Specify the name and version of the OS you’re using.**

### Your First Code Contribution

Unsure where to begin contributing to the projects? You can start by looking through these `good first issue` and `help wanted` issues:

* [`good first issue`][good-first-issue]: issues which should only require a few lines of code and a test or two.
* [`help wanted`][help-wanted]: issues which should be a bit more involved than `good first issue` issues.

Both issue lists are sorted by the total number of comments. While not perfect, the number of comments is a reasonable proxy for the impact a given change will have.

### Pull Requests

Please follow these steps to have your contribution considered by the maintainers:

1. Follow the instructions in the [pull request template](PULL_REQUEST_TEMPLATE.md).
2. Follow the [style guides](#style-guides).
3. After you submit your pull request, verify that all [status checks](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-status-checks) are passing.

    <details><summary>What if the status checks are failing?</summary>If a status check is failing and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied before having your pull request reviewed, the reviewers may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Style Guides

### Git Commit Messages

Git commit messages adhere to [Conventional Commits](https://conventionalcommits.org). In addition to the Conventional Commits specification, please

* Use the present tense (‘Add feature’, not ‘Added feature’).
* Use the imperative mood (‘Move cursor to...’ not ‘Moves cursor to...’).
* Try to limit the first line to 72 characters or fewer.
* Reference issues and pull requests liberally in the commit footer.

[good-first-issue]:https://github.com/search?q=is%3Aopen+is%3Aissue+label%3Agood+first+issue+user%anttikivi+sort%3Acomments-desc
[help-wanted]:https://github.com/search?q=is%3Aopen+is%3Aissue+label%3Ahelp+wanted+user%anttikivi+sort%3Acomments-desc
