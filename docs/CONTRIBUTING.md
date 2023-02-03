# Contributing to Sphynx SDK

> Please read these guidelines before submitting an issue, filing a feature request, or contributing code.

## :question: Got a Question?

If you have a question about using sphynx SDK, please use the [mailing list](https://groups.google.com/group/jam-commerce), [StackOverflow](https://stackoverflow.com), or ask the friendly people in our [chat room](https://gitter.im/jam-commerce/sphynx).

## :bug: I Found a Bug

Sorry! It happens to the best of us. If you've found a bug in sphynx SDK, **please [search](https://github.com/jam-commerce/sphynx/issues/) to see if it's already been reported**. Otherwise, create a [new issue](https://github.com/jam-commerce/sphynx/issues/new). If you can fix the bug yourself, feel free to create a [pull request](#propose-a-change) thereafter.

Please include _as much detail as possible_ to help us reproduce and diagnose the bug. Most importantly:

- Include your test code or file(s). If large, please provide a link to a repository or [gist](https://gist.github.com).
- Please show code in JavaScript only (any version)

If we need more information from you, we'll let you know. If you don't within a reasonable time frame (TBD), your issue will be automatically closed for inactivity.

## :exclamation: Propose a Change

Before you get your hands dirty, please [search](https://github.com/jam-commerce/sphynx/issues/) for a related issue, or [create a new one](https://github.com/jam-commerce/sphynx/issues/new). If you wish to contribute a new feature, this is doubly important! Let's discuss your proposed changes first; we don't want you to waste time implementing a change that is at odds with the project's direction. That said, we'll happily consider any contribution, no matter how great or small.

_This paragraph would contain information about sphynx SDK roadmap, but it doesn't yet exist._ :poop:

It's also important to understand some overarching goals of sphynx SDK, detailed below.

### :soccer: About Project Goals

### :shoe: Contributing Code: Step-by-Step

Follow these steps to get going. If you are having trouble, don't be afraid to [ask for help](#got-a-question).

> PRO TIP: After `npm install`, run `npm start` to start the API

1. [Install Node.js 16 LTS or newer with npm@7+](https://nodejs.org/en/download/).
   - If you're new to installing Node, a tool like [nvm](https://github.com/creationix/nvm#install-script) can help you manage multiple version installations.
   - You will need [Google Chrome](https://www.google.com/chrome/) to run browser-based tests locally.
1. Follow [Github's documentation](https://help.github.com/articles/fork-a-repo/) on setting up Git, forking and cloning.
1. Create a new branch in your working copy. Give your branch a descriptive name, such as `issue/12345`: `git checkout -b issue/12345`.
1. Execute `npm install` to install the development dependencies.
   - Do not use `yarn install`.
   - Some optional dependencies may fail; you can safely ignore these unless you are trying to build the documentation.
   - If you're sick of seeing the failures, run `npm install --ignore-scripts`.

Join us in the [contributors' chat](https://gitter.im/jam-commerce/contributors)!

## :angel: I Just Want To Help

_Excellent._ Here's how:
