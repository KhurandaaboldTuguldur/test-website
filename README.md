
```
test-website
└─ mysite
   ├─ .hugo_build.lock
   ├─ archetypes
   │  └─ default.md
   ├─ assets
   │  └─ css
   │     ├─ main.css
   │     └─ style.css
   ├─ configTaxo.toml
   ├─ content
   │  └─ post
   │     ├─ emoji-support.md
   │     ├─ image-test.md
   │     ├─ markdown-syntax.md
   │     ├─ math-typesetting.md
   │     ├─ placeholder-text.md
   │     └─ rich-content.md
   ├─ data
   ├─ go.mod
   ├─ hugo.toml
   ├─ i18n
   ├─ images
   │  ├─ screenshot.png
   │  └─ tn.png
   ├─ layouts
   │  ├─ 404.html
   │  ├─ partials
   │  │  ├─ analytics.html
   │  │  ├─ footer.html
   │  │  ├─ head.html
   │  │  ├─ header.html
   │  │  ├─ metrika.html
   │  │  ├─ paginator.html
   │  │  ├─ seo
   │  │  │  ├─ extend.html
   │  │  │  ├─ print.html
   │  │  │  └─ tags.html
   │  │  ├─ widgets
   │  │  │  ├─ archive.html
   │  │  │  ├─ category.html
   │  │  │  ├─ recent.html
   │  │  │  ├─ search.html
   │  │  │  └─ tags.html
   │  │  └─ widgets.html
   │  ├─ post
   │  │  └─ single.html
   │  ├─ shortcodes
   │  │  └─ instagram.html
   │  └─ _default
   │     ├─ baseof.html
   │     ├─ list.html
   │     ├─ single.html
   │     └─ summary.html
   ├─ netlify.toml
   ├─ package-lock.json
   ├─ package.json
   ├─ postcss.config.js
   ├─ public
   │  ├─ archives
   │  │  ├─ 2019
   │  │  │  └─ 03
   │  │  │     ├─ index.html
   │  │  │     ├─ index.xml
   │  │  │     └─ page
   │  │  │        └─ 1
   │  │  │           └─ index.html
   │  │  ├─ 2020
   │  │  │  └─ 08
   │  │  │     ├─ index.html
   │  │  │     ├─ index.xml
   │  │  │     └─ page
   │  │  │        └─ 1
   │  │  │           └─ index.html
   │  │  ├─ index.html
   │  │  ├─ index.xml
   │  │  └─ page
   │  │     └─ 1
   │  │        └─ index.html
   │  ├─ categories
   │  │  ├─ index.html
   │  │  ├─ index.xml
   │  │  ├─ page
   │  │  │  └─ 1
   │  │  │     └─ index.html
   │  │  ├─ syntax
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  └─ themes
   │  │     ├─ index.html
   │  │     ├─ index.xml
   │  │     └─ page
   │  │        └─ 1
   │  │           └─ index.html
   │  ├─ css
   │  │  ├─ blonde.css
   │  │  ├─ blonde.min.css
   │  │  └─ style.css
   │  ├─ favicon
   │  │  ├─ apple-touch-icon.png
   │  │  ├─ favicon-16x16.png
   │  │  ├─ favicon-32x32.png
   │  │  ├─ favicon.ico
   │  │  ├─ favicon.png
   │  │  ├─ safari-pinned-tab.svg
   │  │  └─ site.webmanifest
   │  ├─ fonts
   │  │  ├─ material-icons.svg
   │  │  ├─ material-icons.ttf
   │  │  └─ material-icons.woff
   │  ├─ img
   │  │  └─ default.jpg
   │  ├─ index.html
   │  ├─ index.xml
   │  ├─ LICENSE
   │  ├─ netlify.toml
   │  ├─ page
   │  │  ├─ 1
   │  │  │  └─ index.html
   │  │  └─ 2
   │  │     └─ index.html
   │  ├─ post
   │  │  ├─ emoji-support
   │  │  │  └─ index.html
   │  │  ├─ image-test
   │  │  │  └─ index.html
   │  │  ├─ index.html
   │  │  ├─ index.xml
   │  │  ├─ markdown-syntax
   │  │  │  └─ index.html
   │  │  ├─ math-typesetting
   │  │  │  └─ index.html
   │  │  ├─ migrate-from-jekyl
   │  │  │  └─ index.html
   │  │  ├─ page
   │  │  │  └─ 1
   │  │  │     └─ index.html
   │  │  ├─ placeholder-text
   │  │  │  └─ index.html
   │  │  └─ rich-content
   │  │     └─ index.html
   │  ├─ README.md
   │  ├─ robots.txt
   │  ├─ sitemap.xml
   │  ├─ tags
   │  │  ├─ css
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ emoji
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ html
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ index.html
   │  │  ├─ index.xml
   │  │  ├─ markdown
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ page
   │  │  │  └─ 1
   │  │  │     └─ index.html
   │  │  ├─ privacy
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ shortcodes
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  ├─ text
   │  │  │  ├─ index.html
   │  │  │  ├─ index.xml
   │  │  │  └─ page
   │  │  │     └─ 1
   │  │  │        └─ index.html
   │  │  └─ themes
   │  │     ├─ index.html
   │  │     ├─ index.xml
   │  │     └─ page
   │  │        └─ 1
   │  │           └─ index.html
   │  └─ theme.toml
   ├─ resources
   │  └─ _gen
   │     └─ assets
   │        └─ css
   │           ├─ style.css_e03652540c5bbc68d359e86d9fc1015a.content
   │           └─ style.css_e03652540c5bbc68d359e86d9fc1015a.json
   ├─ static
   │  ├─ css
   │  │  ├─ blonde.css
   │  │  └─ blonde.min.css
   │  ├─ favicon
   │  │  ├─ apple-touch-icon.png
   │  │  ├─ favicon-16x16.png
   │  │  ├─ favicon-32x32.png
   │  │  ├─ favicon.ico
   │  │  ├─ favicon.png
   │  │  ├─ safari-pinned-tab.svg
   │  │  └─ site.webmanifest
   │  ├─ fonts
   │  │  ├─ material-icons.svg
   │  │  ├─ material-icons.ttf
   │  │  └─ material-icons.woff
   │  ├─ img
   │  │  └─ default.jpg
   │  ├─ LICENSE
   │  ├─ netlify.toml
   │  ├─ README.md
   │  └─ theme.toml
   ├─ tailwind.config.js
   └─ themes
      └─ Blonde
         ├─ archetypes
         │  └─ default.md
         ├─ assets
         │  └─ css
         │     ├─ main.css
         │     └─ style.css
         ├─ exampleSite
         │  ├─ archetypes
         │  │  └─ default.md
         │  ├─ configTaxo.toml
         │  ├─ content
         │  │  ├─ about.md
         │  │  ├─ archives.md
         │  │  ├─ contact.md
         │  │  ├─ post
         │  │  │  ├─ emoji-support.md
         │  │  │  ├─ image-test.md
         │  │  │  ├─ markdown-syntax.md
         │  │  │  ├─ math-typesetting.md
         │  │  │  ├─ placeholder-text.md
         │  │  │  └─ rich-content.md
         │  │  └─ _index.md
         │  ├─ go.mod
         │  ├─ hugo.toml
         │  ├─ layouts
         │  ├─ netlify.toml
         │  ├─ package-lock.json
         │  ├─ package.json
         │  ├─ postcss.config.js
         │  ├─ static
         │  │  ├─ css
         │  │  │  └─ custom.css
         │  │  ├─ favicon
         │  │  │  ├─ apple-touch-icon.png
         │  │  │  ├─ favicon-16x16.png
         │  │  │  ├─ favicon-32x32.png
         │  │  │  ├─ favicon.ico
         │  │  │  ├─ favicon.png
         │  │  │  ├─ safari-pinned-tab.svg
         │  │  │  └─ site.webmanifest
         │  │  └─ img
         │  │     └─ prism.jpg
         │  └─ tailwind.config.js
         ├─ images
         │  ├─ screenshot.png
         │  └─ tn.png
         ├─ layouts
         │  ├─ 404.html
         │  ├─ partials
         │  │  ├─ analytics.html
         │  │  ├─ footer.html
         │  │  ├─ head.html
         │  │  ├─ header.html
         │  │  ├─ metrika.html
         │  │  ├─ paginator.html
         │  │  ├─ seo
         │  │  │  ├─ extend.html
         │  │  │  ├─ print.html
         │  │  │  └─ tags.html
         │  │  ├─ widgets
         │  │  │  ├─ archive.html
         │  │  │  ├─ category.html
         │  │  │  ├─ recent.html
         │  │  │  ├─ search.html
         │  │  │  └─ tags.html
         │  │  └─ widgets.html
         │  ├─ post
         │  │  └─ single.html
         │  ├─ shortcodes
         │  │  └─ instagram.html
         │  └─ _default
         │     ├─ baseof.html
         │     ├─ list.html
         │     ├─ single.html
         │     └─ summary.html
         ├─ LICENSE
         ├─ netlify.toml
         ├─ README.md
         ├─ static
         │  ├─ css
         │  │  ├─ blonde.css
         │  │  └─ blonde.min.css
         │  ├─ fonts
         │  │  ├─ material-icons.svg
         │  │  ├─ material-icons.ttf
         │  │  └─ material-icons.woff
         │  └─ img
         │     └─ default.jpg
         └─ theme.toml

```