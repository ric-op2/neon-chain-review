# REDLINE MIRAGE

NEON CHAINの追加曲向けに制作した、オリジナルのユーロビート風チップチューンです。

- 150 BPM（60 Hz換算。NTSC実時間は約150.25）、F# minor、80小節、約2分8秒。
- 標準APUのPulse 1・Pulse 2・Triangle・Noiseを使用。DPCMと追加音源は使いません。
- 四つ打ちの低音、オクターブベース、パルスのシンセリードとオフビートのコードを中心に構成。
- 導入 → メインリフ → Aメロ → ビルドアップ → サビ → ブレイク → ラストサビ → エンディング。

`index.html`は試聴ページ、`redline-mirage.mp3`と`.wav`は試聴用、`.nsf`はNSFプレーヤー用、`.txt`は編集可能なFamiStudio形式、`.s`はca65用音楽データです。音楽データは2,214バイトで、再生ドライバーを含みません。

再生成はプロジェクトルートから`outputs/neon-chain-eurobeat/src/compose.py`を同梱Pythonで実行します。FamiStudio 4.5.3を使用します。必要なドライバー設定はVolume Trackのみです。

v0.42でゲームへ組み込みました。起動時に左右キーで選択できます。新曲の譜面はEASY 111ノーツ／HARD 159ノーツ、12旋回、1拍24フレーム、終端7680フレーム。譜面データは`../neon-chain-intersection/assets/stage-redline.json`です。NEON AFTERGLOWも維持しています。
