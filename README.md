# Crossover-appimage

Based on these appimages:
- https://github.com/mmtrt/WINE_AppImage
- https://github.com/niess/python-appimage

## How to run:
chmod +x crossover.appimage
./crossover.appimage
or
chmod +x crossover.appimage
./crossover.appimage --appimage-extract
cd squashfs-root
./AppRun

## Possible bugs:
- Printing and scanning of documents may not work
- 3d acceleration may not work in 32-bit programs. 32-bit OpenGL/Vulkan libraries are included, but some distributions may not detect them
- Updating bindings does not work. Because of this, program shortcuts may disappear. To avoid this, install programs through the internal wine explorer.

## About crossover 
No modifications have been made to the Crossver. Source file: https://media.codeweavers.com/pub/crossover/cxlinux/demo/crossover_20.0.4-1.deb.
To use the program, you will need a license: https://www.codeweavers.com/crossover. For testing, you can use a free trial period of 14 days
This appimage has nothing to do with CodeWeavers. Send all error reports to the Issues section.
