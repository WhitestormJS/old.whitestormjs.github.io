<h2 class="ws" id="tetrahedron">Tetrahedron [Class]</h2>

> WHS.Tetrahedron example: 

```javascript

var tetrahedron = GAME.Tetrahedron({
    geometry: {
        radius: 2,
        detail: 1
    },

    mass: 10,

    material: {
        color: 0xffffff,
        kind: "basic"
    },

    pos: {
        x: 0,
        y: 100,
        z: 0
    }
});

```


`WHS.Tetrahedron` is a simple class, it extends `WHS.Shape` and inherits all it's methods.

In geometry, a **tetrahedron** is *a polyhedron composed of four triangular faces, six straight edges, and four vertex corners*. The tetrahedron is the simplest of all the ordinary convex polyhedra and the only one that has fewer than 5 faces.

<img src="images/shapes/tetrahedron.gif" alt="rendered tetrahedron">

`WHS.Tetrahedron` creates Tetrahedron object by it's `radius` and `detail`.

Parameter         |       Default        | Type      | 
----------------- | -------------------- | --------- | 
**radius**        | 1                    | `Number`  |
**detail**        | 1                    | `Number`  | 

<script src="https://gist.github.com/sasha240100/769a64629d8180f38a17.js"></script>