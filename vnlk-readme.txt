Place the folder "forYourCustomSceneryFolder" somewhere, rename it as you wish (such as to "VNLK") and add the path-to-it in "Additional scenery folders".

Open the folder "forYour-fgdata-folder".

Copy the folder "aluk" into /data/Textures/

(for linux): /fgdata/Textures/

Copy the folder "lum" into /data/Materials/

Add this line in the section <!-- Asia --> inside "/data/Materials/regions/materials.xml":

<region include="Materials/lum/lukla.xml"/>

Set "Regional Textures" in View >Rendering Options