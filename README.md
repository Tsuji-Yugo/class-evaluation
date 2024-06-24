<<<<<<< HEAD
ブランチ
main-develop- task-3-56
              task-3-46
              task-3-50



# class-evaluation
1. プロジェクト概要
プロジェクト名: 大学レビューサイト
目的: 大学生が授業や先生のレビューを共有できるプラットフォームを提供し、授業選択や学習の参考にする。
対象ユーザー: 大学生、教育関係者、授業選択を検討している新入生。

2. 機能要件
2.1 ユーザー機能
ユーザー登録/ログイン機能:

Eメールアドレスによる登録・ログイン
Google, Facebookなどの外部サービスを利用したOAuthログイン
プロフィール管理:

プロフィール編集（名前、プロフィール画像、自己紹介など）
パスワード変更
レビュー投稿機能:

授業レビューの投稿（授業名、授業内容、評価、コメント）
先生レビューの投稿（先生名、授業の評価、コメント）
出席の取り方（ぴ逃げ可能かどうか）
テスト形式、難易度
教科書が必要かどうか
レビューに画像やリンクを追加
レビュー検索・閲覧機能:

授業名、先生名、学部、評価順などで検索・フィルタリング
他のユーザーのレビュー閲覧
レビュー評価機能:

レビューに対する「いいね」機能
有用/無用の投票機能
2.2 管理者機能
ユーザー管理:

ユーザーの登録情報の閲覧、編集、削除
ユーザーの権限管理（通常ユーザー、モデレーター、管理者）
レビュー管理:

投稿されたレビューの閲覧、編集、削除
不適切なレビューの報告対応
コンテンツ管理:

授業や先生の基本情報（名前、学部、授業内容など）の追加・編集・削除
カテゴリの管理
3. 非機能要件
3.1 パフォーマンス
サイトは同時に1000人以上のユーザーがアクセスしてもスムーズに動作すること。
3.2 セキュリティ
ユーザーデータを安全に保存するための暗号化
不正アクセス防止のための多要素認証
SQLインジェクションやクロスサイトスクリプティング（XSS）対策
3.3 ユーザビリティ
モバイルフレンドリーなデザイン
直感的に操作できるUI/UX
アクセシビリティ対応
3.4 保守性
コードのリーダビリティと拡張性を考慮した設計
ドキュメントの充実
テストの自動化
4. 技術要件
4.1 フロントエンド
使用技術: HTML5, CSS3, JavaScript, React.js/Vue.js
レスポンシブデザイン対応
4.2 バックエンド
使用技術: Node.js/Express.js または Ruby on Rails
データベース: PostgreSQL または MySQL
4.3 その他
ホスティング: AWS, Google Cloud, または Heroku
バージョン管理: Git/GitHub
=======
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
>>>>>>> 54cb9dd (初めてのコミット)
