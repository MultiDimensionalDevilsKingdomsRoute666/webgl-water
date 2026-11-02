# WebGL Water Demo

http://madebyevan.com/webgl-water/

A fork of [evanw/webgl-water](https://github.com/evanw/webgl-water), Evan Wallace's classic real-time WebGL water simulation, with ripples, caustics and a floating sphere.

## What's inside

- `index.html` and `main.js`: the demo page and its setup.
- `water.js`, `renderer.js` and `cubemap.js`: the simulation and rendering code.
- `lightgl.js` and `OES_texture_float_linear-polyfill.js`: support libraries.
- `tiles.jpg` and the `xpos/xneg/ypos/zpos/zneg.jpg` images: textures and the skybox.

## How to view it

Serve the folder with a static web server (for example `python3 -m http.server`) and open `index.html` in a browser that supports WebGL.

## Credit

The original demo is by Evan Wallace, [evanw/webgl-water](https://github.com/evanw/webgl-water).

