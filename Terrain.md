
# Create Terrain
After we’ve built our pyramid we can start creating the terrain.

In the Hierarchy window right click > 3D Object > Terrain. Adjust the Terrain size by going to the Inspector tab down to the Terrain window. Select Terrain Settings (the mountain icon at the end on the right). 


<img width="300" alt="Screenshot 2024-09-20 at 5 57 55 PM" src="https://github.com/user-attachments/assets/800203a6-3718-4557-9a87-6c5a0db8a6af">


Scroll down to Mesh Resolution (On Terrain Data). Change the terrain width and length to 50 each.

<img width="300" alt="Screenshot 2024-09-20 at 6 23 14 PM" src="https://github.com/user-attachments/assets/f9b66b73-db12-4550-bc49-a5fc2b239ee9">


Center the pyramid around on the terrain. You can easily do this by selecting the terrain and using the move tool.


<img width="600" alt="Screenshot 2024-09-19 at 6 36 53 PM" src="https://github.com/user-attachments/assets/b1568332-0d34-4268-94df-8eda91a37977">


# Set Height 
  Scroll back up to the Terrain properties. Select the Paint Terrain property (the mountain icon with a paintbrush) and select Set Height on the option bar. Make sure Space is set to World. Set the Height field to about 250. Click Flatten All to actualize changes. 

<img width="300" alt="Screenshot 2024-09-20 at 6 26 12 PM" src="https://github.com/user-attachments/assets/0663ddd3-f54b-4ced-a4bd-31eb507ef443">


# Create the lake
With the terrain object selected, create the lake around by dipping the ground. In the Paint Terrain change Set Height to Raise or Lower Terrain. Select a soft brush with a size of 8-9 and an opacity of 6-7. To lower the terrain, shift and drag the brush around the pyramid. This is easier to do from above on the y-perspective.

<img width="600" alt="Screenshot 2024-09-19 at 6 38 34 PM" src="https://github.com/user-attachments/assets/09c7c052-54ca-4d9a-9adf-c817cc9f39a5">

Once we are satisfied we can begin applying textures to bring the terrain to life. 

# Textures

For textures you can go to the Unity Asset Store and search for free textures that you can automatically download to your unity. Otherwise you can also create a texture by searching online for the texture type you are looking for and downloading it as a png. Make sure all the textures you want to use are in one folder for convenience. In this case I will download a mud and sand texture and move them into my texture folder that already exists and has other textures I will be using. Move this texture folder directly from your files to the unity Asset folder by dragging it in. Now you should be able to access the textures from unity.

<img width="600" alt="Screenshot 2024-09-20 at 7 04 45 PM" src="https://github.com/user-attachments/assets/a52824f1-63f7-4790-92f9-c599916b8f00">

# Painting the Terrain

Make sure youre terrain is selected and acces the Paint Terrain Property to change Raise or Lower Terrain to Paint texture. Click Edit Terrain Layers > Add Layer.
Choose the texture you would like to use as your base. In this case I chose stone. 

<img width="300" alt="Screenshot 2024-09-19 at 7 08 06 PM" src="https://github.com/user-attachments/assets/fb331507-b4f7-4292-b835-34f01b9467ab">


To fix the repetitiveness of the pattern click on the new layer and scroll down to change the Tiling Settings.


<img width="300" alt="Screenshot 2024-09-19 at 7 11 59 PM" src="https://github.com/user-attachments/assets/343aa536-fa7d-4142-bdc6-bbbb3ce09c6b">


So far it should look like this:

<img width="600" alt="Screenshot 2024-09-19 at 6 57 44 PM" src="https://github.com/user-attachments/assets/0890c521-81b5-4e0c-b6f1-5ef7e5633a30">


Lets add the other textures. For every new texture add a new layer which will open a window with your textures and select which you'd like to add. 

<img width="300" alt="Screenshot 2024-09-20 at 7 20 12 PM" src="https://github.com/user-attachments/assets/e546cea9-e92b-45e1-b156-c428292442da">

