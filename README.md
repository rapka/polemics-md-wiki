## polemics.md - WIP Wiki

This is a private version of https://github.com/rapka/polemics-md/ for working on TESCREAL research.

## Running

This is a Node app. I recommend managing node using [nvm](https://github.com/nvm-sh/nvm) on macOS, Linux, Windows WSL. [nvm-windows](https://github.com/coreybutler/nvm-windows) also works with the Windows shell.

### Setup

```
nvm use
npm ci
npm start
```

This will host the blog locally on `localhost:8080`.


## Adding and editing content


All content exists as markdown files inside the `content` folder. The best way to work on this is by using [Obsidian](https://obsidian.md) and opening the entire `content` folder as a vault. This causes relative links in markdown files to break when viewed on Github.


Obdisian uses a slightly modified version of Markdown. More info here:
https://help.obsidian.md/Editing+and+formatting/Obsidian+Flavored+Markdown
https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax
https://www.markdownguide.org/tools/obsidian/

Note: I use the footnote feature in Obsidian, which isn't part of the standard spec.

There is a list of major TODOs in `content/wiki/Cartography/index.md`