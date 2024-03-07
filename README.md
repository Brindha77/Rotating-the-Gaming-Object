# Rotating-the-Gaming-Object

## Aim :

To develop a 3D application for rotating the gaming objects in unity.

## Algorithm :

### Step 1 :
Create a project.

### Step 2 :
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)

### Step 3 :
Click Hierarchy -> 3DObject -> Cylinder Hierarchy -> 3DObject -> Capsule Hierarchy -> 3DObject -> Text Hierarchy -> Effects -> Particle system

### Step 4 :
Create a folder in project and name as Materials Material folder -> Create -> Material (Name: Cylinder) Inspector ->Surface Inputs ->BaseMAp (Choose the color) Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials Material folder -> Create -> Material (Name: Capsule) Inspector ->Surface Inputs ->BaseMAp (Choose the color) Drag the Capsule to the plane and release the mouse

### Step 5 :
Click Hierarchy -> DirectionalLight Inspector -> Change the color to white (255,255,255)

### Step 6 :
Create a folder name Coding and create a C# file to add the coding in it.

### Step 7 :
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Step 8 :
Stop.

## Program :

### DEVELOPED BY : BRINDHA.R
### REG NO : 212222230023
```

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Rotate : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.up, Vector3.right, 80 * Time.deltaTime);
    
        
    }
}
```

## Output :

![ex1](https://github.com/Brindha77/Rotating-the-Gaming-Object/assets/118889143/fd668c69-9be4-4011-be17-68594dab3e00)

## Result :

Thus, developing a 3D application for rotating the gaming objects in unity is executed successfully.