To layer the the textures click the layer you want to apply and scroll down to the brush section. Pick a soft brush with a size 8-10 and opacity of 5-6 for a more natural finish. First layer softly with the dry grass texture. 

<img width="600" alt="Screenshot 2024-09-19 at 7 09 32 PM" src="https://github.com/user-attachments/assets/f272b6cc-4a08-443d-8b5e-ab2000357243">

You can also change the tiling of this layer for a more realistic effect.

<img width="300" alt="Screenshot 2024-09-19 at 7 11 59 PM" src="https://github.com/user-attachments/assets/fd76f7c1-0845-4860-9a7c-dc0f0a9195d5">

Now let's add our mud. Create a new layer and import the mud texture. Begin brushing around the edges following the refrence you are using for your enviorment. 

<img width="600" alt="Screenshot 2024-09-19 at 7 13 53 PM" src="https://github.com/user-attachments/assets/d533ab52-9f27-420c-9e28-d951cfb95ea8">

To diffuse some of the repetitive pattern layer different textures at varying light opacities to blend them in.

<img width="600" alt="Screenshot 2024-09-19 at 7 16 29 PM" src="https://github.com/user-attachments/assets/af1af535-5868-48ff-a39a-42151e2dcb1e">

Once you are satisfied continue with the next step.

<img width="600" alt="Screenshot 2024-09-19 at 7 18 49 PM" src="https://github.com/user-attachments/assets/8b217e41-447c-4114-98f3-a063abd42efb">

# Adding Water

To create a makeshift water effect add a new 3d cube object. 

<img width="600" alt="Screenshot 2024-09-19 at 7 20 14 PM" src="https://github.com/user-attachments/assets/94ede572-c61e-4ccc-8b69-4799d751a7cd">

Go to the materials folder in Assets. Click the plus sign on the upper left corner of the project window. Click on the Material option. This will automatically add a sphere called new material in the folder, rename to “Water.” Select the material to open its properties. Change Opaque to transparent, Alpha to Multiply and change the base map color to blue. 

<img width="300" alt="Screenshot 2024-09-20 at 7 35 21 PM" src="https://github.com/user-attachments/assets/0e0c4a96-f7bd-466b-90f0-b6930bdd6a82">

<img width="500" alt="Screenshot 2024-09-20 at 7 36 03 PM" src="https://github.com/user-attachments/assets/41ad1bdb-6ce6-4f63-8776-4e421f0def32">

Drag the material from the window onto the cube. This will make it a transparent blue.

<img width="600" alt="Screenshot 2024-09-19 at 7 24 59 PM" src="https://github.com/user-attachments/assets/c6ebeeda-eed7-4096-b36b-4d584dbc02fb">

Scale the cube to cover the area of the empty trench. Lower the cube into the ground using the move tool.

<img width="600" alt="Screenshot 2024-09-19 at 7 27 38 PM" src="https://github.com/user-attachments/assets/5c7bca99-0031-4019-8380-7eb895c36a13">

# Placing assets - Trees

Now we are going to use our 2022 PBR XfrogPlants Sampler package that contains the nature assets we want to include. Once we've downloaded this asset from the Unity Asset Store. You can open it in unity through Window > Package manager > Package: My Assets > Import. It should then appear within the Asset folder in the Project tab.

In the Prefab folder we can access the assets. Place a small tree when you do this a tree silhouette will appear.

<img width="600" alt="Screenshot 2024-09-20 at 8 12 52 PM" src="https://github.com/user-attachments/assets/85a4f7dc-5e0d-44cd-9417-fad9d42a6330">


Go into the textures folder of this package and place drag the preffered textured for the leaves and the the bark. 

<img width="600" alt="Screenshot 2024-09-20 at 8 13 28 PM" src="https://github.com/user-attachments/assets/234369c1-2641-476e-b0e7-2f7de3fcc4b5">


In the end it should look like this.

<img width="600" alt="Screenshot 2024-09-20 at 8 13 23 PM" src="https://github.com/user-attachments/assets/80e8d7dd-5d93-47ef-83bb-07e945c97318">

