## アプリ概要
next.jsとsupabaseを用いた子供向けの脳トレ学習アプリです
## 📱 機能

### 子供向け機能
- ✅ 3つの脳トレゲーム
- ✅ プロフィール設定（名前・アバター）
- ✅ スコア記録と表示
- ✅ レベルアップシステム
- ✅ バッジ・実績システム
- ✅ プレイ時間管理
- ✅ モチベーション向上機能

### 保護者向け機能（Supabase設定時）
- ✅ 詳細な学習進捗分析
- ✅ プレイ時間の制限設定
- ✅ ゲーム別パフォーマンス確認
- ✅ 成長レポートの閲覧
- ✅ 複数の子供アカウント管理

### オフラインモード
- ✅ Supabase未設定でも基本機能利用可能
- ✅ ローカルストレージでデータ保存
- ✅ 後からSupabase設定で機能拡張
## 🛠️ 技術スタック

- **フレームワーク**: Next.js 14 (App Router)
- **言語**: TypeScript
- **スタイリング**: Tailwind CSS
- **UI コンポーネント**: shadcn/ui
- **認証・データベース**: Supabase
- **状態管理**: React Hooks
- **アイコン**: Lucide React
## サイトイメージ
![アプリ画面](https://github.com/yuu514237/sanple_app/blob/3ba46f33fb3d06ce4058684dfe87e3e6e0cf67fc/docs/%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8%E7%94%BB%E5%83%8F.png?raw=true)

## サイトURL
https://nohtorepark-dzkt.vercel.app/
ゲームをするで名前を入力後プレイできます。

## テスト・修正の設計及び実施書
[テスト・修正の設計及び実施書_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/15lvwNgZGkXOrj8A2TAwUYORXJMHzhPp-9_pxdnRqbNs/edit?gid=0#gid=0)

## アプリの改善案
[アプリの改善案_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1M5PGvZxDn89s-5gzZsdEHGBBvJ_5vMpliRRB3FvDKl8/edit?gid=1797697990#gid=1797697990)

## 備考
[ESLintの実行結果_GitHub Actions](https://github.com/aihat9161/PortfolioExample_Next.js_BlogAppWorX_ENGINEER-CLASS/actions/runs/14956271682/job/42012343864)

- 活用した生成AIとその用途
  - ChatGPT：要件定義、設計、各種リサーチ
  - v0：アプリのモック作成
  - GitHub Copilot Chat：ローカル環境でのコードの修正相談

- リファクタリングの規則
  - 2つ以上のファイルで使う、行数が10以上のUIコンポーネントはcomponentsフォルダに移行
  - 2つ以上のファイルで使う、行数が10以上の関数はlibフォルダに移行
  - 変数名で2つ以上の単語が入る場合は、「isPublished」のように二つ目以降の単語の頭を大文字とする
