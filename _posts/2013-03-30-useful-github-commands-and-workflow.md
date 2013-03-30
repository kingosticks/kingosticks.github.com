---
layout: post
category : lessons
tagline: "Useful stuff I keep forgetting"
tags : [github, mopidy, python, commands]
---
{% include JB/setup %}

To checkout the remote branch 'feature/some-thing' from my fork:
    git checkout --track origin/feature/some-thing

To add the upstream (mopidy/mopidy) repo so we can pull from/push to it:
    git remote add upstream git://github.com/mopidy/mopidy.git

To update my local repo to most recent upstream (mopidy/mopidy) version:
    git pull upstream develop

To push these updates (and other local changes) to my forked repo (kingosticks/mopidy):
    git push origin develop

Push a new local branch to the remote repo:
    git push -u origin feature/my-new-branch

To delete all old files and directories in my local repo:
    git clean -f -d -x -m
