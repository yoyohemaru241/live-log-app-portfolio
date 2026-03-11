# live-log-app-portfolio
ライブ参戦履歴を管理できるWebアプリです。
ユーザー認証後、ライブ情報（アーティスト・日付・会場・メモ）を登録・編集・削除できます。
Next.js（App Router）とSupabaseを用いて開発しました。

## 技術スタック
フロントエンド：Next.js (React / TypeScript)
バックエンド：Supabase（認証・DB・API）
認証：Supabase Auth（メールログイン対応）

## サイトイメージ
チャート描画：Chart.js![ChatGPT Image 2025年5月27日 00_19_45](https://github.com/user-attachments/assets/ee721251-44e3-4252-81b0-5982d7cb18d4)

##サイトURL
(https://live-log-appv2-n5x7l9f0k-yoyohemaru41-5938s-projects.vercel.app/login)
## 設計ドキュメント

[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1JlDQiNriMLHoHBhYHdZjbdlCwNyKw1vS6fJvtwEY438/edit?gid=649127913#gid=649127913)



## 使用技術
- フロントエンド：Next.js 16.1（React 19）
- バックエンド：Next.js API Routes
- データベース：PostgreSQL（Supabase）
- 認証：Supabase Auth
- デプロイ：Vercel
- バージョン管理：Git、GitHub
- テスト・デバッグ：DevTools（Chrome）
- CI/CD：GitHub Actions（ESLint）
- 開発環境：VS Code
- デザイン・プロトタイプ：v0


## 機能一覧
###ユーザー機能
- ユーザー登録（サインアップ）
-ログイン / ログアウト
-認証ユーザーのみアプリ利用可能（Supabase Auth）
###登録できるライブ情報
-アーティスト名
-ライブ日付
-会場
-開場時間（OPEN）
-開演時間（START）
-メモ（感想など）
###データ管理
-Supabaseデータベースに保存
-ユーザーごとにライブ履歴を管理
###UI / 画面
-ログイン画面
-新規登録画面
-ライブ一覧（History）画面
-ライブ登録画面
-ライブ編集画面
