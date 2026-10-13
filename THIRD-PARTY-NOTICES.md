# Third-Party Notices

PAIA Robot includes the open-source components listed below. These components are not owned by PAIA Technology Inc. Each of them is licensed under its own license, not under the [PAIA Robot Software License Agreement](LICENSE.md). Nothing in that agreement limits the rights these licenses grant you.

This list covers the components bundled in the Windows and macOS installers of PAIA Robot.

## Components under LGPL or MPL

These components are dynamically loaded libraries or separate modules that can be replaced. As described in Section 6 of the License Agreement, you may modify and replace them, and reverse engineer the Software to the extent necessary to debug such modifications. You can get their source code from the links below, or request a copy from service@paia-tech.com. This offer is valid for at least three years after PAIA Technology Inc. last distributes the corresponding version of PAIA Robot.

| Component | Version | License | Source code |
| --- | --- | --- | --- |
| pygame | 2.6.1 | LGPL-2.1-or-later | https://github.com/pygame/pygame |
| FFmpeg (bundled with Electron) | Chromium 124 build | LGPL-2.1-or-later | https://chromium.googlesource.com/chromium/third_party/ffmpeg |
| FFmpeg (bundled with OpenCV) | 4.11 build | LGPL-2.1-or-later | https://ffmpeg.org/download.html, https://github.com/opencv/opencv-python |
| tqdm | 4.67.2 | MPL-2.0 AND MIT | https://github.com/tqdm/tqdm |

## Desktop application

