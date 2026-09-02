# ドリームクラフト＆ビッグボス｜楽天スーパーSALE 名入れのお酒

- 会期: 2026/9/4(金)20:00 〜 9/11(金)1:59
- 店舗: ドリームクラフト＆ビッグボス（https://www.rakuten.co.jp/d-craft/ ／ sid=296346）
- 1ファイル完結（`index.html` に CSS/JS 内包）。画像は `images/` 直下。
- 構成: FV看板 → カウントダウン → ごあいさつ → 名入れのお酒（+10%OFFクーポン） → クロージング。
  ※スタッフ制作ドラフト（sakikohatakeyama/dreamcraft-rakuten-super-sale）からは**パタパタ時計カウントダウンのみ流用**。
  ポイント2倍デー等の他ブロックは今回不要のため削除済み。
- フォント: タイトル等は Zen Kaku Gothic New(900)。数字（カウントダウン/価格）と英字小ラベルのみ Fredoka。
- 配色: FV看板から採取（黄地・赤の描き文字・青・黒アウトライン）。

## 公開前に差し替える箇所（`index.html`）

1. **クーポン取得URL** … `<script>` 内の `COUPON_URL` に URL を入れると `data-coupon` 属性のボタン（名入れ10%OFF）へ一括反映。
2. **制作メモ** … フッター内の `.devnote` を削除。

## 名入れ商品セクション

`#naire` 配下。検索「名入れ 酒」（sid=296346, 107件）から24点を5グループに分類。
価格・レビュー・画像URL・商品URLは取得時点のもの。会期前に最新へ更新すること
（特に価格変動・欠品）。画像は `tshop.r10s.jp/d-craft/...` を直リンク。

## ローカル確認

launch.json 名: `dreamcraft-ss`（`python -m http.server 8735`）。
