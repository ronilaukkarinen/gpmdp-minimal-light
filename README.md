# Minimal Light theme for Google Play Music

## *Make Google Play Music User Interface great again!*

Light, minimal theme for [Google Play Music Desktop Player](https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-).

### Features

- Hides all menus and "I'm Feeling Lucky by default", show them on hover
- Hides top bar when inactive
- Hides most of the player icons by default, show on hover
- More minimal typography
- Concentrates on cover art and artist images
- Fresher accent color

### Screenshots

![Screenshot](https://i.imgur.com/9VzZ4TW.png "Screenshot")

![Screenshot](https://i.imgur.com/lM4EB6d.png "Screenshot")

![Screenshot](https://i.imgur.com/FUsERDi.png "Screenshot")

![Screenshot](https://i.imgur.com/wfD28qS.png "Screenshot")

![Screenshot](https://i.imgur.com/ENAuL1N.png "Screenshot")

### Usage

1. Clone this repo
2. Go to Desktop Settings
3. **Main app**: Browse and select main-app.css
4. **Google Play Music**: Browse and select theme.css

### Fonts

Avenir fonts are commercial and the license prevents me to include it in this repo. If you have Avenir hosted, you can add it by renaming `src/_webfonts.scss.dist` without .dist suffix and compile SCSS.

### Development

1. Fork this repo
2. cd to were you cloned it
3. Run `npm install`
4. Run `gulp watch` (ignore the popup)
5. Inspect, edit save
6. Use compiled theme.css to test