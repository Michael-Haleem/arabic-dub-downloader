# Arabic Video Downloader

A portable Windows tool that downloads YouTube videos **with the Arabic (auto-dubbed) audio track**, for offline watching. It verifies the downloaded audio really is Arabic (YouTube sometimes serves mislabeled streams), and falls back to the original audio when a video has no Arabic track.

## Download

**[Direct download (zip, 162 MB)](https://github.com/Michael-Haleem/arabic-dub-downloader/releases/download/v1.0/arabic-dub-downloader.zip)**

## Setup (one time)

1. Download the zip with the link above.
2. Right-click the zip -> **Properties** -> tick **Unblock** (if shown) -> OK.
3. Right-click the zip -> **Extract All** -> extract to the Desktop.

## Daily use

1. Open the extracted folder and double-click **`Download Arabic Video.bat`**.
2. Paste a YouTube link, press Enter.
3. Press Enter again for best quality (or type e.g. `720`).
4. The finished video appears in the **Downloaded Videos** folder.

`Check Arabic Dub.bat` tells you whether a video or channel has Arabic tracks before downloading. If downloads ever stop working, run `Update Tools.bat` once.

Requires 64-bit Windows 10/11 and an internet connection. Built on the open-source tools [yt-dlp](https://github.com/yt-dlp/yt-dlp), [FFmpeg](https://github.com/yt-dlp/FFmpeg-Builds) and [Deno](https://deno.com). See `README.txt` inside the zip for full details.