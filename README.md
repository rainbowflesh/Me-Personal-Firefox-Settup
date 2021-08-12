# Me Personal Firefox Settup
 火狐客制化

## 浏览器本体客制化使用:

https://github.com/spencerwooo/firefox-overlay-scrollbar

https://github.com/stonecrusher/simpleMenuWizard

https://github.com/muckSponge/MaterialFox

-----

## 禁用下列内容

+ @import "global/global.css"; //这个不禁用所有图标下面会有个黑圈, 很啥b //todo: 单独解决黑圈问题然后启用这个吸assass

## 修改下列内容

tabbar.css: 

    .tab-close-button
        {
            list-style-image: url(close-tab.svg) !important;
            width: 20px !important;
            height: 20px !important;
            margin: 0 !important;
            padding: 0 !important;
        }

这个是改标签关闭按钮大小的, 原版我记得是16px, 但是新建按钮是20, 这强迫症能忍?

还有一个搜索框的高度忘了在哪了, 且用且改

## 可选项
在about:config中开启layout.css.backdrop-filter.enabled, 体验一部分弹出彩蛋的背景毛玻璃透明
// 不开就没有, 是纯色


## 推销插件:
// 顺带推销我自己收集的[屏蔽规则][rule]
+ [uBlacklist][1] 屏蔽搜索引擎不想要的结果 
+ [uBlock][2] 屏蔽网页元素
+ [Dark Reader][3] 网页黑背景
+ [Startup Theme Changer][4] 开机自动切换主题, 用来让我快乐更换9个主题
+ [Nyan Cat ytb][5] ytb进度条换成nyan猫
+ [Smart Prevent Duplicate tab][6] 自动关闭重复标签
- 待续

## 推销主题
[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860093.svg?modified=1628748740 "赞美太阳")](https://addons.mozilla.org/en-US/firefox/addon/prise-the-sun-dark-souls/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860127.svg?modified=1628758537 "猫猫!")](https://addons.mozilla.org/en-US/firefox/addon/lazy-cat-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860107.svg?modified=1628755709 "猫耳初音")](https://addons.mozilla.org/en-US/firefox/addon/neko-miku-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860115.svg?modified=1628757024 "vtb")](https://addons.mozilla.org/en-US/firefox/addon/pekora-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860113.svg?modified=1628756578 "变身初音")](https://addons.mozilla.org/en-US/firefox/addon/yet-another-mikutheme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860109.svg?modified=1628755886 "梓喵")](https://addons.mozilla.org/en-US/firefox/addon/animated-neko-azus-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860140.png?modified=1628759675 "sus")](https://addons.mozilla.org/en-US/firefox/addon/amongsus-thutheme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860121.svg?modified=1628757483 "米其林")](https://addons.mozilla.org/en-US/firefox/addon/run-michirun-run-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860132.png?modified=1628759122 "圆形nyan")](https://addons.mozilla.org/en-US/developers/addon/fat-nyan-theme/edit)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860136.png?modified=1628759532 "pop nyan")](https://addons.mozilla.org/en-US/firefox/addon/pop-nyan-theme/)

[![img](https://addons.cdn.mozilla.net/user-media/version-previews/full/3860/3860139.svg?modified=1628759616 "跳舞鲨鱼")](https://addons.mozilla.org/en-US/firefox/addon/left-shark-dance-theme/)


[1]: https://addons.mozilla.org/en-US/firefox/addon/startup-theme-changer/?utm_content=addons-manager-reviews-link&utm_medium=firefox-browser&utm_source=firefox-browser
[2]: https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/
[3]: https://addons.mozilla.org/en-US/firefox/addon/darkreader/
[4]: https://addons.mozilla.org/en-US/firefox/addon/startup-theme-changer/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[5]: https://addons.mozilla.org/en-US/firefox/addon/nyan-cat-youtube-enhancement/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[6]: https://addons.mozilla.org/en-US/firefox/addon/smart-prevent-duplicate-tabs/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[rule]: https://github.com/isNijikawa/Universal-Web-Filter-rules