# GlibcBuilder

[![Build Status](https://travis-ci.org/staticfloat/GlibcBuilder.svg?branch=master)](https://travis-ci.org/staticfloat/GlibcBuilder)

This repository builds binary artifacts for the MbedTLS project. Binary artifacts are automatically uploaded to
[this repository's GitHub releases page](https://github.com/staticfloat/GlibcBuilder/releases) whenever a tag is created
on this repository.

This repository was created using [BinaryBuilder.jl](https://github.com/JuliaPackaging/BinaryBuilder.jl)

Because we tend to use different versions of `glibc` on different architectures, this repository has multiple releases spread out across multiple branches.  We recommend using the oldest version possible for the architecture you are interested in.
