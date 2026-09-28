# Paperkites

A quiet, offline-first Markdown notes app for macOS. <https://paperkites.app>

Your notes are plain `.md` files in a folder you choose (`~/notes` by default). Paperkites keeps an index
beside them for search, tags, links and todos, but the files are the source of truth: open them in any
other editor, sync them however you like, or keep them in git.

This repository holds the releases and the bug tracker; the app's source is private.

## Download

Get the `.dmg` from [the latest release](https://github.com/thearyanahmed/paperkites-releases/releases).

- macOS 12 or later, on Apple silicon (M1 and newer).
- Intel Macs and Linux aren't supported yet.

Open the `.dmg` and drag Paperkites into Applications. Builds are signed and notarized, so macOS opens
them without a warning.

## Updates

Paperkites updates itself from this repository's releases. It checks when it starts and every few hours
after, downloads in the background, and installs the next time you quit. `:update` restarts into it
straight away.

## This is a beta

Paperkites writes your files carefully (every save is atomic), but keep a backup of your notes folder all
the same. A locked note's password can't be recovered: nobody, including us, can open it without the
password.

## Privacy

No account, no analytics, no telemetry. The network is used only to check for and download updates, and
to open the purchase page when you ask. Licence keys are checked on your machine, offline.

## Report a bug

Run `:bug` in Paperkites, or Help → Report a Bug…. It opens [the bug form](../../issues/new/choose) with
your version filled in. `:logs` (Help → Reveal Logs) shows the log file; attaching it helps.

## Licence

Paperkites is proprietary software. All rights reserved.
