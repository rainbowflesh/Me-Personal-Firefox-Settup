FF 137+ f*cked up everything... again
So I renew, 👉https://github.com/rainbowflesh/mimicfox
This repo no longer support.

# My Mega FireFox tWeak

The edge-frfox combine with sidebar!

Sidebar belike:
<img src="./asset/sidebar.gif" width="720px"/>

And, New feature! Sidebarfox now have dynamic tabbar switch which allow you change tab style in runtime!
<img src="./asset/sidebar_dynamic.gif" width="720px"/>

> To use this feat you need add `uc.tweak.hide-tabs-bar = true` to `about:config`

---

Edge style be like (FF v96):

![edgelike](./asset/preview.gif)

Compare with real edge:
![compare](./asset/compare.png)

- Minimal Firefox version: 91.0
- GTK and QT based DE also supported 😸 -- But you need some tweaks 😾

- [Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab)(\*Optional, supporting and tested)

- [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) (\*Optional, supporting and tested)

- [Tab Center Reforn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn) (\*Optional)

## Usage

### about:config

```cfg
gfx.webrender.all = true

layout.css.backdrop-filter.enabled = true

layout.css.backdrop-filter.enabled-force = true

toolkit.legacyUserProfileCustomizations.stylesheets = true

svg.context-properties.content.enabled = true

layout.css.color-mix.enabled = true

uc.tweak.hide-tabs-bar = true
```

### Install Themes

```bash
git clone https://github.com/rainbowflesh/Me-Personal-Firefox-Settup.git
cd Me-Personal-Firefox-Settup

# Make com-for-table in use,
# and get your profile path by visit
# about:profiles, which `Local Directory` is.
cp -r ./chrome $THEPROFILEPATH/chrome

# or use symbol link make upgrade easily
ln -S ./chrome $THEPROFILEPATH/chrome
```

### Configure sidebar addone's CSS

- **Tree Style Tab**: locate `Advanced`, Import [this](./chrome/treestyletab.css).
- **Sidebery**: copy&paste [this](./chrome/sidebery.css) to `Styles editor`

- **Tab Center Reforn** Import [this](./chrome/tabCenterReborn.css) CSS.

### Tweaking

#### Edge like smooth scrolling

Copy paste `user.js` to profile root folder, like

```txt
| - 01djcrd2.default/user.js
| - 01djcrd2.default/chrome/userChrome.css
```

#### Im lossing right click context menu items, WTF?!

oops, comment out first line in `userChrome.css`

#### If you hate sidebar, comment out:

```css
/* l:6  */
@import url("./SideBarFox/sidebar.css");
```

#### If youwanna auto hide side bar, uncomment last line:

```css
@import url("./SideBarFox/autohide.css");
```

#### If ya dono what canbe changed, issues me and I wll help ;-)

## Themeing!

[![赞美太阳](https://addons.mozilla.org/user-media/version-previews/full/3882/3882953.svg)](https://addons.mozilla.org/en-US/firefox/addon/prise-the-sun-dark-souls/)

[![猫耳初音](https://addons.mozilla.org/user-media/version-previews/full/3860/3860107.svg)](https://addons.mozilla.org/en-US/firefox/addon/neko-miku-theme/)

[![pekora](https://addons.mozilla.org/user-media/version-previews/full/3908/3908060.png)](https://addons.mozilla.org/en-US/firefox/addon/pekora-theme/)

[![变身初音](https://addons.mozilla.org/user-media/version-previews/full/3860/3860113.svg)](https://addons.mozilla.org/en-US/firefox/addon/yet-another-mikutheme/)

[![米其林](https://addons.mozilla.org/user-media/version-previews/full/3860/3860121.svg)](https://addons.mozilla.org/en-US/firefox/addon/run-michirun-run-theme/)

[![圆形 nyan](https://addons.mozilla.org/user-media/version-previews/full/3860/3860590.png)](https://addons.mozilla.org/en-US/developers/addon/fat-nyan-theme/)

[![pop nyan](https://addons.mozilla.org/user-media/version-previews/full/3860/3860589.svg)](https://addons.mozilla.org/en-US/firefox/addon/pop-nyan-theme/)

## References

- [Edge-FrFx](https://github.com/bmFtZQ/edge-frfox), Microsoft Edge style ui.
- [simpleMenuWizard](https://github.com/stonecrusher/simpleMenuWizard), this is why you right click context menu losing things.
