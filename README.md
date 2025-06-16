# AKAI MIDI MIX Checker

🌐 **[Live Demo](https://rikupi.github.io/akai-midimix-checker/)**

## 日本語

AKAI MIDI MIXコントローラーの動作確認・テスト用のWebツールです。
主にAKAI MIDIMIXを接続してもボタンが点灯しないため暗いクラブ等でVJパフォーマンスをする際に見にくいためLEDを全点灯させる機能があります。
※LEDを点灯した後は必ずタブを閉じてください

### 機能

- MIDI MIXの全コントロール（ノブ、フェーダー、ボタン）のリアルタイム表示
- MUTE、REC、BANK LEFT/RIGHTボタンのLED制御
- ボタンLEDのトグル機能
- 全LED一括ON/OFF機能
- MIDIメッセージログ表示
- Chrome/EdgeブラウザのWeb MIDI APIで動作

### 使い方

1. AKAI MIDI MIXをコンピューターに接続
2. Web MIDI API対応ブラウザ（Chrome、Edge）で`index.html`を開く
3. Input/Output両方のドロップダウンからMIDI MIXを選択
4. コントローラーをテスト：
   - ノブやフェーダーを動かして値を確認
   - ボタンを押してLEDをトグル
   - 「All LEDs ON/OFF」で全LEDを一括テスト

### 必要環境

- AKAI MIDI MIXコントローラー
- Web MIDI API対応ブラウザ（Chrome、Edge、Opera）
- インストール不要・依存関係なし

### 開発

このツールはClaude（Anthropic）の支援を受けて開発されました。

---

## English

A simple web-based tool for testing and checking AKAI MIDI MIX controller functionality.

### Features

- Real-time visualization of all MIDI MIX controls (knobs, faders, buttons)
- LED control for MUTE, REC, BANK LEFT/RIGHT buttons
- Toggle functionality for button LEDs
- All LEDs ON/OFF control
- MIDI message logging
- Works directly in Chrome/Edge browsers with Web MIDI API

### Usage

1. Connect your AKAI MIDI MIX to your computer
2. Open `index.html` in a Web MIDI API compatible browser (Chrome, Edge)
3. Select your MIDI MIX from both input and output dropdowns
4. Test your controller:
   - Move knobs and faders to see real-time values
   - Press buttons to toggle their LEDs
   - Use "All LEDs ON/OFF" to test all LEDs at once

### Requirements

- AKAI MIDI MIX controller
- Web browser with Web MIDI API support (Chrome, Edge, Opera)
- No installation or dependencies required

### Development

This tool was developed with the assistance of Claude (Anthropic) to create a simple, effective MIDI controller testing interface.

## Files

- `index.html` - Main application file / メインアプリケーションファイル
- `README.md` - This file / このファイル
- `LICENSE` - MIT License / MITライセンス

## License

MIT License - See LICENSE file for details

## Author

Created with Claude (Anthropic) assistance