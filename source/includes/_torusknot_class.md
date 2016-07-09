<h2 class="ws" id="torusknot">Torusknot [Class]</h2>

> WHS.Torusknot example:

```javascript

var torusknot = GAME.Torusknot({

    geometry: {
        radius:5,
        tube: 2
    },

    mass: 10,

    material: {
        vertexColors: THREE.VertexColors,
        shading: THREE.SmoothShading,
        map: api.texture('assets/textures/bricks.jpg'),
        kind: "phong"
    },

    pos: {
        x: 0,
        y: 100,
        z: 0
    }

});

```


`WHS.Torusknot` is a simple class, it extends `WHS.Shape` and inherits all it's methods.

`WHS.Torusknot` class makes a torusknot figure. It's like crooked donut, very crooked.

Parameter          |       Default        | Type      | Description |
------------------ | -------------------- | --------- | ----------- |
**radius**         | 100                  | `Number`  | Torus radius.
**tube**           | 40                   | `Number`  | Torus tube radius.
**radialSegments** | 8                    | `Number`  | Radial segments.
**tubularSegments**| 6                    | `Number`  | Tubular segments.
**p**              | 2                    | `Number`  | TODO
**q**              | 3                    | `Number`  | TODO
**heightScale**    | 1                    | `Number`  | Height scale.

<script src="https://gist.github.com/sasha240100/186976e65a13e62ec333.js"></script>

<img src="images/shapes/torusknot.png" alt="torusknot shape">