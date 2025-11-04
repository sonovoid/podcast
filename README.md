This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

### Install Node.js `v24.11.0 (LTS)`:

[Node.js Download Link](https://nodejs.org/en/download)

<img width="421" height="340" alt="image" src="https://github.com/user-attachments/assets/4e07e54b-be93-4000-a894-b04d2e194d9c" />

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

## VS Code Extensions

[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for code linting / fixes
[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) for formatting
[Prettier-ESLint](https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint) for formatting
[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) for Tailwind autocomplete
[Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma) for DB schema highlighting + tools
`If the Prisma install fails in VS Code download it manually as shown in the VS Code error message, rename the file to end in .vsix, CTRL+SHIFT+P -> Extensions: Install from VSIX and select the file.`
[Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client) for API testing
[Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) for inline error display

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
