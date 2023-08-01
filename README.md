# Secundo Testcase

### 1. Create a product page in Next.js and Tailwind

Create a single-product page using Next.js and Tailwind CSS. The page includes various components such as product images, description, and relevant products, inspired by e-commerce sites like [ours](https://www.secundo.no/) or other e-commerces.

### 2. Use the provided JSON data for the product page ( you can use more content if you want )

Candidates are expected to use the provided JSON file to fetch product data and create the product page. The product page should be visually appealing and well-structured, including all relevant product information.

### 3. Update README.md

Candidates should include instructions for running the project in the README.md. The instructions should cover the installation of dependencies, running tests and the development for server.

# Expectations

For senior developers, in addition to the basic requirements, we have the following expectations:

- Adhere to clean, modular, and reusable coding practices.
- Ensure responsiveness and cross-browser compatibility for the page.
- Implement performance optimization techniques to enhance efficiency.
- Apply UI/UX principles and industry best practices in design.
- Provide multi-language support for the page.
- Include comprehensive test cases to ensure robust functionality.

# Inspiration

Candidates can draw inspiration from our [product page](https://www.secundo.no/produkt/mobler/salongbord-og-sidebord/retro-og-nett-salongbord-i-morkt-treverk/) or other e-commerce sites to create an engaging and user-friendly product page. You have the freedom to select and utilize tools and frameworks as you deem appropriate to complete the project.


### Apps and Packages

- `msite`: a [Next.js](https://nextjs.org/) app
- `web`: another [Next.js](https://nextjs.org/) app
- `ui`: a stub React component library shared by both `web` and `docs` applications
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `api`: common file for api calls
- `classes`: Used singleton pattern for next js project
- `common`: Contains common utlity functions
- `components`: contains common component

To use the complete app,

- git clone <url>
- pnpm i
- pnpm dev

### Develop

To develop web, run the following command:

```
cd product
pnpm --filter web run dev

```

### Individual build run

- pnpm --filter web run dev

### Build

To build all apps and packages, run the following command:

```
cd product
pnpm build
```
