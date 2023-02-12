# What's new? february 2023
* Upstream build script
* Enable openmp
* Binutils optimizations
* github release: Don't create a new tag every release
* github release: Overwrite existing release

# How to use?
* Example using the latest clang
```
wget "$(curl -s https://raw.githubusercontent.com/XSans0/WeebX-Clang/main/main/link.txt) -O "weebx-clang.tar.gz"
mkdir clang && tar -xf weebx-clang -C clang && rm -rf weebx-clang.tar.gz
```

# Another WeebX Clang repository
* [Weebx-Clang-14](https://gitlab.com/XSans0/weebx-clang.git)
* [WeebX-Clang-15](https://gitlab.com/XSans0/weebx-clang-15.git)
* [WeebX-Clang-15-gr](https://gitlab.com/XSans0/weebx-clang.git) | This build with old good revision
* Build with Full LTO & PGO
* Build only when we have a strong server