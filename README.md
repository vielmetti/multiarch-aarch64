# This repository is frozen

It's not being actively updated, and it's not clear that it's
the best idea. So I'm freezing this repository so that it's
very clear that if you decide to care about it you should fork it
and continue on your own.

## multiarch-aarch64
Manifests for Docker multiarch images that include unofficial aarch64 builds

The grand vision is of a world where all of the official Docker
images run on all of the architectures that Docker runs on. In
the interim the simpler request is for some images to run on
multiple architectures, even if that means stitching together
a multiarch manifest from two or more separate distributions.

This repository is an effort to make plain the process of
creating multiarch images, using the code from 
https://github.com/estesp/manifest-tool as its starting
point.

Each of the `manifest/*.yml` files can be run as follows:

```
manifest-tool push from-spec manifest/multiarch-package-version.yml
```
