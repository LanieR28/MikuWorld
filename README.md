# MikuWorld

[English](#english) | [中文](#中文) | [日本語](#日本語)

---

<a id="english"></a>
## English

**MikuWorld** is a Project SEKAI-style chart editor made by LanieR. It comes in two builds: **MikuWorld** for Windows and **MikuWorldMac** (MWM) for macOS.

It is based on [MikuMikuWorld for UntitledCharts](https://github.com/UntitledCharts/MikuMikuWorld4UC), which in turn derives from Crash5b's [MikuMikuWorld](https://github.com/crash5band/MikuMikuWorld).

### What's new compared with MikuMikuWorld4UC

- **Curved slide generator** — open it from the timeline context menu (right-click). Settings: length, slide width, end position, horizontal shift, symmetry / reverse, type, with a live preview.
- **3D chart preview** ported from MikuMikuWorld v4. The layout is Timeline | Preview | Properties.
- **All-new easings** — 29 easing types, cubic Bézier, and easing trimming. When exporting Sonolus LevelData they are converted to hidden nodes.
- **Command-line conversion** (Windows build): `MikuMikuWorld.exe --convert <input> <output> [--meta-from <file>]`. Converts between `.unchmmws` and LevelData (`.json` / `.json.gz`) in both directions.
- **Lane expansion** — fixed 12 lanes, add lanes on either side.
- **Beat division by measure** by default.
- **Hold notes glow in the same phase** as a whole.
- **Automatic emergency save** on crash or freeze.
- **UI font switches with the interface language.**
- **Native macOS build** — ⌘ shortcuts, native file panels, settings stored in `~/Library/Application Support/MikuWorldMac`.

### Download

Get the files from the [Releases](../../releases) page.

| Platform | File | How to use |
| --- | --- | --- |
| Windows (x64) | `MikuWorld-Windows-x64.zip` | Unzip and run `MikuMikuWorld.exe`. Keep the `res` folder and the two DLLs next to the exe. |
| macOS 13 or later (Apple Silicon) | `MikuWorldMac-macOS-arm64.zip` | Unzip and drag `MikuWorldMac.app` into Applications. The app is not notarized by Apple: on first launch, right-click → Open, or go to System Settings → Privacy & Security and click "Open Anyway". |

### Disclaimer

Game assets (note textures, sound effects) are copyrighted by SEGA / Colorful Palette. This is a non-commercial fan project and is not affiliated with SEGA, Colorful Palette or Crypton Future Media.

### License and credits

The program is based on the MIT-licensed MikuMikuWorld; see [LICENSE](LICENSE) for the original copyright notice. Licenses of third-party libraries are included in the `Licenses` folder shipped with the program. Thanks to Crash5b, the UntitledCharts team and all contributors.

---

<a id="中文"></a>
## 中文

**MikuWorld** 是 LanieR 制作的 Project SEKAI 风格谱面编辑器，同时提供 Windows 版（**MikuWorld**）和 macOS 版（**MikuWorldMac**，简称 MWM）。

本项目基于 [MikuMikuWorld for UntitledCharts](https://github.com/UntitledCharts/MikuMikuWorld4UC)，后者源自 Crash5b 的 [MikuMikuWorld](https://github.com/crash5band/MikuMikuWorld)。

### 相比 MikuMikuWorld4UC 新增的功能

- **曲线 slide 生成器**：在时间轴右键打开。可设置长度、SLIDE 幅、终点位置、横移、对称/反转、类型，并实时预览。
- **谱面 3D 预览**：移植自 MikuMikuWorld v4，布局为 时间轴 | 预览 | 属性。
- **全新缓动**：29 种缓动 + 三次贝塞尔 + 缓动截取；导出 Sonolus LevelData 时转为隐藏节点。
- **命令行转换**（Windows 版）：`MikuMikuWorld.exe --convert <输入> <输出> [--meta-from <文件>]`，`.unchmmws` 与 LevelData（`.json` / `.json.gz`）互转。
- **轨道扩展**：固定 12 轨，可向两侧加轨。
- **默认按小节的节拍分割。**
- **长条整体同相位发光。**
- **崩溃/卡死时自动紧急保存。**
- **按界面语言切换字体。**
- **macOS 原生版本**：⌘ 快捷键、原生文件面板，配置保存在 `~/Library/Application Support/MikuWorldMac`。

### 下载

请到 [Releases](../../releases) 页面下载。

| 平台 | 文件 | 使用方法 |
| --- | --- | --- |
| Windows（x64） | `MikuWorld-Windows-x64.zip` | 解压后运行 `MikuMikuWorld.exe`。`res` 文件夹和两个 dll 要和 exe 放在一起。 |
| macOS 13 以上（Apple Silicon） | `MikuWorldMac-macOS-arm64.zip` | 解压后把 `MikuWorldMac.app` 拖进「应用程序」。应用未经苹果公证，首次打开请右键 → 打开，或在 系统设置 → 隐私与安全性 里点「仍要打开」。 |

### 声明

游戏素材（音符贴图、音效）版权归 SEGA / Colorful Palette 所有。本项目为非商业同人项目，与 SEGA、Colorful Palette、Crypton Future Media 无关。

### 许可与致谢

程序基于 MIT 许可的 MikuMikuWorld，原版权声明见 [LICENSE](LICENSE)；第三方库许可证随程序附在 `Licenses` 文件夹里。感谢 Crash5b、UntitledCharts 团队及所有贡献者。

---

<a id="日本語"></a>
## 日本語

**MikuWorld** は LanieR が制作した、プロジェクトセカイ風の譜面エディタです。Windows 版（**MikuWorld**）と macOS 版（**MikuWorldMac**、略称 MWM）の両方を提供しています。

[MikuMikuWorld for UntitledCharts](https://github.com/UntitledCharts/MikuMikuWorld4UC) をベースにしており、これは Crash5b の [MikuMikuWorld](https://github.com/crash5band/MikuMikuWorld) から派生したものです。

### MikuMikuWorld4UC からの追加機能

- **カーブスライド生成ツール**：タイムライン上で右クリックして開きます。長さ、SLIDE 幅、終点位置、横シフト、対称／反転、タイプを指定でき、リアルタイムでプレビューされます。
- **譜面 3D プレビュー**：MikuMikuWorld v4 から移植。レイアウトは タイムライン | プレビュー | プロパティ。
- **新しいイージング**：29 種類 + 3 次ベジェ + イージングのトリミング。Sonolus LevelData への書き出し時は非表示ノードに変換されます。
- **コマンドライン変換**（Windows 版）：`MikuMikuWorld.exe --convert <入力> <出力> [--meta-from <ファイル>]`。`.unchmmws` と LevelData（`.json` / `.json.gz`）を相互に変換できます。
- **レーン拡張**：12 レーン固定で、左右にレーンを追加できます。
- **拍分割は標準で小節単位。**
- **ロングノーツ全体が同位相で発光。**
- **クラッシュ／フリーズ時の自動緊急保存。**
- **UI 言語に合わせてフォントを切り替え。**
- **macOS ネイティブ版**：⌘ ショートカット、ネイティブのファイルパネル、設定は `~/Library/Application Support/MikuWorldMac` に保存されます。

### ダウンロード

[Releases](../../releases) ページからダウンロードしてください。

| プラットフォーム | ファイル | 使い方 |
| --- | --- | --- |
| Windows（x64） | `MikuWorld-Windows-x64.zip` | 解凍して `MikuMikuWorld.exe` を実行します。`res` フォルダと 2 つの dll は exe と同じ場所に置いてください。 |
| macOS 13 以降（Apple Silicon） | `MikuWorldMac-macOS-arm64.zip` | 解凍して `MikuWorldMac.app` を「アプリケーション」にドラッグします。Apple の公証を受けていないため、初回は右クリック → 開く、または システム設定 → プライバシーとセキュリティ で「このまま開く」を押してください。 |

### 免責事項

ゲーム素材（ノーツのテクスチャ、効果音）の著作権は SEGA / Colorful Palette に帰属します。本プロジェクトは非営利のファンプロジェクトであり、SEGA、Colorful Palette、Crypton Future Media とは関係ありません。

### ライセンスと謝辞

本プログラムは MIT ライセンスの MikuMikuWorld をベースにしています。元の著作権表示は [LICENSE](LICENSE) をご覧ください。サードパーティライブラリのライセンスは、プログラムに同梱の `Licenses` フォルダに含まれています。Crash5b、UntitledCharts チーム、およびすべてのコントリビューターに感謝します。
