Real time Matrix VFX implemeted in Shaders in Unity using Triplanar mapping
=================
![screenshot](documentation/matrix_gif.gif)


For the detailed break down of the technique, have a look at my blog post: https://medium.com/@shahriyarshahrabi/shader-studies-matrix-effect-3d2ead3a84c5

---

The Mesh is from Global Digital Heritage and is licnesed under non commercial use. https://skfb.ly/6UoNJ 


---
## Documentaion 
Once you open the project, you can either open the Triplanar Scene or the ScreenSpace scene (under Assets/Scene).
The screen space showcases the matrix effect on a 2D surfaces whereas the TriplanarScene shows the effect on a 3D scene. 

On both your control center is the Managment/Manager Gameobject. There you can decide if you want to have the matrix effect colored, or generally check how the effect is dispatched. To see the effect press play. 

In the Triplanar Scene, you start with no matrix effect, if you press R, the effect will be overlayed on the mesh. Press R again and the classic matrix effect will be shown. You can press R again to go to the pervious states.

Navigation in Game view is done exactly as Scene View. Right mouse click and then fly around with WASD. Press shift to get a boost in speed. 

If you are having performance issues, turn off the post process effects. 
