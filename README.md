# 4480x1080 Wallpapers

This repository is dedicated to storing desktop wallpapers in the **4480x1080** format. This uncommon format results from combining two monitors with resolutions **1920x1080** and **2560x1080**, placed side by side.

## Cropping Script (`splitwallpaper`)

Some desktop environments do not allow using a single continuous image as wallpaper for both monitors. This is my case, which is why I use the included bash script `splitwallpaper` to split a 4480x1080 image into two files:

- One **1920x1080** for the left screen.
- One **2560x1080** for the right screen.

Feel free to modify the script as needed to suit your own setup.

### Script usage

```bash
./script/splitwallpaper <path_to_image>
```

This will generate two files in the same directory as the original image, ready to be used as independent wallpapers for each monitor.
