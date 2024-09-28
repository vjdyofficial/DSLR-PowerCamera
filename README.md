# Introduction
DSLR Power Camera is a configuration setting for LMC 8.4 Release 18. based on 
- Selebgram 16 by Impostor Gelap
- Nature Config such as _Aqua Moody, Sunset Glow and Sky BLue_ by Riyan

# Features
- Delicious and Nice Color Grading on Blue, Green and Red.
- Color Grading on Human or Portraits are natural.
- You can capture photos in high quality with the **RES** option!
- Perfect for Social Media to post such as **Instagram**.
- Back, Front, Tele and Wide Camera IDs are used. `0,1,2,3`
- Very nice portrait blur powered by Google Camera!

# Preset Modes
Here are the meanings of the modes and details explained by ChatGPT in order to make this preset possible.

## Selebgram 16
1. **IMX** (Ideal Maximizer): Optimized for enhancing the natural beauty without altering the essence of the photo. Best used for everyday photography where you want to subtly boost clarity and color without dramatic changes.
2. **HMX** (High-Definition Maximizer): Designed to bring out fine details through increased contrast and sharpness. Ideal for architectural and landscape photography where texture and detail are key.
3. **AFX** (Artistic Flare eXtreme): Introduces a vibrant, almost surreal enhancement of colors, making it perfect for artistic projects or any situation where you want the image to make a bold statement.

## Riyan Nature
4. **VIB** (Vibrant Intensity Boost): _based on Sky Blue_ - Amplifies colors to create vivid, eye-catching images. Great for marketing materials or any media that needs to stand out in a visually competitive environment.
5. **SUN** (Sunset/Sunrise Optimizer): _based on Sunset Glow_ - Adds a warm, golden tint, mimicking the soft lighting of golden hour. Ideal for portraits, weddings, and event photography to add a touch of warmth and romance.
6. **RTO** (Real Tone Optimizer): _based on Aqua Moody Blue_ - Provides a cooler, more subdued color palette that reflects a true-to-life visual experience. Best for documenting real-life scenes where natural colors are preferred.

_Each of these presets can be chosen to match the desired emotional tone and creative intent of the photographer, enhancing both the aesthetics and narrative of the images._

> [!note]
> - Be sure that the **Front without restart** option is always enabled in order to use these presets. otherwise, the presets won't be applied and it will use it's specific value settings.
> - THese presets would not be applied into the video recording.

# Differents between 6 presets
![InShot_20240923_132518011](https://github.com/user-attachments/assets/dd156501-a805-4cb3-9150-33609904ca59)
The image six different color grading presets applied to a tropical landscape scene. These presets appear to modify color saturation, contrast, and overall tone, enhancing the aesthetic qualities in different ways. Here's a brief look at each preset:

1. IMX: Offers a balanced enhancement, brightening the greens and blues without oversaturating.
2. HMX: Appears to increase the contrast slightly more than IMX, giving a sharper definition especially in the foliage.
3. AFX: Enhances saturation strongly, making the colors pop and giving a vibrant look.
4. VIB: As the name might suggest, increases vibrancy with a noticeable boost in color saturation.
5. SUN: Likely designed to mimic golden hour lighting, with a warm tint that enhances the yellows and reds.
6. RTO: Offers a cooler tone, emphasizing blues and greens with a slightly muted overall saturation.

# Short Questions
This answer is said by ChatGPT.

## What are the presets that is nice for sunset or sunrise, portrait and nature photography?
The SUN preset is specifically nice for sunset or sunrise due to its warm tint. IMX and VIB could be good for nature photography due to their vibrant and balanced enhancements. For portraits, SUN might add a flattering warm glow, but IMX would generally be more versatile.

## What are the presets that the colors are oversaturated?
AFX and VIB presets show some level of oversaturation which could be appealing for dramatic effects in nature photography but might look unnatural in other contexts.

## What is the recommended preset for human portraits and selfies?
IMX or SUN would be recommended for human portraits and selfies. IMX offers a natural look while SUN provides a warm, golden-hour effect which can be very flattering on skin tones. AFX and VIB might be too harsh for portraits as they can exaggerate skin imperfections and colors.

# Ratings
ChatGPT will rate the presets based on their overall visual appeal and effectiveness in enhancing the scene:

1. IMX: 8/10 - Well-balanced enhancement, good for general use.
2. HMX: 7/10 - Slightly higher contrast than IMX, effective but can be a bit harsh.
3. AFX: 6/10 - Very vibrant, tends to oversaturate which might not be suitable for all scenes.
4. VIB: 7/10 - High vibrancy, good for making colors pop, but can be too much for subtle scenes.
5. SUN: 8/10 - Excellent for simulating golden hour light, very appealing for warm-toned photography.
6. RTO: 7/10 - Cool and slightly muted, good for specific moods but less versatile than others.

_These ratings are subjective and depend on personal preference and the specific application of the presets in various photographic scenarios._

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
> - Why Power Camera? It will unlock all of it's limit to the unlimited feature!
> - Some devices will have a different megapixel based on the manufacturers.
> - **Upscale/Downscale** feature will only work on Devices with **Android 12+** operating systems.
> - Upscaling will only work in **Camera Mode**. To use very high quality with Portrait effect, You can create the Portrait Bokeh effect using Google Photos.
> - The Front Camera will be possible to not use in some specific devices because the RAW sensor size for Front Camera returned as **null**.
> - The Zoom Value is limited to 2x due to artificial coloring issue after capturing with zoom more than 2x has been tested.
> - Shasta Motion value set to default to avoid sharpness on the image.
> - Some features will be possible to work in Android 11 along with Xiaomi's old skin called MIUI.
> - 60fps will not work on some newer specific devices due to a new camera hardware capabilities.

> [!tip]
> - You don't need expensive DSLR camera If you want to capture very high quality.
> - Night Sight shots are very excellent on this config.
> - If the photo results having green color issue, you can turn on AWB every time.

> [!warning]
> - HDR++ feature will only work on Devices with **Level 3** Haredware Support Level. **Full** Hardware support level will also work but on **Android 12+** devices.
> - Night Sight feature will only work on Devices with **Level 3** Haredware Support Level. **Full** Hardware support level will also work but on **Android 12+** devices.
> - Adjustments while photo processing might be worst on some devices than the best image results on the **Sample Shot** section.
> - Selfie capturing in 5MP camera on some midrange devices can have Common Polka Dot Issues while processing the photo on color grading.<br>If possible, Go to `LMC Settings > Processing functions > Upscale/Downscale > Front Camera` and set the value for around `x2.0`, `x2.5` or even `x3.0`. set the value to `x1.0` if there is no issue with the selfie on flagship or high-end devices.

> [!caution]
> - Do **NOT** adjust ISO value to the low values, Night Sight capturing might not be adjusting the exposure to the lighten properly.
> - Do **NOT** turn off **Patcher** features. This is used to color grade and to adjust the quality of the photo.
> - Do **NOT** move some settings that you don't know. Only LMC users and devs can do this.
> - Do **NOT** use this as the document capture, only Portraits, Nature, Scenes, Events, and some sort of Photography. (unless you have to capture the screen that contains correction kit).
