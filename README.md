Image_Warp_URP
-------------------------------------

[Asset Store Link](http://u3d.as/2M83)  

© 2020 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)

## Table of Contents

<!--TOC-->
* [Image_Warp_URP](#image_warp_urp)
	* [Table of Contents](#table-of-contents)
	* [Contact](#contact)
	* [Terms of Use](#terms-of-use)
	* [Description Features](#description-features)
	* [Shaders](#shaders)
		* [WarpImage.shadergraph](#warpimage.shadergraph)
		* [others](#others)
	* [Scripts](#scripts)
		* [demo.cs](#demo.cs)
		* [CanvasSwitcher.cs](#canvasswitcher.cs)
		* [followCursor.cs](#followcursor.cs)
		* [imageWarp.cs](#imagewarp.cs)
	* [Videos](#videos)
	* [FAQs](#faqs)
		* [part of my image is cut off.](#part-of-my-image-is-cut-off.)

<!--TOC-->

## Contact

Questions, suggestions, help needed?  
[Github Profile](https://github.com/jgarza9788)

## Terms of Use

Required:
please follow [Unity's EULA](https://unity3d.com/legal/as_terms) 

Suggestion/Optional:
please put my name in the credits, or in the special thanks section. :)  


## Description Features

Easily customize the animation's

* speed
* radius
* wavesize (thickness)
* amplitude (distortion amount)
* color

## Shaders

### WarpImage.shadergraph
MainTex:  
this is the image from the image component in the gameobject.  

Anim:  
Is basically warping strength. however i think this is mostly doing to be used to warp the image.

Texture2D:  
this texture is being used as a map that dictates how much warp will happen at each point of the image.  

Center:  
this is used to shift the center of the warping  

### others
there are other shaders in **Asset/Image_Warp_URP/Shaders/old/** folder, however these are betas and previous attempts.  


## Scripts

### demo.cs
this is used to change the materials, and basically make the demo work.

### CanvasSwitcher.cs
used to turn Canvases on the off.

### followCursor.cs
used to make a UI object follow a cursor.

### imageWarp.cs
this could be used along side the followCursor.cs in order to warp the image based on it's movement.  


## Videos

[Demo1](https://www.youtube.com/watch?v=mFXpAGFWsSM)
[Demo2](https://www.youtube.com/watch?v=m6aK2kRxC3g)


## FAQs

### part of my image is cut off.
for the best use you'll want to have a good amount of transparent/alpha space around the edges.




