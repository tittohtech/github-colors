## Colors of languages from GitHub
Ever wondered what colors are used for all the languages on GitHub?

The script, `github-colors.py`, checks [Github](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) for the list of all languages, saves all colors in `colors.json` and updates the [COLORS.md](./COLORS.md) file.

## Fetch colors
You can use this link to fech the colors.

url: `https://raw.githubusercontent.com/tittohtech/github-colors/master/colors.json`

## Response

```
{
    "1C Enterprise": {
        "color": "#814CCC",
        "url": "https://github.com/trending?l=1C-Enterprise"
    },
    "4D": {
        "color": null,
        "url": "https://github.com/trending?l=4D"
    },
    "ABAP": {
        "color": "#E8274B",
        "url": "https://github.com/trending?l=ABAP"
    },
    "ActionScript": {
        "color": "#882B0F",
        "url": "https://github.com/trending?l=ActionScript"
    },
    "Ada": {
        "color": "#02f88c",
        "url": "https://github.com/trending?l=Ada"
    },
    "Agda": {
        "color": "#315665",
        "url": "https://github.com/trending?l=Agda"
    },
    "AGS Script": {
        "color": "#B9D9FF",
        "url": "https://github.com/trending?l=AGS-Script"
    },
    ... 
}
```
