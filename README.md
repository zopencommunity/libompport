[![Automatic version updates](https://github.com/zopencommunity/libompport/actions/workflows/bump.yml/badge.svg)](https://github.com/ZOSOpenTools/libompport/actions/workflows/bump.yml)

# libomp

LLVM's OpenMP runtime library

### Status (z/OS)

`libomp` builds on z/OS, but is <span style="color:red"><strong>not usable</strong></span>.

- Any program compiled with `-fopenmp` aborts at runtime (stack overflow).
- The runtime does not function at all at this stage.

OpenMP support on z/OS is currently <span style="color:red"><strong>non-functional</strong></span>.

# Installation and Usage

Use the zopen package manager ([QuickStart Guide](https://zopen.community/#/Guides/QuickStart)) to install:
```bash
zopen install libomp
```

# Building from Source

1. Clone the repository:
```bash
git clone https://github.com/zopencommunity/libompport.git
cd libompport
```
2. Build using zopen:
```bash
zopen build -vv
```

See the [zopen porting guide](https://zopen.community/#/Guides/Porting) for more details.

# Documentation


# Troubleshooting

# Contributing
Contributions are welcome! Please follow the [zopen contribution guidelines](https://github.com/zopencommunity/meta/blob/main/CONTRIBUTING.md).
