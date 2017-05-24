---

title: firstPersonControls
longtitle: WHS.firstPersonControls
category: Controls
wip: 
 - Add a properties table
 - Rewrite

tags:
 - controls
 - 1st person controls

---

In video games, the **first person** refers to a graphical perspective rendered from the viewpoint of the player character. In many cases, this may be the viewpoint from the cockpit of a vehicle. 
Many different genres have made use of first-person perspectives, ranging from adventure games to flight simulators. Perhaps the most notable genre to make use of this device is the _first-person shooter_, where the graphical perspective has an immense impact on game play.

```javascript

const sphere = new WHS.Sphere( {
  geometry: {
    radius: 2
  },

  mass: 10,

  material: {
    color: 0xffffff,
    kind: 'lambert'
  },

  pos: {
    y: 100
  }
});

sphere.addTo(world);

world.setControls(
  new WHS.firstPersonControls(sphere, {
    block: document.getElementById('blocker'),
    speed: 5,
    ypos: 1
  })
);

```

## Parameters
```javascript
{
  block: document.getElementById('blocker'),
  speed: 1,
  ypos: 1
}
```
