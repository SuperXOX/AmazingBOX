# 自用直播源📺️

目前这个时代，家庭看电视的人越来越少，而且各大运营商也都开启IPTV业务，家庭现在看电视的也是部分老人而已。

但是，有部分刚需的用户，如：足球直播、篮球直播、运动会直播、某些电视剧、新闻等突然需要看直播却无从入手。

现整理一份基本需求项目，希望能帮助有需要的人，这样无论在PC、iOS、MacOS、安卓、以及各电视平台都能立即实现观看的直播源方案。

## 目录

- [URL](#🌐稳定地址)
- [各平台软件壳](#💾各平台软件壳)
- [自行搜索数据源](#🪜自行搜索数据源)
- [台标徽标](#📺台标徽标)
- [EPG电子节目单](#📋EPG电子节目单)
- [国内外开源项目参考](#📚国内外开源项目参考)
  
## 🌐稳定地址

全球最大的IPTV开源项目地址（稳定更新）:

- [收集来自世界各地8000多个公开可用的IPTV](https://github.com/iptv-org/iptv)

自用自己更新的IPTV源:

- 自己首次开发的m3u[CCTV - 1-6.m3u](https://raw.githubusercontent.com/SuperXOX/BOX/master/M3U/CCTV%20-%201-6.m3u)
- 稳定含IPv6链的源主打央视TV[IPv6主打央视.m3u](https://raw.githubusercontent.com/SuperXOX/BOX/master/M3U/%E8%87%AA%E7%94%A8%E5%85%A8IPTV.m3u)

## 💾各平台软件壳

支持IPTV流的应用程序。

<details>
<summary>细分平台</summary>
<p>

 ### Windows

 - [VLC for Windows](https://www.videolan.org/vlc/download-windows.html) 免费开放源代码的便携式跨平台媒体播放器。
 - [Kodi](https://kodi.tv/) 具有库支持的免费跨平台媒体播放器。
   - [IPTV Simple PVR](https://kodi.tv/addon/pvr-client/pvr-iptv-simple-client) - Kodi的IPTV直播电视和广播PVR客户端插件。

 ### MacOS

 - [VLC for Mac OS X](https://www.videolan.org/vlc/download-macosx.html) 免费和开放源代码的便携式跨平台媒体播放器。
 - [IINA](https://iina.io/) - 适用于macOS的现代媒体播放器。
 - [Kodi](https://kodi.tv/) - 具有库支持的免费跨平台媒体播放器。
   - [IPTV Simple PVR](https://kodi.tv/addon/pvr-client/pvr-iptv-simple-client) - Kodi的IPTV直播电视和广播PVR客户端插件。

 ### AppleTV

 - [iPlayTV](https://apps.apple.com/us/app/iplaytv/id1072226801)
   - 食用指南
     1. 打开iPlayTV 点击 ➕号;
     2. 选择 Remote Playlist File;
     3. 第一行随意输入一个名字;
     4. 第二行输入上面给你的地址;
     5. 第三行不用管;
     6. 点 save 即可;

 ### iOS

 - [GSE SMART IPTV](https://apps.apple.com/us/app/gse-smart-iptv/id1028734023) 完整的用户定义的高级IPTV解决方案，用于实时和非实时电视/流。
 - [Movie Stream: Watch Smart IPTV ](https://apps.apple.com/us/app/movie-stream-ip-tv-films/id1450912244) - 启用Chromecast的应用程序，可让您将收藏的视频从移动设备流式传输到电视。
 - [nPlayer](https://apps.apple.com/cn/app/nplayer/id1116905928) - 支持播放列表文件：CUE、M3U、PLS

 ### Android

 - [NET IP TV](https://play.google.com/store/apps/details?id=com.dnamedya.netiptv)
 - [Kodi](https://kodi.tv/) 具有库支持的免费跨平台媒体播放器。
  - [IPTV Simple PVR](https://kodi.tv/addon/pvr-client/pvr-iptv-simple-client) - Kodi的IPTV直播电视和广播PVR客户端插件。

 ### PlayStation 4 / Xbox One

 - [Plex](https://www.plex.tv/apps-devices/#modal-devices-playstation-4) 客户端服务器媒体播放器。为了通过Plex App观看IPTV，可以使用 [Cigaras / IPTV.bundle](https://github.com/Cigaras/IPTV.bundle) 插件。

</p>
</details>

## 🪜自行搜索数据源

- [电视直播源搜索引擎](https://www.foodieguide.com/iptvsearch/) - 国内外电视频道直播源搜索，m3u8、flv、rtsp、rtmp、txt直播源链接地址每日更新

## 📺台标徽标

- [国内台标徽标站](https://live.fanmingming.com/e.xml) - 此站点仅为国内台标徽标站点，使用方法详见：国内外开源项目参考第一项

## 📋EPG电子节目单

- [一个全球 EPG 电视节目表](https://epg.pw/test_channel_page.html) - 目前较好用的电视节目表

## 📚国内外开源项目参考

- [一个可直连访问的电视/广播图标库与相关工具项目](https://live.fanmingming.com/) - ✯ 🔕 永久免费 直连访问 完整开源 不断完善的台标 支持IPv4/IPv6双栈访问 🔕
