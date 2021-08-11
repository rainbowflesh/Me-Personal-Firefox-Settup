# Me Personal Firefox Settup
 火狐客制化

使用:

https://github.com/spencerwooo/firefox-overlay-scrollbar

https://github.com/stonecrusher/simpleMenuWizard

https://github.com/muckSponge/MaterialFox

-----

禁用下列内容

+ @import "global/global.css"; 

+ @import "icons/icons.css";

修改下列内容

tabbar.css: 

    .tab-close-button
        {
            list-style-image: url(close-tab.svg) !important;
            width: 20px !important;
            height: 20px !important;
            margin: 0 !important;
            padding: 0 !important;
        }

还有一个搜索框的高度忘了在哪了, 且用且改