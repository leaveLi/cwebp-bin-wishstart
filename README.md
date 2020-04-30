# cwebp-bin-wishstart

## 安装

```
$ npm install cwebp-bin-wishstart
```

## 使用

```js
const { execFile } = require("child_process");
const cwebp = require("cwebp-bin-wishstart");

execFile(cwebp, ["input.png", "-o", "output.webp"], (err) => {
	if (err) {
		throw err;
	}

	console.log("Image is converted!");
});
```

## CLI

```
$ npm install --global cwebp-bin-wishstart
```

```
$ cwebp --help
```
