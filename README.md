# kimi-portfolio

An explorer's portfolio — Field Journal world.

「自分が探検家として宇宙の各地を巡る」体験をテーマにした、Web 制作実績向けのポートフォリオサイトです。各惑星 ＝ 1 つのプロジェクトとして表示し、訪問者が地図を辿るように作品を見ていける構成にしています。

## Concept

テーマはフィールドジャーナル / 異星の大地での野営。トーンは夕暮れ〜夜空のアウトドア配色（深い青 × オレンジ × クリーム）。訪問者はゲーム起動風のローディングを経て、全 5 ページを本を捲るように縦スクロールしていきます。

## Sections

Page 01 / Camp — Welcome・Hero（キャンプサイトの夕景）

Page 02 / Mission — なぜ今、オリジナル HP なのか

Page 03 / Profile — Dossier 風の自己紹介

Page 04 / Map — 惑星ごとの制作実績（Works）

Page 05 / Signal — Contact・連絡チャンネル

## Features

ゲーム起動風のブートシーケンス、コンパス型カスタムカーソル（緯度経度の表示とホバー時の LOCK）、スクロールで伸びる EXP ゲージ（LV.01 → LV.05）、scroll-snap と IntersectionObserver による reveal アニメーション、焚き火・テント・旗・星空などの SVG / CSS 装飾。

## Tech

Pure HTML / CSS / JavaScript。フレームワークやビルドツールを使わず、単一の `index.html` だけで完結します。フォントは Google Fonts の IBM Plex Mono / IBM Plex Serif / Zen Kaku Gothic New。そのまま GitHub Pages にデプロイ可能。

## Run locally

ブラウザで `index.html` を直接開くだけで動作します。ローカルサーバーで見たい場合は以下。

```bash
python3 -m http.server 8000
```

その後ブラウザで http://localhost:8000 を開く。

## Status

🚧 Prototype — 制作中。Planet 02 / 03 の実プロジェクト差し替え、Profile セクションの内容反映、サウンド演出の検討、レスポンシブ調整の磨き込みを今後進める予定。

## License

Private repository · © Kimi 2026
