# 🚀 AI Prompt Management App

> **“Turn your best ideas into reusable power tools.”**

A modern web app built with [Next.js](https://nextjs.org) and [Supabase](https://supabase.com), designed to **organize, store, and share your AI prompts** efficiently.  
Whether you’re crafting prompts for business, research, or creative projects, this app helps you manage them all in one place — securely and beautifully.

---

## ✨ Why This App?

- Tired of losing great prompts in scattered documents?
- Want to **reuse winning prompts** and share them with teammates?
- Need secure storage with modern tech?

→ This app makes your AI prompt workflow **organized, searchable, and shareable**.

---

## 🚀 Core Features

### 🔐 Secure Authentication

- Sign up / Log in
- Password reset
- Row Level Security (Supabase Auth) ensures private user data

---

### 📋 Prompt Management

- Create, edit, delete prompts
- View detailed prompt pages
- Dashboard listing all your prompts

---

### 🏷 Tag Management

- Create and delete tags
- Assign multiple tags to prompts (many-to-many via join table)
- Filter prompts by tags
- Tag cloud display

---

### 🖼 Result Management

- Save text results
- Upload images (Supabase Storage)
- View and delete results
- Detailed result pages

---

### 🔎 Search & UI

- Search prompts by keyword
- Filter prompts by tags on dashboard
- Responsive design with Tailwind CSS

---

### 🔗 Sharing Made Simple

- Generate shareable public URLs for prompt results
- Signed URLs support for secure sharing even with private storage

---

## 💡 What Sets It Apart

- Full-stack solution with Supabase Auth, Storage, RLS, and PostgreSQL
- Developed using Next.js App Router with modern architecture
- Mobile-friendly and fast
- Runs entirely on **free tiers** (Vercel + Supabase)

---

## 🎯 Perfect For

- Teams managing AI prompt libraries
- SaaS product prototypes needing prompt features
- AI researchers and hobbyists
- Web apps requiring **secure multi-user data handling**

---

## 🔧 Tech Stack

- Next.js
- Supabase
- Tailwind CSS
- TypeScript

---

## 🖼 Screenshots

*(Add screenshots here showing dashboard, prompt editor, and tag filters for maximum impact!)*

---

## ▶️ Getting Started

```bash
npm install
npm run dev
```
Then visit http://localhost:3000.

# AIプロンプト管理アプリ

このアプリは、[Next.js](https://nextjs.org) と [Supabase](https://supabase.com) を使って構築した、AIプロンプトの管理・共有用Webアプリです。  
ユーザーが自分のプロンプトやその結果を整理・保存・共有しやすくすることを目的としています。

---

## 🚀 機能一覧

### 🔐 認証機能

- ユーザー登録・ログイン
- パスワードリセット
- ログアウト
- Supabase Auth を利用した RLS（Row Level Security）によるユーザーデータ分離

---

### 📋 プロンプト管理

- プロンプトの作成・編集・削除
- プロンプト詳細ページの表示
- ダッシュボードでのプロンプト一覧表示

---

### 🏷 タグ管理

- タグの作成・削除
- プロンプトへの複数タグ付け（中間テーブルによる多対多対応）
- タグによるプロンプトの絞り込み
- タグクラウド表示

---

### 🖼 結果管理

- テキスト結果の保存
- 画像アップロード（Supabase Storage使用）
- 結果の削除
- 結果詳細ページの表示

---

### 🔎 UI機能

- ダッシュボードでのタグ絞り込み検索
- プロンプトキーワード検索（オプション）

---

### 🔗 共有機能

- プロンプト結果を共有するための公開URL生成
- Supabase の署名付きURL対応（ストレージ非公開運用時にも対応可能）

---

### ⚙️ その他

- Next.js App Router を用いた動的ルーティング
- Protected Layout による認証済みページ保護
- Tailwind CSS によるレスポンシブ対応

---

## 💡 こだわりポイント

### ✅ 1. Supabase を活かした本格構成

- Supabase の Auth、Database（PostgreSQL）、Storage、RLS を一貫して活用
- RLS によりユーザー単位でデータ分離
- サービスロールキーや署名付きURLを活用した柔軟な共有機能

---

### ✅ 2. Next.js App Router の活用

- app ディレクトリ構成で開発
- 動的ルーティング（例：/prompt/[id]）
- クライアントコンポーネントとサーバーコンポーネントの適切な使い分け
- Protected Layout による認証制御

---

### ✅ 3. リレーション設計

- プロンプトとタグの多対多を中間テーブル（prompt_tags）で実装
- プロンプト → 結果 の 1:N 関連を実装
- Supabase クエリで JOIN 相当の処理を実装

---

### ✅ 4. UI/UX へのこだわり

- Tailwind CSS を使った美しい UI
- スマホ対応（レスポンシブ）
- タグフィルタリングなど実務に通じる使いやすい UI

---

### ✅ 5. 無料枠で運用可能

- Vercel の無料枠で運用可能
- Supabase の無料枠とも組み合わせて低コスト運用を実現

---

## 🎯 活かせる分野

- SaaS アプリ開発
- マルチユーザー対応の管理画面
- データ管理系アプリ
- 画像アップロード / ストレージ活用系アプリ
- 認証・認可が必要な Web アプリ

---

## 🔧 使用技術

- Next.js
- Supabase
- Tailwind CSS
- TypeScript

---

## 🖼 スクリーンショット

*(ここに UI の画像を貼ると効果的です)*

---

## ▶️ セットアップ方法

ローカル環境で動かす場合は以下のコマンドを実行してください：

```bash
npm install
npm run dev
