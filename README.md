# 📚 Winterguard's Log

> 윈터가드의 블로그입니다.

## Project Setting

### Getting Started

> Need Lastest NPM version

First, run the development server:

```bash
 "dev": "next dev",
 "build": "next build",
 "build:static": "next build && next export",
 "deploy:gh-pages": "touch out/.nojekyll && push-dir --dir=out --branch=gh-pages --cleanup",
 "publish:gh-pages": "npm run build:static && npm run deploy:gh-pages",
 "start": "next start"
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
