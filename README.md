# Astro proof-of-concept for simonplend.com

# TODO

- [ ] Backwards plan launching a new version of simonplend.com

# Features

### Required features

- [ ] Automatic jump links/table of contents from headings
- [ ] Heading anchors
  - Headings automatically have IDs generated for them
  - Headings automatically converted to links
- [X] Code syntax highlighting
  - Built in to Astro
- [ ] Easy to add Open Graph image, description etc.
- [ ] ConvertKit form integration
- [ ] RSS feed
  - Docs: https://docs.astro.build/en/guides/rss/
  - Example: [`examples/astro-blog-official/src/pages/rss.xml.js`](examples/astro-blog-official/src/pages/rss.xml.js)
- [ ] Sitemap
- [ ] Post tags and tag pages
- [ ] Site analytics with Plausible
- [ ] Embed YouTube videos
- [ ] Embed Vimeo videos

### Nice to have features

- [ ] Dynamically generated Open Graph images
- [ ] Estimated post reading time
- [ ] Support for line highlighting in code blocks
  - https://github.com/shikijs/shiki/pull/259
  - https://github.com/withastro/astro/pull/2587
- [ ] Site search
- [ ] Light mode / Dark mode
- [ ] Easy to embed StackBlitz

## Blog inspiration

- https://ted.dev/
- https://daveceddia.com/

## Astro blog templates

- [Astro Starter Kit: Blog](https://github.com/withastro/astro/tree/main/examples/blog)
- [Charca/astro-blog-template](https://github.com/Charca/astro-blog-template)
- [AstroPaper](https://astro.build/themes/details/astro-paper/)

## Astro integrations

### Site structure

- [@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/)
- [Astro SEO](https://github.com/jonasmerlin/astro-seo) - Meta and Open Graph tags
- [astro-robots-txt](https://github.com/alextim/astro-lib/tree/main/packages/astro-robots-txt)
- [@astrojs/image](https://docs.astro.build/en/guides/integrations-guide/image/)
- [@astrojs/prefetch](https://docs.astro.build/en/guides/integrations-guide/prefetch/)

### Content

- [astro-icon](https://github.com/natemoo-re/astro-icon)
- [Astro ImageTools](https://github.com/RafidMuhymin/astro-imagetools)
- [@astro-community/astro-embed-youtube](https://github.com/astro-community/astro-embed/tree/main/packages/astro-embed-youtube)
- [@astro-community/astro-embed-vimeo](https://github.com/astro-community/astro-embed/tree/main/packages/astro-embed-vimeo)

## Markdown plugins

- Astro uses `remark-gfm` and `remark-smartypants` by default
- [remark plugins](https://github.com/remarkjs/awesome-remark)
- [rehype plugins](https://github.com/rehypejs/awesome-rehype)
- [remark-toc](https://www.npmjs.com/package/remark-toc) - Table of contents
- [rehype-accessible-emojis](https://www.npmjs.com/package/rehype-accessible-emojis) - Not sure if it's for MDX only?
- [markdown-it-anchor](https://github.com/valeriangalliat/markdown-it-anchor)
