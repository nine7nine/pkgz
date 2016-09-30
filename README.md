# CloudCompare - Archlinux package

http://www.cloudcompare.org/

https://github.com/cloudcompare/trunk

I'm still tinkering with my pkgbuild and new to Cloudcompare, but there is no proper Archlinux package. So...
Just to keep on top of things, I will upload it on github to work on. 

There are two main folders/source packages;

* cloudcompare-git: archlinux source package for use with GCC

* cloudcompare_ICC-git: Archlinux source package for use with Intel C/C++ Compiler suite

There are currently a few plugins disabled, mostly plugins that require special and/or proprietary SDKs. Aside from that, I have lit up most of the plugins, with only a couple to still get sorted out, building and working. I've enabled openmp support, ffmpeg support and will likely enable BLAS support too, at some point.

I'm still working on getting qGMMREG plugin working, but have run into a few kinks to iron out.
