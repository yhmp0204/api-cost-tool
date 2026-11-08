# AI APIコスト試算ツール

個人開発者向けに、AI APIの利用料金を「1回あたり・月額の円」で見積もる静的ツールです。

公開ページ: https://yhmp0204.github.io/api-cost-tool/

## できること
- 用途別プリセット（写真認識1回／チャット往復1回／月1万回）
- 入力・出力トークン数、月間回数、為替レートはすべて手入力で変更可能
- 対応モデル（6種類）の1回あたり・月額を円で比較

## 対応モデル
- Google: Gemini 2.5 Flash-Lite / Gemini 2.5 Flash / Gemini 3.5 Flash-Lite
- Anthropic: Claude Haiku 4.5 / Claude Sonnet 4.5
- OpenAI: GPT-6 Luna

## 料金データについて
- 単価は各社の公式料金ページで確認した標準単価です（確認日: 2026-11-08）。出典はツール内の「前提・出典」と `pricing.json` に記載しています。
- 無料枠は反映していません。実際の請求とは異なる場合があります。

## ファイル
- `index.html` — ツール本体（単体でブラウザで開けます）
- `pricing.json` — 料金データ（正本）
