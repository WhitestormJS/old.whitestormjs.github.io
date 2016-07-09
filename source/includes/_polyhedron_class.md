<h2 class="ws" id="polyhedron">Polyhedron [Class]</h2>

> WHS.Polyhedron example: 

```javascript

var polyhedron = GAME.Polyhedron({
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


`WHS.Polyhedron` is a simple class, it extends `WHS.Shape` and inherits all it's methods.

In elementary geometry, a **polyhedron** is *a solid in three dimensions with flat polygonal faces, straight edges and sharp corners or vertices*.

<img src="images/shapes/polyhedron.gif" alt="rendered polyhedron">

`WHS.Polyhedron` creates Polyhedron object by it's `radius` and `detail`.

Parameter         |       Default        | Type      | 
----------------- | -------------------- | --------- | 
**verticesOfCube**| get verticesOfCube   | `Array`   |
**indicesOfFaces**| get indicesOfFaces   | `Array`   |
**radius**        | 6                    | `Number`  |
**detail**        | 2                    | `Number`  | 

<script src="https://gist.github.com/sasha240100/d821cc016863b6d71266.js"></script>