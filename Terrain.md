
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

<img width="800" alt="Screenshot 2024-09-19 at 7 24 59 PM" src="https://github.com/user-attachments/assets/c6ebeeda-eed7-4096-b36b-4d584dbc02fb">

Scale the cube to cover the area of the empty trench. Lower the cube into the ground using the move tool.

<img width="600" alt="Screenshot 2024-09-19 at 7 27 38 PM" src="https://github.com/user-attachments/assets/5c7bca99-0031-4019-8380-7eb895c36a13">

# Placing assets - Trees

Now we are going to use our 2022 PBR XfrogPlants Sampler package that contains the nature assets we want to include.








