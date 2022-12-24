# B4UC's Hugo Theme (BUGO)

## forked from yihui xie's xmin theme

bugo is a simpler and modified version of Xmin by Yihui Xie, it basically the
theme template for my website [iamb4uc.xyz](https://iamb4uc.xyz). It has more
or less the same amount of css in it compared to the original one, I used some
custom fonts in the font section, since for me those are very readable.


```bash
find . -not -path '*/' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
   9 ./layouts/partials/footer.html
   0 ./layouts/partials/foot_custom.html
  20 ./layouts/partials/header.html
   0 ./layouts/partials/head_custom.html
   5 ./layouts/404.html
  12 ./layouts/_default/single.html
  20 ./layouts/_default/list.html
  13 ./layouts/_default/terms.html
  77 ./static/css/style.css
  13 ./static/css/fonts.css
 169 total

```
