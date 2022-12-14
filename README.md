# Errors and solutions
- problem: installing next-auth@4 was producing an error
- solution: [install next-auth@4.3.3 instead](https://github.com/nextauthjs/next-auth/issues/4479)

- problem: Invalid `prisma.post.findMany()` invocation: Error occurred during query execution: ConnectionError...
- solution: use Supabase connection string `URI` with the port `5432` instead of the connection string with the port `6543`
    - [another solution](https://github.com/prisma/prisma/issues/11643#issuecomment-1268341203)


# Fullstack Authentication Example with Next.js and NextAuth.js

This is the starter project for the fullstack tutorial with Next.js and Prisma. You can find the final version of this project in the [`final`](https://github.com/prisma/blogr-nextjs-prisma/tree/final) branch of this repo.
