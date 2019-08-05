# Virtual Lolly

Making virtual lollipops for you to send to people to pep them up.

(Also a proof of concept site demonstrating a JAMstack approach where newly created content is rendered from a content API, while a static render of it is being built into the site for future )

![](vlolly-screenshot.jpg)


## Deployed and hosted on Netlify

[![Netlify Status](https://api.netlify.com/api/v1/badges/ea24a6f2-024b-4d26-94c2-69d7ed96516d/deploy-status)](https://app.netlify.com/sites/vlolly/deploys)

- User generated data stored by [Fauna DB](https://www.fauna.com) via a serverless function
- Site generate (pre-rendered) by [Eleventy](https://11ty.io)
- Newly created items served via a client-side request to the content API thanks to [Netlify's custom 404 routing](https://www.netlify.com/docs/redirects/#custom-404)

