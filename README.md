# OpenCV Calib3D Interactive Virtual Laboratory — Version 1.0

An interactive browser-based teaching aid for camera geometry and calibration concepts used in OpenCV `calib3d`.

## Version 1.0 modules
1. Pinhole Camera Projection
2. Intrinsic Parameter Playground
3. Radial Lens Distortion
4. Real Image Analysis
5. Checkerboard Calibration Concept

## Run locally
Open `index.html` in a modern browser. No installation is required for Version 1.0.

## GitHub Pages
Upload this repository to GitHub, then enable **Settings → Pages → Deploy from a branch → main / root**. The lab will be available as a website.

## Classroom use
Use the modules sequentially: projection → intrinsics → distortion → real image → calibration workflow. The checkerboard module is an educational visualization; quantitative calibration requires real calibration images and OpenCV functions such as `findChessboardCorners()` and `calibrateCamera()`.

## Reference
OpenCV Camera Calibration and 3D Reconstruction documentation:
https://docs.opencv.org/4.13.0/d9/d0c/group__calib3d.html

## Disclaimer
This is an independent educational project based on concepts documented by OpenCV. It is not an official OpenCV project and does not imply endorsement by OpenCV.
