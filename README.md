# `Lukla_mods_FG`
 Modification files for FlightGear Lukla Airport

See [this thread](https://forum.flightgear.org/viewtopic.php?f=5&t=38532&p=379109#p379103)

## BETA testing version

You should only use these files if you are confident that you know what you are doing with FlightGear scenery.  They are still being used for development. 

### Background

The idea is to produce a better version of the Himalayan "Tenzing–Hillary Airport" at Lukla, ICAO: VNLK ([Wikipedia entry](https://en.wikipedia.org/wiki/Tenzing–Hillary_Airport)). This repository brings together the GNU-GPL contributions from the FlightGear Forum. If you want to comment on or contribute to this project please do so at the [forum thread](https://forum.flightgear.org/viewtopic.php?f=5&t=38532&p=379109#p379103).

### Installation instructions:

Place the folder "forYourCustomSceneryFolder" somewhere, rename it as you wish (such as to "VNLK") and add the path-to-it in "Additional scenery folders".

Open the folder "forYour-fgdata-folder".

Copy the folder "aluk" into /data/Textures/

(for linux):  /fgdata/Textures/  

Copy the folder "lum" into /data/Materials/

Add this line in the section `<!-- Asia -->` inside 
"/data/Materials/regions/materials.xml":

`<region include="Materials/lum/lukla.xml"/>`

Set "Regional Textures" in View >Rendering Options





