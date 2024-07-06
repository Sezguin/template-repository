# Contributing to Sezguin's template-repository

First off, cheers for considering contributing to this template-repository. Just don't mess it up and everything will be fine. Though there's no a lot going on here so I don't see how you could.

## Getting Started

- Make sure you have a [GitHub account](https://github.com/signup/free)
- Submit a ticket for your issue, assuming one does not already exist.
  - Clearly describe the issue including steps to reproduce when it is a bug.
  - Make sure you fill in the earliest version that you know has the issue.

## Making Changes

- Create a fork from where you want to base your work.
  - This is usually the main branch.
  - Only target release branches if you are certain your fix must be on that branch.
- Create a topic branch from where you want to base your work.
  - This is usually the main branch.
  - To quickly create a topic branch based on main; `git checkout -b fix/main/my_contribution main`.
  - Please avoid working directly on the `main` branch.
- Make commits of logical sizes, bigger isn't always better you know.
- Check for unnecessary whitespace with `git diff --check` before committing, otherwise Megalinter will shout at you.
- Make sure your commit messages are in the proper format - check some of my examples for references.

## Submitting Changes

- Push your changes to a topic branch in your fork of the repository.
- Submit a pull request to the repository in the organisation.
- The core team looks at Pull Requests on a regular basis.
- After feedback has been given we expect responses within two weeks. After two weeks we may close the pull request if it isn't showing any activity.

## Thank you for your contribution