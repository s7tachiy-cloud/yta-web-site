# YTA WEB - 自社HP MVP（v0.1）

シンプルなHP制作サービス「YTA WEB」の自社サイト。

## 構成

```
site/
├── index.html         トップ
├── service.html       サービス紹介
├── pricing.html       料金
├── flow.html          流れ
├── samples.html       サンプル一覧
├── faq.html           FAQ
├── tokushoho.html     特商法表示（noindex）
├── css/
│   └── style.css
├── .nojekyll          GitHub Pages 用
└── README.md
```

## 技術選定

- **静的 HTML + CSS のみ**（JS フレームワーク不使用）
- フォント: Noto Sans JP（Google Fonts CDN）
- レスポンシブ: モバイル対応済み（768px ブレークポイント）

## 公開

GitHub Pages 経由で公開予定。

## プレースホルダー（要差し替え）

| 場所 | 現在の値 | 差し替え予定 |
|---|---|---|
| メールアドレス（mailto / 特商法） | `info@yta-web.com` | ドメイン取得後の正式アドレス |
| タグライン | 「見てから買えるHP制作。明朗会計。」 | 確定（v0.2 内修正3回目）|
| 特商法 所在地 | 「お問い合わせにより開示」 | バーチャルオフィス契約後に住所反映 |
| 特商法 電話番号 | 「お問い合わせにより開示」 | IP電話契約後に番号反映 |

## 関連ドキュメント

- 要件定義: `../要件定義.md` v0.2
- ビジネスプラン: `../../00_戦略/ビジネスプラン.md` v0.4
- 制作フロー: `../../02_オペレーション/制作フロー.md` v0.3
