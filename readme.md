Change index.md and build the html like

```bash
pandoc --css=styling.css -V lang=en -V highlighting-css= --mathjax -s -f markdown+smart --toc --metadata --to=html5 index.md -o index.html
```