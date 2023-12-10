# My Own Firefox Style Sheets Setup
- userChrome.css
  - fontOverride.css
    - Font Source: `Google Sans`, `Product Sans`
    - You can get both fonts by extracting assets from a Pixel phone or open an issue.
  - iconOverride.css
    - Icon Source: [Tabler](https://github.com/tabler/tabler-icons)
    - Modified to fit FireFox's SVG rules. (`currentColor` -> `context-fill`, etc.)
    - Supports [TWP - Translate Web Pages](https://github.com/FilipePS/Traduzir-paginas-web)'s URL bar icon.
  - tabCloseButton.css
    - Show close button when mouse hover on tab.

## Installation
1. Follow the [official guide](https://support.mozilla.org/en-US/kb/contributors-guide-firefox-advanced-customization)
   - Clone this repo to Firefox profile folder and rename cloned folder to `chrome`
2. Edit `about:config`
    - `toolkit.legacyUserProfileCustomizations.stylesheets` = `true`
    - `svg.context-properties.content.enabled` = `true`
    - `layout.css.color-mix.enabled` = `true`

![Preview](https://cdn.discordapp.com/attachments/917129797510000691/1107395825593757766/image.png)
