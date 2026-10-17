# Yonatan Simson

Computer vision engineer working on **SLAM, visual-inertial odometry, 3D reconstruction and sensor fusion**: from camera models and calibration to filters, bundle adjustment and dense mapping.

Background: M.Sc. EE (Ben-Gurion University). Worked on SLAM evaluation and ORB-SLAM at Magic Leap, edge stereo depth at Intel RealSense, and now multi-sensor mapping (stereo, LiDAR, 360°, RTK GNSS) on embedded GPUs.

### Own projects

| Repo | What it is |
|---|---|
| [msckf_x](https://github.com/YonatanSimson/msckf_x) | Monocular MSCKF VIO in C++, written from the papers: FEJ, fisheye/omni camera models, static + dynamic init, simulation gates, EuRoC/TUM-VI/KITTI benchmarks |
| [indoor_3d](https://github.com/YonatanSimson/indoor_3d) | Offline indoor reconstruction from ARKit RGB-D: TSDF fusion, COLMAP pose refinement, depth upsampling |

### Contributions on top of open-source tools

| Repo | My changes |
|---|---|
| [kalibr](https://github.com/YonatanSimson/kalibr) | Fixed-ξ omni (MEI) calibration with k2/k3 distortion, corner reuse from Basalt, target-pose seeding |
| [basalt](https://github.com/YonatanSimson/basalt) | Python bindings for project / unproject / RANSAC pose, spherical camera model for IMU↔360° calibration |
| [basalt-headers](https://github.com/YonatanSimson/basalt-headers) | Equirectangular camera model for 360×180 panoramic input |
| [opengv](https://github.com/YonatanSimson/opengv) | SQPnP with angular error for omnidirectional cameras, Python wheels and CI |
| [natural-neighbor-interpolation](https://github.com/YonatanSimson/natural-neighbor-interpolation) | CUDA support and a faster CPU path |
| [pymcc](https://github.com/YonatanSimson/pymcc) / [pymccrgb](https://github.com/YonatanSimson/pymccrgb) | Memory-leak and overflow fixes, faster surface interpolation for point-cloud ground classification |

**Interests:** 3D geometry · navigation · deep learning for geometry
