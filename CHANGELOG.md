# Changelog

## v1.0.0 — 2026-10-08

### English

First release. Windows (MikuWorld) and macOS (MikuWorldMac) builds are published together.

- Curved slide generator (timeline context menu): length, slide width, end position, horizontal shift, symmetry / reverse, type, live preview.
- 3D chart preview ported from MikuMikuWorld v4; layout is Timeline | Preview | Properties.
- All-new easings: 29 types, cubic Bézier and easing trimming; converted to hidden nodes when exporting Sonolus LevelData.
- Command-line conversion (Windows): `MikuMikuWorld.exe --convert <input> <output> [--meta-from <file>]`, between `.unchmmws` and LevelData (`.json` / `.json.gz`).
- Lane expansion (fixed 12 lanes, add lanes on either side).
- Beat division by measure by default.
- Hold notes glow in the same phase as a whole.
- Automatic emergency save on crash or freeze.
- UI font follows the interface language.
- Native macOS build: ⌘ shortcuts, native file panels, settings in `~/Library/Application Support/MikuWorldMac`.

### 中文

首个版本，同时发布 Windows 版（MikuWorld）和 macOS 版（MikuWorldMac）。

- 曲线 slide 生成器（时间轴右键打开）：长度、SLIDE 幅、终点位置、横移、对称/反转、类型、实时预览。
- 移植自 MikuMikuWorld v4 的谱面 3D 预览，布局为 时间轴 | 预览 | 属性。
- 全新缓动：29 种 + 三次贝塞尔 + 缓动截取；导出 Sonolus LevelData 时转为隐藏节点。
- 命令行转换（Windows 版）：`MikuMikuWorld.exe --convert <输入> <输出> [--meta-from <文件>]`，`.unchmmws` 与 LevelData（`.json` / `.json.gz`）互转。
- 轨道扩展（12 轨固定，向两侧加轨）。
- 默认按小节的节拍分割。
- 长条整体同相位发光。
- 崩溃/卡死时自动紧急保存。
- 按界面语言切换字体。
- macOS 原生版本：⌘ 快捷键、原生文件面板，配置保存在 `~/Library/Application Support/MikuWorldMac`。

### 日本語

初回リリース。Windows 版（MikuWorld）と macOS 版（MikuWorldMac）を同時に公開します。

- カーブスライド生成ツール（タイムラインの右クリックメニュー）：長さ、SLIDE 幅、終点位置、横シフト、対称／反転、タイプ、リアルタイムプレビュー。
- MikuMikuWorld v4 から移植した譜面 3D プレビュー。レイアウトは タイムライン | プレビュー | プロパティ。
- 新しいイージング：29 種類 + 3 次ベジェ + イージングのトリミング。Sonolus LevelData への書き出し時は非表示ノードに変換。
- コマンドライン変換（Windows 版）：`MikuMikuWorld.exe --convert <入力> <出力> [--meta-from <ファイル>]`。`.unchmmws` と LevelData（`.json` / `.json.gz`）を相互変換。
- レーン拡張（12 レーン固定、左右にレーンを追加）。
- 拍分割は標準で小節単位。
- ロングノーツ全体が同位相で発光。
- クラッシュ／フリーズ時の自動緊急保存。
- UI 言語に合わせたフォント切り替え。
- macOS ネイティブ版：⌘ ショートカット、ネイティブのファイルパネル、設定は `~/Library/Application Support/MikuWorldMac` に保存。
