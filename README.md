# 🎵 自定义音频播放器模块 / Custom Audio Player Module

🌍 **选择语言 / Select Language:**  
🇨🇳 [中文](#📜-中文说明) | 🇺🇸 [English](#📜-english-version)

---

## 📜 中文说明

### 🎵 介绍
这是一个自定义的音频播放器模块，旨在替代 WordPress 或 HTML5 自带的简易播放器控件。  
经过不断改进和 AI 的帮助，已非常符合我的使用习惯。

### 🔧 使用方法
1. **打开你的 WordPress 编辑器**，在写作台插入 **自定义 HTML**。
2. **粘贴以下代码** 到相应位置：
3. **替换以下内容**：
   - **封面图片URL**：替换 `封面图片URL` 为你的歌曲封面图片链接。
   - **歌曲标题**：替换 `歌曲标题` 为你的歌曲名称。
   - **创作者主页链接**：替换 `创作者主页链接` 为歌曲创作者主页的链接。
   - **歌曲文件URL**：替换 `歌曲文件URL` 为你的音乐文件链接。

### 📌 示例代码
```html
<div class="music-player-container">
    <div class="music-player">
        <div class="cover">
            <img src="封面图片URL" alt="歌曲封面">
        </div>
        <div class="content">
            <div class="info">
                <div class="title">歌曲标题</div>
                <p class="artist">
                    <a href="创作者主页链接" target="_blank" class="artist-link">创作者名字</a>
                </p>
            </div>
            <div class="audio-wrapper">
                <audio controls>
                    <source src="歌曲文件URL" type="audio/mpeg">
                    您的浏览器不支持音频播放。
                </audio>
            </div>
        </div>
    </div>
</div>

📜 English Version
🎵 Introduction
This is a custom audio player module designed to replace the default WordPress or HTML5 audio player.
With continuous improvements and AI assistance, it now meets my needs perfectly.

🔧 How to Use
Open your WordPress editor and insert custom HTML in the writing area.
Paste the following code into the appropriate section:
Replace the following content:
Cover Image URL: Replace Cover Image URL with your song's cover image link.
Song Title: Replace Song Title with the name of your song.
Creator Homepage Link: Replace Creator Homepage Link with the link to the creator's homepage.
Song File URL: Replace Song File URL with the link to your music file.

<div class="music-player-container">
    <div class="music-player">
        <div class="cover">
            <img src="Cover Image URL" alt="Song Cover">
        </div>
        <div class="content">
            <div class="info">
                <div class="title">Song Title</div>
                <p class="artist">
                    <a href="Creator Homepage Link" target="_blank" class="artist-link">Creator Name</a>
                </p>
            </div>
            <div class="audio-wrapper">
                <audio controls>
                    <source src="Song File URL" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </div>
</div>
