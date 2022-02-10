This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Prequisites

¸Make sure to isntall serverless ```npm i -g serverless``` first
¸Create your required distribution and use it in serverless.yml
-- Ţhere will be an issue that arises out of deploying the nextjs with the AWS ACM that gets auto created, make sure to create CNAME aliases in Route53 for the concerned ACM. That is the only way to address the issue
¸Always run only ```serverless```. DO NOT USE deploy command