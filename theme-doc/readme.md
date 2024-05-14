## Theme guide 

<details>
    <summary>Table of Contents</summary>
    
___
1. [Theme list](#Theme-list) <div>
   
2. [For theme developers](#For-theme-developers) <div>
2.1 [Some suggestions](#Some-suggestions) <div>

   2.2 [Additional info](#Additional-info)
___
</details>

Here you can find most of the themes working with Pyoncord (more will be added in the future) and some quick links for theme developers.

> [!NOTE] 
> There is also a **list of compatible themes** with Pyoncord below

If this is your first time using a client mod, I suggest that you try [Pyontheme](https://raw.githubusercontent.com/rennpy/pyontheme/main/pyontheme.json) (honestly, this is my guide so I can showcase what I want 🚎) <br>
You can be sure it will always work for most recent versions of Pyoncord, naturally.

Here is a link to the [github page](https://github.com/rennpy/pyontheme) for it, which includes a preview.

To get the raw links of the themes, hold on their names listed below to open the copy link prompt

## Theme list
| Theme name & link | Author |
| --------- | :----------------------- |
| [Orchid's love](https://raw.githubusercontent.com/VodkaXMartini/VendettaTheme/main/Orchid.json) | FtVodka |
| [Eye Candy](https://raw.githubusercontent.com/Quinxxxx/Discord-themes/main/Vendetta/Eye_candy.json)  | Moodle |
| [RosieBlue](https://raw.githubusercontent.com/Moodzz1/DT/main/Vendetta/RosieBlue.json) | Moodle |
| [RosieDark](https://raw.githubusercontent.com/Rairof/Discord-Theme/main/RosieDark.json) | Rairof |
| [Tokyo Nights](https://raw.githubusercontent.com/LuckyJinx13/Public-Themes/main/Tokyo%20Nights.json) | Mkultra.waifu |
| [Atherion 2.0](https://raw.githubusercontent.com/LYNK-INCUU/Cosmicka/main/Aetherion-Vendetta.json) | Lyntxrya#7769 |
| [Catppuccin](https://github.com/catppuccin/vendetta) | (link to all variants) |
| [Maggie's purple](https://raw.githubusercontent.com/maggster165/vendettathemes/main/maggiespurple.json) | Maggie.pi (little of it needs fixing) |

## For theme developers

If you are a theme dev or want to try theme-making, you should look at the [theme docs](https://docs.riichi.tech/) from riichi (kinda outdated) <br>
And most importantly use [ThemeLings](https://github.com/nexpid/Themelings) by nexpid which is used to find new strings, semantic keys, raw colours and other strings along with icons discord changes or adds <br>

### Some suggestions
You should join the discord if you haven't already and ask in #theme-dev if you need help with anything.

Making your first theme might get a little complicated; take some breaks.

### Additional info

There currently isnt a channel for publishing themes yet, but once that is the case, reach out to cbani (me) within the discord server to make a submission via dms!

As for any already established theme-devs, keep me up to date with your themes, or even make a pull request to add/delete some of your themes to the list. I am open to improving this documentation as much as possible for the benefit of all pyoncord developers.

## Making themes for Pyoncord

This section will cover every aspect of a theme, and how you can make one yourself with enough time and effort. 

First, here is a complete overview of a .json theme file, this one being for Pyontheme. 

This is how the beginning section looks;

```json
{
    "name": "Pyontheme",
    "description": "Theme about Pyoncord (real and true)",
    "authors": [
        {
            "name": "rennpy",
            "id": "650805815623680030"
        }
     ],
   
```
As you can see, this is where you put your theme's name, description and author(s). Pretty simple, right?

The following strings go over the semantic, or main colors;
```json
    
    "semanticColors": {
        "HEADER_PRIMARY": [
            "#d4d2ff"
        ],
        "HEADER_SECONDARY": [
            "#6460af"
        ],
        "TEXT_NORMAL": [
            "#e0deff"
        ],
        "TEXT_MUTED": [
            "#c1c0df"
        ],
        "INTERACTIVE_NORMAL": [
            "#6460af"
        ],
        "INTERACTIVE_HOVER": [
            "#403e6f"
        ],
        "INTERACTIVE_ACTIVE": [
            "#e0deff"
        ],
        "INTERACTIVE_MUTED": [
            "#bbbad6"
        ],
        "BACKGROUND_PRIMARY": [
            "#212034"
        ],
        "BACKGROUND_SECONDARY": [
            "#2b2a3b"
        ],
        "BACKGROUND_SECONDARY_ALT": [
            "#26253b"
        ],
        "BACKGROUND_TERTIARY": [
            "#26253b"
        ],
        "BACKGROUND_ACCENT": [
            "#2d2c48"
        ],
        "BACKGROUND_FLOATING": [
            "#2d2c48"
        ],
        "BACKGROUND_MOBILE_PRIMARY": [
            "#0f0e18"
        ],
        "BACKGROUND_MOBILE_SECONDARY": [
            "#0f0e18"
        ],
        "BACKGROUND_NESTED_FLOATING": [
            "#2d2c48"
        ],

        "BACKGROUND_MESSAGE_HOVER": [
            "#26253b"
        ],
        "BACKGROUND_MODIFIER_HOVER": [
            "#26253b"
        ],
        "BACKGROUND_MODIFIER_ACTIVE": [
            "#2d2c48"
        ],
        "BACKGROUND_MODIFIER_SELECTED": [
            "#2d2c48"
        ],
        "BACKGROUND_MODIFIER_ACCENT": [
            "#2d2c48"
        ],
        "SCROLLBAR_THIN_THUMB": [
            "#26273b"
        ],
        "SCROLLBAR_THIN_TRACK": [
            "transparent"
        ],
        "SCROLLBAR_AUTO_THUMB": [
            "#6b68a3"
        ],
        "SCROLLBAR_AUTO_TRACK": [
            "#6b68a3"
        ],
        "CHANNELTEXTAREA_BACKGROUND": [
            "#26273b"
        ],
        "CHANNELS_DEFAULT": [
            "#5e5b8e"
        ],
        "TEXT_LINK": [
            "#6b68a3"
        ],
        "TEXT_DANGER": [
            "#6b68a3"
        ],
        "KEYBOARD": [
            "#161621"
        ],
        "BG_BACKDROP": [
            "#000000B2"
        ],
        "REDESIGN_BUTTON_SECONDARY_BACKGROUND": [
            "#26273b"
        ],
        "CHANNEL_ICON": [
            "#e0deff"
        ],
        "CHAT_BACKGROUND": [
            "#161621"
        ],
        "CARD_PRIMARY_BG": [
            "#2d2c48"
        ]
    },
   ```


