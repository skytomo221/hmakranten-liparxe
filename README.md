# hmakranten liparxe

hmakranten liparxeは、はてなブログでリパライン語を書くときに、他の文字体系（特にラテン文字）とマッチするように、作られたフォントです。

## はてなブログの設定方法

1. 設定からデザインを開きます。
2. カスタマイズを開きます。
3. デザインCSSを開きます。
4. 以下をコピー＆ペーストします。

```css
/* リパライン語用フォント */
@font-face {
    font-family: "hmakranten liparxe";
    src: url("https://skytomo221.github.io/hmakranten-liparxe/WOFF/hmakranten_liparxe.woff"); format('woff');
}
.lineparine {
    font-family: "hmakranten liparxe";
}
```

リパライン語を書く際は以下のようにして、書きます。

```html
<span class="lineparine">hmakranten liparxe</span>
```

## ライセンス

このフォントはSource Sans Proを改変したものなので、
SIL OPEN FONT LICENSE Version 1.1に従います。
詳しくは[LICENSE](./LICENSE.md)を参照してください。
