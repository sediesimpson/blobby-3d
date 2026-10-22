# blobby, but in 3d 👻

a little translucent, jelly-like ghost who peeks in from the edge of the screen,
waddles to the middle, hops, twirls & then waltzes away

this is the 3D version of [blobby](https://github.com/sediesimpson/blobby)

**[watch blobby](https://sediesimpson.github.io/blobby-3d/)**

![blobby in 3D](blobby-3d.png)

## how it's made

- **three.js** for the 3D scene, camera, lights and rendering
- **a sculpted sphere** for blobby's body
- **a jelly wobble** that reshapes his body every frame, with his top trailing behind as he moves
- **a timeline written in JavaScript** with easing, like CSS keyframes rebuilt by hand
- **squash and stretch, anticipation & follow-through**, three classic animation principles

## the show

1. **peek**: leans in from the left edge, with a curious head tilt
2. **waddle**: a walk to centre stage
3. **hop, hop, twirl**: two big bouncy hops & a full 3D spin
4. **waltz**: glides off to the right in 3/4 time, turning as he goes

if your computer is set to reduce motion, Blobby skips the show and stands calmly in the middle instead.

## run it yourself

```
git clone https://github.com/sediesimpson/blobby-3d.git
cd blobby-3d
python3 -m http.server
```

then open http://localhost:8000 in your browser
