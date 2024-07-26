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




<!-- Docs for all the files in this website -->

All the dates functions are available in the utils.ts file, which is in the lib folder.

In the layout.tsx file, the functions for the layout of all the pages of the website are available, including the custom 'cn' classNames and a variable for our fontFamily.

In the theme-provider.ts file, I defined the shadcn dark theme that I used to change the colours of everything coming from shadcn to dark theme colours.

The components folder was created when i ran the shadcn commandd in the terminal, everything installed from shadcn will be added into the folder as components that can be used again many times.


The Phone number/country generator with automatic country code is comig from react-phone-number-input from npm website.



<!-- BACKEND -->

All the id's of all the databases in appwrite are in the'.env.local' file.

They were rendered as props in 'appwrite.config.ts' file.

