我是安装教程详细版

## 准备在前
##### 初始化
1. 打开火狐, 访问 [about:profiles][2] .
2. 找到 Local Directory, 选择 Open Folder, 会打开一个文件夹.
3. 文件夹放回上一级, 会有一个叫 "巴拉巴拉.default-release" 的文件夹, 删掉.
4. 准备安装客制化👇

### 安装 win10 风格的滚动条
1. [下载仓库][3]
2. 解压文件, 然后进入 firefox 文件夹.
3. 把里面的 defaults 文件夹和 config.js 文件一并拖到 C:\Program Files\Mozilla Firefox 下 (即存放firefox.exe 的目录).
4. 进入初始化过程中访问的 "巴拉巴拉.default-release" 文件夹, 在里面创建一个文件夹, 起名为 "chrome"
5. 解压后文件里有个叫 "profile" 的文件夹, 把里面的 "userChrome" 文件夹和 "userChrome.js" 文件一并放到第四步创建的 "chrome" 文件夹里.
6. 启动火狐, 如果提示你安装火狐便正常安装.
7. 你好了.

退回原版:

修改userChrome.js 中

    userChrome.import("/userChrome/win10_scrollbars.uc.js", "UChrm");
    
到

    userChrome.import("/userChrome/custom_scrollbars.uc.js", "UChrm");
    
### 安装

[1]: about:config
[2]: about:profiles
[3]: https://github.com/spencerwooo/firefox-overlay-scrollbar/archive/refs/heads/master.zip

