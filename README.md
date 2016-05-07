---
---

# Photon Book Creator

A light documentation and book template based on [Jekyll](https://jekyllrb.com/).

[Demo »](http://cedricss.github.io/photon-book-creator)

## Themes

### Minimal Theme

<a href="http://cedricss.github.io/photon-book-creator"><img  src="https://raw.githubusercontent.com/cedricss/photon-book-creator/master/img/photon-theme-minimal.png"</img></a>

### Freelancer Theme

<a href="http://cedricss.github.io/photon-book-creator"><img  src="https://raw.githubusercontent.com/cedricss/photon-book-creator/master/img/photon-theme-freelancer.png"</img></a>

## Configuration

`_config.yml`:

```yaml
themes:
    # General themes available: minimal, freelancer
    general: minimal
    # Code block themes available: monokai, github, vs
    code: monokai
```

`data/toc.yml`:

```yaml
entries:

- title: Entry 1
  pages:

  - title: Page 1
    url: page-1.html
    sections:
    - title: Section a
    - title: Section b
    - title: Section c
```

# Credits

- [CREDITS.md](CREDITS.md)

# Author

**Cédric Soulas**
- <https://github.com/cedricss>
- <https://twitter.com/CedricSoulas>

## License

Open sourced under the [MIT license](LICENSE.md).