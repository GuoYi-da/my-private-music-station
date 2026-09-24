# 我的私人音乐台

一个采用复古电台风格的三页静态音乐网站。首页介绍电台，曲库提供五首可以直接播放的音乐，关于页列出曲目来源与授权。

## 本地运行

直接打开 `index.html` 即可浏览。也可以在项目目录运行：

```bash
python -m http.server 8765
```

然后访问 `http://127.0.0.1:8765/index.html`。

## 页面与音频

- `index.html`：首页和精选歌曲入口
- `music.html`：五首歌曲的 HTML5 原生播放器
- `about.html`：网站简介、作者署名与许可信息
- `styles.css`：三页共用的响应式样式
- `assets/audio/`：每首歌曲的 MP3 和 Ogg 文件

音乐由 Kevin MacLeod 创作，均按 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 使用。曲目文件及逐首来源链接见 [关于页](about.html)。MP3 文件使用 Wikimedia Commons 提供的 Ogg 转码版本；本站未剪辑曲目内容。
