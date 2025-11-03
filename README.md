This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

### Install Node.js `v24.11.0 (LTS)`:

[Node.js](https://nodejs.org/en/download)

After install, open PowerShell or Command Prompt and verify:

```
node -v
npm -v
```

### If you run this in VS Code Terminal and get an error, allow PowerShell to run npm:
In PowerShell running as Administrator, run:

```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
``` 

then type `Y` and try again.

### Install `pnpm` because it's faster and more efficient:

```
npm install -g pnpm
```

Then verify install using:

```
pnpm -v
``` 

### Opt-out of anonymous telemetry collection!!!

Run:

```
npx next telemetry disable
# or
pnpm exec next telemetry disable
```

### Inside the repository folder, run the development server:

```bash
npm run dev
# or
pnpm dev
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
