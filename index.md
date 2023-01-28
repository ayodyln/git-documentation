# Git Basics

![GitLogo](imgs/Git_Logo.png)

## What is Git?

Git is a project management tool for the development of applications. The tool gained prominence in the industry for being an open-source version control system. With the capabilities to be distributed, meaning that this is a version control system that puts a copy of the repository (package of code) on a developer's computer. Enabling them to interact with that local copy by _branching_, _merging_, and _committing_ changes. Also giving a developer the ability to navigate between branches, commit history, and much more all in something called a _repository_. Which is essentially a Git initialized project that lets you have version control capabilities.

## Why use Git? What problem does it solve?

When working with projects in general, it would be wise to work on that project and produce multiple versions of that. So that the project iterates and grows to a final version (e.g., rough drafting up to a final version). Using Git can help establish a workflow that ensures the development of a project, with multiple iterations. The ability to travel back in _time_ of a git repository history is possible too since each commit is tracked in a timeline. It is also possible to traverse branches too, which can be different build versions of an application--production or development for example.

Having the ability to traverse a figurative tree, in other words, a _file tree structure_. Lets developers or teams manage each step of a project and go back to a commit in the repositories history. One major thing that Git helps solve is the ability to collaborate with others on a project. Working on a selected file could lead to conflicts of some kind. For example, for a project, there is a location designated for the files, and being able to work on the same file as another is not recommended or is impossible. You would have to coordinate with what files you would be working on and also figure out a way to have access to the source of the project. To solve this Git, lets developers install copies of the repository on their machine and then contribute to the projects through their commits.

## What is the difference between Git and Github?

Multiple services use the name **Git** within their branding. Such as `Github`, `GitLab`, and `GitBucket`. This is because Git is an open-source system that services have created hosting. The version control system itself could run independently of these services, although most are free to use. It's possible to house a repository locally on one machine, or a part of a local network/server. However, hosting a repository remotely is easy and it safeguards it from being accidentally deleted, meaning there is a backup in a safe location.

Github does not own the Git DVCS, since that is open source. What they do is build upon that service and make it visual and easy to use. When a repository is set up on GitHub, that is known as a _remote_. Meaning it is not locally present on the machine, but is remotely accessible. Typically, git remotes have been configured to be a URL. This is where GitHub comes to play, by integrating their service with Git. Any code commits on a working project, could be _pushed_ to the remote, updating the source of truth for an application.

<br>

# Git rebase

## What is Git rebase?

![Git Rebase](imgs/pre_rebase.png)

Git creates a trail that represents the history/timeline of a repository. But this timeline can get layered or start to look like a tree, these layers are branches. In the [Why use Git?](#why-use-git-what-problem-does-it-solve) section, git branches were mentioned as to how they can be used as production or dev branches.

![Merge Example](imgs/Merge.png)

We could merge those branches into one again. The history is preserved though, meaning that the branch and its commits still exist. But the code was merged into one project once again, updating the code and the project is continuing on one _main_ branch again. This is a common practice of managing branches and is notable on GitHub with how the community works on public repositories.

![Git Rebase 2](imgs/rebase.png)

Instead, we could rebase the new branch into the main branch of the repository. What is different about merging here, is that the history of that branch is technically destroyed. Albeit, navigating to them via _checkout_ is still possible. But those commits in the "location" of the old branch are _orphaned_. The image example above demonstrates what is happening to the branch. The new branch's commits have been moved and their "past lives" have been more or less, deleted.

### `What are some advantages and disadvantages of Git rebase?`

**Advantages**:

- Commits and work is being saved and _moved_ to the main branch.
- Project and version history is being merged into one cohesive timeline.

**Disadvantages**:

- Branch history is destroyed and former commits are orphaned.
- Branch history is placed at closer to the _head_ of the main branch. Rewriting history in a way.

## When shouldn't you use Git rebase? Why?

This process is rewriting history and is destructive. It could be used productively probably, if and only the developers involved know what they are doing and have true sight of goals in mind. If there is teamwork involved and an extensive history of a project, you shouldn't be using git rebase. To keep the milestones in place, not only for reference and integrity of the repository. This could introduce conflicts and a loss of translation could happen in public repositories.

- ### Create a new repo and demonstrate your knowledge of the following items with screenshots:

  - A rebase merge

  - An interactive rebase merge

## When you shouldn't rebase with a remote repo.

# Git reset, checkout, and revert

## What is Git reset?

## What is the difference between hard, mixed and soft?

## What is Git checkout?

## What is Git revert?

## In what ways are these commands the same and what ways are they different?

## When would you use reset, checkout, or revert? Why?

- ### Create a new repo and demonstrate your knowledge of the following items with screenshots:

  - a Git reset
  - a Git checkout
  - a commit
  - a Git revert

# Git submodules

## What are Git submodules?

## When would you use a submodule?

## What are the advantages and disadvantages of Git submodules?
