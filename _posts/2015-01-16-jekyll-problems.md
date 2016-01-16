---
title: Troubleshooting Jekyll
layout: post
category: tech, how-to, jekyll, announcements
---
Thank you for bearing with me on Thursday as the technology broke. (Technology always breaks.)

There were actually two different issues in the ```_config.yml``` files, which should be very easy to fix. If you're intrepid, you can try the fix at home. If not, we'll go over them together in lab next time. The solution is to change a few things in the ```_config.yml``` file. Here's more or less what it should like, taken from the working Brume file:

```yaml
########################### EDIT YOUR SETTINGS HERE
# Site settings
title: "Your site title" # put an awesome site title here, make sure it's very short
email: "you@example.com" # put your email address in here; optional
description: "Your site description." # edit your site description; keep it brief
url: http://[GitHub username].github.io # replace [GitHub username] with your github username (no brackets)
github_username: [GitHub username] # replace with your github username

###...
```
Perhaps the easiest way to do this is to *merge* the *upstream changes* in the repo. Conceptually, what this means is: integrate the changes I've made in the eng7006/jekyll-[template] repo into your forked copy, so that you're working with the changes that I have made. This is a really useful feature of git, although one I wasn't planning on covering for a long time.

Concretely, how to do this: when you download (clone) your forked copy of the repo (described below the fold [here](https://github.com/eng7006/jekyll-brume/)), you'll now see a button in the repo timeline in GitHub desktop that reads "Update from eng7006/master." Click it. The changes will now be merged into your local copy of the repo.

You're not done, however, since you now have conflicts between your version (which you edited in class) and the new version (which is different). In the rightmost pane in GH Desktop, it will ask you to resolve the conflicts. Click on the "open in external editor" button, which will bring up the ```_config.yml```. You'll notice that you see two versions of the lines in question. Delete the old stuff, as well as all the stuff that shows up white in Atom (e.g., "<<<<<<...HEAD", "=======...").

Now, edit the new stuff with your title, description, and so on. Be sure to use quotation marks. Save the file, commit the change, and sync the changes up to GitHub.

And... you're done. This *should* work, goddammit. It would be useful, for those of you who are feeling intrepid, to test this for me.

**A note:** To do this, you will have to engage in part of the workflow we did in class last time, described in detail  download a local copy of your forked Jekyll repository to your personal computer, open ```_config.yml``
