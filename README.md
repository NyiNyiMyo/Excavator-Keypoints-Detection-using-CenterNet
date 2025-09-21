# Excavator Keypoints Detection using CenterNet

[![python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/CenterNet-black)

This repository contains keypoints detection project focused on **Robotic like Machine, Excavator** with **6 keypoints** using **CenterNet**.

<img src="https://github.com/user-attachments/assets/75d920b6-9c4f-4bdf-965c-0beb845f221d" width="270">
<img src="https://github.com/user-attachments/assets/f6ee2a50-45b1-4481-b9fd-e42d49aeb3fc" width="270">
<img src="https://github.com/user-attachments/assets/9cea0efe-60b4-42a7-b948-5623d472a723" width="270">

<img src="https://github.com/user-attachments/assets/75d920b6-9c4f-4bdf-965c-0beb845f221d" width="270">
<img src="https://github.com/user-attachments/assets/f6ee2a50-45b1-4481-b9fd-e42d49aeb3fc" width="270">
<img src="https://github.com/user-attachments/assets/9cea0efe-60b4-42a7-b948-5623d472a723" width="270">

<img src="https://github.com/user-attachments/assets/3e8c1a0a-6227-4f90-95de-21c8784acd7a" width="270">
<img src="https://github.com/user-attachments/assets/c6a91c17-441d-44bd-85f4-bf754ee81bb2" width="270">
<img src="https://github.com/user-attachments/assets/611f8ae0-0e20-4da2-8126-15ea9c24531d" width="270">

<img src="https://github.com/user-attachments/assets/3e8c1a0a-6227-4f90-95de-21c8784acd7a" width="270">
<img src="https://github.com/user-attachments/assets/c6a91c17-441d-44bd-85f4-bf754ee81bb2" width="270">
<img src="https://github.com/user-attachments/assets/611f8ae0-0e20-4da2-8126-15ea9c24531d" width="270">

---

## 🧭 Dataset Overview

Total train images: 642 / Total val images: 54

✅ keypoint_names = [ 'bucket', 'hinge1', 'hinge2', 'driver_seat', 'rear', 'b_hinge' ]  
✅ skeleton = [[0, 5], [1, 2], [2, 3], [3, 4], [5, 1]]

---

## 🏗️ Model Architecture

- 🦾 Model: **CenterNet**
- 🦾 Type: **Bottom-up**
- 🦾 Weight: **"multi_pose_dla_3x.pth"**
- 🦾 Framework: **PyTorch + DCNv2**
- 🦾 Input Size: **720**
- 🦾 Trained Epochs: **20**

---
