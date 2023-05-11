## NextJS Page Pre-rendering and Data Fetching

### Description:

- `getStaticProps()`: pre-fetch data for component to pre-render.
  - Inside `getStaticProps` function, you can execute NodeJS code
  - `revalidate`: NextJS will regenerate the page again and again, even after the page was built and deployed.
- `getStaticPaths()`
