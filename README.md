```diff
   ___  ________   ________ ___  ________   ___  _________  ___      ___   
  |\  \|\   ___  \|\  _____\\  \|\   ___  \|\  \|\___   ___\\  \    /  /|   
  \ \  \ \  \\ \  \ \  \__/\ \  \ \  \\ \  \ \  \|___ \  \_\ \  \  /  / /  
   \ \  \ \  \\ \  \ \   __\\ \  \ \  \\ \  \ \  \   \ \  \ \ \  \/  / /   
    \ \  \ \  \\ \  \ \  \_| \ \  \ \  \\ \  \ \  \   \ \  \ \ \    / /    
     \ \__\ \__\\ \__\ \__\   \ \__\ \__\\ \__\ \__\   \ \__\ \ \__/ /     
      \|__|\|__| \|__|\|__|    \|__|\|__| \|__|\|__|    \|__|  \|__|/      
                                                                           
                                                                           
                        The Big Screen Experience                          
```

This theme is designed with a strong focus on htpc setups using Jellyfin Desktop as the client, while fully supporting both desktop and mobile devices.

## Key features

- A minimalist TV-mode UI optimized for remote control and keyboard navigation
- A redesigned mobile interface placing key elements within easy thumb reach
- Custom cards with a smoother overall appearance and custom animations
- Consistently centered menus, pages, and titles where appropriate
- Improved use of previously unused screen space, especially in TV mode
- A new, compact player OSD on sufficiently wide displays
- Full support for user-defined colors, transparency, and background images
- Many additional small and large refinements throughout the UI

Give it a try!

## Apply

Add the following to your custom branding

```css
@import url('https://cdn.jsdelivr.net/gh/albervad/infinitv@main/infinitv.css');
@import url('https://cdn.jsdelivr.net/gh/albervad/infinitv@main/infinitv-mobile.css');
```

## Customize

Give it your style by changing `:root` values:
- Accent color: `--accent-h: 212` > use the `H` value from an HSL-color picker
- Set your wallpaper with `--bgImage: url("https://picsum.photos/1920/1080")`
- Set background darkness from `0.00` to `1.00`
- Set opacity from `1.00` to `0.00`
- Give roundings more radius
- Optional: delay pause-screen overlay with `--pause-screen-delay: 4s`

Example:

```css
:root {
  --accent-h: 212;
  --accent-s: 92%;
  --accent-l: 56%;

  --bgImage: url("https://www.solidbackgrounds.com/images/1920x1080/1920x1080-black-solid-color-background.jpg");

  --bgdarkness: 0.6;
  --headeropacity: 0.7;
  --itemopacity: 0.8;

  --rounding-media: 12px;
  --rounding-system: 6px;

  --pause-screen-delay: 4s;
}
```

## Optimal Results

- [Jellyfin Desktop v2.0.0](https://github.com/jellyfin/jellyfin-desktop/releases)
- Set `theme` to `Dark`
- Set `display mode` to `TV`

> Or use a modern, chromium based webbrowser

# TV-Mode Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/home-tv.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/movie-tv.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/movies-tv.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/tvshows-tv.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/show-tv.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/season-tv.png"></td>
  </tr>
</table>


# Desktop Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/desktop-drawer.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/desktop-tvhows.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/desktop-show.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/desktop-movie.png"></td>
  </tr>
</table>


# Mobile Screenshots

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/mobile-home.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/mobile-drawer.png"></td>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/mobile-tvshows.png"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/albervad/infinitv/refs/heads/main/resource/mobile-show.png"></td>
     <td></td>
     <td></td>
  </tr>
</table>


## Disclamer

*This is a hobby project to expand my basic knowledge of CSS. Therefore, it does not claim to be complete or bug-free. Ideas and problems will be addressed when free time allows.*

