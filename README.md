# lilgui-datgui-color-comparison

Color behavior explored for lil-gui vs dat-gui with various color formats:

```js
const params = {
    color0: "#FFAE23", // #RRGGBB string
    color1: "#ffae23", // #rrggbb string
    color2: 'rgb(123,10,250)',  // RGB string
    color3: 'rgba(123,10,250,0.5)', // RGBA string            
    color4: [ 0, 128, 255 ], // RGB array
    color5: [ 0, 128, 255, 0.3 ], // RGBA array
    color6: { r: 110, g: 0, b: 40 }, // RGB object
    color7: { r: 110, g: 0, b: 40, a: 0.5 }, // RGBA object
    color8: { h: 350, s: 0.9, v: 0.3 }, // HSV object
};
```

* [Example with lil-gui](withlilgui.html)
* [Example with dat-gui](withdatgui.html)
