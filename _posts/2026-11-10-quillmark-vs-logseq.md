---
title: "Quillmark vs Logseq: outlines, block references, mobile apps and price"
description: "Quillmark vs Logseq compared on outlining, block references, iOS and Android apps, sync and price, with who should pick which."
layout: post
---

Last updated: November 2026

**Short answer:** Both apps are outliners. Pick Logseq if you want block references, free open-source software and plain Markdown or Org-mode files on your own disk. Pick Quillmark if you want polished iOS and Android apps, end-to-end encrypted sync built in, and semantic search, and you don't need to reference single blocks. Logseq's app is free. Its newer features (the DB version and its sync) go to [backers paying $5/month or more on Open Collective](https://opencollective.com/logseq). Quillmark is free on 2 devices and $8/month for Pro.

## Quillmark vs Logseq at a glance

| | Quillmark | Logseq |
|---|---|---|
| Note structure | Foldable outlines; zoom into and drag any branch | [Outliner on local Markdown and Org-mode files](https://apps.apple.com/us/app/logseq/id1601013908) |
| Page links and backlinks | `[[` links, backlinks on every note | [Page links and backlinks](https://apps.apple.com/us/app/logseq/id1601013908) |
| Block references | Not offered | [`((` block references and block embeds](https://discuss.logseq.com/t/the-basics-of-logseq-block-references/8458) |
| Search | Semantic search (Pro) | Search across your graph |
| Desktop | macOS, Windows | [Mac, Windows, Linux, plus a web app](https://github.com/logseq/logseq) |
| iOS | Yes | [App Store app, version 0.10.9, last updated April 2024](https://apps.apple.com/us/app/logseq/id1601013908); new DB-version iOS app [in alpha](https://github.com/logseq/logseq) |
| Android | Yes | [F-Droid, not Google Play](https://f-droid.org/packages/com.logseq.app/) |
| Sync | Built-in, end-to-end encrypted, offline-first | New RTC sync [in alpha](https://github.com/logseq/logseq), for [active monthly backers](https://opencollective.com/logseq) |
| Open source | No | [Yes, AGPL-3.0](https://github.com/logseq/logseq) |
| Price | Free (2 devices), Pro $8/month, Teams $14/user/month | [Free; backer tiers from $5/month](https://opencollective.com/logseq) |
| Students | Pro free with a school email | No student plan listed |

## Outlines and block references

Both apps treat a note as a tree of bullets, so you can fold and nest your ideas in either one.

In **Quillmark**, every note is an outline. You can fold, zoom and drag any branch, and one shortcut turns a bullet into its own note. You link notes by typing `[[`, and every note lists the notes that link to it. Pro adds semantic search, so you can find a note by what it means even if you don't remember the words you used.

**Logseq** goes a step further and lets you link to a single bullet, not just a page. Type `((` and some text and Logseq [searches your entire graph for blocks](https://discuss.logseq.com/t/the-basics-of-logseq-block-references/8458). You can also Alt-drag a bullet, or right-click it and pick "Copy block ref". The reference shows the original block's text in place. A counter on the original block shows how many times it has been referenced. A [block embed](https://discuss.logseq.com/t/the-difference-between-logseqs-block-embeds-and-block-references/8459) goes further and pulls in the block along with its children.

**Bottom line:** If you want to quote one bullet in many places and keep each copy in step with the original, Logseq is the one to pick. Quillmark doesn't have block references. Instead, you turn the bullet into its own note and link to it with `[[`.

## Mobile apps

Quillmark has native apps for iOS and Android, and they use the same encrypted sync as the desktop apps. Notes are stored on the device first, so you can write offline and your changes sync when you reconnect.

Logseq's mobile story is in flux:

- **iOS:** The [App Store app is free](https://apps.apple.com/us/app/logseq/id1601013908), runs on iPhone and iPad, and was last updated in April 2024 (version 0.10.9). Logseq says its DB version has [its own new mobile app on iOS, with Android coming soon](https://github.com/logseq/logseq), but that app is still in alpha and you have to sign up to get in.
- **Android:** Logseq isn't on Google Play. It's distributed through [F-Droid](https://f-droid.org/packages/com.logseq.app/), where version 0.10.15 was added in December 2025. Forum users say the app's [file-system access doesn't fit Play Store rules](https://discuss.logseq.com/t/publish-android-beta-app-to-play-store/8217).
- **Sync between phone and desktop:** Logseq's file-based app keeps notes as files on your device. Without the new sync, it's up to you to move those files between devices. Logseq's new RTC sync is [in alpha](https://github.com/logseq/logseq) and open to [active monthly backers](https://opencollective.com/logseq).

**Bottom line:** If you take a lot of notes on your phone, Quillmark gives you store-installed apps and sync that works out of the box. With Logseq on mobile, you'll be choosing between an older stable app and an alpha.

## Price

| | Quillmark | Logseq |
|---|---|---|
| Free | Unlimited notes on 2 devices, outlines, backlinks | [Desktop and web apps free, including at work](https://opencollective.com/logseq) |
| Entry paid tier | Pro, $8/month: unlimited devices, version history, semantic search, publishing | [Backers, $5/month: early access to insider builds and the DB version](https://opencollective.com/logseq) |
| Higher tier | Teams, $14/user/month: shared spaces, admin controls, SSO, priority support | [Sponsors, $15/month](https://opencollective.com/logseq); logo tiers from $100/month |
| Students | Pro free with a school email | No student plan listed |
| Refunds | 14-day refund window on paid plans | Not stated |

Logseq is the cheaper option if you're happy with its free app and can handle syncing yourself. Its paid tiers are support for an open-source project. They give you early access to features; they aren't a finished subscription product. Quillmark costs more once you go past 2 devices, but sync, mobile apps and version history are part of the product. Students pay nothing for Pro. See [Quillmark pricing]({{ '/pricing/' | relative_url }}) for details.

## Who should pick which

**Pick Quillmark if you:**
- want outlines that just work on macOS, Windows, iPhone and Android
- want end-to-end encrypted sync without having to set it up
- want to search your notes by meaning
- are a student and want Pro for free

**Pick Logseq if you:**
- use block references or block embeds often
- want free, open-source software (AGPL-3.0)
- want your notes as Markdown or Org-mode files on your own disk
- use Linux or want a web app
- don't mind alpha software on mobile, or syncing your files yourself

## FAQ

**Does Quillmark have block references like Logseq?**
No. Quillmark has `[[` page links and automatic backlinks. To reuse a bullet, you turn it into its own note and link to it.

**Is Logseq free?**
Yes. The desktop and web apps are [free, including for use at a company](https://opencollective.com/logseq). Backer tiers start at $5/month and give early access to the DB version and its sync.

**Does Logseq have a mobile app?**
Yes. There's an [iOS app on the App Store](https://apps.apple.com/us/app/logseq/id1601013908) and an [Android app on F-Droid](https://f-droid.org/packages/com.logseq.app/). A new iOS app for the DB version is [in alpha](https://github.com/logseq/logseq).

**Is Logseq on Google Play?**
No. On Android it's distributed through [F-Droid](https://f-droid.org/packages/com.logseq.app/).

**Which is cheaper?**
Logseq, if you only use its free app. Quillmark is free on 2 devices and $8/month for Pro, and Pro is free for students.

## Next steps

1. Write down how often you quote one bullet in several places. If it's often, try Logseq's block references first.
2. Install both apps on the phone you actually use and take notes during one meeting or lecture.
3. Edit a note on your phone while offline, reconnect, and check that the change shows up on your computer.
4. Add up the monthly cost for the number of devices you use.
