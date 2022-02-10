# Visualize-AI Kit

Repository with useful visual assets that can be used by educators, parents and community - to help teach these concepts and have conversations with kids in meaningful ways.

All folder names are relative to `/docs` base folder:

| Folder | Purpose |
|:--- |:--- |
| zines  | Printable sheets that can be folded into zines for handing out to students. |
| videos | Timelapse or animated videos that help explain concepts visually |
| tiles  | Individual visual tiles that can be assembled into zines, reused in videos |
| slides | Powerpoint assets with embedded visuals that are accessible, with custom fonts |
| fonts  | Custom fonts that convert visual writing into accessibility-friendly text |


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
| [Asterix](https://aikidskit.github.io/visuals/fonts/Asterix.ttf) | Custom font created in FontMaker by a middle-schooler |
