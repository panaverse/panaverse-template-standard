# Standard for submitting Templates on ThemeForest

[Quality & Technical Requirements](https://help.author.envato.com/hc/en-us/categories/360000038846-Quality-Technical-Requirements)

[Themes Item Preparation & Technical Requirements](https://help.author.envato.com/hc/en-us/articles/360000470826-Themes-Item-Preparation-Technical-Requirements)

## Check List:
1. Organize your file and documentation so that it is easy to view, edit and understand. Group, label and organize common elements so that buyers are able to easily edit your file. **The more editable your file is, the more valuable it is to buyers.**
2. Ensure that your code is validated and in a style that represents the latest and best practices in the industry. 
3. Our main selling point is that we are building Full-Stack Strongly and Fully Typed Web2 and Web3 Templates. To understand the concept read these articles:
- [Fully Typed Web Apps](https://www.epicweb.dev/fully-typed-web-apps)
- [Build a Full Stack App with Next.js, Tailwind, tRPC and Prisma ORM](https://dev.to/franciscomendes10866/build-a-full-stack-app-with-nextjs-tailwind-trpc-and-prisma-orm-4ail)
5. All our templates will use the following tech stack:
- Our Programming Language is TypeScript (Version 4.9+)
- Our Full-Stack Web Platform is Next.js (Version 12.3+)
- Our component library is Chakra UI (Version 2.3.6+)
- To develop simple API integrated with Next.js we will use [API Routes]{https://nextjs.org/docs/api-routes/introduction} with [tRPS](https://trpc.io/docs/v10/nextjs) (Version 10+)
- For Database Access we will use [Prisma](https://www.prisma.io/nextjs) (Version 4.5+). It will be used to access data in Next.js API Routes.
- For Database we can use anything because Prisma supports these [databases](https://www.prisma.io/docs/reference/database-reference/supported-databases). However, for local development we will use SQLite which is shipped with every Prisma release. For cloud deployment we will use [CockroachDB serverless](https://www.cockroachlabs.com/blog/announcing-cockroachdb-serverless/), it has [Vercel integration](https://vercel.com/integrations/cockroachdb)
- For Headless CMS we will use Contentful and Strapi. But currently Strapi does not support deployment and import/export.
- Ethers for Ethereum integration (Version 5.7+)
- For Smart Contracts we will use Solidity (Version 0.8.17+) with Hardhat (Version 2.12+)
- For Quick [Deployment](https://vercel.com/docs/cli/deploy) we will use Vercel with [CLI](https://vercel.com/docs/cli)
6. Each template must have documentation for the user.
7. Have two versions with seprate directories: a. plain site b. with Contentful integrated (Headless CMS)
8. The Contentful version should export files: https://www.contentful.com/developers/docs/tutorials/cli/import-and-export/ 
9. Have the ability to change colors from the central place https://chakra-ui.com/docs/styled-system/theme
10. Must implement reponsive sytles https://chakra-ui.com/docs/styled-system/responsive-styles
Please test your template with all these breakpoints (The inspect element on the browsers have these breakpoints built in, use it to test):
- 320px - Mobile S
- 375px - Mobile M
- 425px - Mobile L
- 768px - Tablet
- 1024px - Laptop
- 1440px - Laptop L
- 2560px - 4K

