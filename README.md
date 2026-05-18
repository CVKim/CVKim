<div align="left">

<!-- Professional header -->
![header](https://capsule-render.vercel.app/api?type=slice&color=0:1e3a8a,100:0c4a6e&text=Gwangyeol%20Kim&fontSize=46&fontColor=ffffff&height=200&desc=Deep%20Learning%20Deployment%20Engineer&descSize=18&descAlign=70&descAlignY=80)

</div>

## Profile

**Industrial Machine Vision Engineer** · Deep Learning Deployment · **7+ years**

제조 / 물류 도메인에서 비전 시스템과 Deep Learning inference 파이프라인을 설계 / 최적화합니다. 학습 (PyTorch) → 변환 (ONNX) → 배포 (TensorRT / ONNX Runtime / OpenVINO) → C++ runtime 까지 전 stage 를 다루며, **저수준 cubin / runtime header 단계의 최적화** 와 **2D / 3D 비전 알고리즘** 양쪽을 함께 수행합니다.

---

## Experience

### Manufacturing Domains
다양한 제조 / 물류 현장에서 비전 시스템 양산 경험:

| 도메인 | 검사 / 작업 대상 |
|---|---|
| Semiconductor | Wafer 검사, OLB / PCB inspection |
| Display | Panel / module 검사 |
| Bio / Medical | 진단키트 자동화 검사 |
| Automotive | 부품 검사, Bin-picking |
| Logistics | Palletizing, 박스 인식 |
| Coating / Surface | 외관 / 표면 결함 검사 |

### Deep Learning Models

산업 현장에 맞춰 학습 / 최적화 / 배포해온 모델 카테고리:

| 카테고리 | 대표 모델 / 기법 |
|---|---|
| **Object Detection** | RF-DETR, D-FINE, DETR family · YOLO 시리즈 (v5 / v7 / v8 / v11) |
| **Classification** | ResNet / EfficientNet / ViT 계열 |
| **Segmentation** | U-Net 계열, instance / semantic segmentation |
| **Anomaly Detection** | Reconstruction-based, embedding-based, PatchCore-like 접근 |
| **Defect Generation** | Diffusion / GAN 기반 결함 합성 (학습 데이터 부족 도메인 대응) |
| **Multi-Object Tracking** | ByteTrack, DeepSORT (제조 라인 이동 객체 추적) |

### Inference / Deployment Stack
학습 / 변환 → 배포 / 최적화 전 사이클:

| 단계 | Tooling |
|---|---|
| **Training** | PyTorch, LibTorch, TensorFlow |
| **Conversion** | ONNX, ONNX-graphsurgeon, polygraphy |
| **Optimization** | **TensorRT** (custom plugin: A10, Flash Attention 변종), ONNX Runtime, **OpenVINO** |
| **Targets** | NVIDIA GPU (server / desktop / Jetson), Edge PC (CPU SIMD), x86 / ARM |
| **Runtime** | C++ inference app, multi-stream batching, GPU memory profiling |
| **Cross-platform** | Linux build → Windows AMD64 runtime engine 최적화 |

### 2D / 3D Vision Algorithms

Deep Learning 외 전통 vision 알고리즘 능력:

- **2D Metrology / 외관 검사**: 룰베이스 알고리즘 설계, 광학적 한계 / 객체 특성 수학적 모델링 (SVD, Polynomial fitting), C++ / Python 전·후처리 구현
- **3D Robot Vision**: Bin-picking, Palletizing 양산 솔루션. RGB / ToF / Stereo 입력, motion calibration (hand-eye, eye-hand)
- **Vision Libraries**: Cognex VisionPro, Matrox MIL, OpenCV, PCL, Eigen

### Industrial System Integration

- **Camera SDKs**: Arena (Lucid), Basler pylon, HIK MVS, Matrox MIL, Sapera (Teledyne DALSA), GO_SDK (Gocator 3D)
- **Vision interfaces**: GigE Vision, USB3 Vision, Camera Link, Area / Line / ToF 카메라
- **PLC / Control**: Mitsubishi, LS Electric, Siemens
- **Auto optical system**: 광학 셋팅 표준화 / 자동화 도구 개발

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
<img src="https://img.shields.io/badge/Edge%20PC-555?style=for-the-badge">
<img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/Industrial%20Cameras-555?style=for-the-badge">
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
</p>

### Data & Persistence
<p>
<img src="https://img.shields.io/badge/JSON-5E5C5C?style=for-the-badge&logo=json&logoColor=white">
<img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white">
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
