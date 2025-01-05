---
title: "Usage"
weight: 20
---

# Usage Guide {#usage-guide}

## Content Management {#content-management}

### Creating New Content {#creating-content}
Create new content using Hugo's content commands:
```bash
hugo new posts/my-post.md
```

### Customizing Layouts
Override theme layouts by copying them to your site's layouts directory:
```bash
cp -r themes/minimalist/layouts/ layouts/
```

### Adding Pages
Add new pages to the content directory:
```bash
hugo new about.md
