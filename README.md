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


## 設計ドキュメント

[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1JlDQiNriMLHoHBhYHdZjbdlCwNyKw1vS6fJvtwEY438/edit?gid=649127913#gid=649127913)



## 使用技術
フロントエンド：Next.js 14（App Router）

バックエンド：Next.js（API Routes）

データベース：Supabase（PostgreSQL）

認証：Supabase Auth（メール/SNSログイン）

デプロイ：Vercel

バージョン管理：Git、GitHub

テスト・デバッグ：Chrome DevTools

グラフ描画：Chart.js

スタイリング：Tailwind CSS

型チェック：TypeScript


## 機能一覧
ユーザー登録／ログイン（メール・SNS対応）

習慣の登録／編集／削除（曜日指定OK）

毎日の習慣チェック記録（気分5段階＋メモ）

記録のカレンダー表示（アイコンと色で可視化）

分析機能（習慣の達成率、気分の推移などをグラフで表示）

モバイルファーストなUI設計（iPhone対応）
