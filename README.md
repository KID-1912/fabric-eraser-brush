# fabric-eraser-brush

<h3 align="center">
    fabric.js添加擦除画笔支持，来源于官方自定义构建(Erasing)作为npm包；
    fabric.js adds erasing brush support, sourced from the official custom build (Erasing) as an npm package.
</h3>

<br/>

![](https://kid-1912.github.io/img/FabricJS.jpg)

---

<p align="center">
  <a href="https://www.npmjs.com/package/fabric-eraser-brush">
    <img
     alt="NPM URL"
     src="https://img.shields.io/badge/npm-fabricEraserBrush?logo=npm">
  </a>
  <img
     alt="version"
     src="https://img.shields.io/badge/version-1.0.1-blue">
</p>

## Install

```shell
npm install fabric-eraser-brush -S
```

## Usage

```js
import { fabric } from "fabric";
import "fabric-eraser-brush";

const canvas = new fabric.Canvas("canvas", {
  isDrawingMode: true,
});
canvas.freeDrawingBrush = new fabric.EraserBrush(canvas);
canvas.freeDrawingBrush.width = 15; // optional
```

more usage see [Erasing with Eraser Brush](http://fabricjs.com/erasing)
