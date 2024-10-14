# Bismuth

A theme that aims to provide fine-grained semantic distinctions while being easy-on-the-eyes with a warm-leaning color palette WHILE ALSO remaining colorful and enjoyable to look at. Does it succeed? ehhhhhhh... it can vary. But it does generally help with breaking down big dense repos or learning a new language by organizing the tokens into some pretty fine-grained categories. Originally based off of the material synthwave theme, with influence from the Palenight and OneDark themes. Uses both Textmate and Semantic token scopes.

The Name was inspired by the element 83 - Bismuth. A silvery-grey post-transition metal that melts at relatively low temperatures and forms beautiful rhombic geometric crystals with in a rainbow of colors when oxidized at various temperatures. It holds the title of being the most diamagnetic element, and is somewhat surprisingly not toxic for human ingestion.

## Current Status: Soft-Released

If you wist to install this theme for VScode:

First, download the `.vsix` from this repo.

Next, launch VScode, open the command pallette, and select `Extensions: Install from VSIX...`

Then, select the downloaded file to install the theme, and you will then be able to choose the Bismuth theme from your list of installed themes!

**Enjoy!**

## Tinkering

To work on the theme and/or build your own version from the source, you must install the Visual Studio Extension Manager tool:

```sh
npm install -d vsce
```

To build an installable extension from the current `bismuth-color-theme.json` run:

```sh
vsce package
```

and you will generate a new `.vsix` file.