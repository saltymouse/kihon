# Kihon・キホン

Don't over-complicate your styles! You probably don't need Bootstrap to style your blog and demo pages.

> スタイルを考えすぎるな！ブログやランディングページを作る際にはBootstrapは多分不要。

Modern web-standards are easy to use, widely supported, and have no network overhead (it's in the browser)!

> 最新のウェブ標準は使いやすくてよくサポートされている。しかも、すでにブラウザーに入っているためにデータ通信量はゼロ！

With just a light dusting of CSS you can turn your basic HTML into an easy-to-read experience.

> たった100行のCSSでHTMLページを読みやすいオシャレなページに変換できる。

Kihon demonstrates the following modern techniques in under 800 bytes of CSS

> キホンは下記の標準機能を800バイトで証明する

Technique     | MDN Reference | Kihon Example
:------------|:-------------|:--------|
Responsive design / レスポンシブデザイン | [media-queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) | [L35](https://github.com/saltymouse/kihon/blob/master/kihon.css#L35-L39)
Grid layouts / 2次元レイアウト | [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout) |
Flexible content / 要素の配置を柔軟 | [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) | [L35](https://github.com/saltymouse/kihon/blob/master/kihon.css#L35-L39)
Variables / 変数 | [Custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) | [L1](https://github.com/saltymouse/kihon/blob/master/kihon.css#L1-L3)
Dark mode / ダークモード | [prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) | [L8](https://github.com/saltymouse/kihon/blob/master/kihon.css#L8)
Stylish (system) fonts / オシャレなフォント（OS） | [system-ui](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family) | [L25](https://github.com/saltymouse/kihon/blob/master/kihon.css#L25)
Multi-lingual style targets / 複数言語対応 | [:lang](https://developer.mozilla.org/en-US/docs/Web/CSS/:lang) | [L41](https://github.com/saltymouse/kihon/blob/master/kihon.css#L41)

### Size comparison

 Project     | Uncompressed | Gzipped
:------------|:-------------|:--------|
Kihon  | ![](https://img.badgesize.io/saltymouse/kihon/master/kihon.css.svg) | ![](https://img.badgesize.io/saltymouse/kihon/master/kihon.css.svg?compression=gzip)
Bootstrap |  ![](https://img.badgesize.io/twbs/bootstrap/master/dist/css/bootstrap.css.svg?color=orange) | ![](https://img.badgesize.io/twbs/bootstrap/master/dist/css/bootstrap.css.svg?compression=gzip&color=yellow)

### Browser support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>iOS Safari |
| --------- | --------- | --------- | --------- | --------- |
| IE11<sup>[1](#footnote-ie11)</sup>, Edge 👍| 👍| 👍| 👍| 👍

> <sup name="footnote-ie11">1</sup> Not supported but looks fine. Remove CSS Variables for full IE11 support.

Ready to use for most blogs and landing pages. Hack away and keep it simple!  
このままでブログやランディングページとして使える！カスタマイズする場合にはシンプルにしておけ！

Inspired by the wonderfully subversive [motherfuckingwebsite.com](http://motherfuckingwebsite.com)
