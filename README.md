This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

### バージョン管理
このプロジェクトでは、Voltaを使用しNode.Jsのバージョン管理を行う。またパッケージ管理ツールにはpnpmを採用している。
- Voltaの[公式ドキュメント](https://docs.volta.sh/guide/)
- pnpmの[公式ドキュメント](https://pnpm.io/ja/)
- Voltaの[インストール方法](https://isub.co.jp/%E3%80%90%E7%92%B0%E5%A2%83%E6%A7%8B%E7%AF%89%E3%80%91/%E3%80%90node-js%E3%80%91%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E7%AE%A1%E7%90%86%E3%82%92volta%E3%81%AB%E7%A7%BB%E8%A1%8C%E3%81%99%E3%82%8B/)
- Node.Jsとpnpmのバージョン指定
```
node -v
v22.8.0

pnpm -v
9.11.0

// インストール方法
volta install node@22.8.0
volta install pnpm@9.11.0
```

### プロジェクトの立ち上げ
- プロジェクトのディレクトリに移動し、下記コマンドを入力
```
pnpm i

pnpm run dev
```


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
