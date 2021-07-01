# CMake

**CMake** is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice. The suite of CMake tools were created by Kitware in response to the need for a powerful, cross-platform build environment for open-source projects such as ITK and VTK.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/build
$ dnf install -y cmake
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y cmake
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/cmake).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/cmake) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
