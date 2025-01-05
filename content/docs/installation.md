---
title: "Installation"
weight: 10
---

# Installation {#installation}

## Requirements {#installation-requirements}
- Hugo extended version (recommended)
- Git

## Installation Steps {#installation-steps}

### 1. Clone the repository {#clone-repository}
```bash
git clone https://github.com/yourusername/minimalist-hugo-theme.git
```

2. Navigate to your Hugo site directory:
```bash
cd your-hugo-site
```

3. Add the theme as a submodule:
```bash
git submodule add https://github.com/yourusername/minimalist-hugo-theme.git themes/minimalist
```

4. Update your site configuration (config.toml):
```toml
theme = "minimalist"
