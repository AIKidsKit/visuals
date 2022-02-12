## Using Custom Fonts

 * Upload font to a server.
 * Define font in CSS `@font-face { font-family: YOUR-FONT-NAME; src: url(YOUR-FONT-URL); }`
 * Use font by applying rule in CSS `body { font-family: YOUR-FONT-NAME; }`

Here's how we are using it in *this* repo - visit the [GitHub Pages](https://aikidskit.github.io/visuals/#/) site to see it in action:

```html
  <style>
    @font-face { font-family: Asterix; src: url('fonts/Asterix.ttf'); } 
    body {
       font-family: Asterix
    }
  </style>
```

---

| Name | Description |
|:---|:---|
| [Asterix](https://aikidskit.github.io/visuals/fonts/Asterix.ttf) | Custom font from kid - regular writing example |
| [StarryWrites](https://aikidskit.github.io/visuals/fonts/StarryWrites.ttf) | Custom font from kid - whimsical writing example |
| [cursiveme](https://aikidskit.github.io/visuals/fonts/cursiveme.ttf) | Custom font from adult -  cursive writing example |
