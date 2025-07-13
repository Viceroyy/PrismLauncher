The only difference in this port from upstream is the use of CMake over Meson. We need this in order to build universal/"fat" dylibs for macOS with `{CMAKE,VCPKG}_OSX_ARCHITECTURES`

It should really be removed one day -@getchoo
