# macOS Custom Icon Collection

This is my collection for custom folder/drive icons I use on macOS. They use the design language of 10.13 High Sierra.

## Building

Make sure you have Imagemagick installed (required for converting the PSD source files to PNGs).  
Note: The buildscript will not work on any platform except Darwin because of the required utility `iconutil`.

1. Open a terminal
2. Run the build script:  
    ```shell
    $ ./buildall
    ```
3. The resulting icns files will be inside of the `dist/` folder

## Project structure / Adding a new icon

1. Navigate to `src/`
2. Create a new folder. The name of this folder will be used for the final icns file  
    *Example:* If you name your folder `MyIcon`, the resulting icns file will be `MyIcon.icns`.
3. Add PSD files for the following sizes (named `<SIZE>.psd`)
    - 16x16 px as `16.psd`
    - 32x32 px as `32.psd`
    - 64x64 px as `64.psd`
    - 128x128 px as `128.psd`
    - 256x256 px as `256.psd`
    - 512x512 px as `512.psd`
    - 1024x1024 px as `1024.psd`