In the LOD Group change the visibility percentagess accordingly to make sure the tree is visible from a distance. 

<img width="300" alt="Screenshot 2024-09-20 at 8 14 54 PM" src="https://github.com/user-attachments/assets/276aeec6-d7bc-46de-af6a-850684807e9f">


Do this for every tree asset you want to include. Once you have an adjusted prefab of every variation you want to include, duplicate these and place them around the terrain.

<img width="600" alt="Screenshot 2024-09-20 at 8 19 57 PM" src="https://github.com/user-attachments/assets/d444842f-d838-444b-b403-26738e4316d5">

# Placing Assets - People

Next, we are going to use the City People Lite asset that contains various human models. These models will simulate tourists visiting the temple.
After having the asset installed and imported to the project, within the assets folder, you will find the prefabs, models, and animations. In our case, we went with the animations to place around the terrain, as this provided more natural and dynamic poses, rather than the default T-pose of the models/prefabs.

<img width="200" alt="Screenshot 2024-09-20 202753" src="https://github.com/user-attachments/assets/dd03e29a-ef92-41d6-a00e-a51e5f3cbec5">

_Note:_ Due to using the animations, when placing the models, the textures do not appear and it is instead defaulted to white. So, we chose to improvise and decided on applying another solid material color instead. We specifically chose a tan colored material that existed from the nature asset, but an alternative could be to create a new material and manually change the color as it was previously described when creating the temple. This change in color allowed for some of the clothing details from the model to show.

After placing the model from “Animations” within the scene, click on the model and head to the “Inspector” tab. Then, where it says “Model”, click on “Select”.

<img width="300" alt="Screenshot 2024-09-20 182917" src="https://github.com/user-attachments/assets/e4ae544c-f618-4c3b-b713-0d30068d9e37">

Afterwards, make sure you are on the “Materials” tab.

<img width="300" alt="Screenshot 2024-09-20 182947" src="https://github.com/user-attachments/assets/2fbd86d9-ccc3-4013-abe6-6d683ff8f045">

Where it says “peopleColors” below the “Remapped Materials” section, click on the circle/dot on the side and apply the material you wish to use. Finally, click “apply”.

<img width="300" alt="Screenshot 2024-09-20 184412" src="https://github.com/user-attachments/assets/9c23e0fd-060c-4903-8941-e0413df05a4d">

Be sure to do these steps for every different model you decide to place around. The following image shows the default version on the left and the one with the material added to the right:

<img width="600" alt="Screenshot 2024-09-20 184759" src="https://github.com/user-attachments/assets/3884d1ab-cd37-4579-b5e7-1b32a83cc08b">

# Placing Assets – Dogs

For our last details, let’s add some stray and/or domesticated dogs belonging to some of the people.
After having the 3D Stylized Animated Dogs Kit installed and imported, you can proceed to go directly to the models or prefab folder and pick the dog breeds you want to place around the scene. In this case, the default poses were not an issue.

<img width="600" alt="Screenshot 2024-09-20 181338" src="https://github.com/user-attachments/assets/df9b0db3-7dba-4e20-9619-5f3a65655e9c">

Example from our scene:

<img width="600" alt="Screenshot 2024-09-20 210930" src="https://github.com/user-attachments/assets/acd68b8a-b102-4c1c-8775-00e54aacb221">

# Result

Here is our final look at our scene!

Front:

<img width="600" alt="Screenshot 2024-09-20 202107" src="https://github.com/user-attachments/assets/eaf79256-5433-4efb-a998-f65e65bc3df1">

Top:

<img width="600" alt="Screenshot 2024-09-20 202330" src="https://github.com/user-attachments/assets/1672a7da-00d5-46a0-a86a-e2a6050b3aee">

Back:

<img width="600" alt="Screenshot 2024-09-20 202232" src="https://github.com/user-attachments/assets/ea26e95f-67ae-428d-936b-0342e59434a7">

