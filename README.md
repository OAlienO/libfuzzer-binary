# libfuzzer-binary

using libfuzzer to fuzz binary without source code

## dependency

[radare2](https://github.com/radare/radare2)

```
git clone https://github.com/radare/radare2.git
cd radare2
sys/install.sh
```

[radare2-r2pipe - c](https://github.com/radare/radare2-r2pipe/tree/master/c)

```
sudo apt-get install pkg-config
git clone https://github.com/radare/radare2-r2pipe.git
cd radare2-r2pipe/c
make
```

[cJSON](https://github.com/DaveGamble/cJSON)

we use cJSON as submodule

[ninja](https://github.com/ninja-build/ninja/wiki/Pre-built-Ninja-packages)

```
sudo apt-get install ninja-build
```

## clone this repo

```
git clone --recurse-submodules https://github.com/OAlienO/libfuzzer-binary.git
```

## build

```
ninja
```
