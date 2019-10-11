# Overview

A large portion of the project that we are building on is based on the [core Gutenberg project](https://wordpress.org/gutenberg/). So many thanks goes out to everyone who has contributed in any way. 👏

## What is Mobile Gutenberg?

Mobile Gutenberg is the mobile variation of the [Gutenberg project](https://wordpress.org/gutenberg/), also known as the block editor for WordPress. It uses a mixture of technologies from platform-specific Swift and Java, but also cross-platform technology like Javascript and React Native.

If you'd like to follow the codebase more closely, you can follow along on the [Github repository](https://github.com/wordpress-mobile/gutenberg-mobile).

## The Goal of Mobile Gutenberg

The goal of the project is to build upon the successes of the web project and "translate" the interface to feel "native" on each mobile platform.

We aim to provide as clean and intuitive of an interface as possible, while adhering to established patterns on each platform.

# Principles

While the core principles of Gutenberg on the web also apply to mobile, here are some of the over-arching principles that encompass the experience on mobile.

### Native

The editor feels "native" to each platform, honoring platform standards and patterns.

### Contextual

Controls are relevant to the context and task at hand, and don't get in the way.

### Reachable

Primary actions are reachable to perform any given task, especially for one-handed use.

### Discoverable

It is clear to the user what actions are available and what they do.

# Key Concepts

* **Block Editor**: the content editing and publishing interface that we are building.

* **Gutenberg**: the codename for the new block editor in WordPress.

* **Block**: an abstract unit for organizing and composing content, strung together to create content for a webpage. Just about everything you see on the editor canvas is a block.

* **Block Name**: the name provided when the block is created (eg. Paragraph, Image, Gallery, Quote, etc).

* **Quick Toolbar**: a toolbar that contains controls relevant to the currently-selected block, usually preceded by a persistent inserter button. It typically sits at the top of the keyboard.

* **Inline Toolbar**: the toolbar that is attached directly to the bottom of the selected block on the canvas.

* **Block Library**: the library of all available block types.

* **Block Category**: a classification for the type of block, which is used to group by similarity in the Block Library.

* **Editor Canvas**: surface on which the editor creates and edits content. This houses any composition of blocks.

* **Editor Chrome**: the UI elements that surround canvas and blocks. For example, the editor's Navigation/App Bar, software keyboard, etc.

* **Inserter**: the surface that contains a grid of all available block types – typically in the form of a Bottom Sheet.

* **Re-usable Block**: a user-defined grouping of blocks that is made available for re-use, allowing any edits to be applied to all instances. *Note: this is not available on mobile.*

# Anatomy

*To-do: add intro blurb here*

## Editor UI

## Block Anatomy

- States
  - Static
  - Selected
  - InnerBlocks
- Wrapper
- Block Contents
- Inline Toolbar
- Quick Toolbar
- Block Settings
  - Inspector
  - Grouping
  - Types of Settings

---

Previous: [Intro](README.md)

Next up: [Guidelines](guidelines.md)