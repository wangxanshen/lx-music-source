# LX Music 自定义音源（gdstudio）

基于 [music-api.gdstudio.xyz](https://music-api.gdstudio.xyz) 的洛雪音乐自定义音源脚本，提供多平台音乐播放链接。

## 导入链接

在洛雪音乐 **设置 → 基本设置 → 音乐来源 → 自定义源管理 → 在线导入** 中输入以下任一链接：

```
https://raw.githubusercontent.com/wangxanshen/lx-music-source/main/gdstudio-source.js
```

或 CDN 加速：

```
https://fastly.jsdelivr.net/gh/wangxanshen/lx-music-source@main/gdstudio-source.js
```

```
https://gcore.jsdelivr.net/gh/wangxanshen/lx-music-source@main/gdstudio-source.js
```

## 功能

- 支持 wy（网易云）、kw（酷我）、tx（QQ 音乐）、kg（酷狗）、mg（咪咕）五个音源
- 多音质：128k / 320k / FLAC / FLAC 24bit，不可用时自动降级
- 搜索结果缓存，减少重复请求

## 致谢

- [lyswhut/lx-music-desktop](https://github.com/lyswhut/lx-music-desktop)
- [music-api.gdstudio.xyz](https://music-api.gdstudio.xyz)

## 免责声明

本项目仅供学习交流，不得用于商业用途。使用者应遵守相关法律法规和第三方 API 服务条款。
