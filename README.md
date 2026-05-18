<div align="left">

<!-- Professional header -->
![header](https://capsule-render.vercel.app/api?type=slice&color=0:1e3a8a,100:0c4a6e&text=Gwangyeol%20Kim&fontSize=46&fontColor=ffffff&height=200&desc=Machine%20Vision%20%26%20AI%20Solution%20Developer&descSize=18&descAlign=70&descAlignY=80)

</div>

## Profile

**Machine Vision & AI Solution Developer** · **7+ years**

> 현장의 난제를 Deep-dive 엔지니어링으로 해결하는 풀스택 자동화 · 비전 AI 전문가

머신비전 시스템 설계부터 딥러닝 모델 (Detection / Segmentation / Anomaly Detection / OCR / Generative AI) 의 학습 · 최적화 · 배포까지 **End-to-End 파이프라인**을 다룹니다. **C++ / Python 기반 고성능 추론 엔진** (TensorRT / OpenVINO / ONNX Runtime / CUDA / Flash Attention / SIMD) 과 **3D Vision 알고리즘** (Epipolar Geometry, Depth Processing, Point Cloud) 양쪽을 production-grade 로 구현해 왔습니다.

---

## Domain Experience

다양한 제조 / 물류 양산 현장에서 적용한 비전 AI · 자동화 솔루션:

| 산업 도메인 | 적용 기술 · 주요 성과 |
|---|---|
| **자동차 부품 검사** (도장 라인, 볼조인트, 외관) | Edge AI (Jetson Orin) 기반 로봇 충돌 방지 Vision Safety Agent · 2-Stage Detection + Classification 앙상블로 **미검률 0.1% 미만** · Diffusion 기반 결함 데이터 합성 양산 적용 |
| **타이어 3D 외관 + 양각/음각 OCR** | 곡면 특성 보정 (Patch-based Median, SVD Polynomial Fitting), PCA Alignment + Statistical Depth Analysis · Rotation-Aware Custom PARSeq + Top-K 후보 매칭 · C++ Native End-to-End OCR 파이프라인 |
| **물류 자동화** (Palletizer / Depalletizer / Rack 가이드) | YOLOv8-OBB Custom Cutout 기반 박스 검출률 **+5%** · 2D Intensity + 3D ToF Depth 융합 위치 보정 · **Eye-to-Hand Auto Calibration** (Reprojection 검증, XY ±10mm · Z ±5mm 정밀도) |
| **반도체 자동화 설비** (Wafer / Cut / Align) | Asymmetric Geometric Align 알고리즘 신규 개발 · Priority-based Async I/O + Lock-Free Circular Queue 로 Deterministic Real-time 제어 · WPF/MVVM UI 표준화 |
| **디스플레이 검사 설비** (OLB / PCB / Bonding / Cutting) | CXP 고속 카메라 전환으로 Tact Time **4× 향상** · AI VAT (Vision Auto Teaching) + Rule-based 앙상블로 자재성 오검률 **99% 개선** · DCT / Median Custom Filter 로 **Cpk 1.33+** 달성 |
| **바이오 / 진단키트 자동화** | 사내 최초 **GPU 가속 자체 Vision AI Inference Framework** (CUDA / TensorRT / ONNX Runtime) 양산 적용 · Multi-spectrum 광학 시스템 · Robot-Vision Guiding |

---

## Core Competencies

### Deep Learning Tasks
- **Object Detection** — YOLO 시리즈 (v7 / v8 / v11, HBB / OBB), RTMDet, RF-DETR, D-FINE · Head 구조 변경, OBB fine-tuning, Custom Cutout 학습 전략
- **Segmentation** — SAM2 Decoder **U-Net 기반 경량화** 및 Few-shot 적응, DeepLabv3+, Auto-labeling 파이프라인 구축
- **Anomaly Detection** — DINOv2 기반 비지도 학습 fine-tuning, PaDiM / PatchCore, Foundation Model 활용
- **OCR** — Scene Text Recognition (PARSeq Rotation-Aware 재설계, SVTR, PaddleOCR), End-to-End OBB → Perspective Rectify → Orientation Cls → Recognize 파이프라인 C++ Native 구현
- **Generative AI** — Stable Diffusion 기반 **Defect Image Synthesis** (소수 샘플로 희귀 결함 합성), Custom Loss Function 설계 · 양산 적용
- **Multi-Object Tracking** — ByteTrack, DeepSORT · Severe Occlusion 환경의 Component-based Tracking, Temporal Difference Classification 으로 Move/Stay 판단 정밀화

### Inference Engine & Optimization
- **TensorRT** — Custom Plugin 개발 (**Flash Attention 3**, A10), Dynamic Shape, Multi-stream batching, Cross-platform engine 최적화 (Linux build → Windows AMD64), Patch / Batch inference 가속
- **OpenVINO** — GPU 미사용 현장의 CPU 실시간 추론 파이프라인, ONNX 변환 + Runtime 최적화
- **CUDA Custom Kernel** — Flash Attention native C++ 구현, multi-thread inference context
- **ONNX Toolchain** — `onnx-graphsurgeon`, `polygraphy` graph surgery, FP16 / FP32 precision pinning, layerPrecisions / layerOutputTypes 미세 제어
- **C++ Concurrency** — Singleton + Context 공유 (Multi-thread safe), Priority-based Async I/O, Lock-Free Circular Queue

### 3D Vision & Computational Geometry
- **3D Reconstruction** — Epipolar Geometry, Multi-view stereo, Point Cloud Processing (PCL)
- **Mathematical Modeling** — SVD, PCA, Polynomial Fitting, Cubic Spline Interpolation, Dynamic Programming (Cost Map 기반 최적 경로 탐색)
- **Sensor Fusion** — 2D Intensity + 3D Depth (ToF) 융합, Cell-grid Median 기반 Statistical Depth Analysis
- **Robot-Vision Calibration** — Eye-to-Hand / Hand-Eye **Auto Calibration**, Inverse Kinematics 기반 Extrinsic 산출, Reprojection Error 정량 검증
- **Sub-pixel Precision** — Cognex VisionPro / MIL / OpenCV 기반 Sub-pixel Edge / Blob Detection, 적응형 필터링

### Industrial System Integration
- **Industrial Cameras** — GigE Vision / USB3 Vision / CoaXPress / Camera Link · Area / Line / ToF (Arena, Basler pylon, HIK MVS, Matrox MIL, Sapera, GO_SDK)
- **PLC & Control** — Mitsubishi / LS Electric / Siemens 통신 표준화, Auto Optical System (AF / WB / 조명 자동 보정)
- **Edge Deployment** — NVIDIA Jetson Orin 기반 low-latency inference + PLC 신호 연동 시스템

---

## Research & Patents

| Type | Description |
|---|---|
| 📄 **Paper (arXiv)** | [arXiv:2411.16767](https://arxiv.org/pdf/2411.16767) — Diffusion-based Defect Generation for Industrial Inspection |
| 🇰🇷 Patent (KR) | 도메인이 상이한 복수의 손실함수를 활용한 이미지 복원 방법 — No. 10-2910338 |
| 🇰🇷 Patent (KR) | 복수의 손실 함수를 활용한 결함 데이터 획득 방법 — No. 10-2924934 |
| 🇺🇸 Patent (US) | App. No. 19/362,423 (2025.10) — pending |
| 🇪🇺 Patent (EU) | App. No. EP25210652.1 (2025.10) — pending |

---

## Technical Stack

### Languages
<p>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white">
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white">
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white">
</p>

### Deep Learning & GPU
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/LibTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white">
<img src="https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white">
<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/OpenVINO-0071C5?style=for-the-badge&logo=intel&logoColor=white">
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/cuDNN-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
</p>

### Computer Vision
<p>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/PCL-22A699?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/Eigen-44A833?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white">
<img src="https://img.shields.io/badge/SIMD-4EAA25?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/Cognex%20VisionPro-1E90FF?style=for-the-badge">
<img src="https://img.shields.io/badge/Matrox%20MIL-FF8C00?style=for-the-badge">
</p>

### Industrial / Edge
<p>
<img src="https://img.shields.io/badge/NVIDIA%20Jetson%20Orin-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/Edge%20PC-555?style=for-the-badge">
<img src="https://img.shields.io/badge/Industrial%20Cameras-555?style=for-the-badge">
<img src="https://img.shields.io/badge/CoaXPress%20%2F%20Camera%20Link-444?style=for-the-badge">
<img src="https://img.shields.io/badge/PLC%20Mitsubishi-CC0000?style=for-the-badge">
<img src="https://img.shields.io/badge/PLC%20LS%20Electric-005BAC?style=for-the-badge">
<img src="https://img.shields.io/badge/PLC%20Siemens-009999?style=for-the-badge&logo=siemens&logoColor=white">
</p>

### DevOps & Build
<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/WSL2-4D4D4D?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Subversion-809CC9?style=for-the-badge&logo=subversion&logoColor=white">
<img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white">
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white">
<img src="https://img.shields.io/badge/JetBrains%20DotMemory-000000?style=for-the-badge&logo=jetbrains&logoColor=white">
</p>

### Data & Persistence
<p>
<img src="https://img.shields.io/badge/JSON-5E5C5C?style=for-the-badge&logo=json&logoColor=white">
<img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/DBeaver-372923?style=for-the-badge&logo=dbeaver&logoColor=white">
</p>

---

## GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=CVKim&theme=github_dark" alt="profile" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=CVKim&theme=github_dark" alt="languages" height="180" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=CVKim&theme=github_dark" alt="commits per language" height="180" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=CVKim&theme=github_dark" alt="stats" height="180" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=CVKim&theme=github_dark&utcOffset=9" alt="productive time" height="180" />
</p>

---

## Contact

<a href="https://linkedin.com/in/광열-김-73a08b271" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:kgy2521@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://mvmldl.tistory.com/">
  <img src="https://img.shields.io/badge/Tech%20Blog-000000?style=for-the-badge&logo=Tistory&logoColor=white">
</a>
<a href="https://arxiv.org/pdf/2411.16767">
  <img src="https://img.shields.io/badge/arXiv%202411.16767-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white">
</a>
