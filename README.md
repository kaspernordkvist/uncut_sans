# Uncut Sans
Yet another slightly quirky sans serif, designed with absolutely no investigation or research into any other typefaces from any specific time period. It tries to capture the essence of nothing, really. There’s no deeper meaning behind the design, but hopefully it’s still interesting enough to be taken into consideration for your next project.

[**Download the latest version here**](https://github.com/kaspernordkvist/uncut_sans/releases/latest)

------

## Preview

![Uncut Sans font preview](/misc/readme/preview_1.png)

![Uncut Sans font preview](/misc/readme/preview_2.png)

![Uncut Sans font preview](/misc/readme/preview_3.png)

![Uncut Sans font preview](/misc/readme/preview_4.png)

------

## Using Uncut Sans

[**Download and install the latest version here**](https://github.com/kaspernordkvist/uncut_sans/releases/latest)

Embed using CDN
```
<link rel="preconnect" href="https://cdn.jsdelivr.net/">
```
```
@font-face {
	font-family: "Uncut Sans";
	font-style: normal;
	font-weight: 400;
	src: url("https://cdn.jsdelivr.net/gh/kaspernordkvist/uncut_sans/Webfonts/Uncut-Sans-Regular.woff2") format("woff2"),
	     url("https://cdn.jsdelivr.net/gh/kaspernordkvist/uncut_sans/Webfonts/Uncut-Sans-Regular.woff") format("woff");
	font-display: swap
}
```

Enable OpenType features in CSS
| Command | Description |
| --- | --- |
| Alternate R | `.text { font-feature-settings: "ss01";}` |
| Alternate Y and y | `.text { font-feature-settings: "ss02";}` |
| Alernative Q, Ø, and ø | `.text { font-feature-settings: "ss03";}` |
| Alernative a | `.text { font-feature-settings: "ss04";}` |
| Alernative 1, 2, and 4 | `.text { font-feature-settings: "ss05";}` |
| Alternate !, ?, and * | `.text { font-feature-settings: "ss06";}` |
| Round punctuation | `.text { font-feature-settings: "ss07";}` |
| Alternate arrows | `.text { font-feature-settings: "ss08";}` |
