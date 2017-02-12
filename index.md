---
layout: default
---

## Getting Started

### Step 1: Download

#### Debian and derivatives

Download the `.deb` file from the [releases page][1] and install. The executable will be installed to `/usr/bin`.

#### MacOS and OSX

Download the `interactive-rebase-tool` from the [releases page][1] and copy it to a location on your `PATH`.

### Step 2: Configure Git

From your command line:

    git config --global sequence.editor interactive-rebase-tool

---

## Features

Quickly `pick`, `squash`, `fixup`, `edit`, `reword`, and `drop` commits.

![Change Actions][img-actions]

Easily reorder commits.

![Reorder Commits][img-move]

[1]:https://github.com/MitMaro/git-interactive-rebase-tool/releases
[img-actions]: assets/images/git-interactive-rebase-actions.gif
[img-move]: assets/images/git-interactive-rebase-move.gif
