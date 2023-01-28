# n4m-qrcode-generator

MaxMSP QRCode generator allow you to generate a QRCode image from some text, web URL, etc.

![QRCode generator](http://float.intplusplus.cn/Kapture%202019-01-21%20at%2020.53.57.gif)

It uses "[Node for Max](https://github.com/Cycling74/n4m-examples)" package of Max8.

And the node package "[node-qrcode](https://github.com/soldair/node-qrcode)".

***

## Files

`qrcode-generator.maxpat` : The Max patch to run the example. It will generate a png file in qrcode folder from the message text.<br />
`qrcode-generator.js` : The launcher JS for the NodeJS script. <br />
`README.md` : This file!<br />

***

## Usage

1. Launch the `qrcode-generator.maxpat` Max patch.
2. Click on the [script npm install] once to install the NodeJS package. And then click on the [script start] message to start the Node process.
3. Click the two example message object. You will see the image file generated in qrcode folder, and the image rendered in window.
4. You can scan the QRCode image using mobile phone App to see the result.

----
Cheers~

Contra

- patreon (**buy me a coffee** XD): [avantcontra](https://www.patreon.com/avantcontra)
- website: [avantcontra.com](https://www.avantcontra.com)
- instagram: [avantcontra](https://instagram.com/avantcontra)
- twitter: [avantcontra](https://twitter.com/avantcontra)
- 公/知/小/抖/B：[实验编程](https://space.bilibili.com/309452713)
