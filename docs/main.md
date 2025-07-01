# Realtime Video Processing

## Seeds

### Blob Tracking (Touch Designer)

![progress](https://progress-bar.xyz/0/)

Blob tracking detects and tracks areas of motion or color changes within a video feed, creating abstract shapes that follow movement. In TouchDesigner, this is often used to generate reactive visuals or drive particle systems. Artists can create visuals that dance along with performers or audience movements on stage.

https://www.tiktok.com/@sssynthomo_/video/7459177934583041302  
https://www.tiktok.com/@mityukovaaa/video/7513527333949803778  
https://www.tiktok.com/@rybinfx/video/7468574846209805586  
https://www.tiktok.com/@nicholaspjm/video/7512274182223187218

### Pose Detection (MediaPipe)

![progress](https://progress-bar.xyz/0/)

Pose detection uses body landmarks to track human movement in real-time. MediaPipe’s solution provides high-precision skeletal data for applications like interactive dance pieces, gesture-driven effects, or live puppeteering of digital avatars. It’s perfect for translating human motion into dynamic visuals or controlling parameters in a live show.

[Link 1](https://www.youtube.com/watch?v=ha2n8wnsMS4) - [Link 2](https://www.youtube.com/watch?v=uk999TevwY4) - [Link 3](https://www.tiktok.com/@zonk_music/video/7434547758398229802) - [Link 4](https://www.tiktok.com/@iwatchpiratedmovies/video/7521566653927214391) - [Link 5](https://www.tiktok.com/@blankensmithing/video/7515513497631984926)     


### Realtime Depth (MiDaS)

![progress](https://progress-bar.xyz/0/)

Realtime depth estimation extracts the relative distance of objects from the camera, allowing for layering or separating visual elements based on depth. Artists can use MiDaS depth maps to create effects like simulated 3D parallax, foreground-background separation, or depth-based particle interactions, adding spatial depth to otherwise flat visuals.

https://www.youtube.com/watch?v=ho6KGlHmWHk

### Image Segmentation (YoloV8)

![progress](https://progress-bar.xyz/0/)

Image segmentation divides an image into meaningful regions, often isolating objects from the background. YOLOv8 can segment objects while detecting them, enabling live compositing or stylization of specific elements in a video feed. This technique empowers artists to selectively manipulate parts of the scene, like applying effects only to people or certain objects.

https://www.youtube.com/shorts/O7DG53cWsEI

### Fast (Non-realtime) AI Image generation

![progress](https://progress-bar.xyz/30/)

It is possible to use lightning AI generation models for quasi-realtime image generation. Based on captured frames and a given prompt frames can be transformed. Not feasible for high framerates, but can me combined with other effects, like for example frame interpolation or datamoshing among others.

https://www.tiktok.com/@mericostx/video/7438679966314663201  
https://www.tiktok.com/@alt.grr/video/7519908983608577302

### Datamoshing

![progress](https://progress-bar.xyz/0/)

Datamoshing is a glitch art technique where video compression artifacts are manipulated to create trippy visual effects. It often involves removing keyframes so motion data “bleeds” between scenes. The result is melting, morphing visuals as pixels smear unpredictably across frames.

https://www.tiktok.com/@nzjared/video/7403960887557524743  
https://www.youtube.com/watch?v=rMSsw4CZvKg

### TikTok Accounts

https://www.tiktok.com/@okamirufu.vizualizer  
https://www.tiktok.com/@alt.grr  


## Tech Stack

### MediaPipe

MediaPipe is a powerful framework from Google that offers real-time machine learning pipelines for video and multimedia streams. It provides ready-to-use solutions like pose tracking, face mesh, hand tracking, and segmentation, all optimized for speed on CPU, GPU, or even mobile devices. It’s highly modular, making it perfect for creating interactive visuals and AR effects.


### YoloV8

YOLOv8 (You Only Look Once, version 8) is a state-of-the-art object detection framework known for its excellent speed and accuracy. It can detect and classify objects in video frames in real-time, making it ideal for live installations, interactive artworks, and reactive visuals. Its flexibility allows training custom object classes for specialized artistic projects.

Also has a nice pose estimator named YoloV8-Pose. More accurate but heavier.

### MiDaS

MiDaS is a deep learning model for monocular depth estimation, predicting a depth map from a single RGB image. It’s fast enough for near-real-time applications and useful for generating 3D-like effects or layering visuals based on depth. Artists can leverage MiDaS to create immersive parallax, depth-driven distortions, or background separation.

### Touch Designer

TouchDesigner is a node-based visual programming environment designed for real-time graphics, interactive installations, and live performance visuals. It can ingest video streams, apply complex effects, and integrate with Python for advanced logic. Artists often use it to build reactive visuals that respond instantly to data from vision systems like MediaPipe or YOLO.
