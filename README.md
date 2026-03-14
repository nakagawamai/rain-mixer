# Rain Mixer 🌧️

雨の音で心を落ち着けるアンビエントサウンドアプリ

## 開発者
仲川 舞 (Mai Nakagawa)

---

## Vercelへのデプロイ手順

### 前提条件
- [Node.js](https://nodejs.org) (v18以上) がインストール済みであること
- [GitHub](https://github.com) アカウント
- [Vercel](https://vercel.com) アカウント（GitHubでサインアップ可）

---

### ステップ1: 依存パッケージのインストール

```bash
cd rain-mixer
npm install
```

### ステップ2: ローカルで動作確認

```bash
npm start
```

ブラウザで `http://localhost:3000` を開いて確認。

### ステップ3: GitHubにアップロード

1. [github.com](https://github.com) で新しいリポジトリを作成（例: `rain-mixer`）
2. 以下のコマンドを実行：

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/あなたのユーザー名/rain-mixer.git
git push -u origin main
```

### ステップ4: Vercelでデプロイ

1. [vercel.com](https://vercel.com) にGitHubアカウントでログイン
2. 「Add New Project」→ GitHubリポジトリ `rain-mixer` を選択
3. 設定はそのまま「Deploy」をクリック
4. デプロイ完了！URLが発行されます（例: `https://rain-mixer.vercel.app`）

---

## ファイル構成

```
rain-mixer/
├── public/
│   ├── index.html          # HTMLテンプレート
│   ├── manifest.json       # PWA設定
│   └── privacy-policy.html # プライバシーポリシー
├── src/
│   ├── App.jsx             # メインアプリ
│   └── index.js            # エントリーポイント
├── package.json
├── vercel.json
└── README.md
```

## プライバシーポリシー

公開後は `https://あなたのURL/privacy-policy.html` でアクセス可能です。
App Store申請時にこのURLを使用してください。

## ライセンス
© 2025 仲川 舞. All rights reserved.
