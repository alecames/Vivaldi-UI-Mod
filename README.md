# Minimal Vivaldi UI Mod

Just a quick CSS skin for the [Vivaldi](https://vivaldi.com) browser made for personal use. Pretty barebones, just made it for fun.

## How to install

- Download or clone this repo
- Go to `vivaldi://experiments/` and toggle `Allow CSS modifications`
- Go to `vivaldi://settings/appearance/` and under `Custom UI Modifications` select the downloaded [mod](/mod) folder
- Restart Vivaldi

## How to make your own

- Make a folder somewhere on your system and create a `mod.css` file
- Go to `vivaldi://inspect/#apps`
- Find `chrome-extension://.../browser.html` and hit `Inspect`
- In the DevTools window that opens, go to `Sources > Filesystem` and add the folder with your `.css` file to the filesystem, hit `Allow` on the confirmation dialog

Now changes in the `mod.css` file will be updated on the Vivaldi UI as long as the DevTools window is open

## Screenshot
![image](https://user-images.githubusercontent.com/18179415/222575725-f2dbd1b5-0e2b-4e43-9796-a3801b7c6ab6.png)
