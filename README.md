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

## How it works

Pass some data to the API using a POST request like so:

```json
{
  "data": "The battery life of the phone is 24 hours ans 20 minutes. My name is Matthieu and I'm 25 years old.",
  "format": {
    "name": { "type": "string" },
    "age": { "type": "number" },
    "batteryLifeHrs": { "type": "number" },
    "batteryLifeMns": { "type": "number" }
  }
}
```

The API returns:

```json
{
  "name": "Matthieu",
  "age": 25,
  "batteryLifeHrs": 24,
  "batteryLifeMns": 20
}
```
