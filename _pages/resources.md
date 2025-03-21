---
layout: resources
title: "Immersive Computing Resources"
permalink: /resources/
---

Below is a compiled list of resources that can be useful for immersive computing research, including datasets, toolboxes, optimization libraries, simulators, and testbeds.

## Table of Contents
1. [Immersive Datasets](#immersive-datasets)
2. [Immersive Computing Toolbox](#immersive-computing-toolbox)
3. [Optimization Toolbox](#optimization-toolbox)
4. [Simulator/Emulator](#simulatoremulator)
5. [Testbeds](#testbeds)
6. [Network Traces](#network-traces)

---

## Immersive Datasets

### 2D Image/Video
- **<a href="https://r0k.us/graphics/kodak/">Kodak True Color Image Dataset</a>**: A standard test suite for image compression testing.

- **<a href="https://ultravideo.fi/dataset.html">Ultra Video Group (UVG) 4k Video Dataset</a>**:  A collection of high-resolution (4K) video sequences suitable for compression and quality assessment research.

- **<a href="https://mcl.usc.edu/mcl-jcv-dataset/">USCMediaCommLab 2k Video Dataset</a>**:  Video dataset featuring 2K resolution clips, often used for benchmarking video processing algorithms.

### Multiview Image/Video
- **<a href="https://www.epfl.ch/labs/cvlab/data/data-wildtrack/">WILDTRACK Seven-Camera HD Dataset</a>**:  A 7-camera HD dataset for multi-view detection in real environments.

- **<a href="https://iccv2021-mmp.github.io/">Multi-camera Multiple People Tracking Dataset</a>**:  Focused on multi-camera tracking of multiple people in challenging scenarios.

- **<a href="https://exposing.ai/duke_mtmc/">Duke Multi-Target Multi-Camera Tracking Dataset</a>**:  A large-scale multi-camera tracking dataset often used in person re-identification.

- **<a href="https://assembly-101.github.io">Assembly101</a>**:  A large-scale multi-view video dataset for understanding procedural activities.

### Volumetric
- **<a href="https://github.com/ytrock/THuman2.0-Dataset">THUman2.1 Dataset</a>**:  High-quality human scans captured by a dense DLSR rig.

- **<a href="https://github.com/zhengyuf/PointAvatar">PointAvatar</a>**:  The PointAvatar dataset provides preprocessed 3D head avatar data, including synchronized video frames and mesh information.

- **<a href="https://github.com/philgras/neural-head-avatars">NHA</a>**:  The Neural Head Avatars dataset includes preprocessed training data, head tracking results, and optimized head avatars for two subjects.


### NeRF/GS Static or Dynamic Scene
- **<a href="https://github.com/facebookresearch/Neural_3D_Video">Neural 3D Video Synthesis Dataset</a>**:  A dataset from Facebook Research for neural 3D video synthesis approaches.

- **<a href="https://www.matthewtancik.com/nerf">Synthetic 360-degree scenes</a>**:  Synthetic environments used for NeRF training and evaluation.

- **<a href="https://github.com/Fyusion/LLFF">Forward-facing scenes</a>**:  Commonly used for light field and NeRF-based reconstructions.

- **<a href="https://jonbarron.info/mipnerf360/">Unbounded 360-degree outdoor scenes</a>**:  Outdoor 360-degree scenes for NeRF training in unbounded environments.

- **<a href="https://github.com/tobias-kirschstein/nersemble-data">NeRSemble Dataset</a>**:  The NeRSemble Dataset is a large-scale multi-view video dataset of facial performances.

- **<a href="https://github.com/aoliao12138/ReRF_Dataset">ReRF</a>**:  Three multi-view videos for kpop, box, and sing scenarios.


---

## Immersive Computing Toolbox
- **<a href="https://interdigitalinc.github.io/CompressAI/">CompressAI</a>**:  A library and tools for end-to-end compression research using machine learning.

- **<a href="https://www.ffmpeg.org/">FFMPEG</a>**:  A complete, cross-platform solution to record, convert and stream audio and video.

- **<a href="https://bellard.org/bpg/">BPG</a>**:  BPG (Better Portable Graphics) is a new image format. Its purpose is to replace the JPEG image format when quality or file size is an issue.

- **<a href="https://gitlab.com/AOMediaCodec/SVT-AV1">SVT-AV1 Encoder</a>**:  The Scalable Video Technology for AV1 (SVT-AV1 Encoder) is an AV1-compliant software encoder library.

- **<a href="http://hevc.info/mvhevc">Multiview High Efficiency Video Coding (MV-HEVC)</a>**:  Extensions of HEVC for encoding multi-view video content.

- **<a href="https://github.com/google/draco">DRACO 3D Data Compression</a>**:  A library for compressing and decompressing 3D geometric meshes and point clouds.

- **<a href="https://vcgit.hhi.fraunhofer.de/jvet/VVCSoftware_VTM">VVC Reference Software</a>**:  The official reference software for the Versatile Video Coding standard.

- **<a href="https://github.com/Netflix/vmaf">Video Multi-Method Assessment Fusion (VMAF)</a>**:  A perceptual video quality assessment algorithm developed by Netflix.

- **<a href="https://github.com/richzhang/PerceptualSimilarity">Learned Perceptual Image Patch Similarity Metric (LPIPS)</a>**:  A metric for perceptual image patch similarity using deep features.

- **<a href="https://docs.nerf.studio/">nerfstudio</a>**:  A simplified end-to-end framework for creating, training, and testing Neural Radiance Fields.

- **<a href="https://docs.gsplat.studio/main/">gsplat</a>**:  Tools and documentation for generating 3D scenes via splatting techniques.

---

## Optimization Toolbox
- **<a href="https://github.com/bayesian-optimization/BayesianOptimization">Bayesian Optimization</a>**:  A Python library for Bayesian optimization of black-box functions.

- **<a href="https://github.com/ppgaluzio/MOBOpt">Multi-objective Bayesian Optimization (MOBOpt)</a>**:  A library for multi-objective Bayesian optimization in Python.

- **<a href="https://pymoo.org/">pymoo: Multi-objective Optimization in Python</a>**:  A framework that supports multi-objective optimization, genetic algorithms, and more.

- **<a href="https://www.gurobi.com/">Gurobi</a>**:  A state-of-the-art solver for linear, integer, and quadratic programming.

---

## Simulator/Emulator
- **<a href="http://mahimahi.mit.edu/">Mahimahi</a>**:  A tool for recording and replaying HTTP traffic over emulated network conditions.

- **<a href="https://www.nsnam.org/">ns-3</a>**:  A discrete-event network simulator used for internet systems research and education.

- **<a href="https://man7.org/linux/man-pages/man8/tc.8.html">tc</a>**:  A Linux command for controlling network traffic and simulating latency, loss, and bottlenecks.

- **<a href="https://github.com/akamai/cell-emulation-util?tab=readme-ov-file">cell-emulation-util</a>**:  A script based on Linux TC netem to emulate the latency, loss, and bandwidth of a real-world cellular network.

---

## Testbeds
- **<a href="https://www.emulab.net/portal/frontpage.php">Emulab</a>**:  A network testbed that allows researchers to run experiments on various environments.

- **<a href="https://www.cloudlab.us/">Cloudlab</a>**:  A flexible infrastructure allowing cloud computing research on diverse hardware.

- **<a href="https://console.cloud.google.com/">Google Cloud</a>**:  A public cloud platform providing a range of services for computing, storage, machine learning, etc.

- **<a href="https://aws.amazon.com/">Amazon AWS</a>**:  On-demand cloud computing platforms and APIs by Amazon.

- **<a href="https://github.com/ILLIXR/ILLIXR">ILLIXR</a>**:  Illinois Extended Reality testbed or ILLIXR is the first fully open-source Extended Reality (XR) system and testbed.

---

## Network Traces
- **<a href="https://www.fcc.gov/reports-research/reports/measuring-broadband-america">Federal Communications Commission</a>**: Broadband performance measurement data from various U.S. ISPs.

- **<a href="https://qualinet.github.io/databases/commute_path_bandwidth_traces_from_3g_networks/">3G/HSDPA Mobile Dataset</a>**: Commute Path Bandwidth Traces from 3G Networks.

- **<a href="https://github.com/ravinet/mahimahi/tree/master/traces">Mahimahi Cellular</a>**: These trace files represent the time-varying capacity of U.S. cellular networks as experienced by a mobile user.

- **<a href="https://github.com/GreenLv/Lumos">Lumos</a>**: A dataset about the throughput and delivery time of adaptive video streaming, which was collected in real-world mobile networks from December 2019 to May 2021.

- **<a href="https://puffer.stanford.edu/data-description/">Puffer</a>**: Anonymized video sessions and telemetry data from real Puffer users.

- **<a href="https://github.com/hkust-spark/ns3-sparkrtc/blob/f7025dffd2f3ef1bfeeb6c142601833ca98cec4d/examples/sample.tr">Interactive Video Streaming</a>**:  Example traces for interactive video streaming.