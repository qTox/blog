---
layout: post
title:  "Maintainer Wanted"
date:   2017-02-15
author: "sudden6"
tags: "packages, maintainer, help"
---

# Outdated Linux packages

As many of you noticed, the packages for Linux in the [openSUSE Build Service]
repository are quite outdated. Our long time maintainer, `abbat`, can't
maintain the OBS packages any longer, so we're looking for help.

# What do I have to do?

Packaging work is mostly about keeping bash scripts for the builds up to date.
Most of them have already been [written], but things break every now and then
or need small adjustments.

For release packages the most work is probably one week before the release
with making sure that all the packages will build correctly and one to two
weeks after the release, when all the bug reports about broken packages come
in ;)

qTox releases happen every 6 weeks and their planned dates are published
[here].

# I want!

If you're interested in helping your favourite FOSS project or want to know
more, take a look at [this github issue] or ping `Diadlo`, `sudden6` or
`zetok` on the [#qtox @ freenode IRC channel].

[#qtox @ freenode IRC channel]: https://webchat.freenode.net/?channels=qtox
[this github issue]: https://github.com/qTox/qTox/issues/4174
[openSUSE Build Service]: https://build.opensuse.org/
[here]: https://github.com/qTox/qTox/milestones
[written]: https://github.com/abbat/tox.pkg
