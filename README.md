# cwebp-bin-wishstart

## vendor 资源转存wishstart

## 安装

```
$ npm install cwebp-bin
```


## 使用

```js
const {execFile} = require('child_process');
const cwebp = require('cwebp-bin');

execFile(cwebp, ['input.png', '-o', 'output.webp'], err => {
	if (err) {
		throw err;
	}

	console.log('Image is converted!');
});
```


## CLI

```
$ npm install --global cwebp-bin
```

```
$ cwebp --help
```

