---
title: MacDown 0.2.2 with TOC Support
author: Tzu-ping Chung
published_at: 2014-08-05
---

MacDown 0.2.2 is just out of the door. This is mainly a bug-fixing release, correcting a very serious bug that causes MacDown to crash continuously on some machines, and bahave stragely on others. I had been unable to reproduce the problem (and still can’t), but thanks to [Zachary Alex Stern’s report](https://github.com/MacDownApp/macdown/issues/102) it is identified as a resigin issue on high-resolution displays (including Retina Macs, Apple Cinema Display, and other similar devices). The fix comes from wenbi. A big thank you to all that involved in this, and sorry to everyone affected by the issue.

But the post is not about that. Well, not mainly, at least. Although 0.2.2 is a bug-fixing release, I’ve added some improvement as well, most importantly support for table of content.

To enable TOC support, check “Renders TOC” in the “View” menu, and add `[TOC]` (case intensitive, must be in its own paragraph) anywhere in the document, and it will collect all the headers in it and render them as a tree.

![TOC rendering in MacDown 0.2.2](http://d.pr/i/cxlc+)

As indicated being exposed as a menu item, this setting is per-document, not application-wide. It is off by default.

There are some other nice features as well, and bug fixes are also issued. You can read the release note when you get the update in the app, or, if you missed that (honestly, who reads release notes before pressing “Update Now”?), it’s also listed [here](/history/).

As always, you can grab the update in-app when you are notified, or just [download directly](/download/v0.2.2/). Enjoy. :)
