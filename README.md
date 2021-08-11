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

## 推销插件:
// 顺带推销我自己收集的[屏蔽规则][rule]
+ [uBlacklist][1] 屏蔽搜索引擎不想要的结果 
+ [uBlock][2] 屏蔽网页元素
+ [Dark Reader][3] 网页黑背景
+ [Startup Theme Changer][4] 开机自动切换主题, 用来让我快乐更换9个主题
+ [Nyan Cat ytb][5] ytb进度条换成nyan猫
+ [Smart Prevent Duplicate tab][6] 自动关闭重复标签
- 待续


[1]: https://addons.mozilla.org/en-US/firefox/addon/startup-theme-changer/?utm_content=addons-manager-reviews-link&utm_medium=firefox-browser&utm_source=firefox-browser
[2]: https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/
[3]: https://addons.mozilla.org/en-US/firefox/addon/darkreader/
[4]: https://addons.mozilla.org/en-US/firefox/addon/startup-theme-changer/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[5]: https://addons.mozilla.org/en-US/firefox/addon/nyan-cat-youtube-enhancement/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[6]: https://addons.mozilla.org/en-US/firefox/addon/smart-prevent-duplicate-tabs/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search
[rule]: https://github.com/isNijikawa/Universal-Web-Filter-rules
