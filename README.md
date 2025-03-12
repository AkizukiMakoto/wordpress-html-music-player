# 🎵 自定义音频播放器模块 / Custom Audio Player Module

🌍 **选择语言 / Select Language:**  
🇨🇳 [中文](#-中文说明) | 🇺🇸 [English](#-english-version)

---

## 📜 中文说明 | Chinese Instructions

### 🎵 介绍 | Introduction
这是一个自定义的音频播放器模块，旨在替代 WordPress 或 HTML5 自带的简易播放器控件。  
经过不断改进和 AI 的帮助，已非常符合我的使用习惯。  

This is a custom audio player module designed to replace the default WordPress or HTML5 audio player.  
With continuous improvements and AI assistance, it now meets my needs perfectly.  

---

### 🔧 使用方法 | How to Use
1. **打开你的 WordPress 编辑器**，在写作台插入 **自定义 HTML**。  
   **Open your WordPress editor** and insert **custom HTML** in the writing area.
2. **粘贴以下代码** 到相应位置：  
   **Paste the following code** into the appropriate section.
3. **替换以下内容** | **Replace the following content**：
   - **封面图片URL / Cover Image URL**：替换 `"封面图片URL"` 为你的歌曲封面图片链接。  
     Replace `"Cover Image URL"` with your song's cover image link.
   - **歌曲标题 / Song Title**：替换 `"歌曲标题"` 为你的歌曲名称。  
     Replace `"Song Title"` with the name of your song.
   - **创作者主页链接 / Creator Homepage Link**：替换 `"创作者主页链接"` 为歌曲创作者主页的链接。  
     Replace `"Creator Homepage Link"` with the link to the creator's homepage.
   - **歌曲文件URL / Song File URL**：替换 `"歌曲文件URL"` 为你的音乐文件链接。  
     Replace `"Song File URL"` with the link to your music file.

---

### 📌 代码示例 | Example Code
```html
<div class="music-player-container">
    <div class="music-player">
        <div class="cover">
            <img src="封面图片URL" alt="歌曲封面 / Song Cover">
        </div>
        <div class="content">
            <div class="info">
                <div class="title">歌曲标题 / Song Title</div>
                <p class="artist">
                    <a href="创作者主页链接 / Creator Homepage Link" target="_blank" class="artist-link">创作者名字 / Creator Name</a>
                </p>
            </div>
            <div class="audio-wrapper">
                <audio controls>
                    <source src="歌曲文件URL / Song File URL" type="audio/mpeg">
                    您的浏览器不支持音频播放。 / Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </div>
</div>
