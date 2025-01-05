---
title: "Configuration"
weight: 30
---

# Configuration {#configuration}

## Theme Settings {#theme-settings}

### Basic Configuration Options {#basic-configuration}
Edit your config.toml to customize the theme:

```toml
[params]
  author = "Your Name"
  description = "Your site description"
  social = [
    { platform = "github", url = "https://github.com/yourusername" }
  ]
```

### Menu Configuration
Add menu items in config.toml:

```toml
[menu]
  [[menu.main]]
    name = "Home"
    url = "/"
    weight = 1
  [[menu.main]]
    name = "Documentation"
    url = "/docs/"
    weight = 2
```

### Custom Styles
Override theme styles by creating:
```bash
assets/css/custom.css
