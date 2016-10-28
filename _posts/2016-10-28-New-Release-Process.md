---
layout: post
title:  "New Release Process"
date:   2016-10-28
author: "sudden6"
tags: "update,development,releases"
---


qTox is changing it's release process for you :)

# The Current State

Currently qTox has no fixed release cycle. That means we do a release when
we feel like doing a release, which can be at any given interval. We
determined this approach is not really fitting qTox.

# Why?

It means that a new feature could be merged just before a release and can
break this release. Additionally having no defined release dates makes it
hard to set goals to reach and we had to learn that it makes us set
unrealisticaly high goals.

# 5:1 A Magic Ratio

After some discussion we settled on release cycle of 6 weeks, split in two
parts. The first 5 weeks of each development cycle are intended for
features and the last week is a stabilizing phase.

During the first part anyone is welcomed to send their pull requests (PRs) about
stuff they want to change in qTox. In the second part only PRs fixing bugs,
updating the translations and minor chores are allowed. This allows us to
test each release and avoid any last minute bugs.

# Cool, how can I help?

A good first start is always to look at our [README] or to
check out our IRC channel [#qtox@freenode.net][IRC-channel]. The README has
a list with various ways to help qTox, from non-Programmer tasks to Code-Guru
level. We will be glad for any feedback, be it on IRC, Github Issues or
our [mailing list].

# The future

Expect ~~us~~ more polished qTox releases \o/

![polishing cat](https://i.imgur.com/BO0O7nv.gif)


[readme]: https://github.com/qTox/qTox/tree/e8e946d4c8f21e55680ab7ff8ea0a60026b399e2#help-us
[IRC-channel]: https://webchat.freenode.net/?channels=qtox
[mailing list]: https://lists.tox.chat/listinfo/general
