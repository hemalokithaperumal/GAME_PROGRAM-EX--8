# GAME_PROGRAM-EX--8
### Landscape Creation and Foliage in Unreal Engine
## Aim
To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for realistic environment generation.

## Procedure

1.Create a New Landscape:

1.Open your Unreal Engine project.

2.Go to the Modes Panel and select Landscape.


3.Set the desired section size, number of components, and overall resolution.

4.Click Create to generate the landscape.

2.Apply a Landscape Material:

1.In the Content Browser, create a new Material and name it M_Landscape.

2.Open the material and:

3.Use Landscape Layer Blend to blend textures (e.g., grass, rock, dirt).

4.Connect appropriate texture samplers to different layers.

5.Output the final blend to the Base Color, Normal, and optionally Roughness inputs.

6.Save the material.

7.Select the landscape in the scene, go to the Details Panel, and assign M_Landscape to the Landscape Material slot.

3.Add Foliage:



1.Go to the Foliage Mode from the Select Mode dropdown.

2.In the Foliage Panel, click the + icon to add Static Meshes (e.g., trees, grass, bushes).

3.Adjust settings like Density, Scale, and Randomness.

4.Use the brush tool to paint foliage onto the landscape.


## output

<img width="1540" height="828" alt="image" src="https://github.com/user-attachments/assets/13e1348b-cdb4-490d-b013-6711b84b41da" />
<img width="1519" height="838" alt="image" src="https://github.com/user-attachments/assets/94a84525-754d-4793-bf2f-5247e87574f5" />


## Result

A landscape was successfully created and enhanced with:

A layered, textured material using M_Landscape.
Static mesh fol
