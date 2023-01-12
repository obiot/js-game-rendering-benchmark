# Javascript rendering/game engines comparison

This is a particle-based performance test that compares a set of Javascript-based rendering/game engines that are currently maintained.

## Description

- Up to 10.000 different particles moving on a canvas with various speed
  - A custom option through the count query is also available for comparing particle counts between libraries more freely. Be aware that drawing a large number of particles on specific libraries may cause the test to freeze.
- Different libraries used to render the scene are chosen only if they have been maintained in the previous month of this benchmark. The following libraries compared are:

| Name                                                          | Stars                                                                                | Last Commit                                                                                 | Description                                                                                                 | Game engine |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ----------- |
| [three.js](https://github.com/mrdoob/three.js)                | ![GitHub Repo stars](https://img.shields.io/github/stars/mrdoob/three.js)            | ![GitHub last commit](https://img.shields.io/github/last-commit/mrdoob/three.js)            | JavaScript 3D library                                                                                       | no          |
| [PixiJS](https://github.com/pixijs/pixi.js)                   | ![GitHub Repo stars](https://img.shields.io/github/stars/pixijs/pixi.js)             | ![GitHub last commit](https://img.shields.io/github/last-commit/pixijs/pixi.js)             | Super fast HTML 5 2D rendering engine that uses webGL with canvas fallback                                  | no          |
| [Phaser](https://github.com/photonstorm/phaser)               | ![GitHub Repo stars](https://img.shields.io/github/stars/photonstorm/phaser)         | ![GitHub last commit](https://img.shields.io/github/last-commit/photonstorm/phaser)         | A popular, polished, free HTML5 game framework.                                                             | yes         |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js)         | ![GitHub Repo stars](https://img.shields.io/github/stars/BabylonJS/Babylon.js)       | ![GitHub last commit](https://img.shields.io/github/last-commit/BabylonJS/Babylon.js)       | a complete JavaScript framework for building 3D games with HTML 5 and WebGL                                 | yes         |
| [PlayCanvas](https://github.com/playcanvas/engine)            | ![GitHub Repo stars](https://img.shields.io/github/stars/playcanvas/engine)          | ![GitHub last commit](https://img.shields.io/github/last-commit/playcanvas/engine)          | JavaScript game engine built on WebGL and WebVR                                                             | yes         |
| [Two.js](https://github.com/jonobr1/two.js)                   | ![GitHub Repo stars](https://img.shields.io/github/stars/jonobr1/two.js)             | ![GitHub last commit](https://img.shields.io/github/last-commit/jonobr1/two.js)             | A renderer agnostic two-dimensional drawing api for the web.                                                | no          |
| [MelonJS](https://github.com/melonjs/melonjs)                 | ![GitHub Repo stars](https://img.shields.io/github/stars/melonjs/melonjs)            | ![GitHub last commit](https://img.shields.io/github/last-commit/melonjs/melonjs)            | Can use Tiled Map Editor, the engine is declared "lightweight"                                              | yes         |
| [Kaboom](https://github.com/replit/kaboom)                    | ![GitHub Repo stars](https://img.shields.io/github/stars/replit/kaboom)              | ![GitHub last commit](https://img.shields.io/github/last-commit/replit/kaboom)              | JavaScript game library                                                                                     | yes         |
| [LayaAir](https://github.com/layabox/LayaAir)                 | ![GitHub Repo stars](https://img.shields.io/github/stars/layabox/LayaAir)            | ![GitHub last commit](https://img.shields.io/github/last-commit/layabox/LayaAir)            | LayaAir is an open-source 2D/3D engine. LayaAir Engine is designed for high performance games.              | yes         |
| [Kontra](https://github.com/straker/kontra)                   | ![GitHub Repo stars](https://img.shields.io/github/stars/straker/kontra)             | ![GitHub last commit](https://img.shields.io/github/last-commit/straker/kontra)             | A lightweight JavaScript gaming micro-library, optimized for js13kGames.                                    | yes         |
| [Hilo3d](https://github.com/hiloteam/Hilo3d)                  | ![GitHub Repo stars](https://img.shields.io/github/stars/hiloteam/Hilo3d)            | ![GitHub last commit](https://img.shields.io/github/last-commit/hiloteam/Hilo3d)            | A 3D WebGL Rendering Engine developed by Alibaba Group                                                      | yes         |
| [Hilo](https://github.com/hiloteam/Hilo)                      | ![GitHub Repo stars](https://img.shields.io/github/stars/hiloteam/Hilo)              | ![GitHub last commit](https://img.shields.io/github/last-commit/hiloteam/Hilo)              | A Cross-end HTML5 Game development solution developed by Alibaba Group                                      | yes         |
| [webgl-operate](https://github.com/cginternals/webgl-operate) | ![GitHub Repo stars](https://img.shields.io/github/stars/cginternals/webgl-operate)  | ![GitHub last commit](https://img.shields.io/github/last-commit/cginternals/webgl-operate)  | A TypeScript based WebGL rendering framework.                                                               | no          |
| [Rhodonite](https://github.com/actnwit/RhodoniteTS)           | ![GitHub Repo stars](https://img.shields.io/github/stars/actnwit/RhodoniteTS)        | ![GitHub last commit](https://img.shields.io/github/last-commit/actnwit/RhodoniteTS)        | Rhodonite Web3D Library in TypeScript                                                                       | no          |
| [Ct.js](https://github.com/ct-js/docs.ctjs.rocks)             | ![GitHub Repo stars](https://img.shields.io/github/stars/ct-js/docs.ctjs.rocks)      | ![GitHub last commit](https://img.shields.io/github/last-commit/ct-js/docs.ctjs.rocks)      | Ct.js is a full-blown 2D game engine that allows you to easily create games based on the PIXI.js framework. | yes         |
| [Zogra](https://github.com/SardineFish/zogra-renderer)        | ![GitHub Repo stars](https://img.shields.io/github/stars/SardineFish/zogra-renderer) | ![GitHub last commit](https://img.shields.io/github/last-commit/SardineFish/zogra-renderer) | A simple WebGL2 renderer.                                                                                   | no          |

## DOM and Canvas

TBA

## WebGL

TBA

## Rendering engines

TBA

## Game engines

TBA

## Conclusion

TBA

It should be noted that being faster is not always preferable. Aside from performance, one must consider the features a library provides such as asset loading, sprite animation, input, etc. to easily create various games. In addition to this, some rendering/game engines may have a steeper learning curve than others, making them less desirable to use. It is important to consider user experience as well as speed in development and implementation.

## Readings

- [A collection of WebGL and WebGPU frameworks and libraries](https://gist.github.com/dmnsgn/76878ba6903cf15789b712464875cfdc)
- [A collection of primarily HTML5 based game engines and frameworks](https://github.com/bebraw/jswiki/wiki/Game-Engines)
- [quidmonkey's Benchmark comparison of pixijs and impactjs](https://github.com/quidmonkey/particle_test)
- [slaylines' benchmark comparison of some popular canvas engines](https://github.com/slaylines/canvas-engines-comparison)