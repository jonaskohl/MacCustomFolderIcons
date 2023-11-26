# macOS Custom Folder Icons

## Adding a new icon

1. Navigate to src/
2. Create a new folder. The name of this folder will be used for the final icns file
3. Add PSD files for the following sizes (named `<SIZE>.psd`)
    - 16x16 px as `16.psd`
    - 32x32 px as `32.psd`
    - 64x64 px as `64.psd`
    - 128x128 px as `128.psd`
    - 256x256 px as `256.psd`
    - 512x512 px as `512.psd`
    - 1024x1024 px as `1024.psd`
4. Open a terminal inside of the root folder of this repo
5. Run the following command:  
    ```shell
    $ ./buildall
    ```
The resulting icns file will be inside of the dist/ folder