| Component | License |
| --- | --- |
| [Electron](https://github.com/electron/electron) | MIT |
| [Chromium](https://www.chromium.org/) | BSD-3-Clause and others; the full list is in `LICENSES.chromium.html` in the installation directory |
| [Node.js](https://github.com/nodejs/node) | MIT and others |
| [Blockly](https://github.com/google/blockly) | Apache-2.0 |
| [Vue](https://github.com/vuejs/core), [Vue Router](https://github.com/vuejs/router), [Pinia](https://github.com/vuejs/pinia), [Vue I18n](https://github.com/intlify/vue-i18n) | MIT |
| [Quasar](https://github.com/quasarframework/quasar) | MIT |
| [Material Icons and Material Symbols](https://github.com/google/material-design-icons) (via @quasar/extras) | Apache-2.0 |
| [three.js](https://github.com/mrdoob/three.js) | MIT |
| [CodeMirror](https://github.com/codemirror/dev) | MIT |
| [highlight.js](https://github.com/highlightjs/highlight.js) | BSD-3-Clause |
| [markdown-it](https://github.com/markdown-it/markdown-it) | MIT |
| [Driver.js](https://github.com/kamranahmedse/driver.js) | MIT |
| [axios](https://github.com/axios/axios) | MIT |
| [Day.js](https://github.com/iamkun/dayjs) | MIT |
| [canvg](https://github.com/canvg/canvg) | MIT |
| [Azure Storage Blob SDK](https://github.com/Azure/azure-sdk-for-js) | MIT |
| [electron-store](https://github.com/sindresorhus/electron-store), [electron-dl](https://github.com/sindresorhus/electron-dl), [electron-context-menu](https://github.com/sindresorhus/electron-context-menu) | MIT |
| [update-electron-app](https://github.com/electron/update-electron-app) | MIT |
| [electron-squirrel-startup](https://github.com/mongodb-js/electron-squirrel-startup) | Apache-2.0 |
| [Squirrel.Windows](https://github.com/Squirrel/Squirrel.Windows) (Windows installer and updater) | MIT |

The application also includes the dependencies of these packages, all under permissive licenses: MIT, ISC, BSD-2-Clause, BSD-3-Clause, Apache-2.0, 0BSD, MIT-0, CC0-1.0, Unlicense, and Python-2.0.

## Simulator and AI training (Python runtime)

| Component | License |
| --- | --- |
| [Python](https://www.python.org/) | PSF-2.0 |
| [PyInstaller](https://github.com/pyinstaller/pyinstaller) bootloader and runtime hooks | Bootloader: GPL-2.0-or-later with the bootloader exception, which allows the bundled application to be distributed under any license; runtime hooks: Apache-2.0 |
| [MuJoCo](https://github.com/google-deepmind/mujoco) | Apache-2.0 |
| [PyTorch](https://github.com/pytorch/pytorch) | BSD-3-Clause |
| [NumPy](https://github.com/numpy/numpy), [SciPy](https://github.com/scipy/scipy), [pandas](https://github.com/pandas-dev/pandas), [scikit-learn](https://github.com/scikit-learn/scikit-learn) | BSD-3-Clause |
| [Matplotlib](https://github.com/matplotlib/matplotlib) | Matplotlib License (PSF-based); bundled fonts such as DejaVu and STIX are under their own licenses |
| [OpenCV](https://github.com/opencv/opencv) | Apache-2.0 (its bundled FFmpeg is listed above) |
| [Pillow](https://github.com/python-pillow/Pillow) | MIT-CMU |
| [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) | MIT |
| [Gymnasium](https://github.com/Farama-Foundation/Gymnasium), [Gym](https://github.com/openai/gym) | MIT |
| [MushroomRL](https://github.com/MushroomRL/mushroom-rl) | MIT |
| [TensorBoard](https://github.com/tensorflow/tensorboard) (paia-tensorboard) | Apache-2.0 |
| [MLGame3D](https://pypi.org/project/mlgame3d/) | MIT |
| mlgame3d-envs (based on [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents)) | Apache-2.0 |
| [Protocol Buffers](https://github.com/protocolbuffers/protobuf) | BSD-3-Clause |
| [gRPC](https://github.com/grpc/grpc) | Apache-2.0 |
| [websockets](https://github.com/python-websockets/websockets) | BSD-3-Clause |
| [PyOpenGL](https://github.com/mcfletch/pyopengl) | BSD-style |
| [pyGLFW](https://github.com/FlorianRhiem/pyGLFW) | MIT |
| [PyYAML](https://github.com/yaml/pyyaml) | MIT |
| [SDL2, SDL2_image, SDL2_mixer, SDL2_ttf](https://github.com/libsdl-org) (bundled with pygame) | Zlib |
| [FreeType](https://freetype.org/) (bundled with pygame) | FreeType License |
| libjpeg, libpng, libtiff, libwebp, libogg, libopus, PortMidi (bundled with pygame) | IJG, libpng, libtiff, BSD-3-Clause, BSD-3-Clause, BSD-3-Clause, MIT |
| [libmodplug](https://github.com/Konstanty/libmodplug) (bundled with pygame) | Public Domain |
| [OpenSSL](https://github.com/openssl/openssl) | Apache-2.0 |
| [SQLite](https://www.sqlite.org/) | Public Domain |
| [zlib](https://zlib.net/) | Zlib |
| [libffi](https://github.com/libffi/libffi) | MIT |

The Python runtime also includes the dependencies of these packages, all under permissive licenses: MIT, BSD-2-Clause, BSD-3-Clause, Apache-2.0, PSF-2.0, and Unlicense.

## Other redistributable components

| Component | License |
| --- | --- |
| Microsoft Visual C++ Runtime and Universal C Runtime (Windows) | Microsoft Visual C++ Redistributable license terms |
| Intel OpenMP runtime, bundled with PyTorch (Windows) | Intel Simplified Software License |
| LLVM OpenMP runtime, bundled with PyTorch (macOS) | Apache-2.0 WITH LLVM-exception |

## License texts

The full license texts of these components are included in PAIA Robot: open **Settings > About PAIA Robot > Open-Source Licenses**. The license texts of Electron and Chromium are in the `LICENSE` and `LICENSES.chromium.html` files in the PAIA Robot installation directory.
