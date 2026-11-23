# Longshot Ocarina Recomp

Team MagicBean's static recompilation continuation of *Hookshot* (`MagicBeanDev/Longshot`). Rather than emulating console hardware at runtime, Longshot lowers Switch 2 *Ocarina of Time* ARM64 instructions into C and builds a native Vulkan executable.

<img width="1024" height="1024" alt="images1" src="https://github.com/user-attachments/assets/392ded8a-1c14-4079-b007-1879a74337fa" />
<img width="960" height="600" alt="images2" src="https://github.com/user-attachments/assets/1ea95305-06ad-478d-9fc4-fc55f5dd830f" />

## Static ARM64-to-C Translation (Zero Emulation Overhead)

* **5K, Ultrawide & Pre-Bloom AA**: Native 21:9/32:9 output with anchored 16:9 HUD, HDR, pre-bloom NVIDIA DLAA, DLSS, FSR 3.1/4, and 2x–8x frame generation.
* **Grass & Shader Pipeline**: Includes the `v3.1.1` grass-rendering performance hotfix alongside `All / Most / None` shader preparation modes.

<img width="3840" height="2160" alt="images3" src="https://github.com/user-attachments/assets/188068cf-8cb3-468d-9cc1-2fff32d1b6aa" />
<img width="3840" height="2160" alt="images4" src="https://github.com/user-attachments/assets/3b1919c6-c399-4e5e-bc52-c945472c1fe6" />



## High-Refresh Physics & Castle Town Uplifts

- **Castle Town Market Speedups**: `+29%` baseline uplift in `v3.0.0` followed by an extra `+37%` boost in `v3.1.0` with targeted gains on AMD Radeon and Intel Arc GPUs.
- **Uncapped Framerate Parity**: Resolved >60 FPS timing bugs affecting Epona fence jumps, Shadow Temple barges, water ripples, frozen Zoras, and cloth physics.

<img width="1280" height="720" alt="images5" src="https://github.com/user-attachments/assets/ac1aef23-a06b-442a-a08a-5d321ad8cca5" />

## Modding API & Launcher Setup

1. Launch **Longshot Launcher** (`v1.0.0+`) on a 6-core+ CPU with Vulkan 1.3 and supply your own legally dumped copy for one-time compilation.
2. Import existing *Hookshot* saves directly and configure RomFS mods or the new preliminary **Modding API** inside `renderer/longshot_options.ini`.
3. Hand-drawn DualSense/Xbox prompts, custom NFC tag dumping, and Discord Rich Presence work out of the box.

<img width="565" height="353" alt="images6" src="https://github.com/user-attachments/assets/4413592e-94a2-406d-a00f-2b83320247cc" />
