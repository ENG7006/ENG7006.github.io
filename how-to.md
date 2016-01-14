---
layout: inner
title: How To...
permalink: /how-to/
---
If you're stuck with the tech (and not with the coding), the first thing to do is to look at recent posts in the [how-to category](/blog/categories/#how-to). The most recently added tech will likely be first.

Often, the documentation or instructions for a thing are included with the thing. For example, all the instructions you need to get started using a particular Jekyll template are in the readme for that template, e.g. check out the [\*folio repo](https://github.com/eng7006/jekyll-folio).

A number of the tools that we are using have their own instruction sets:
* GitHub desktop comes with its own beginning set of instructions the first time you use it.
* You can also access a robust set of help materials online, e.g. [Getting Started with GitHub Desktop](https://help.github.com/desktop/guides/getting-started/)
* Slack will likely be quite intuitive, but if you need help getting started, you can check out their [Getting Started with Slack](https://eng7006.slack.com/getting-started)

### Basic git & GitHub Workflow for ENG 7006
That said, here is probably the most complicated and common thing we will do all semester, use git to save and deploy work:

#### To Fork a Repo
If you're working with repos that already exist in the ENG 7006 GitHub organization:
1. Go to the organization's repo page: https://github.com/eng7006/[repo-name].
2. Click the "Fork" button.
3. You now have a repo of the same name in your personal GitHub account, ready for download and editing.

#### To Download a Repo
Either you can click the download to GitHub Desktop button (easiest option, a bit hard to find; immediately to the left of the "Download ZIP" button on the repo home page).

Or, in GitHub desktop:
1. Click on the add repo button at the top left, with the big plus sign. "Create" will make you a brand spanking new, empty repo; "Add" will take currently existing files on your computer and make a repo for them. What you will want for now is "Clone," which will take a repo on GitHub and beam it down to your computer.
2. This will bring up a list of repos to which you have access: ENG 7006 organizational repos and your own private repos.
3. When you select one, GitHub will prompt you for a local folder to store it in. A convenient place is ```Home/git/[repo name]```.
4. You're ready to start editing.

#### Working with a Repo
You've downloaded a repo, and made some changes in Atom. Not too many changes! A small change here and there that you can summarize in 5 words. Time to commit the change!
1. GitHub Desktop will tell you which files you have changed in the middle pane, and then give you a digest of those changes on the right.
2. Give the changes a name: three to five words that explain very briefly what you've changed. This goes in the "Summary" box.
3. Explain the changes a bit more in the box below Summary, the "Description."
4. Once you've entered those things, press the "Commit" button. You'll see a new little ring appear in the timeline at the top.
5. Make some more changes, making commits after small changes.
6. Once you're done working, or once you've made one big change (composed of many small changes), hit the "Sync" button at the top right, above the timeline. And bam!—your changes have now been saved to GitHub.

Get in the rigorous habit of committing after small changes and of syncing your commits up to GitHub after every work session. This way, you won't end up with conflicts, when you've made changes locally in two different places. Git has straightforward workflows to "merge conflicts," but it's still an annoying process and you should avoid it if you can. It's easy to do so, when you're working alone. (More on collaboration later.)

#### Submitting Work
This bit presumes you've forked a repo, as described above.

To turn work in, you "Submit a Pull Request":
1. Click the "Pull Request" button at the top right, above the timeline.
2. Give it a useful summary and description, as with a commit. This will be information to me.
3. Click the "Send Pull Request button."
