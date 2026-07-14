# mpv-config

MPV config featuring **uosc**, **thumbfast**, and **ArtCNN shaders**.

## Scripts

- **[uosc](https://github.com/tomasklaen/uosc)** — Modern UI replacing the default OSC. Line timeline, top bar, volume controls, menus, heatmap…
- **[thumbfast](https://github.com/po5/thumbfast)** — Fast thumbnail previews on timeline hover (integrated with uosc).

## Shaders

4 **ArtCNN** variants (based on [ArtCNN](https://github.com/Artoriuz/ArtCNN)) for anime upscaling:

| Key | Shader | Purpose |
|-----|--------|---------|
| `Ctrl+1` | `ArtCNN_C4F16.glsl` | Base (FP16) |
| `Ctrl+2` | `ArtCNN_C4F32.glsl` | Base (FP32) |
| `Ctrl+3` | `ArtCNN_C4F16_DS.glsl` | Denoise + Sharpen (FP16) |
| `Ctrl+4` | `ArtCNN_C4F32_DS.glsl` | Denoise + Sharpen (FP32) |
| `Ctrl+0` | Disable all shaders | |

## Features

- Default **`high-quality`** profile, `vo=gpu-next`, `hwdec=auto-safe`
- **Keybinds**: seek 5s/60s, speed ±0.25/±0.05, rotate video, cycle deband, crop (modernx), seek-to (thumbfast)
- **uosc**: line timeline, progress bar in windowed mode, no-border top bar, volume on the right, type-to-search menus
- Thumbnails at 200×200, auto tone-mapping
