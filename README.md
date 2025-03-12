# 自定义音频播放器模块 / Custom Audio Player Module

这是一个自定义的音频播放器模块，旨在替代WordPress自带或HTML5自带的简易播放器控件。经过不断改进和AI的帮助，已非常符合我的使用习惯。

## 使用方法 / How to Use

1. 打开你的WordPress编辑器，在写作台插入自定义HTML。
2. 将以下代码粘贴到相应位置。
3. 请替换代码中的以下内容：
   - **封面图片URL**：替换为你的歌曲封面图片的链接。 
   - **歌曲标题**：替换为你歌曲的标题。
   - **创作者主页链接**：替换为歌曲创作者的主页链接。
   - **歌曲文件URL**：替换为你的歌曲文件链接。

### HTML代码示例 / HTML Code Example

```html
<div class="music-player-container">
    <!-- 音乐播放器区域 -->
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
            <!-- HTML5 原生音频控件 -->
            <div class="audio-wrapper">
                <audio controls id="audioPlayer">
                    <source src="歌曲文件URL" type="audio/mpeg">
                    您的浏览器不支持音频播放。 / Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </div>
</div>
