# Miras Studio

Portfolio of Miras Kaliyev: dialogue restoration, voice finishing and audio mixing for video.

## Develop

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
```

The `dist/` folder is a standalone static website ready for GitHub Pages. All asset paths are relative, including video, subtitles and fonts. No API keys, login or server are required.

## Credits

Footage: Cinestudy / Sonnyboo Productions, Restaurant Scene, written and directed by Peter John Ross. Full film credits are included in the website footer. https://cinestudy.org/2019/01/28/restaurant-scene/

Music: “Heartbreaking” — Kevin MacLeod (incompetech.com), Creative Commons Attribution 4.0. Edited excerpt with fades, EQ/level adjustments and dialogue ducking. https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1100208

Fonts: Cormorant Garamond and Manrope, OFL licenses included in public/fonts.

Source code and practice footage are not offered under an unrestricted license. The original assets remain subject to their respective terms.

## Published repository

The compiled website is published from the root of the main branch using GitHub Pages. `miras-studio-source.zip` contains the editable React/Vite project. To rebuild, extract it and copy the three `wide-*.mp4` files from this repository into `public/media/`, then run `npm ci` and `npm run build`.
