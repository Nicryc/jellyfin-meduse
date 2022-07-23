# Jellyfin Meduse

A custom and a personal interpretation CSS theme for Jellyfin.

## How to use?

### `icon-fix.css`
`icon-fix.css` is to fix Font Awesome Light icons related issues. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/icon-fix.css");
```

### `backdrop-blur.css`
`backdrop-blur.css` adds a background blur effect when navigating Jellyfin. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/backdrop-blur.css");
```

### `badge.css`
`badge.css` change the design of the badges (used in the dashboard mainly). To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/badge.css");
```

### `button.css`
`button.css` creates a pretty 3D effect on buttons when hovering them among some little fixes. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/button.css");
```

### `card.css`
`card.css` changes different elements in the cards (used to present medias) mainly the border radius. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/card.css");
```

### `color.css`
`color.css` replaces accentuation colors by others. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/color.css");
```

### `input.css`
`input.css` slightly modifies text input, text area input and select input design. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/input.css");
```

### `jellyfin-custom-theme.css`
General and little modifications of Jellyfin. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/jellyfin-custom-theme.css");
```

### `keywords-position.css` (does not work)
Attempt to move the keywords and metadata providers links in the media detail pages below the poster. To load it:

```css
@import url("https://cdn.jsdelivr.net/gh/Nicryc/jellyfin-meduse@main/keywords-position.css");
```

It works badly though.

## Recommendation
I recommend to load the file in this order:
1. `jellyfin-custom-theme` (mandatory since it imports other CSS files)
2. `icon-fix`
3. `input`
4. `button`
5. `card`
6. `color`
7. `badge`
8. `backdrop-blur`
9. `keywords-position`

## Note
This theme doesn't intend to be cross-browser compatible and is only tested with Firefox.