# What's new? October 2023
* Build Clang-17.x
* Stop Build Clang-16.x
* Cleanup repository. Delete All Clang-16.x release, Except Clang-16.0.6

# How to use?
* Example using the latest clang
```
wget "$(curl -s https://raw.githubusercontent.com/XSans0/WeebX-Clang/main/main/link.txt)" -O "weebx-clang.tar.gz"
mkdir clang && tar -xf weebx-clang -C clang && rm -rf weebx-clang.tar.gz
```

# Another WeebX Clang repository
* [Weebx-Clang-14](https://gitlab.com/XSans0/weebx-clang.git)
* [WeebX-Clang-15](https://gitlab.com/XSans0/weebx-clang-15.git)
* [WeebX-Clang-15-gr](https://gitlab.com/XSans0/weebx-clang/-/tree/release/15-gr) | This build with old good revision
* Build with Full LTO & PGO
* Build only when we have a strong server