# TWENTY

> Anticloud offline package — upstream: twentyhq/twenty @ `main`.

## What This Project Does

The open alternative to Salesforce, designed for AI.

**Topics:** crm, crm-system, customer, good-first-issue, graphql, hacktoberfest, javascript, marketing, monorepo, nestjs, open-source, postgresql, react, reactjs, sales, typescript, web

## Upstream README

<p align="center">
  <a href="https://www.twenty.com">
    <img src="./packages/twenty-website/public/images/core/logo.svg" width="100px" alt="Twenty logo" />
  </a>
</p>

<h2 align="center">The #1 Open-Source CRM</h2>

<p align="center"><a href="https://twenty.com"><img src="./packages/twenty-website/public/images/readme/globe-icon.svg" width="12" height="12"/> Website</a> · <a href="https://docs.twenty.com"><img src="./packages/twenty-website/public/images/readme/book-icon.svg" width="12" height="12"/> Documentation</a> · <a href="https://github.com/orgs/twentyhq/projects/1"><img src="./packages/twenty-website/public/images/readme/map-icon.svg" width="12" height="12"/> Roadmap </a> · <a href="https://discord.gg/cx5n4Jzs57"><img src="./packages/twenty-website/public/images/readme/discord-icon.svg" width="12" height="12"/> Discord</a> · <a href="https://www.figma.com/file/xt8O9mFeLl46C5InWwoMrN/Twenty"><img src="./packages/twenty-website/public/images/readme/figma-icon.webp"  width="12" height="12"/>  Figma</a></p>

<p align="center">
  <a href="https://www.twenty.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./packages/twenty-website/public/images/readme/github-cover-dark.webp" />
      <source media="(prefers-color-scheme: light)" srcset="./packages/twenty-website/public/images/readme/github-cover-light.webp" />
      <img src="./packages/twenty-website/public/images/readme/github-cover-light.webp" alt="Twenty banner" />
    </picture>
  </a>
</p>

<br />

# Why Twenty

Twenty gives technical teams the building blocks for a custom CRM that meets complex business needs and quickly adapts as the business evolves. Twenty is the CRM you build, ship, and version like the rest of your stack.

<a href="https://twenty.com/resources/why-twenty"><img src="./packages/twenty-website/public/images/readme/star-icon.svg" width="14" height="14"/> Learn more about why we built Twenty</a>

<br />

# Installation

### <img src="./packages/twenty-website/public/images/readme/globe-icon.svg" width="14" height="14"/> Cloud

The fastest way to get started. Sign up at [twenty.com](https://twenty.com) and spin up a workspace in under a minute, with no infrastructure to manage and always up to date.

### <img src="./packages/twenty-website/public/images/readme/book-icon.svg" width="14" height="14"/> Build an app

Scaffold a new app with the Twenty CLI:

```bash
npx create-twenty-app my-app
```

Define objects, fields, and views as code:

```ts
import { defineObject, FieldType } from 'twenty-sdk/define';

export default defineObject({
  nameSingular: 'deal',
  namePlural: 'deals',
  labelSingular: 'Deal',
  labelPlural: 'Deals',
  fields: [
    { name: 'name', label: 'Name', type: FieldType.TEXT },
    { name: 'amount', label: 'Amount', type: FieldType.CURRENCY },
    { name: 'closeDate', label: 'Close Date', type: FieldType.DATE_TIME },
  ],
});
```

Then ship it to your workspace:

```bash
npx twenty app:publish --private
```

See the [

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
