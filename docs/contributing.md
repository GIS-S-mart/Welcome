# Welcome to the open science benchmarking platform contributing guide

In this guide you will get an overview of the contribution workflow from opening an issue, creating a pull request, reviewing, and merging the pull request.

## Resources

Here are some resources to help you get started with open source contributions:

- [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [Clone a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github)
- [Commit changes](https://docs.github.com/en/github/committing-changes-to-your-project)
- [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)
- [Create pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests)
- [Address merge conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts)
- [Write markdown files](https://guides.github.com/features/mastering-markdown/)

## How to create a new benchmark?

1. [Browse the existing set of benchmarks](https://github.com/GIS-S-mart)
2. If your purpose is not covered by existing benchmarks but you are not sure whether it is specific enough to motivate the invention of a new one, then post on the [discussions page of the organization team](https://github.com/orgs/GIS-S-mart/discussions) and briefly outline the new benchmark so as to enable subject-matter experts from the community to argue. Tag your issue with the label *new_benchmark*.
3. If your purpose is not covered by existing benchmarks and you are not sure that it is specific enough to motivate the invention of a new one, then create a new issue from the [issues page of the organization](https://github.com/GIS-S-mart/organization_team/issues) and briefly outline the new benchmark. Tag your issue with the label *new_benchmark*.
4. Create a new private repository to host your benchmark by navigating to the [repository template](https://github.com/GIS-S-mart/Benchmark-0_Template) and clicking on the button "Use this template".
5. Define the new benchmark and commit the changes once you are happy with them.
6. When you're finished with the changes, create a pull request (see below).
7. Your pull request is merged! Once your pull request is merged, your benchmark will be publicly visible.

## How to modify an existing benchmark?

- ### How to submit a new benchmark problem?

- ### How to submit a new comparison criterion?

- ### How to submit a new experimental protocol?

- ### How to submit a new solution?

## How start a discussion with organization members?

On the team's page, you can use team discussions for conversations that span across projects/repositories and don't belong to a specific issue or pull request. Instead of opening an issue in a repository to discuss an idea, you can include the entire organization team by having a conversation in a team discussion.

Any organization member can post on the team's page or participate in a public discussion. *Private* posts are only visible to team members and organization owners, and *public* posts are visible to all members of the organization.

### Issues

#### Create a new issue

If you spot a problem with the docs, [search if an issue already exists](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments). If a related issue doesn't exist, you can open a new issue using a relevant [issue form](https://github.com/github/docs/issues/new/choose). 

#### Solve an issue

Scan through our [existing issues](https://github.com/github/docs/issues) to find one that interests you. You can narrow down the search using `labels` as filters. See [Labels](/contributing/how-to-use-labels.md) for more information. As a general rule, we don’t assign issues to anyone. If you find an issue to work on, you are welcome to open a PR with a fix.

### Make Changes

#### Make changes in a codespace

For more information about using a codespace for working on GitHub documentation, see "[Working in a codespace](https://github.com/github/docs/blob/main/contributing/codespace.md)."

#### Make changes locally

1. [Install Git LFS](https://docs.github.com/en/github/managing-large-files/versioning-large-files/installing-git-large-file-storage).

2. Fork the repository.
- Using GitHub Desktop:
  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

- Using the command line:
  - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

3. Create a working branch and start with your changes!


### Commit your update

Commit the changes once you are happy with them. Don't forget to [self-review](/contributing/self-review.md) to speed up the review process:zap:.

### Pull Request

When you're finished with the changes, create a pull request, also known as a PR.
- Fill the "Ready for review" template so that we can review your PR. This template helps reviewers understand your changes as well as the purpose of your pull request. 
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
Once you submit your PR, a Docs team member will review your proposal. We may ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

