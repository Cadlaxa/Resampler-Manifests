# WIP (Work-in-Progress)

tool for (manifest generator)[https://github.com/oxygen-dioxide/openutau-manifests] by oxygen dioxide
## Windows

|  Resampler |  Author  |  Resample Manifest  |  Additional Notes |
| ------------ | ------------ | ------------ | ------------ |
|  worldline  | StAkira |    |   Built into OpenUtau. Works on all platforms. |
|  [bkh01.exe](http://z-server.game.coocan.jp/utau/utautop.html#bkh01) |  Zteer | [bkh01.yaml]()  |
|  [doppeltler32.exe](http://utau2008.xrea.jp/2020/engine/) | Ameya  | [doppeltler32.yaml]()  |
|  [doppeltler64.exe](http://utau2008.xrea.jp/2020/engine/) | Ameya | [doppeltler64.yaml]()  |
| [EFB-GT.exe](http://custom-made.seesaa.net/article/312529786.html) | Custom.Maid | |
| EFB-PB.exe | Custom.maid | [EFB-PB.yaml]() |
|  [f2resamp32.exe](http://utau2008.xrea.jp/2020/engine/f2resamp004.zip) | Ameya | [f2resamp.yaml]()  |
|  [f2resamp64.exe](http://utau2008.xrea.jp/2020/engine/f2resamp004.zip) | Ameya  | [f2resamp.yaml]()  |
|  [fresamp11.exe](http://utau2008.xrea.jp/downloads/fresamp011.zip) | Ameya  | [fresamp11.yaml]()  |
|  fresamp12.exe | Ameya |   |
|  [fresamp14.exe](http://utau2008.xrea.jp/downloads/fresamp014.zip) | Ameya   | [fresamp14.yaml]()  |
| [fresamp14omp.exe](http://utau2008.xrea.jp/downloads/fresamp014omp.zip)  | Ameya | [fresamp14omp.yaml]()   | Ported to OpenMP with faster rendering speed than fresamp14.exe. |
| [lessampler.exe](https://github.com/YuzukiTsuru/lessampler/releases/) | YuzukiTsuru | [lessampler.yaml]() | [See additonal notes.](https://github.com/stakira/OpenUtau/wiki/Resamplers-and-Wavtools#compatible-with-adjustments) |
| [macres.exe](https://github.com/titinko/macres/releases)   | titinko   | [macres.yaml]()  |
| model4.exe  | Ameya  |   |
| [moresampler.exe](https://bowlroll.net/file/139123) |  Kanru Hua | [moresampler.yaml]() | [See adjustments for compatibility.](https://github.com/stakira/OpenUtau/wiki/Resamplers-and-Wavtools#compatible-with-adjustments) |
| [phavoco.exe](http://utau2008.xrea.jp/downloads/phavoco010.zip) | Ameya   | [phavoco.yaml]()  |
| [phaavoco.exe](http://utau2008.xrea.jp/2020/engine/phaavoco001.zip) | Ameya | [phaavoco.yaml]()  |
| resampler.exe  | Ameya  | [resampler.yaml]() | UTAU built-in resampler.  |
| [SpaceWorld_win64.exe](https://github.com/LovelyA72/SpaceWorld/releases) | LovelyA72 | [SpaceWorld_win64.yaml]() | [See adjustments for compatibility.](https://github.com/stakira/OpenUtau/wiki/Resamplers-and-Wavtools#compatible-with-adjustments) |
|[StrayCatRunner.exe](https://github.com/Astel123457/straycat-server) | Astel123457 |  [StrayCatRunner.yaml]()|
|[StrayCat.py](https://github.com/UtaUtaUtau/straycat) | UtaUtaUtau | [StrayCat.yaml]()  |
| [TIPS.exe](http://scientistb.web.fc2.com/program/)  | ScientistB | [TIPS.yaml]()  |
| [tn_fnds.exe](http://z-server.game.coocan.jp/utau/utautop.html#tn_fnds) | Zteer | [tn_fnds.yaml]() |
| [UDB](https://github.com/YuzukiTsuru/UDB/releases/tag/0.0.3.1) | YuzukiTsuru | [UDB.yaml]() | UDB means UTAU Debug Engine.|
| [vs4u.exe](http://ackiesound.ifdef.jp/download.html#vs4u) | AckieSound | [vs4u.yaml]() |
| [w4u.exe](http://utau2008.xrea.jp/downloads/w4u001.zip) | Zany | [w4u.yaml]()  |
| [WARP.exe](http://custom-made.seesaa.net/article/312530509.html) | Custom.Maid |  [WARP.yaml]()|
| [wn4u.exe](https://utaforum.net/threads/world4utau-update.20035/) | Zany | [wn4u.yaml]() | [See adjustments for compatibility.](https://github.com/stakira/OpenUtau/wiki/Resamplers-and-Wavtools#compatible-with-adjustments) |
| [young3.exe](https://bowlroll.net/file/203018) | Zany | [young3.yaml]()  |

### Compatible with adjustments

- [moresampler.exe](https://bowlroll.net/file/139123)
  - Add `moresampler.exe` and the default `moreconfig.txt` to the `Resamplers` folder.
  - Add `moresampler.exe` to `Wavtools` folder without `moreconfig.txt`.
  - Moresampler should now function as either resampler only, or as both wavtool and resampler.
- [[SpaceWorld_win64.exe|https://github.com/LovelyA72/SpaceWorld/releases]] and [[wn4u.exe|https://utaforum.net/threads/world4utau-update.20035/]]
    - May experience issues if the voicebank is missing any frq files. SpaceWorld version 1.0.1 will not crash in the event of a missing frq file.
- [[lessampler|https://github.com/YuzukiTsuru/lessampler/releases/]]
    - In development, lack of flag support
    - Oversized Audio Model Attention

## MacOS
|  Resampler |  Author  |  Resample Manifest  |  Additional Notes |
| ------------ | ------------ | ------------ | ------------ |
|  worldline  | StAkira  |   | Built into OpenUtau. Works on all platforms. |
| [macres](https://github.com/titinko/macres/releases)   | titinko   | [macres.yaml]()  |

## Linux
|  Resampler |  Author  |  Resample Manifest  |  Additional Notes |
| ------------ | ------------ | ------------ | ------------ |
|  worldline  | StAkira  |   | Built into OpenUtau. Works on all platforms. |
| [macres](https://github.com/titinko/macres/releases)   | titinko   | [macres.yaml]()  |

# Resampler Manifest
A resampler manifest is a YAML file used to store the expressions supported by a resampler. With resampler manifests, users can add all of a resampler's supported flags at once using the `Add all expressions suggested by renderers` button in the `Expressions` editor.

<img width="453" alt="image" src="https://user-images.githubusercontent.com/54425948/227085816-4cced732-98dd-4c76-bc40-9a94f971a066.png">

Resampler manifests should have the same name as the resampler executable, stored in the same folder. The manifest must have a `.yaml` file extension. For example, the resampler manifest for `moresampler.exe` should be `moresampler.yaml` located in the same folder with `moresampler.exe`.

Below is a full example of a resampler manifest for Moresampler. To create a resampler manifest with OpenUtau, add the resampler's expressions to any `.ustx` project file. Open the project file in a text editor and copy the `expressions:` section into a blank manifest file.
```yaml
expressions:
  gen:
    name: Gender Factor
    abbr: gen
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: g
  mbre:
    name: Breathiness (Moresampler)
    abbr: mbre
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: Mb
  tens:
    name: Tension
    abbr: tens
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: Mt
  pit:
    name: Pitch deviation (flag)
    abbr: pit
    type: Numerical
    min: -1200
    max: 1200
    default_value: 0
    is_flag: true
    flag: t
  pkcp:
    name: Peak Compressor
    abbr: pkcp
    type: Numerical
    min: 0
    max: 100
    default_value: 86
    is_flag: true
    flag: P
  amp:
    name: Amplitude Modulation
    abbr: amp
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: A
  cons:
    name: Unvoiced Consonant Gain
    abbr: cons
    type: Numerical
    min: -20
    max: 100
    default_value: 0
    is_flag: true
    flag: b
  fstr:
    name: Force Stretch
    abbr: fstr
    type: Options
    min: 0
    max: 1
    default_value: 0
    is_flag: true
    options:
    - ''
    - e
    - Me
  opn:
    name: Openness
    abbr: opn
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: Mo
  res:
    name: Resonance
    abbr: res
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: Mr
  dry:
    name: Dryness
    abbr: dry
    type: Numerical
    min: -100
    max: 100
    default_value: 0
    is_flag: true
    flag: Md
  cors:
    name: Coarseness
    abbr: cors
    type: Numerical
    min: 0
    max: 100
    default_value: 0
    is_flag: true
    flag: MC
  grwl:
    name: Growl
    abbr: grwl
    type: Numerical
    min: 0
    max: 100
    default_value: 0
    is_flag: true
    flag: MG
  dist:
    name: Distortion
    abbr: dist
    type: Numerical
    min: 0
    max: 100
    default_value: 0
    is_flag: true
    flag: MD
  stbl:
    name: Stabilization
    abbr: stbl
    type: Numerical
    min: 0
    max: 10
    default_value: 0
    is_flag: true
    flag: Ms
  mint:
    name: Model Interpolation
    abbr: mint
    type: Numerical
    min: 0
    max: 100
    default_value: 100
    is_flag: true
    flag: Mm
```
