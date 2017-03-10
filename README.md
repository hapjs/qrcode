# qrcode

install 

```shell
npm install -DS git+https://github.com/hapjs/qrcode.git
```

usage

```html
<div class="qrcode"></div>
```

```js
var qrcode = new QRCode(document.querySelector(".qrcode"), {
    text: "Hello World",
    width: 100,
    height: 100,
    colorDark : "#000000",
    colorLight : "#ffffff",
    correctLevel : QRCode.CorrectLevel.H
});
```
