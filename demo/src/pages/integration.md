---
title: Markdown integration test
layout: ../layouts/Base.astro
---

This page’s Markdown just contains URLs to items you might like to embed. The integration in `astro.config.mjs` automatically converts them to an embed:

```js
// astro.config.mjs

import { defineConfig } from 'astro/config';
import embeds from 'astro-embed/integration';

defineConfig({
  integrations: [embeds()],
});
```

https://twitter.com/astrodotbuild/status/1511750228428435457

https://vimeo.com/32001208

http://www.youtube.com/watch?v=Hoe-woAhq_k
