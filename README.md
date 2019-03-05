# Money Button: Paywall Example

Example application showing how to build a paywall using [Money Button](https://moneybutton.com).

## Demo

To run a demo of Markdown Paywall, first clone the repo to your computer.

Next, create an [app for testing](https://docs.moneybutton.com/docs/api-apps.html).

Then you will want to create two .env files:

First, copy <code>api/.env.example</code> to <code>api/.env</code> and set the <code>WEBHOOK_SECRET</code> variable to be the same as your app.

Second, copy <code>web/.env.example</code> to <code>web/.env</code> and set <code>CLIENT_IDENTIFIER</code> to be the same as your app.

Now you can install Markdown Paywall and run it with these commands:

```
yarn
yarn dev
```

## Index

* `api`: [Express.js](https://expressjs.com/) app which implements the test's backend including payment webhook handling.
* `web`: [Next.js](https://nextjs.org/) app which implements the test's frontend including a paywall.
