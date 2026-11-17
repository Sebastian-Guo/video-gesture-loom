# Motion Loom · Video Gesture Drawing

An independent video drawing tool using the Finger Ribbons style from Gesture Loom.

Choose a video → Start drawing → Export PNG. Video processing and hand tracking run locally in your browser, with up to two hands. Pause and resume, or adjust palette, width, opacity, and smoothing before drawing again.

MP4 / H.264 is recommended. Occlusion, fast movement, and small hands may cause missed detections. Export your artwork before closing the page.

Local preview: `python3 -m http.server 8000`.

Hand tracking uses MediaPipe Hand Landmarker.
