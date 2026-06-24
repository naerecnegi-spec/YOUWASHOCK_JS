# YOU WA SHOCK ! (Native JSFX Clone for REAPER)

This is a native JSFX (Jesusonic) clone of the famous freeware exciter/maximizer VST plugin **"YOU WA SHOCK !"**.
It resolves compatibility and MIDI-related noise issues on modern 64-bit DAWs by running natively inside REAPER and ignoring MIDI input.

---

## Features / 特徴

- **MIDI Noise Fix / MIDIノイズ問題の解消**: 
  - 100% immune to MIDI-induced clicking and crackling.
  - トラック上にMIDIアイテムが存在する場合に発生していたプチプチ・パチパチ音（SynthMakerのバグ）が完全に解消されます。
- **64-bit Native / 64bitネイティブ動作**: 
  - Lightweight, stable, and highly optimized for REAPER.
  - 32bitブリッジが不要になり、動作が極めて軽量・安定します。
- **Zero Latency / ゼロレイテンシー**: 
  - Implemented with phase-coherent 2nd-order crossovers.
  - 位相干渉の少ない2次クロスオーバーフィルターを採用し、レイテンシーはありません。
- **4 Classic Presets / 4つのクラシックプリセット**:
  - **Preset A (Balanced)**: The standard master-bus enhancer. / 全体的に音圧と明瞭度を上げる標準マスタリングモード。
  - **Preset B (Bass Punchy)**: Enhances low frequencies and punch. / 低域のサチュレーションを強め、パンチを出すモード。
  - **Preset C (Air / Sparkle)**: Adds high-end air and brilliance (asymmetric excitation). / 高域にきらびやかな空気感を追加するエキサイターモード。
  - **Preset D (Heavy / Fat)**: Warm, dense saturation across the entire frequency range. / 全帯域を強く歪ませて太くするモード。
- **Safety Soft-Clipper / 安全設計のソフトクリッパー**: 
  - Never clips digitally above `0 dBFS` (capped at `-0.45 dBFS`).
  - 音割れを防ぎつつ音圧を最大化します。

---

## How to Install / 導入方法

### English Instructions

1. Download the [YOU_WA_SHOCK.jsfx](YOU_WA_SHOCK.jsfx) file.
2. In REAPER, open the menu: **Options** -> **Show REAPER resource path in explorer/finder...**
3. Locate the **`Effects`** folder in the directory that opens.
4. Copy the `YOU_WA_SHOCK.jsfx` file into that `Effects` folder.
5. In REAPER's FX Browser, right-click and select **Scan for new plugins** (or restart REAPER).
6. Search for `YOU WA SHOCK` in the FX Browser and add it to your track.

### 日本語での導入手順

1. [YOU_WA_SHOCK.jsfx](YOU_WA_SHOCK.jsfx) ファイルをダウンロードします。
2. REAPERを起動し、上部メニューから **「Options」** ＞ **「Show REAPER resource path in explorer/finder...」**（REAPERのデータフォルダを表示）を選択します。
3. 開いたフォルダの中にある **`Effects`** フォルダを開きます。
4. ダウンロードした `YOU_WA_SHOCK.jsfx` ファイルを、その `Effects` フォルダ内にコピー（または移動）します。
5. REAPERの FXブラウザを開き、右クリックメニューから **「Scan for new plugins」** を選択します（またはREAPERを一度再起動します）。
6. FX追加画面で `"YOU WA SHOCK"` と検索するとリストに表示され、通常のプラグインと同様に使用できます。
