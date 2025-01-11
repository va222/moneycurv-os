<a href="https://moneyCurve ">
<p align="center"><img alt="MoneyCurve – An open source expense tracker application to track your incomes, investments, subscriptions, and expenses at ease." width="100" height="100" src="./public/icons/logo.svg"></p>
  <h1 align="center">moneyCurve </h1>
</a>

<p align="center">
  MoneyCurve is an open-source expense tracker application to effortlessly track and manage your expenses.
</p>

<p align="center">
  <a href="https://github.com/gokulkrishh/moneyCurve /blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/gokulkrishh/moneyCurve ?label=license&logo=github&color=f80&logoColor=fff" alt="License" />
  </a>
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#implementation"><strong>Implementation</strong></a> ·
  <a href="#routes"><strong>App Routes</strong></a> ·
  <a href="#contributions"><strong>Contributions</strong></a>
</p>
<br/>

## Introduction

MoneyCurve is an open-source application to effortlessly track and manage your incomes, expenses, investments, and subscriptions.

## Tech Stack

- [Next.js](https://nextjs.org/) – framework
- [Components](https://ui.shadcn.com/) – ui-components
- [Tailwind](https://tailwindcss.com/) – CSS
- [Supabase](https://supabase.com/) – database
- [Vercel](https://vercel.com/) – hosting
- [Resend](https://resend.com/) – emails

## Implementation

- MoneyCurve is built using [NextJs](https://nextjs.org) from scratch.
- [Postgresql](https://www.postgresql.org/) is used as the ORM for easily communicating with the database for storing user, subscription data, etc. You can refer to the Prisma schema [here](/prisma/schema.prisma).
- [Supabase](https://supabase.com/) is an open-source Firebase alternative, the data is stored in the Postgres database (private data are encrypted) and uses a magic link for authentication provided by supabase.
- [LemonSqueezy](https://lemonsqueezy.com/) is used as the payment system. Its implementation is super simple.

## Routes

| Path      | Production             | Local                     |
| --------- | ---------------------- | ------------------------- |
| Home      | /                      | /                         |
| Signup    | app.moneyCurve /signup | app.localhost:3000/signup |
| Signin    | app.moneyCurve /signin | app.localhost:3000/signin |
| Dashboard | app.MoneyCurve        | app.localhost:3000        |


## License

MoneyCurve is an open source under the GNU Affero General Public License Version 3 (AGPLv3) or any later version. 
