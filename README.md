# aarch64-toolchains
A set of the toolchains built for aarch64-unknown-linux-gnu host machines.
All of the toolchains were built with the [`crosstool-ng`](https://github.com/crosstool-ng/crosstool-ng).

## Host platform
These toolchains were built for the AArch64 GNU/Linux hosts.
For building these toolchains, I used my own Raspberry Pi 4 SBC.

## Target platforms:
- `x86_64` (64-bit) GNU/Linux distributions,
- `x86_64` (64-bit) Windows operating systems (MinGW Toolchain),
- `i686` (32-bit) Windows operating systems (MinGW Toolchain).

## Updating:
These toolchains may not be updated in the future, so be aware they might be obsolete. Currently I don't use any automated build system to frequently update these.

## Issues:
Please **do not** create issues about:
* toolchain rebuild/update requests,
* new toolchains for the other targets,
* asking for the advice how to use the toolchains (the toolchains are for people who knows how to use them 😉️),
* the issues building the software with the toolchains (they might be just too old to be used).

The accepted topics examples for the issues are:
* legal concerns,
* documentation update requests.

If you're looking for a place for talk about the toolchain usage, issues with the current toolchain versions (that won't be fixed by me), other sources for toolchain builds etc, jump to the GitHub *discussions* tab that is available on my repository.

## Licensing:
Each set of the binaries/libraries might be licensed under their own agreements. See the `usr/share/licenses` inside the toolchain root folders for their licenses.

I **do not own** any of these files – I've just built them and generated with the `crosstool-ng` script. If you want to reshare these files somewhere, make sure you're resharing them with their licenses and you don't break any of the conditions on which the software can be reshared. I would also appreciate to get an attribution, but I don't force anyone to do that once resharing it.
