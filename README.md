---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: dfebcdb0a6485b98fc73c7f97b4204db_c7700258660611f18b225254006c9bbf
    ReservedCode1: V6nI9wNXD5Osurcl4nTrZ9lUKkhC9ReIkJywq2JfzHHKo1o4IFLIqqTeQKyKlufEmLN6w0aQ52WYf6uhDAevGXRsCqhHtXzzP1AA6V9zLDtPLEp7fyB9hH5P4OKX1LOYwzSAeRT/+Ufb8i1d97maaX0L5F3fcOH4E6I/zXSMaVeRPgmTaqLo0N6pf1I=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: dfebcdb0a6485b98fc73c7f97b4204db_c7700258660611f18b225254006c9bbf
    ReservedCode2: V6nI9wNXD5Osurcl4nTrZ9lUKkhC9ReIkJywq2JfzHHKo1o4IFLIqqTeQKyKlufEmLN6w0aQ52WYf6uhDAevGXRsCqhHtXzzP1AA6V9zLDtPLEp7fyB9hH5P4OKX1LOYwzSAeRT/+Ufb8i1d97maaX0L5F3fcOH4E6I/zXSMaVeRPgmTaqLo0N6pf1I=
---

# 探囊取物 - 网页视频批量抓取工具

一键下载网页中的视频，支持 M3U8 流媒体、MP4 直链、yt-dlp 万能模式，自动合并 TS 片段。

## 功能

- 批量粘贴网页地址，一行一个
- 自动识别页面视频：M3U8 流媒体 / MP4 直链
- 多线程并发下载 TS 片段，速度拉满
- 内置 ffmpeg 自动合并为完整 MP4
- 内置 yt-dlp 兜底，覆盖更多网站
- 实时进度条 + 时间戳日志
- 支持中途停止

## 使用方法

1. 解压 `探囊取物.zip`
2. 将 `ffmpeg.exe` 和 `探囊取物.exe` 放在同一目录
3. 双击运行 `探囊取物.exe`
4. 在"网页地址"框中粘贴视频播放页 URL，每行一个
5. 选择保存目录（默认 `下载/探囊取物`）
6. 点击 **全部下载**

## 系统要求

- Windows 10/11 64 位
- 无需安装 Python 或任何依赖

## 常见问题

**Q：下载完提示"片段保留在 .tmp_xxx"？**
A：ffmpeg 合并失败。检查 ffmpeg.exe 是否与主程序在同一目录。

**Q：某些网站下不了？**
A：工具会自动尝试 yt-dlp 万能模式兜底。如果仍然失败，可能是网站有反爬机制。

## 免责声明

本工具仅供学习交流，请勿用于下载版权保护内容。使用者自行承担法律责任。
