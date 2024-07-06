# Template Repository by Sezguin

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## What's all this then?

This is a basic template repository I've put together to be used as a starting point for any other repositories I create. My idea is to have this as an initial template repo, from which other more specified template repositories can be created from (see [react-nextjs-template-repository](https://github.com/Sezguin/react-nextjs-template-repository)).

## What's included?

There's not a lot, just some basic formatting and housekeeping gubbins:

* A workflow for MegaLinter reviews on PR - see the `job-megalinter.yml` in the `.github/workflows` folder for more information.
* A catch-all `.gitignore` for the most common items.
* A default `dependabot.yml` to scan monthly for GitHub Action updates.
* A `cspell.json` file for repository dictionaries.
* A standard CONTRIBUTING and LICENSE (MIT).

### MegaLinter

MegaLinter is currently set up to run its default configuration containing many linters. You can customise the 'flavour' (set of linting tools) you'd like your project to have [here](https://megalinter.io/latest/flavors/).

This is recommended once you've chosen a particular type of project to start, as it takes its sweet time to run across your code base.

Currently it's also set up to lint when a PR has been opened to main - this can be configured to your liking in the workflow.

Finally, you'll need a Fine-Grained Personal Access Token for MegaLinter to use in order to be able to make changes to your repository. This token will sit under your account with a variable referencing the value within the repository you create from the template.

By default, it's called `MEGALINTER_PAT` and requires these permissions:
* **Read** access to metadata
* **Read** and **Write** access to code, pull requests and workflows

With repository access to the repo of choice.

That's about it! Please star the repository if it's useful to you in any way, and feel free to [contribute](https://github.com/Sezguin/template-repository/blob/main/CONTRIBUTING.md) or make [suggestions](https://github.com/Sezguin/template-repository/issues).

Have a swell day.