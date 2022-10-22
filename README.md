# Standard for submitting Templates on ThemeForest

[Quality & Technical Requirements](https://help.author.envato.com/hc/en-us/categories/360000038846-Quality-Technical-Requirements)

[Themes Item Preparation & Technical Requirements](https://help.author.envato.com/hc/en-us/articles/360000470826-Themes-Item-Preparation-Technical-Requirements)

## Check List:
1. Imagine and wire frame a design. Decide if you are designing for a particular audience (restaurants, or hotels, or artist’s portfolios…) or if you are going for a more general template. The other option is to take inpiration from a website or template. Check out the [Latest Design Trends](https://github.com/panacloud-modern-global-apps/ui-design-trends).
2. Once you are happy with the design, create the site! Be meticulous with your code, comment everything so it’s extremely readable and clear, and format everything properly.
3. Fill your site with good looking filler text content. You can use [Lorem Ipsum](https://loremipsum.io/), but in the places where text is highly visible, you should write the content yourself so it is personally applicable to the site you made.
4. Donot use copyrighted images, etc. For Oper Source Images, Video, etc. check this [link](https://github.com/dimitrisraptis96/design-heaven).
5. Create a simple read-me on how to replace content in your site and host it with a popular web host like Vercel. Include an affiliate links!
6. Organize your file and documentation so that it is easy to view, edit and understand. Group, label and organize common elements so that buyers are able to easily edit your file. **The more editable your file is, the more valuable it is to buyers.**
7. Ensure that your code is validated and in a style that represents the latest and best practices in the industry. 
8. Our main selling point is that we are building Full-Stack Strongly and Fully Typed Easily Customizable Responsive Accessible Web2 and Web3 Templates. To understand the concept read these articles:
- [Fully Typed Web Apps](https://www.epicweb.dev/fully-typed-web-apps)
- [Build a Full Stack App with Next.js, Tailwind, tRPC and Prisma ORM](https://dev.to/franciscomendes10866/build-a-full-stack-app-with-nextjs-tailwind-trpc-and-prisma-orm-4ail)
9. All our templates will use the following tech stack:
- Our Programming Language is [TypeScript](https://github.com/panacloud-modern-global-apps/learn-typescript) (Version 4.9+)
- Our Full-Stack Web Platform is [Next.js](https://github.com/panacloud-modern-global-apps/nextjs) (Version 12.3+). [Practice projects available here](https://github.com/panacloud-modern-global-apps/nextjs-projects).
- Our component library is [Chakra UI](https://github.com/panacloud-modern-global-apps/chakra-nextjs-projects) (Version 2.3.6+)
- For minor animation [Framer-Motion](https://chakra-ui.com/getting-started/with-framer) (Version 2.3+)
- To develop simple API integrated with Next.js we will use [API Routes](https://nextjs.org/docs/api-routes/introduction) with [tRPC](https://trpc.io/docs/v10/nextjs) (Version 10+)
- For Database Access we will use [Prisma](https://www.prisma.io/nextjs) (Version 4.5+). It will be used to access data in Next.js API Routes.
- For Database we can use anything because Prisma supports these [databases](https://www.prisma.io/docs/reference/database-reference/supported-databases). However, for local development we will use SQLite which is shipped with every Prisma release. For cloud deployment we will use [CockroachDB serverless](https://www.cockroachlabs.com/blog/announcing-cockroachdb-serverless/), it has [Vercel integration](https://vercel.com/integrations/cockroachdb)
- For Headless CMS we will use Contentful and Strapi. But currently Strapi does not support deployment and import/export.
- Ethers for Ethereum integration (Version 5.7+)
- For Smart Contracts we will use Solidity (Version 0.8.17+) with Hardhat (Version 2.12+)
- For Quick [Deployment](https://vercel.com/docs/cli/deploy) we will use Vercel with [CLI](https://vercel.com/docs/cli)
10. Each template must have documentation for the user.
11. Have two versions with seprate directories: a. plain site b. with Contentful integrated (Headless CMS)
12. The Contentful version should export files: https://www.contentful.com/developers/docs/tutorials/cli/import-and-export/ 
13. Have the ability to change colors from the central place https://chakra-ui.com/docs/styled-system/theme
14. Must implement reponsive sytles https://chakra-ui.com/docs/styled-system/responsive-styles
Please test your template with all these breakpoints (The inspect element on the browsers have these breakpoints built in, use it to test):
- 320px - Mobile S
- 375px - Mobile M
- 425px - Mobile L
- 768px - Tablet
- 1024px - Laptop
- 1440px - Laptop L
- 2560px - 4K
15. If appropriate make you Website an [PWA](https://github.com/shadowwalker/next-pwa)

