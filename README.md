## PBRScenes

Physically Based Rendering Scenes

This repository combines scenes from multiple sources primaly for the project [PBRVulkan](https://github.com/Zielon/PBRVulkan).

All materials are based on [Disney](https://media.disneyanimation.com/uploads/production/publication_asset/48/asset/s2012_pbs_disney_brdf_notes_v3.pdf) BRDF. The scene description is based on [Tinsel](https://github.com/mmacklin/tinsel) project.


Example of scene description
```
material red
{
	color 0.63 0.065 0.05
}

mesh
{
	file cornell_box/cbox_redwall.obj
	material red
	position .5536 .2744 .2796
	scale 0.01 0.01 0.01
}
```

The orignal source can be find [here](https://drive.google.com/file/d/1UFMMoVb5uB7WIvCeHOfQ2dCQSxNMXluB/view) in [GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) project.

### Disney

[0] [Disney BSDF](https://blog.selfshadow.com/publications/s2015-shading-course/burley/s2015_pbs_disney_bsdf_notes.pdf) \
[1] [Disney in Arnold](http://shihchinw.github.io/2015/07/implementing-disney-principled-brdf-in-arnold.html) \
[2] [Disney Tinsel](https://github.com/mmacklin/tinsel/blob/master/src/disney.h) \
[3] [SIGGRAPH Course](https://blog.selfshadow.com/publications/s2012-shading-course/#course_content) \
[4] [Disney Report](http://simon-kallweit.me/rendercompo2015/report/)

### Sources

[5] [Tinsel](https://github.com/mmacklin/tinsel) \
[6] [GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) \
[7] [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
