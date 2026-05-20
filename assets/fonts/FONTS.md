# Fonts Folder

Store custom fonts here.

## What to Add

- Downloaded font files
- Brand fonts
- Custom typography

## Supported Formats

```txt
WOFF2 (Recommended)
WOFF
TTF
OTF
```

## Folder Example

```txt
fonts/
├── Poppins-Regular.ttf
├── Poppins-Bold.ttf
└── Inter-Regular.ttf
```

## Download Fonts

Fonts can be downloaded from:

- Google Fonts
- Adobe Fonts
- Design team exports
- Figma specifications

## Using Fonts in CSS

Example:

```css
@font-face {
  font-family: "Poppins";
  src: url("./assets/fonts/Poppins-Regular.ttf");
}

body {
  font-family: "Poppins", sans-serif;
}
```

## Figma Font Reference

Before downloading fonts:

1. Open Figma.
2. Select text element.
3. Check:

```txt
Typography → Font Family
Typography → Font Weight
```

4. Download required font family.
5. Add files into:

```txt
assets/fonts/
```
