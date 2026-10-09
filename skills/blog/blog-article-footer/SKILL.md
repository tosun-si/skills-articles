---
name: blog-article-footer
description: Mazlum's standard "follow me" footer for blog articles (Medium, dev.to, cross-posts) with his social/media links. Trigger when writing, finishing, or cross-posting a blog article (article.md, article-devto.md, Medium/dev.to drafts), or when asked for the article footer / social links.
---

# Blog article footer

Every article ends with a short intro sentence followed by the list of media links.

## Template

```markdown
---

If you enjoyed this article, follow me for more content on AI agents, Google Cloud, Software, DevOps, Tech and data engineering:

- [dev.to](https://dev.to/mazlum_tosun)
- [Medium](https://medium.com/@mazlum.tosun)
- [YouTube](https://bit.ly/gcp-learning-mazlum-gb)
- [X](https://x.com/MazlumTosun3)
- [LinkedIn](https://www.linkedin.com/in/mazlum-tosun-900b1812)
```

## Rules

- **Links are fixed** — always use the exact URLs above, in this order.
- **The intro sentence is adaptable** — tailor the list of topics to the article's nature (e.g. drop "AI agents" for a pure Terraform article, add "Kotlin" for a JVM one). Keep the "If you enjoyed this article, follow me for more content on ...:" shape.
- On a **dev.to cross-post** of a Medium article:
  - Set `canonical_url` in the front matter to the Medium URL.
  - Add at the top: `> *This article was originally published on [Medium (...)](<medium-url>).*`
  - The footer stays the same (keep the dev.to link in the list).
