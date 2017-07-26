## Sticky Searches Add-on for Anki

This is an add-on for the spaced-repetition flashcard app [Anki](https://apps.ankiweb.net/)

Adds a number of **quick-toggles** to the **Browser** search bar that allow you to **preserve specific search parameters** across multiple searches, so that you do not have to type them in repeatedly.

### Table of Contents

<!-- MarkdownTOC -->

- [Screenshots](#screenshots)
- [Features](#features)
- [Installation](#installation)
- [License and Credits](#license-and-credits)

<!-- /MarkdownTOC -->

### Screenshots

![](screenshots/screencast.gif)

### Features

By default the add-on comes with four toggles:

*Static*

- Deck (Hotkey: Alt+D): Limit results to current deck 
- Card (Hotkey: Alt+C): Limit results to first card of each note

*Dynamic*

- Sticky (Hotkey: Alt+S): Will remember the entirety of the current query
- Tags (Hotkey: Alt+T): Limit results to current tag selection

Static toggles have predefined values, while dynamic ones are extracted from
the current search.

Advanced users can customize these toggles and set up additional ones by modifying the configuration section in the source code.

### Installation

*AnkiWeb*

[Link to the add-on on AnkiWeb]()

*Manual installation*

1. Go to *Tools* -> *Add-ons* -> *Open add-ons folder*
2. Find and delete `Sticky Searches.py` and `sticky_searches` if they already exist
3. Download and extract the latest add-on release from the [releases tab](https://github.com/Glutanimate/sticky-searches/releases)
4. Move `Sticky Searches.py` and `sticky_searches` into the add-ons folder
5. Restart Anki

### License and Credits

Some of the features in this add-on where inspired by the following fantastic add-ons:

- "Limit searches to current deck" by [Damien Elmes](https://github.com/dae/ankiplugins/blob/master/searchdeck.py)
- "Ignore accents in browser search" by [Houssam Salem](https://github.com/hssm/anki-addons)

'Sticky Searches' was originally known as 'Browser Search Modifiers', but has since been reworked from the ground up with the kind support of a fellow Anki user.

If you enjoyed this add-on and would like to hire my services to work on an add-on of your own, please feel free to reach out to me through <em>ankiglutanimate [αt] gmail . com</em>

*Sticky Searches* is *Copyright © 2017 [Aristotelis P.](https://glutanimate.com/)*

Licensed under the [GNU AGPL, version 3 or later](https://www.gnu.org/licenses/agpl-3.0.en.html).
