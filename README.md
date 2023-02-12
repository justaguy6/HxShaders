#  hxShaders

how to apply it to your Friday Night Funkin Mod with shaders 

1. Install the haxelib
```
haxelib git HxShaders https://github.com/JonnycatMeow/HxShaders.git
```
2. Paste this in your project.xml 
```
<haxelib name="HxShaders"/>  
``` 
3. Remove the code that says  import flixel.system.FlxAssets.FlxShader; and replace it with 
```
import FlxShader;
``` 
4. OPTIONAL IF YOU WANT OPENGL FRAMEWORK AND METAL FRAMWORK 
``` 
<!--Dependency's for opengl--> 
<dependency name="Metal.framework" if="mac||iphoneos"/> 
<dependency name="OpenGL.framework" if="mac" />    
<dependency name="OpenGLES.framework" if="iphoneos" /> 
```

# Credits
- [YoshiCrafter29](https://github.com/YoshiCrafter29) -  For making the FlxShader.
- [Jobf](https://github.com/jobf) -  For making the FlxShadertoy.
- [MasterEric](https://github.com/MasterEric) -  For making the FlxRuntimeShader.

# How to tell which version of opengl is supported? 

install glview on mac app store to see if the version is compatibile
