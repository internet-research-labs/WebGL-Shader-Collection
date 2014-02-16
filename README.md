# WebGL-Shader-Collection

A framework-independent collection of WebGL shaders using a standard design
pattern. In particular, the shaders will share variable names - uniform,
attribute, and varying - across one another.

## Manifest

A list of shaders, and a map of which shaders can be *directly* plugged into
one-another, without worrying about inconsistencies across uniform and varying
variables. Note that all vertex shaders have the extension `.vert` and all
fragment (pixel) shaders have the extension `.frag`.

* **Pass Through**: Simple pass-through shader with no setup
  * `pass-through/pass.vert`
  * `pass-through/pass.frag`
* **Phong**: Basic phong shader
  * `phong/phong.vert`
  * `phong/phong.frag`

## Install

There are no install directions. Copy-and-paste, take the whole file, whatever.

## UNLICENSE

This is unlicensed obviously. Steal it. Ruin it. Do whatever.

We really don't care.
