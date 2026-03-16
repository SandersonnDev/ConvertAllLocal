# ConvertAllLocal - FR
[EN_Readme.md](https://github.com/SandersonnDev/ConvertAllLocal/blob/b9ca7b7e0815930338f5391ad77236c5f6d4a2dc/EN_Readme.md)

ConvertAllLocal est une application locale qui permet de convertir tous les formats vidéo, image et icônes les plus utilisés dans le web et le développement d'applications, sans téléchargement ni envoi de fichiers vers des services externes.

## Fonctionnalités
- **Conversion 100% locale** : Tout se passe sur votre machine (via FFmpeg pour vidéo/audio, ImageMagick/Sharp pour images).
- **Formats supportés** : Couvre 95% des besoins web/apps modernes.
- **Interface simple** : Drag & drop ou sélection fichier, choix format de sortie, conversion en 1 clic.
- **Batch processing** : Convertir plusieurs fichiers d'un coup.
- **Optimisé web** : Présets pour tailles/résolutions (ex: WebP 80% qualité, MP4 H.264).
- **Aucun internet requis** : Fonctionne offline après installation.

## Formats Supportés

### Vidéo
| Format | Usage principal | Avantages |
|--------|-----------------|-----------|
| MP4 (H.264) | Web, YouTube, apps mobiles | Universel, streaming fluide |
| WebM (VP9/AV1) | Sites open-source (Chrome/Firefox) | Bande passante faible |
| MOV | iOS/macOS | Natif Apple |
| MKV | Apps multi-pistes | Sous-titres/audio flexibles |
| AVI/FLV | Anciens fichiers | Compatibilité legacy |

### Images & Icônes (Web + Multi-OS)
| Format | Usage principal | Web | Windows | macOS | Linux |
|--------|-----------------|-----|---------|-------|-------|
| **JPEG** | Photos | ✅ | ✅ | ✅ | ✅ |
| **PNG** | Logos, graphismes, icônes | ✅ | ✅ | ✅ | ✅ |
| **WebP** | Moderne optimisé | ✅ | ✅ Win10+ | ✅ | ✅ |
| **AVIF** | 2026+ standard | ✅ | ✅ Win11 | ✅ Ventura+ | ✅ |
| **GIF** | Animations courtes | ✅ | ✅ | ✅ | ✅ |
| **SVG** | UI responsive, icônes | ✅ | ✅ | ✅ | ✅ |
| **ICO** | Favicons, apps Windows | ✅ | ✅ Natif | ❌ | ❌ |
| **ICNS** | Icônes apps macOS | - | ❌ | ✅ Natif | ❌ |
| **PNG 256x256** | Icônes apps Linux | ✅ | ✅ | ✅ | ✅ Natif |

**Présets suggérés** : ICO (Windows), ICNS (macOS), PNG 256x256 (Linux), WebP/SVG (web moderne).
