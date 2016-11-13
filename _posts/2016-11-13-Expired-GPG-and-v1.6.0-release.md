---
layout: post
title:  "Expired GPG key and v1.6.0 release"
date:   2016-11-13
author: "Zetok Zalbavar"
tags: "update,release,apt,packages,gpg"
---

Previous posts have been a bit lengthy. If someone felt ***tl;dr***, this one
is shorter, of course not because writing long blog posts is bothersome ;-)


# Expired GPG key

Recently users of [OBS] that used Debian-based distributions were hit by a
problem with the [expired GPG key] used to sign DEB packages.

The problem was quickly fixed, but not without some casualties. Manual work on
your side will be required. Sorry about that.

![Rebuilding cat in progress](https://i.imgur.com/3se4g.jpg)

*You don't even need to [travel back in time] in order to fix the problem. ;-D*

Just use the following command to add the new GPG key:

```bash
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 0xF2AA0B1E5EF8303B
```

Update, and get ready for newest qTox ;-)


# v1.6.0 release

`~O~`

#### Increased font size

Helpful especially for Windows users. If you suffered because of tiny fonts,
situation should now improve.

#### Auto-answer calls

Now you can automatically pick up video or audio call from selected contacts.

#### Settings redesign

Settings got what they deserved, but there is still room for improvements. If
you have any ideas how else they could be made better, please [make an issue]
with a proposal. This might sound a bit scary/bothersome, but it really isn't.
Even a screenshot with added arrows can be good enough, provided that reasoning
about the change is included :-)

#### Breaking changes

None (that we know of). Testing week mentioned in the previous blog post passed
away without any significant problems detected, so there [should not be]
anything surprising out there.

#### Change log

Full [changelog here].

Enjoy :-)


[changelog here]: https://github.com/qTox/qTox/blob/v1.6.0/CHANGELOG.md#v160-2016-11-13
[expired GPG key]: https://github.com/qTox/qTox/issues/3874
[make an issue]: https://github.com/qTox/qTox/issues/new
[OBS]: https://software.opensuse.org/download.html?project=home%3Aantonbatenev%3Atox&package=qtox
[should not be]: https://www.youtube.com/watch?v=bYJGt67Mwmo
[travel back in time]: https://www.reddit.com/r/linux/comments/31yayt/manjaro_forgot_to_upgrade_their_ssl_certificate/
