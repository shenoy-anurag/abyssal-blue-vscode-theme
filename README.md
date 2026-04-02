# Abyssal Blue 🪼

![VS Code Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/shenoy-anurag.abyssal-blue)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/shenoy-anurag.abyssal-blue)
[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-blue)](https://vscode.dev/editor/theme/shenoy-anurag.abyssal-blue)

A Visual Studio Code theme for the those who love the OG Monokai colors for syntax highlighting, and love the deep dark blues of the ocean.

There are two themes in this package:
1. Abyssal Blue.
2. Abyssal Blue Abyss.

Abyss has a slightly darker color palette.

## Abyssal Blue Preview
![Image preview for the Abyssal Blue theme](assets/abyssal-ts-v0.0.3.png)

The main/default theme is `Abyssal Blue`.

Inspired by the colors of the Midnight & Abyssal Zone of the Ocean. Learn about the [Abyssopelagic Zone](https://www.whoi.edu/ocean-learning-hub/ocean-topics/how-the-ocean-works/ocean-zones/), also referred to colloquially as the Abyss.

## Abyssal Blue Abyss Preview
I have created a darker version of the theme, which has the name `Abyssal Blue Abyss`.

![Image preview for the Abyssal Blue Abyss theme](assets/abyssal-abyss-ts-v0.0.3.png)

# Installation

1.  Install [Visual Studio Code](https://code.visualstudio.com/)
2.  Launch Visual Studio Code
3.  Choose **Extensions** from menu
4.  Search for `abyssal blue`
5.  Click **Install** to install it
6.  Click **Reload** to reload the Code
7.  From the menu bar click: Code > Preferences > Color Theme > **Abyssal Blue**

You can also use the hotkey **Cmd + Shift + P** (on Mac) or **Ctrl + Shift + P** (on Windows) to open the Command Palette, type "theme", and select **Color Theme**, and then pick the **Abyssal Blue** theme.

# Color Palette 
## Abyssal Blue
| Color Name | Color | Primary Application Areas | Hex |
| ------ | ------ | ------ | ------ |
| Dark Denim | ![Color Swatch for the Dark Denim color](assets/palette/default-midnight/highlight.png) | Status Bar, Highlight for Activity Bar | `#005588` |
| Medium Persian Blue | ![Color Swatch for the Medium Persian Blue color](assets/palette/default-midnight/button-hover.png) | Button Hover | `#0167a4` |
| Halite Blue | ![Color Swatch for the Halite Blue color](assets/palette/default-midnight/suggest.png) | Suggestion Widget, List Focus | `#062f4a` |
| Cyanophobia | ![Color Swatch for the Cyanophobia color](assets/palette/default-midnight/peekview-editor.png) | PeekView Editor | `#001f33` |
| Washed Black | ![Color Swatch for the Washed Black color](assets/palette/default-midnight/activity-title-menu-tabs.png) | Activity Bar, Title Bar, Menu, Tabs Bar | `#1c202a` |
| Dark Slate | ![Color Swatch for the Dark Slate color](assets/palette/default-midnight/sidebar-tab-inactive.png) | Sidebar & Inactive Tab | `#1e222a` |
| Coarse Wool | ![Color Swatch for the Coarse Wool color](assets/palette/default-midnight/peekview-title.png) | PeekView Title, Empty Editor | `#1a1e28` |
| Sky Captain | ![Color Swatch for the Sky Captain color](assets/palette/default-midnight/editor-active.png) | Dropdown Items, Menu Items | `#252a34` |
| Sky Captain v2 | ![Color Swatch for the Sky Captain v2 color](assets/palette/default-midnight/editor-dropdown-menuitem.png) | Dropdown Items, Menu Items | `#262732` |

## Monokai Syntax Highlighting Palette
| Color Name | Color | Primary Application Areas | Hex |
| ------ | ------ | ------ | ------ |
| Office Neon Light | ![Color Swatch for the Office Neon Light color](assets/palette/monokai-classic/keyword.png) | Keyword, Storage, Tag | `#f92672` |
| Poison Potion | ![Color Swatch for the Poison Potion color](assets/palette/monokai-classic/class.png) | Class & Function names | `#a6e22e` |
| Turquoise Sea | ![Color Swatch for the Turquoise Sea color](assets/palette/monokai-classic/storage-n-lib-fn.png) | Storage Type, Library function name | `#66d9ef` |
| Dragon Ball | ![Color Swatch for the Dragon Ball color](assets/palette/monokai-classic/arguments.png) | Function arguments | `#fd971f` |
| Purple Illusionist | ![Color Swatch for the Purple Illusionist color](assets/palette/monokai-classic/constants.png) | Numbers and Constants | `#ae81ff` |

Color names from https://colornamer.robertcooper.me/

# Preferences shown in the preview

The font in the preview image is Monaspace Neon, [available here](https://monaspace.githubnext.com/). Editor settings to activate font ligatures:

```json
{
    "editor.fontFamily": "Monaspace Neon, Monaco, 'Courier New', monospace",
    "editor.fontLigatures": true,
}
```

I'm using Monaco, Courier New, and monospace fonts as fallbacks, but you can use whatever font you like, or omit them. ☺️

# Misc

This is my first attempt at creating a vs code theme, so if you find an issue or an out-of-place color, please feel free to [file an issue](https://github.com/shenoy-anurag/abyssal-blue-vscode-theme/issues).

If you use [the VS Code Babel extension](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel), you may see some inconsistencies in color for JSX, that's not coming from this theme.

If you wish to make your own VS Code extension or theme, check out the [VS Code Extension Documentation](https://code.visualstudio.com/api/get-started/your-first-extension).

This theme is inspired by my favorite theme of all time, [Monokai](https://github.com/microsoft/vscode/blob/f91019e7676ab34ef03e1ccb550a7a6c949fa4cd/extensions/theme-monokai/themes/monokai-color-theme.json), not be confused with the Pro version of the same.