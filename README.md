# ZolaProse

[Zola](https://www.getzola.org) + [prose.sh](https://prose.sh) = ZolaProse

A blog, powered by Zola, using template and style from prose.sh

## Features

- Minimalism
- No JavaScript
- Purely static — no server-side rendering or special middleware required
- Built-in RSS feed support
- Fast and lightweight performance
- Markdown-first content approach

## Usage

### Deploy via Web Hosting Service

1. Fork this repository
2. Import the project into your preferred web hosting service (e.g., Vercel,
   Netlify, Cloudflare Pages, etc.)
3. Configure deployment settings:

| Setting              | Value          |
| -------------------- | -------------- |
| **Build Command**    | `zola build`   |
| **Output Directory** | `public`       |

### Local Build

Ensure you have [Zola](https://www.getzola.org/documentation/getting-started/installation/) installed, then run:

```bash
zola build
```

The built site will be generated in the `public` directory.

For local development with live reload:

```bash
zola serve
```

# License

Everything except the `/content` is under the MIT License.
