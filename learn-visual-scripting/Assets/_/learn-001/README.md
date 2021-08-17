# Overview

1. Create a cube on the scene
2. Add ScriptMachine component to Cube
3. Click New at Graph and save the ScriptGraph asset anywhere

![](./Screenshots/Unity_r3VALUTK0Z.png)

4. Click Regnerate Units in Visual Scripting section in ProjectSettings

In side ScriptGraph, add following nodes

- Debug with one message
- String literal

![](./Screenshots/Unity_5wzxhzj448.png)

After adding these two nodes, can enter Play mode. While in play mode, there the ScriptGraph will be executed like this

![](./Screenshots/Unity_vCnXv35vfY.png)

Notice that the graph should be looking very similiar at editor time and run time. But in runtime, the node that is currently being executed is highlighted differently.

The following words should be printed on editor console.

```
Hello World
```

![](./Screenshots/Unity_BEVs2DxUWZ.png)