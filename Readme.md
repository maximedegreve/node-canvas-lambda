# 🛟 node-canvas-lambda 

This package is a modified version of [node-canvas](https://github.com/Automattic/node-canvas/) that removes JPG and SVG support to make it more compact and suitable for use in Lambda functions.

## 📝 Instructions

Update your package.json file by adding the following code. This change will help reduce the package size and enable it to work with Lambda functions. Make sure to use only PNG in your canvas code.

```
"canvas": "maximedegreve/node-canvas-lambda#3.0.0",
```

## 🥸 Tested on

- Netlify

