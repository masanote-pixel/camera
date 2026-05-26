# PicAI カメラアプリ — インストールガイド

## ファイル構成
```
picai-pwa/
├── index.html      ← メインアプリ
├── manifest.json   ← PWA設定
├── sw.js           ← サービスワーカー（オフライン対応）
├── icon-192.png    ← アプリアイコン（192×192）
├── icon-512.png    ← アプリアイコン（512×512）
└── README.md       ← このファイル
```

## 公開方法（無料）

### オプション A: GitHub Pages（推奨・無料）
1. GitHubアカウントを作成（https://github.com）
2. 新しいリポジトリを作成（例: `picai-app`）
3. このフォルダの全ファイルをアップロード
4. Settings → Pages → Source: main branch → Save
5. `https://あなたのID.github.io/picai-app/` でアクセス可能

### オプション B: Netlify（ドラッグ＆ドロップで超簡単・無料）
1. https://netlify.com にアクセス
2. アカウント作成（無料）
3. `picai-pwa` フォルダをそのままドラッグ＆ドロップ
4. 数秒でURLが発行されます

### オプション C: Vercel（無料）
1. https://vercel.com にアクセス
2. GitHubと連携してデプロイ

---

## スマホへのインストール方法

### iPhone（Safari必須）
1. Safariでアプリの URL を開く
2. 画面下部の **□↑ 共有ボタン** をタップ
3. 「**ホーム画面に追加**」を選択
4. 「追加」をタップ → 完成！

### Android（Chrome）
1. ChromeでアプリのURLを開く
2. 自動でインストールバナーが表示される
3. 「**ホーム画面に追加**」をタップ
4. または：メニュー（⋮）→「アプリをインストール」

---

## 特徴
- ✅ オフラインでも動作（Service Worker）
- ✅ ホーム画面アイコンに対応
- ✅ フルスクリーン表示（アドレスバー非表示）
- ✅ iPhone・Android両対応
- ✅ インストール不要でブラウザからも使用可能
