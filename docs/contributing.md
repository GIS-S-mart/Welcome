# How to contribute to industrial engineering research benchmarks? 

In this guide, you will get an overview of the contribution workflow from creating a new benchmark or modifying a existing one.

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
2. If your purpose is not covered by existing benchmarks but you are not sure whether it is specific enough to motivate the invention of a new one, then post on the [discussions page of the organization team](https://github.com/orgs/GIS-S-mart/discussions) and briefly outline the new benchmark so as to enable subject-matter experts from the community to argue. Tag your issue with the `labels` *'new_benchmark'*.
3. If your purpose is not covered by existing benchmarks and you are not sure that it is specific enough to motivate the invention of a new one, then create a new issue from the [issues page of the organization](https://github.com/GIS-S-mart/organization_team/issues) and briefly outline the new benchmark. Tag your issue with the `label` and `issue form` *'benchmark'*.
4. Create a new private repository to host your benchmark by navigating to the [repository template](https://github.com/GIS-S-mart/Benchmark-0_Template) and clicking on the button "Use this template".
5. Define the new benchmark and commit the changes once you are happy with them.
6. When you're finished with the changes, create a pull request (see below).
7. Your pull request is merged! Once your pull request is merged, your benchmark will be publicly visible.

## How to update an existing benchmark?

1. If you want to improve (e.g. create/modify/delete a new goal, metric, problem, solution, etc.) an existing benchmark, [search if an issue already exists]().

   1. If a related issue doesn't exist, you can open a new issue using the relevant `issue form` and tag it with the right `label`:
      1.  *'goal'* `label` and `issue form` to create, update or delete a goal;
      2.  *'metric'* `label` and `issue form` to create, update or delete a metric; 
      3.  *'exercise'* `label` and `issue form`  to create, update or delete a benchmark exercise;
      4.  *'solution'*  `label` and `issue form`  to create, update or delete a candidate solution;
      5.  *'protocol'* `label` and `issue form`  to create, update or delete a measurement protocol;
2. Alternatively, you may scan through the [existing issues]() to find one that interests you. You can narrow down the search using `labels` as filters.
3. We don’t assign issues to anyone. If you find an issue to work on, you are welcome to open a pull request with a fix.
4. Make changes locally:

   1. [Install Git LFS](https://docs.github.com/en/github/managing-large-files/versioning-large-files/installing-git-large-file-storage) if needed.

   2. Fork the repository using GitHub Desktop:
      - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
      - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

   3. Create a working branch and start with your changes!
5. Commit the changes once you are happy with them.
6. When you're finished with the changes, create a pull request:

   - Fill the "Ready for review" template so that we can review your pull request. This template helps reviewers understand your changes as well as the purpose of your pull request. 
   - Don't forget to [link your pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
   - Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
   - Once you submit your pull request, a team member will review your proposal. We may ask questions or request additional information.
   - We may ask for changes to be made before a pull request can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
   - As you update your pull request and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
   - If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

## How to start a discussion with organisation members?

On the [team's page](https://github.com/GIS-S-mart/organization_team), you can use [team discussions](https://github.com/orgs/GIS-S-mart/discussions) for conversations that span across projects/repositories and don't belong to a specific issue or pull request. Instead of opening an issue in a repository to discuss an idea, you can include the entire organisation team by having a conversation in a team discussion.

Any organisation member can post on the [team's page](https://github.com/GIS-S-mart/organization_team) or participate in a [public discussion](https://github.com/orgs/GIS-S-mart/discussions) . *Private* posts are only visible to team members and organisation owners, and *public* posts are visible to all members of the organisation.
