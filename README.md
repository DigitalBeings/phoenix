# Phoenix

Rigged glTF vehicle that an avatar can sit on and commandeer.

![image](https://user-images.githubusercontent.com/64185677/169653413-2d3e2241-b89f-4780-9407-e948c7998042.png)

"phoenix bird" (https://skfb.ly/6vLBp) by NORBERTO-3D is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).

## `.metaversefile`

The .metaversefile goes in the directory with the GLB file in order to create the XRpackage.


```
{
  "name": "phoenix",
  "start_url": "phoenix.glb",
  "components": [
    {
      "key": "sit",
      "value": {
        "subtype": "saddle",
        "sitOffset": [0, 0.6, 0],
        "walkAnimation": ["wing_2_low|Take 001|BaseLayer", "wing_2_low001|Take 001|BaseLayer", "Object001|Take 001|BaseLayer", "Object002|Take 001|BaseLayer", "Object003|Take 001|BaseLayer", "Object004|Take 001|BaseLayer"],
        "walkAnimationHoldTime": 1,
        "walkAnimationSpeedFactor": 0.1,
        "speed": 0.02,
        "damping": 0.99
      }
    }
  ]
}
```
