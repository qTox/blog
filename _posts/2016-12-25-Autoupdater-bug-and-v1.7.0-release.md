---
layout: post
title:  "Autoupdater bug and v1.7.0 release"
date:   2016-12-25
author: "Diadlo, sudden6, Zetok Zalbavar"
tags: "update,windows,release"
---

# Bug in the updater

A [bug in the updater] code rendered qTox versions `1.6` and `1.5` unable to
perform an update on Windows.

![no dashing through cat](https://i.imgur.com/khlbtPE.jpg)

Sadly, there is no way to fix or work around it.

If you're a Windows user, you'll need to manually install the newest qTox
version.

# v1.7.0 release

Due to speeded up release cycle, `1.7` is a slightly smaller release. Some bugs
were fixed and there were some small UI improvements. For details, refer to the
[changelog].

[31 people] contributed to this release. Kudos to them! :-)

## Translations

Aside from numerous updates to the already available translations,
initial Korean and Pirate translations have been added. *Arr!*

## Switch to TokTok

For some time toxcore's development was halted. TokTok project helped with the
situation by revitalizing development.

qTox `1.7` targets [TokTok/c-toxcore]'s version 0.1 instead of
[irungentoo/toxcore].

## Copy link action

One of the small UI improvements is an option in the right-click menu, shown
upon clicking on the link in the chat. Small step for qTox, big leap for the
usability.

# Random quote

```
<sudden6> who cares about Christmas when it's qTox release day :P
```

[31 people]: https://github.com/qTox/qTox/compare/v1.6.0...v1.7.0
[bug in the updater]: https://github.com/qTox/qTox/issues/3910
[changelog]: https://github.com/qTox/qTox/blob/v1.7.0/CHANGELOG.md#v170-2016-12-25
[irungentoo/toxcore]: https://github.com/irungentoo/toxcore
[TokTok/c-toxcore]: https://github.com/TokTok/c-toxcore
