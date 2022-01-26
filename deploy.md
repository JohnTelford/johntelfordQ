---
slug: deploy
title: Deploy
tags: []
---

:::caution Work in Progress
:::

---

## Deploy

Deploying a website is making it available on the Internet. The production version is deployed when stakeholders agree. Meanwhile, developers working on features, fixes, or testing may deploy private website with their changes, without disturbing other developers work or the production version. This enables the stakeholders to monitor progress.

---

## prerequisites

- Deploy
  - Production version
  - Private development stages deployments
  - Vendor

---

## Deployment

[Docusaurus](https://docusaurus.io/docs#features) supports static site hosting services such as [Vercel](https://vercel.com/), [GitHub Pages](https://pages.github.com/) , [Netlify](https://www.netlify.com/) and others. I have used these and other hosting services. My choice is Vercel.

This site is using [Vercel](https://vercel.com/) Global [Content Delivery Network (CDN)](https://en.wikipedia.org/wiki/Content_delivery_network) for deployment. Their motto is _Develop, Preview, Ship_.

:::note

---

### Vercel

This site is using [Vercel](https://vercel.com/) Global [Content Delivery Network (CDN)](https://en.wikipedia.org/wiki/Content_delivery_network) for deployment. Their motto is _Develop, Preview, Ship_.

Vercel builds the website and deploys when `git` pushes changes from the _Local Repository_ to the _Central Repository_, _Vercel_ then automatically builds the website and deploys to the Internet.

Another way is using the Vercel Command Line Interface (CLI) that builds the website and deploys it.

Some benefits deploying project with Vercel are:

- Performance
- Ease of use

:::

Some features I like are:

- Automatic deploys after a push to the GitHub repository.
  - Production website
  - Team member deploy to a secure website
- Command line deployments using the `vercel` app.
- Builds are quick, especially those with few changes.
- Redeploy previous deployments and look at the code used to generate them.

---
