# tutorial to force Vibrant Visuals on unsupported device (for Android and Windows)
## ⚠️ Disclaimer

This project is provided **for educational and personal use only**.  
It is **not affiliated with, endorsed, or supported by Mojang, Microsoft, or any related entity**.  

By using any information, instructions, or tools from this repository, you acknowledge that:

- You may be violating the **Minecraft End User License Agreement ([EULA](https://www.minecraft.net/en-us/eula))** or other applicable terms of service.  
- The authors and contributors of this repository **take no responsibility** for any damage, account bans, data loss, or legal issues that may arise.  
- **No modified game files, cracked versions, or copyrighted assets** from Minecraft are distributed here.  
- You use the information **at your own risk**.  

If you want to enjoy Minecraft with all features officially, please purchase and play the game on supported devices.  

## Tutorial for:
- **[Android](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/tree/main?tab=readme-ov-file#android)**
- **[Windows](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/tree/main?tab=readme-ov-file#windows)**
- **[Download more shaders](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device?tab=readme-ov-file#download-more-shader)**
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
- Start by download the `MT manager.apk` from [uptodown](https://mt-manager.en.uptodown.com/android) or [mediafire](https://www.mediafire.com/file/2h6p0ep9hkaxxcs/mt-manager-2-19-0.apk/file), this application will help you edit the `tiers.bin` in the minecraft apk file.
> the **application** maybe blocked by the **Play protect**, you may have to turn it off to install the `.apk` file.
- Second, and get the current `minecraft.apk` file, you can get it from **ROOT** or any website *(btw, I will not take any responsibility if you download minecraft from an unreliable source.)*, use any file explorer to get the `tiers.bin` in `.../assets/assets/`.
- Now put them into a folder and open the *MT Manager* app.
![step1.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/1.jpg)
- On the right side, press on the `minecraft.apk` in click **view**.
![step2.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/2.jpg)
- Go to `.../assets/assets/`.
![step2.5.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/2.5.jpg)
- On left side, press on `tiers.bin` a choose "**Add ->**".
![step3.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/3.jpg)
- Choose like this and press **OK**.
![step4.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/4.jpg)
- If everything is done, install the `.apk` and enjoy (with 5fps ofc💔)
![step5.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/5.jpg)

 \
 *Well, because my phone is too weak to record a video so I will just leave some photo here:*\
  \
 ![pic1.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/Screenshot_2025-09-13-20-13-45-66_2cbc9fd271adfa2ebd7600c42501803f.jpg)
 ![pic2.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/Screenshot_2025-09-15-16-19-51-13_2cbc9fd271adfa2ebd7600c42501803f.jpg)
 ![pic3.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/Screenshot_2025-09-15-16-30-19-98_2cbc9fd271adfa2ebd7600c42501803f.jpg)

> about my phone: [Oppo A76](https://www.oppo.com/en/smartphones/series-a/a76/specs/)
---
## Windows
On window devices, it is much easier, no need to modify the application.\
 \
Simply download the **Better Render Dragon** from their [Githup](https://github.com/QYCottage/BetterRenderDragon).\
 \
Then unarchive and run the `mcbe_injector.exe`, it will automatically enable minecraft for windows if you have it installed.\
After the loading stage done, the game will appear with a small winhow like this:\
 \
![The ingame board.](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/brd.png)\
Now `force Enable Vibrant Visuals` and done, ur ready to experience vibrant visual with 10fps💔
> Note: Old Nvidia or AMD GPU may don't work, **Minecraft** still require some new modules to work
## Download more shader
### Prizma Visuals *(Al3xis5)*
![prizma](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/prizma.png)\
"Prizma goal is to provide detailed PBR textures, beautiful 3D bump effects, amazing sky and the best visual experience. Prizma take full advantage of the new Vibrant Visuals mode and heavily adjusts everything to give the best visuals".
- Curseforge: https://www.curseforge.com/minecraft-bedrock/texture-packs/prizma-pbr-deferred-pack
- mcpedl: https://mcpedl.com/prizma-pbr-deferred-pack/
### Revolution Vibrant Visual *(Aleeee)*
![revo](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/revo.png)\
"As the name suggests, this project aims to revolutionize Minecraft Bedrock's graphics by using the deferred lighting technique and making it as similar as possible to Minecraft Java. This is its second version, but I'll be evolving it little by little. Keep in mind that this is the first deferred project I've created, and I'm fairly new to this, so some of the deferred projects already available might be better than this one".
- Curseforge: https://www.curseforge.com/minecraft-bedrock/texture-packs/revolution-vibrant-visual
- mcpedl: https://mcpedl.com/revolution-vibrant-visual/
### Luminous Dreams *(xxpoggyislitxx)*
![lumi](https://github.com/Iz-HaruVN/force-Vibrant-Visuals-for-unsupported-device/blob/main/assets/lumi.png)\
"Luminous Dreams is being reborn with v1.0, embracing a unique style designed to make your world feel warm and welcoming. In the past, Luminous Dreams aimed for realism, but that approach never truly captured our vision—it just didn’t feel right in Minecraft. Now, we’ve reimagined nearly every aspect of the pack to give it its own distinct identity".
- Curseforge: https://www.curseforge.com/minecraft-bedrock/texture-packs/poggy-s-luminous-dreams-deferred-renderer-shader-pack-beta
- mcpedl: https://mcpedl.com/poggy-s-luminous-dreams-deferred-renderer-shader-pack-beta/
