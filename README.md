# Introduction
DSLR Power Camera is a configuration setting for LMC 8.4 Release 18. based on Selebgram 16 by Impostor Gelap.

# Features
- Delicious and Nice Color Grading on Blue, Green and Red.
- Color Grading on Human or Portraits are natural.
- You can capture photos in **HD**, **FHD**, and **QHD** resolution powered by a RAW capabilities.
- Perfect for Social Media to post such as **Instagram**.
- Back, Front, Tele and Wide Camera IDs are used. `0,1,2,3`
- Very nice portrait blur powered by Google Camera!

# How HD, FHD, and QHD options work?
We have to emulate this on my Samsung Phone and show you the demo on the image:

![Slide 16_9 - 1](https://github.com/user-attachments/assets/3ed88ea8-b9cf-41ca-a045-8d2663e0d25a)
This image shows the detiled information about the `Resolution`, `Megapixel`, `Raw Size`, and `Possible Image File Size`

## Take Note!
> - Some devices will have a different megapixel based on the manufacturers.
> - **Upscale/Downscale** feature will only work on Devices with **Level 3** Haredware Support Level. **Full** Hardware support level does not work.

# Notices and Importances
> [!important]
> If your device supports 60 FPS video, you must enable this feature flags in LMC 8.4 Developer Settings.
> 
> `camcorder.1080p60_thr`
> `camcorder.4k60fps`
> `camera.60fps`
> `fps.video_setting_writeable`
> 
> If your device supports 4K, you must enable this feature flags in LMC 8.4 Developer Settings.
> 
> `camera.use_video_resolution_option`
> 
> _leave disabled if your specific device does not support some features due to hardware limitations._

> [!note]
> Why Power Camera? It will unlock all of it's limit to the unlimited feature!

> [!tip]
> - HD, FHD, and QHD options uses **Upscale/Downscale** feature in **LMC 8.4 **. HD Upscale value is 1x, FHD Upscale Value is 2x, and QHD upscale value is 3x. so, you will have a idea on how these things work.
> - Color Grading will not work on the video, only on the photo. But Leica Vignette effect will work.
> - You don't need expensive DSLR camera If you want to capture very high quality.
> - Do not use this as the document capture, only Portraits, Nature, Scenes, Events, and some sort of Photography. (unless you have to capture the screen that contains correction kit).
> - Night Sight shots are very excellent on this config.

> [!warning]
> - HDR++ feature will only work on Devices with **Level 3** Haredware Support Level. **Full** Hardware support level does not work.
> - Night Sight feature will only work on Devices with **Level 3** Haredware Support Level. **Full** Hardware support level does not work.
> - Adjustments while photo processing might be worst on some devices than the best image results on the **Sample Shot** section.
> - Selfie capturing in 5MP camera on some midrange devices can have Common Polka Dot Issues while processing the photo on color grading.<br>If possible, Go to `LMC Settings > Processing functions > Upscale/Downscale > Front Camera` and set the value for around `x2.0`, `x2.5` or even `x3.0`. set the value to `x1.0` if there is no issue with the selfie on flagship or high-end devices.

> [!caution]
> - Do **NOT** adjust ISO value to the low values, Night Sight capturing might not be adjusting the exposure to the lighten properly.
> - Do **NOT** turn on **Upscale/Downscale**, and **Patcher** features. This is used to color grade and to adjust the quality of the photo.
> - Do **NOT** move some settings that you don't know. Only LMC users and devs can do this.
