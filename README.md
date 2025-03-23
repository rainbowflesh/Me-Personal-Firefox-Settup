# The SideFox

A cutting edge (yes) firefox custom theme, Feature with fancy sidebar, mica & acrylic effect, less tweak, more default.

<img src="./asset/sidebar.gif" width="720px"/>

## Install

### Steps

1. Install [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) (\*Optional, supporting and tested)
2. Copy everything from `sidebar_extensions/sidebery.css` to [Sidebery styles editor](moz-extension://e4229f2c-09a8-4adb-ae4c-66435999c4d7/page.setup/setup.html#styles_editor)
3. Go [about:config](about:config) then add below:

```cfg
gfx.webrender.all = true

layout.css.backdrop-filter.enabled = true

layout.css.backdrop-filter.enabled-force = true

toolkit.legacyUserProfileCustomizations.stylesheets = true

svg.context-properties.content.enabled = true

layout.css.color-mix.enabled = true

uc.tweak.hide-tabs-bar = true

browser.tabs.allow_transparent_browser = true

sidebar.revamp = true

widget.windows.mica.popups = true

<!-- ====== Optional ====== -->

<!-- Icon only extension menu -->
uc.tweak.iconOnlyExtensionMenu = true

<!-- mica for everyone -->
uc.tweak.win11-mica = true

```

### Another way

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

### Tweaking

## Themes

[![赞美太阳](https://addons.mozilla.org/user-media/version-previews/full/3882/3882953.svg)](https://addons.mozilla.org/en-US/firefox/addon/prise-the-sun-dark-souls/)

[![猫耳初音](https://addons.mozilla.org/user-media/version-previews/full/3860/3860107.svg)](https://addons.mozilla.org/en-US/firefox/addon/neko-miku-theme/)

[![pekora](https://addons.mozilla.org/user-media/version-previews/full/3908/3908060.png)](https://addons.mozilla.org/en-US/firefox/addon/pekora-theme/)

[![变身初音](https://addons.mozilla.org/user-media/version-previews/full/3860/3860113.svg)](https://addons.mozilla.org/en-US/firefox/addon/yet-another-mikutheme/)

[![米其林](https://addons.mozilla.org/user-media/version-previews/full/3860/3860121.svg)](https://addons.mozilla.org/en-US/firefox/addon/run-michirun-run-theme/)

[![圆形 nyan](https://addons.mozilla.org/user-media/version-previews/full/3860/3860590.png)](https://addons.mozilla.org/en-US/developers/addon/fat-nyan-theme/)

[![pop nyan](https://addons.mozilla.org/user-media/version-previews/full/3860/3860589.svg)](https://addons.mozilla.org/en-US/firefox/addon/pop-nyan-theme/)

## References

- [Firefox-Mod-Blur](https://github.com/datguypiko/Firefox-Mod-Blur), Firefox CSS Theme - For dark theme lovers / More compact / Modular / Blur.
- [Firefox-UWP-Style](https://github.com/Guerra24/Firefox-UWP-Style), Sun Valley + MDL2 Theme for Firefox.
- [Edge-FrFx](https://github.com/bmFtZQ/edge-frfox), Microsoft Edge style ui.
- [simpleMenuWizard](https://github.com/stonecrusher/simpleMenuWizard), this is why you right click context menu losing things.
