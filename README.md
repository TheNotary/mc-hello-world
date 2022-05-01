# MC Hello World

This is my first Minecraft mod.  

## References

- MC Forge installer + MDK mod template: https://files.minecraftforge.net/net/minecraftforge/forge/index_1.16.5.html

## Setup Process:

i. Open IDEA, and import project.
ii. Select your build.gradle file and have it import.
iii. Run the following command: `gradlew genIntellijRuns` (`./gradlew genIntellijRuns` if you are on Mac/Linux).  I think it does the de-obfuscation stuff to make modding easy.  
iv. Refresh the Gradle Project in IDEA if required.

If at any point you are missing libraries in your IDE, or you've run into problems you can 
run `gradlew --refresh-dependencies` to refresh the local cache. `gradlew clean` to reset everything 
{this does not affect your code} and then start the process again.


Additional Resources: 
=========================
Community Documentation: http://mcforge.readthedocs.io/en/latest/gettingstarted/  
LexManos' Install Video: https://www.youtube.com/watch?v=8VEdtQLuLO0  
Forge Forum: https://forums.minecraftforge.net/  
Forge Discord: https://discord.gg/UvedJ9m  
