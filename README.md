# ドリームクラフト＆ビッグボス｜楽天スーパーSALE 特設ページ

- 会期: 2026/9/4(金)20:00 〜 9/11(金)1:59
- 店舗: ドリームクラフト＆ビッグボス（https://www.rakuten.co.jp/d-craft/ ／ sid=296346）
- 1ファイル完結（`index.html` に CSS/JS 内包）。画像は `images/` 直下。
- ベース: かわすい／ビッグボスの「お祭り感」SALE会場。配色はFV看板から採取（黄地・赤の描き文字・青・黒アウトライン）。
- カウントダウンはスタッフ制作ドラフト（sakikohatakeyama/dreamcraft-rakuten-super-sale）のパタパタ時計をそのまま採用。

## 公開前に差し替える箇所（`index.html`）

1. **FV看板** … `images/fv.webp`。最終版の画像に差し替え。
2. **クーポン取得URL** … `<script>` 内の `COUNT... COUPON_URL` に URL を入れると `data-coupon` 属性の全ボタンへ一括反映。
   個別に分けたい場合は各 `<a class="tget" data-coupon href="#">` の href を直接編集。
3. **対象ショップ限定クーポン** … `#coupons` の `.flag-slot` を `<a href="取得URL"><img src="クーポン画像" alt="..."></a>` に置換。枠は増減可。
4. **おすすめのお酒（通常品）** … `#recommend` の `.rec-card` を実データに。`.rec-photo` に `<img>`、`.rec-name`／`.rec-price` を実値、カード全体を `<a href>` でラップ。
5. **制作メモ** … `.devnote`（フッター内）と、このセクションのコメントを削除。

## 名入れ商品セクション

`#naire` 配下。検索「名入れ 酒」（sid=296346, 107件）から24点を5グループに分類済み。
価格・レビュー・画像URL・商品URLは取得時点のもの。会期前に最新へ更新すること
（特に価格変動・欠品）。画像は `tshop.r10s.jp/d-craft/...` を直リンク。

## ローカル確認

launch.json 名: `dreamcraft-ss`（`python -m http.server 8735`）。
