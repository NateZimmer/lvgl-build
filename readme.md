
A basic LVGL build

[![Windows Build](https://github.com/NateZimmer/lvgl-build/actions/workflows/ci_win.yml/badge.svg)](https://github.com/NateZimmer/lvgl-build/actions/workflows/ci_win.yml)

# build setup 

```
cmake -B out
cmake --build out
```

### LVGL Docs 

Docs: https://docs.lvgl.io/9.3/details/integration/building/cmake.html#integrating-lvgl-cmake

### repo setup 

```
git submodule add git@github.com:lvgl/lvgl.git lvgl
cd lvgl
git checkout v9.3.0
```