# ConvertAllLocal - EN
[FR_Readme.md](https://github.com/SandersonnDev/ConvertAllLocal/blob/f5e8fc8b47bf5c9c88bc3f16a1c75da0e2d3dd4a/Readme.md)

ConvertAllLocal is a local application that converts all the most used video, image, and icon formats in web and application development, without downloading or sending files to external services.

## Features
- **100% local conversion**: Everything happens on your machine (via FFmpeg for video/audio, ImageMagick/Sharp for images).
- **Supported formats**: Covers 95% of modern web/app needs.
- **Simple interface**: Drag & drop or file selection, output format choice, 1-click conversion.
- **Batch processing**: Convert multiple files at once.
- **Web optimized**: Presets for sizes/resolutions (ex: WebP 80% quality, MP4 H.264).
- **No internet required**: Works offline after installation.

## Supported Formats

### Video
| Format | Main use | Advantages |
|--------|----------|------------|
| MP4 (H.264) | Web, YouTube, mobile apps | Universal, smooth streaming |
| WebM (VP9/AV1) | Open-source sites (Chrome/Firefox) | Low bandwidth |
| MOV | iOS/macOS | Native Apple |
| MKV | Multi-track apps | Flexible subtitles/audio |
| AVI/FLV | Legacy files | Backward compatibility |

### Images & Icons (Web + Multi-OS)
| Format | Main use | Web | Windows | macOS | Linux |
|--------|----------|-----|---------|-------|-------|
| **JPEG** | Photos | ✅ | ✅ | ✅ | ✅ |
| **PNG** | Logos, graphics, icons | ✅ | ✅ | ✅ | ✅ |
| **WebP** | Modern optimized | ✅ | ✅ Win10+ | ✅ | ✅ |
| **AVIF** | 2026+ standard | ✅ | ✅ Win11 | ✅ Ventura+ | ✅ |
| **GIF** | Short animations | ✅ | ✅ | ✅ | ✅ |
| **SVG** | Responsive UI, icons | ✅ | ✅ | ✅ | ✅ |
| **ICO** | Favicons, Windows apps | ✅ | ✅ Native | ❌ | ❌ |
| **ICNS** | macOS app icons | - | ❌ | ✅ Native | ❌ |
| **PNG 256x256** | Linux app icons | ✅ | ✅ | ✅ | ✅ Native |

**Suggested presets**: ICO (Windows), ICNS (macOS), PNG 256x256 (Linux), WebP/SVG (modern web).
