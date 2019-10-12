# blender-Donut

A blender tutorial walk through creation of a donut...

I tried to pimp the scene with some creations of my own, leveraging things I've learned so far...

`Donut.blend`
`DonutTexture.png`
`MugTexture.png`

* Plate (with rogue sprinkles on it...)
* Official mug (with it's own texture painting...) of my company...
* Camera View animation...

## Preview (WIP)

![alt text](Samples/donut-wip-8.png "Latest WIP Preview...")

## Rendered Sample Animation (Camera move)

![Click here for file link and choose display raw there...](Samples/AnimationSample.mp4 "Rendered animation sample...")

## How to convert rendered animation images to a movie

* Render the animation to ./RenderResult/0001.png ...etc...
* Go there...
* Use ffmpeg to convert the PNGs to mp4

Example:

`ffmpeg -r 24 -i %04d.png -vcodec libx264 -crf 25  -pix_fmt yuv420p RenderResult.mp4`

## Based on

### YouTube Tutorial

* https://www.youtube.com/playlist?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U


