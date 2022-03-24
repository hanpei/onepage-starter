# ONEPAGE-STARTER

### Overview

A blog template for onepage.
one page is a static site generator, written by rust.
Check this repo: [ONEPAGE](https://github.com/hanpei/onepage)

- Read /pages markdown files
- Parse md to html by [pulldown cmark](https://docs.rs/pulldown-cmark/latest/pulldown_cmark/)
- Render into [tera template](https://github.com/Keats/tera)
- styled by [picocss](https://picocss.com/) and [highlightjs](https://highlightjs.org/)

### Online demo

[My blog](https://blog.nexts.top)

### Structure

- `/dist`: generated site
- `/pages`: markdown source file
  - `index.md` => _index page_
  - `/posts/*.md` => _post page_
  - `/image` images used in markdown file
- `/static`: static resources
  - `/assets`: img/css/font
  - `/favicon` favicon files
- `/templates`: html templates
