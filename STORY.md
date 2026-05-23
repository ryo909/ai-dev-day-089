# Day089 Story — Flea Shipping Thickness Gauge

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day089専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: flea_market_shipping_fit
- Mechanic: lane_fit
- Input/Output: dimension_rows -> fit_lanes
- Audience Promise: 梱包前に送料事故を避けやすくなる。
- Publish Hook: 品物、たたみ方、梱包材、厚み余白を入れると、収まる発送レーンと超過しそうな箇所が見える。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day089｜フリマ発送厚みゲージ
フリマ出品物の厚み・重さ・梱包材から、発送方法の候補と危ない超過を出すツールです。
