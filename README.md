# Aurora Blog

Aurora 的个人博客，基于 `YYsuni/2025-blog-public` 模板搭建。

## 本地开发

这个项目使用 Next.js、React、TypeScript 和 Tailwind CSS。

```bash
pnpm install
pnpm dev
```

默认开发地址是：

```text
http://localhost:2025
```

## 部署

推荐使用 Vercel 导入这个 GitHub 仓库部署。

需要在 Vercel 配置的公开环境变量：

```text
NEXT_PUBLIC_GITHUB_OWNER=ziqizhuang0-71
NEXT_PUBLIC_GITHUB_REPO=blog
NEXT_PUBLIC_GITHUB_BRANCH=main
NEXT_PUBLIC_GITHUB_APP_ID=你的 GitHub App ID
NEXT_PUBLIC_GITHUB_ENCRYPT_KEY=自己设置一串随机文本
```

GitHub App 的 Private Key 不要提交到仓库，也不要发到公开网络。
