# weather-cctv-restoration
# Generative Video Restoration System for Weather-Degraded CCTV Footage

### Minor Project – School of Electronics Engineering, KIIT-DU (2025–26)

This project aims to restore CCTV surveillance videos degraded due to adverse weather conditions such as rain, fog, haze, and low visibility. The system enhances frame clarity, improves resolution, and maintains temporal consistency, making footage more useful for real-time monitoring and computer-vision tasks.

---

## Problem Statement
CCTV cameras capture critical surveillance footage — but during bad weather, the visibility reduces drastically due to:
- Heavy rain streaks
- Fog/haze distortion
- Noise and motion blur
- Reduced contrast and loss of detail

This degraded footage affects:
- Human monitoring efficiency
- Vehicle detection and number-plate recognition models

There is a need for an intelligent system to restore such footage for reliable surveillance. 

---

## Proposed Solution
A **generative deep-learning based pipeline** that:
1. Removes weather artifacts (De-weathering)
2. Enhances image resolution (Super-Resolution)
3. Ensures smooth frame transitions (Temporal Stability)
4. Improves detection accuracy for surveillance analytics

---

## Architecture & Modules
| Module | Description |
|--------|-------------|
| De-weathering | Removes fog using CNN models (UNet / AOD-Net) |
| Super-Resolution | Enhances pixel quality using ESRGAN / EDSR |
| Temporal Consistency | Optical flow-based stability to avoid flickering |
| Evaluation | YOLOv8 (vehicle detection), OCR (license plates) |
| Deployment | Optimized for Raspberry Pi for real-time inference |

---

## Expected Outcomes
✔ Clearer surveillance footage  
✔ Increased detection accuracy (YOLO + OCR)  
✔ Stable, flicker-free enhanced video  
✔ Real-time performance on edge devices

---

## Technologies Used
- **Deep Learning:** PyTorch / TensorFlow
- **Models:** UNet, AODNet, ESRGAN, EDSR
- **Computer Vision:** Optical Flow, OpenCV
- **Surveillance AI:** YOLOv8, EasyOCR
- **Hardware:** Raspberry Pi (Edge Deployment)

---

## Dataset
- Public & synthetic CCTV weather-degraded datasets  
- Real-time environment captured samples  
- (+ augmentation techniques)

---

## Evaluation Metrics
- PSNR, SSIM — image restoration quality
- Inference speed (FPS on Raspberry Pi)
- CV performance boost for YOLO/OCR

---

## Team
| Name | Roll No. |
|------|----------|
| Arnav Singhal | 2330293 |
| Anushka Sharma | 23303291 |
| Bhavya Suman | 2330298 |
| Abhishek Kumar Singh | 2330207 |

Supervisor: **Prof. Suprava Patnaik**

---

## Future Scope
- Multi-weather adaptation using GANs
- Integration into Smart City infrastructure
- Real-time alert & traffic analytics

---

## Status
**Work in progress** — model training, integration & edge testing underway.

