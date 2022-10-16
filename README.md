# 🎮 Plasma Engine
A Friday Night Funkin' engine designed to be lightweight and easy to mod. Use `.hx` files to make modcharts, stages, characters, states, and more!

#### psst hey vizz here if you want debug builds so you can see all your hscript errors here they are!

### WINDOWS : https://drive.google.com/file/d/10mho5g__RmmdnCnU6JnTcA6jPDAXL95e/view?usp=sharing

### MAC: compiler errors

### LINUX: more errors :skull:




# 🖥️ Building the game
- Step 1. [Install git-scm](https://git-scm.com/downloads) if you don't have it already.
- Step 2. [Install Haxe](https://haxe.org/download/)
- Step 3. [Install HaxeFlixel](https://haxeflixel.com/documentation/install-haxeflixel/)
- Step 4. Run these commands to install required libraries:
```
haxelib git flixel https://github.com/YoshiCrafter29/flixel
haxelib git hxCodec https://github.com/swordcube/hxCodec-testing
haxelib git hscript-improved https://github.com/YoshiCrafter29/hscript-improved
haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc
haxelib git openfl https://github.com/openfl/openfl
```
- Step 5. If you run on Windows, install [Visual Studio Community 2019](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=community&rel=16&utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=download+from+relnotes&utm_content=vs2019ga+button) using these specific components in `Individual Components` instead of selecting the normal options:
```
* MSVC v142 - VS 2019 C++ x64/x86 build tools
* Windows SDK (10.0.17763.0)
```
- Step 6. Run `lime test <windows/linux/mac>`, choosing your OS. (Ex. `lime test windows`)
