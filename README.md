# Better AO3 Tags and Fonts

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nyxmidnight/ao3tagsfonts?sort=semver) ![GitHub](https://img.shields.io/github/license/nyxmidnight/ao3tagsfonts.svg) ![GitHub Release Date](https://img.shields.io/github/release-date/nyxmidnight/ao3tagsfonts.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/nyxmidnight/ao3tagsfonts.svg) ![Maintenance](https://img.shields.io/maintenance/yes/2019) ![Archive of our Own account](https://img.shields.io/badge/AO3-nyxmidnight-red.svg?logo=archive-of-our-own&logoColor=white&labelColor=990000&color=555555)

**Better AO3 Tags and Fonts** contains various readability and usability improvements for ArchiveOfOurOwn.org. It now also supports the OpenDyslexic font.

## Getting Started

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/nyxmidnight/ao3tagsfonts/master/css/ao3butbetter.user.css)

### Prerequisites

You will need a userstyle manager that supports installing UserCSS stylesheets. I use **Stylus** ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/)).

Furthermore, the font selected in the stylesheet configuration menu will **only** work if you have the corresponding font installed on the computer you are using. Here is a list of the fonts; some are web-safe option that come installed with different Mac and Windows computers, some are free fonts with links where they can be downloaded.

-   system-ui: This option uses the default system font installed on a Mac computer or an iOS phone.
-   Segoe UI: A font that comes with Windows and Windows program for Windows 7 to 10 inclusively.
-   Arial: Web-safe option for both Mac and Windows.
-   Helvetica Neue: Common Mac font.
-   [Lato](http://www.latofonts.com/lato-free-fonts/): Open source font.
-   [Noto Sans](https://www.google.com/get/noto/): A personal favourite made by Google for consistency across many different languages, not all of which use the Latin alphabet.
-   [OpenDyslexic](https://opendyslexic.org/): As the website says, "[A] typeface designed against some common symptoms of dyslexia." Hopefully, if you are dyslexic, it will make AO3 easier to read.
-   [Open Sans](https://www.opensans.com/): Commissioned by Google, freely available.
-   Roboto: Default Android font.
-   Trebuchet MS: Included with Windows XP, macOS, iOS and Chrome OS.
-   [Ubuntu](https://design.ubuntu.com/font/): Ubuntu (Linux) font.
-   Verdana: Another common web-safe font, easy to read at low resolutions.
-   sans-serif: If all else fails, this option uses the default sans-serif font on your machine.

### Installing

To install, with a userstyle manager that supports installing UserCSS stylesheets, open the raw file within the browser.

:package: [Install the userCSS](https://raw.githubusercontent.com/nyxmidnight/ao3tagsfonts/master/css/ao3butbetter.user.css)

## Built With

-   [Stylus](https://github.com/openstyles/stylus) - Userstyle manager
-   [Firefox](https://firefox.com/)'s Web Development Tools
-   CSS3

## Features

-   Tags coloured by category
    -   **Red:** Archive's content warnings (Graphic depiction of violence, Major character death, Rape/non-con, Underage, or None, or Choose Not To Use Archive Warnings)
    -   **Cyan:** Relationships
    -   **Yellow:** Characters
    -   **Grey:** Other information (freeform tags)
-   Better default font choices
    -   **UI:** Segoe UI
    -   **Text:** Verdana
-   :new: Fonts can now be set by the user from a dropdown list, if the user has the font installed on their computer
    -   **Site interface font:** system-ui (mac), "Segoe UI" (default), "Arial", "Helvetica Neue", "Lato", "Noto Sans", "OpenDyslexic", "Open Sans", "Roboto", "Trebuchet", "Ubuntu", "Verdana", "sans-serif"
    -   **Work summary font, Story body font** and **News & documentation font:** "Arial", "Helvetica Neue", "Lato", "Noto Sans", "OpenDyslexic", "Open Sans", "Roboto", "Trebuchet", "Ubuntu", "Verdana" (default), "sans-serif"
-   Better default text width on works
    -   **Width:** 45 em
-   Better default text width for documentation, news and FAQ
    -   **Width:** 65 em
-   Visible labels for mandatory tag icons (Content rating; Relationships, pairings, orientations; Content warnings; Is the work finished or the prompt fulfilled?)

## Screenshots

Screenshots taken with "Noto Sans" font selected in all menus.

[![Front page](https://i.imgur.com/tEqLVGnt.png)](https://i.imgur.com/tEqLVGn.png) [![Tags page](https://i.imgur.com/GJeTIVet.png)](https://i.imgur.com/GJeTIVe.png) [![Recent Works page](https://i.imgur.com/8t4QsLft.png)](https://i.imgur.com/8t4QsLf.png) [![Fandoms page](https://i.imgur.com/11s782xt.png)](https://i.imgur.com/11s782x.png) [![FAQ page](https://i.imgur.com/rsAbi3Qt.png)](https://i.imgur.com/rsAbi3Q.png)

[![Dashboard page](https://i.imgur.com/4CJRHJit.png)](https://i.imgur.com/4CJRHJi.png) [![Work page header](https://i.imgur.com/4sXuwast.png)](https://i.imgur.com/4sXuwas.png) [![Work page body with summary, notes](https://i.imgur.com/PAw07hYt.png)](https://i.imgur.com/PAw07hY.png) [![Work page footer with notes, series, kudos, and comment textarea](https://i.imgur.com/z71f9oJt.png)](https://i.imgur.com/z71f9oJ.png)

## Installation

Use in a user style manager like [Stylus](https://github.com/openstyles/stylus).

## Roadmap

-   [x] Convert to UserCSS format for easy installation with the Stylus browser extension.
-   [x] Add user customizable variables.
-   [ ] Fix spacing issues with icon labels.
-   [x] Fix overlapping text issues in Series headings. :sparkles:

## Contributing

Feel free to use it, modify it, fork it at your leisure.

## Support

Please feel free to open an issue on this repo and I'll look into it.

## Versioning

I use [Semantic Versioning](http://semver.org/) for versioning.

## Author

**Nyx** - [NyxMidnight](https://github.com/nyxmidnight)

## License

This project is licensed under the Unlicense - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements

Based on the public domain work of [Athari](https://userstyles.org/styles/152660/archiveofourown-org-fonts-tags-ath).
