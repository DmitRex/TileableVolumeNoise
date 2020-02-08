Original program, but with Source Engine vtex.exe support.
Program outputs each frame of 3D noise as separate file now, instead of atlas.
Each file has correct postfix (_zXXX.tga) where XXX is frame number, so vtex.exe can eat them easily.
Also, program outputs txt script with correct compile settings for vtex.

Tileable Volume Noise
---------------------

Collection of functions that can be used to generate tileable volume/3d noise. An example of volume noise functions that can be specifically used for clouds is also presented.

![TileableVolumeNoise_Example](https://github.com/sebh/TileableVolumeNoise/raw/master/Examples/noiseErosionPacked.jpg)

This code is part of the "Physically Based Sky, Atmosphere and Cloud Rendering in Frostbite" presentation from [SIGGRAPH 2016 Course: Physically Based Shading in Theory and Practice](http://blog.selfshadow.com/publications/s2016-shading-course/).

Done in collaboration with [weirdfoo](https://twitter.com/weirdfo).

This library uses
 - [GLM](http://glm.g-truc.net)
 - [LibTarga](http://research.cs.wisc.edu/graphics/Gallery/LibTarga/)
