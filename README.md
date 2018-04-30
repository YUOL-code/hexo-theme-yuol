# hexo-theme-yuol

[bootstrap-url]: https://getbootstrap.com/
[yuol-osc]: https://YUOL-code.github.io/

A hexo theme for Yangtze University open source community. Based on [Bootstrap v4.1][bootstrap-url].

- [Preview][yuol-osc]

## Installation

### Install

```bash
$ git clone --depth 1 https://github.com/YUOL-code/hexo-theme-yuol.git themes/yuol
$ npm i -S hexo-renderer-njucks
```

**This theme require Hexo 2.4 and above. Also `hexo-renderer-njucks` plugin as template renderer is required.**

### Enable

Modify theme setting in `_config.yml` to `yuol`.

### Update

```bash
cd themes/yuol
git pull
```

## Configuration

```yaml
# Header
menu:
  Home: /
  Archives: /archives

# Miscellaneous
favicon: /favicon.png
```

- **menu** - Navigation menu
- **favicon** - Favicon path
