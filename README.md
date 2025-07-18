# 🌬️ Breath Detection with Stereo Vision (and a bit of OpenCL magic)

Ever wanted to watch someone breathe using two cameras and a GPU?  
No? Well, we did it anyway.

This repo uses **stereo vision** + **disparity estimation** (via AdCensus algorithm) + **OpenCL acceleration** to detect subtle chest movements — i.e., human breathing — in real-time.

Because... why not?

## 🧠 What's Going On?

- 🎥 Two cameras = stereo vision
- 📏 Disparity map = depth perception
- 💨 Depth changes = chest movement = **breathing**
- ⚡ OpenCL = GPU speed boost  
- 🧮 Based on the AdCensus algorithm (the census you actually care about)

## ⚙️ Features

- Real-time breath detection via disparity changes
- GPU-accelerated using OpenCL (no CUDA here)
- Stereo image capture and processing
- Works with low-cost cameras and mid-tier GPUs
