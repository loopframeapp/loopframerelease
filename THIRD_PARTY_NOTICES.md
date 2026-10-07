# Third-party software in Furiko

Furiko bundles or downloads the following programs. Except for Sparkle, which is
linked into the app, they run as separate processes.

| Component | Version | License | Source |
|-----------|---------|---------|--------|
| FFmpeg / FFprobe (static builds by eugeneware/ffmpeg-static, GPL-enabled) | FFmpeg 6.0 (ffmpeg-static tag b6.1.1) | GNU GPL v2 or later | https://ffmpeg.org/download.html and https://github.com/eugeneware/ffmpeg-static |
| yt-dlp | latest at build time; updatable in Settings | The Unlicense | https://github.com/yt-dlp/yt-dlp |
| Deno | 2.9.7 | MIT | https://github.com/denoland/deno |
| bgutil-ytdlp-pot-provider (plugin and server) | 2.0.0 | GNU GPL v3 | https://github.com/Brainicism/bgutil-ytdlp-pot-provider |
| Sparkle (in-app updater framework) | 2.10.0 | MIT (with bundled third-party notices) | https://github.com/sparkle-project/Sparkle |

## Source code offer (GPL)

FFmpeg and the bgutil provider are distributed under the GNU General Public
License. The complete corresponding source for the exact versions above is
available at the URLs listed. For three years from the date you received
Furiko you can also request a copy of that source by opening an issue at
https://github.com/loopframeapp/loopframerelease/issues.

FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project.
The full license texts are available at:

- GPL v2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt
- GPL v3: https://www.gnu.org/licenses/gpl-3.0.txt
- MIT (Deno): https://github.com/denoland/deno/blob/main/LICENSE.md
- MIT (Sparkle): https://github.com/sparkle-project/Sparkle/blob/2.x/LICENSE
- Unlicense (yt-dlp): https://unlicense.org
