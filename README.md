# tutorial to force Vibrant Visuals on unsupported device (for Android and Windows)
## **What is Vibrant Visuals?**
Vibrant Visuals is a visual graphics upgrade that will transform the way players experience Minecraft. Initially releasing for Minecraft: **Bedrock Edition**, it is our developer’s vision for what Minecraft looks like with improved visual elements such as directional lighting, volumetric fog, and more. The result is dazzling – shadows move as the sun arcs across the sky, water reflects the landscape around it, and clouds appear infinite as they stretch far into the distance. 

Vibrant Visuals brings thousands of individually crafted elements while preserving what makes Minecraft unique. Chief Creative Officer Jens Bergensten describes it as “a new look that still stays true to our creative principles”, as biomes and builds come to life with the addition of a range of graphical enhancements. But what you will notice the most is the interplay of light and shadow. 

Improvements including volumetric lighting mean you’ll be able to watch the sun’s rays carve across the Overworld, and every block will cast its own shadow. Light will shine through your windows, and you’ll be able to see reflections in water and on the surface of metallic blocks, while subsurface scattering brings a gentle glow to leaves and grass. “Water is one of my favorite improvements,” said Game Art Director Jasper Boerstra. “It looks absolutely amazing.”.
> Read more: [here](https://www.minecraft.net/en-us/article/minecraft-vibrant-visuals)
## Android
**To force Vibrant Visuals on Android, you'll have to modify the `tiers.bin`.**
- **🔍 What is `tiers.bin`?**\
 \
`tiers.bin` is a configuration file used by **Minecraft Bedrock’s rendering engine**.  
It defines a mapping between **GPU models** and their assigned **render tier levels**.  

These tiers tell the game which graphical features a GPU is allowed to use, such as:
- Lighting quality  
- Transparency effects  
- **Vibrant Visuals** (high-end graphics mode)\
 \
By modifiding this file, **Minecraft** will think we're using a *high-end* device and letting us use *Vibrant Visual*.
---
**Tutorial**
- Start by download the `MT manager.apk` from [uptodown](https://mt-manager.en.uptodown.com/android) or [mediafire](https://www.mediafire.com/file/2h6p0ep9hkaxxcs/mt-manager-2-19-0.apk/file), this application will help you edit the `tiers.bin` in the minecraft apk file.\
> the **application** maybe blocked by the **Play protect**, you may have to turn it off to install the `.apk` file.
- Second, download the modified `tiers.bin` from my Githup ([here](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/android/force%20vibrant%20visual/tiers.bin)), and get the current `minecraft.apk` file, you can get it from **ROOT** or any website *(btw, I will not take any responsibility if you download minecraft from an unreliable source.)*
- Now put them into a folder and open the *MT Manager* app

---
## Windows
On window devices, it is much easier, no need to modify the application.\
 \
Simply download the **Better Render Dragon** from their [Githup](https://github.com/QYCottage/BetterRenderDragon).\
 \
Then unarchive and run the `mcbe_injector.exe`, it will automatically enable minecraft for windows if you have it installed.\
After the loading stage done, the game will appear with a small winhow like this:\
 \
![The in game board.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/brd.png)\
Now `force Enable Vibrant Visuals` and done, ur ready to experience vibrant visual with 10fps💔
> Note: Old Nvidia or AMD GPU may don't work, **Minecraft** still require some new modules to work
