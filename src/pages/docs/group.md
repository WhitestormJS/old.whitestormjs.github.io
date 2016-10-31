---

title: Making groups

tags:
 - three.js
 - webgl
 - 3d

---

Sometimes you need to make groups of objects _(it's not conveniently to apply transforms to each object when can make just one to a group)_. In Three.js you make it using `THREE.Object3D` and it's children.

In Whitestorm.js we have `WHS.Group` that can do it in two ways: 

### You add objects to an empty group:

```javascript

const sphere = new WHS.Sphere();
const box = new WHS.Box();
const group = new WHS.Group();

sphere.addTo(group);
box.addTo(group)

```

### You make group from objects.

```javascript

const sphere = new WHS.Sphere();
const box = new WHS.Box();
const group = new WHS.Group(box, sphere);
// OR: const group = new WHS.Group([box, sphere]);

```

> You can list elements in sequence or pass an array. (see es6 rest/spread).
