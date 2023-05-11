# Serverless Functions on Vercel

This repo provides an example for deploying a serverless function on Vercel. This repository was created using the [Serverless Function Quickstart](https://vercel.com/docs/concepts/functions/serverless-functions/quickstart).

## Description
In the `/api` directory there are two files: one JavaScript/Node endpoint (`api/js.js`) and one TypeScript endpoint (`api/ts.ts`). The functions return a small JSON response, for example:

```json
{
    "hello": "javascript"
}
```

## Run Locally
To run locally using the the Vercel CLI.

```bash
npx vercel dev
```

Each endpoint can be found at the following localhost URLs:

- http://localhost:3000/api/js
- http://localhost:3000/api/ts

### Deployed on Vercel
This example is deployed on Vercel at the following URLs:

- https://sf-testing-api-dir.vercel.app/api/ts
- https://sf-testing-api-dir.vercel.app/api/js
