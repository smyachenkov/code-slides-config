# [Carbon](https://carbon.now.sh/) codestyle config

## Theme

Right now carbon.now.sh does not support import and export of themes, but it could be achieved via change of values in local storage.

Execute this command in your browser console:
 
```javascript
localStorage["CARBON_THEMES"] = JSON.stringify(
    [
      {
        "custom": true,
        "highlights": {
          "attribute": "#d19a66",
          "background": "#1E1E1E",
          "comment": "#6A9955",
          "definition": "#DCDCAA",
          "keyword": "#C586C0",
          "meta": "#D4D4D4",
          "number": "#B5CEA8",
          "operator": "#D4D4D4",
          "property": "#DCDCAA",
          "string": "#CE9178",
          "tag": "#569cd6",
          "text": "#D4D4D4",
          "variable": "#9CDCFE"
        },
        "id": "theme:ix4tpvc8c39",
        "name": "Custom Dark"
      },
      {
        "custom": true,
        "highlights": {
          "attribute": "#d19a66",
          "background": "rgba(255,255,255,1)",
          "comment": "#888888",
          "definition": "#DCDCAA",
          "keyword": "#0A0A88",
          "meta": "#D4D4D4",
          "number": "#B5CEA8",
          "operator": "#C9545A",
          "property": "#DCDCAA",
          "string": "#29AD13",
          "tag": "#569cd6",
          "text": "rgba(0,0,0,1)",
          "variable": "#000000"
        },
        "id": "theme:fgy2ytpy5za",
        "name": "Custom Light"
      }
    ]
);
```

## Config

Select gear menu -> misc -> import config. Select `carbon-dark-config.json` or `carbon-light-config.json`

Refresh page.

## Background

Set background. Use `1E1E1E` for the dark theme or `FFFFFF` for the light theme.

That's all, now select theme `Custom Light` or `Custom Dark` from the theme menu and paste your code in editor window.
