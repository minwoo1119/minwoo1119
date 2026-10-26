<div align="center">

# Hi, I'm Minwoo Lee

### C++ Software Engineering · Computer Vision · AI · App Development

**영상처리와 AI 기술을 실제 소프트웨어와 서비스로 구현하는 개발자입니다.**  
산업용 비전 소프트웨어부터 로컬 AI 시스템, 모바일 앱까지 직접 설계하고 개발합니다.

<p>
  <a href="https://minwoo1119.github.io/its-minu/ko"><img src="https://img.shields.io/badge/Portfolio-007AFF?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:minwoo1119@naver.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://lmw1119.tistory.com/"><img src="https://img.shields.io/badge/Blog-000000?style=flat-square&logo=tistory&logoColor=white" alt="Blog" /></a>
  <a href="https://www.linkedin.com/in/sksmsalsndi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

</div>

---

## About Me

현재 **산업용 머신비전 분야에서 Vision SW Researcher**로 재직하며 C++/MFC 기반 Windows 검사 소프트웨어의 기능 개발 및 안정화 작업을 수행하고 있습니다.

- **Software Engineering:** C++, MFC, Win32, C#/.NET, WPF, 멀티스레딩 및 디버깅
- **Computer Vision & Edge AI:** OpenCV, 영상 분석, OCR, 비지도 이상 탐지, ONNX Runtime, TensorRT
- **AI & Product Development:** Python, PyTorch, FastAPI, 로컬 LLM/RAG, React Native, Flutter, React/Next.js

알고리즘의 성능뿐 아니라 **유지보수성, 실행 안정성, 사용자 경험, 실제 배포**까지 고려합니다.

## Professional Projects

> 현재 수행 중인 업무를 회사명 및 비공개 정보 없이 요약했습니다. 자세한 내용은 [포트폴리오](https://minwoo1119.github.io/its-minu/ko)를 참고해 주세요.

### Windows 기반 검사 소프트웨어 기능 개선 및 안정화

- C++/MFC 기반 검사 기능, ROI 판정 조건 및 검사 결과 기록 로직 개선
- Variation 데이터 로깅 구조를 정비하고 멀티스레드·메모리 관련 실행 오류 분석
- 기존 코드 흐름을 추적하며 기능 변경이 검사 결과와 시스템 안정성에 미치는 영향을 검토

`C++` `MFC` `Win32` `Multithreading` `Debugging`

### 설비 운영 및 데이터 분석 플랫폼 개발

- 설비 클라이언트와 서버 간 WebSocket 통신, 운영 로그 및 데이터 수집 흐름 개발
- 관리 Web UI·API와 검사 이미지/로그 분석 기능 연동
- C# 기반 데이터 분석 기능과 기존 Windows 애플리케이션 연계

`C++` `C#/.NET` `Python` `React` `WebSocket` `Data Analytics`

---

## Released Mobile Apps

### [SaSang (사상) — 사진으로 기록하는 여행 지도](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/17)

<img src="https://img.shields.io/badge/Released-iOS%20%26%20Android-34C759?style=flat-square" alt="Released on iOS and Android" />

방문한 지역의 **실제 지도 경계 안을 여행 사진으로 채우는** 모바일 앱입니다. GIS 데이터를 모바일용 벡터 경로로 전처리하고, SVG ClipPath로 사진을 마스킹하는 커스텀 지도 렌더러를 구현했습니다. 로컬 저장과 지도 확대·이동 인터랙션을 지원합니다.

`React Native` `Expo` `TypeScript` `react-native-svg` `Reanimated` `GIS`

[App Store](https://apps.apple.com/us/app/%EC%82%AC%EC%83%81/id6806609419) · [Google Play](https://play.google.com/store/apps/details?id=com.sasang.app) · [Project Details](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/17)

### [Yesang (예상) — 경조사 금전·일정 관리](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/16)

<img src="https://img.shields.io/badge/Released-iOS%20%26%20Android-34C759?style=flat-square" alt="Released on iOS and Android" />

축의금·부의금 등 경조사 내역을 사람, 이벤트, 거래 기록별로 관리하는 모바일 앱입니다. 서버 API와 로컬 SecureStore를 공통 도메인 인터페이스로 추상화해 **로그인·게스트 모드에서 동일한 사용자 흐름**을 제공하도록 설계했습니다.

`React Native` `Expo Router` `TypeScript` `Zustand` `TanStack Query` `Zod`

[App Store](https://apps.apple.com/us/app/%EC%98%88%EC%83%81/id6768654211) · [Google Play](https://play.google.com/store/apps/details?id=com.minwoo1119.yesang) · [Project Details](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/16)

<details>
<summary><b>Previously Released — 금품타 (Geumpumta)</b></summary>

Flutter 기반 대학생 학습시간 인증 및 랭킹 앱으로, App Store와 Google Play에 출시했습니다. 학교 Wi-Fi 인증, 백그라운드 타이머 시간 보정, 실시간 학습 통계와 랭킹을 구현했습니다. **현재 서비스 운영은 종료되었습니다.**

`Flutter` `Dart` `Riverpod` `Firebase`

[Project Details](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/7)

</details>

---

## Selected Engineering Projects

### [Industrial Anomaly Detection on Edge](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/21)

정상 이미지 기반 **PatchCore 이상 탐지 모델**을 학습하고 Jetson Orin Nano 환경의 C++/TensorRT 추론 파이프라인으로 최적화했습니다. 포트폴리오 기준 INT8 추론 지연시간 **14.3 ms (약 70 FPS)**를 기록했습니다.

`C++` `PatchCore` `PyTorch` `ONNX` `TensorRT` `CUDA` `Jetson Orin Nano`

### [Micro-pipette Detection & Hybrid OCR System](https://minwoo1119.github.io/its-minu/ko/computer-vision/projects/1)

YOLO 객체 탐지와 Custom CNN·PaddleOCR을 결합한 숫자 인식 파이프라인을 구현했습니다. ONNX/TensorRT 가속으로 추론 지연시간을 **300 ms → 80 ms (약 73% 감소)**로 개선했습니다.

`C++` `Python` `YOLO` `PaddleOCR` `ONNX Runtime` `TensorRT`

### SEM Particle Analyzer

전자현미경(SEM) 이미지에서 입자를 검출·분할하고 크기와 형상 지표를 계측하는 Windows 데스크톱 애플리케이션입니다. CLAHE, Distance Transform, Watershed 기반 분석과 MVVM 구조 및 단위 테스트를 적용했습니다.

`C#` `.NET 8` `WPF` `OpenCvSharp` `Watershed` `MVVM` `xUnit`

### Video-based 7-Segment OCR System

C++/MFC 멀티스레드 영상 링 버퍼와 OpenCV를 활용해 연속 비디오에서 7-Segment 숫자 표시를 검출·판독하는 시스템입니다.

`C++` `MFC` `OpenCV` `Multithreading` `Ring Buffer` `Template Matching`

### [dograc — Local RAG Platform](https://github.com/minwoo1119/dograc)

외부 LLM API에 문서를 전송하지 않는 로컬 RAG 플랫폼입니다. Ollama와 BGE-M3 기반 문서 검색·답변 생성, 인용 근거 표시, 실행 추적 UI, Windows 런처 및 Docker 미사용 환경의 저장소 폴백을 구현했습니다.

`Python` `FastAPI` `Next.js` `Ollama` `BGE-M3` `Qdrant` `SQLite` `Docker`

<details>
<summary><b>More Projects — AI, Research & Web</b></summary>

- **ChwieolUp-AI:** 채용 메일 분류 및 면접 회고 질문 생성을 위한 Ollama/Gemma·FastAPI AI 서빙 시스템
- **JobForeigner (JobTalk):** 외국인 구직자를 위한 React/TypeScript·FastAPI 기반 다국어 채용 플랫폼
- **Instruction-Tuned LLM Alignment:** Gemma 모델의 SFT·DPO 효과를 비교하고 정량 평가한 연구
- **LLM Fine-Tuning for Healthy Aging:** 건강·의학 문헌 기반 데이터셋 구축과 Unsloth/LoRA 파인튜닝

[Explore All Projects](https://minwoo1119.github.io/its-minu/ko)

</details>

---

## Tech Stack

| Area | Tools & Technologies |
| --- | --- |
| **Languages & Desktop** | `C++` `C#` `Python` `TypeScript` `Dart` `MFC` `WPF` `.NET` |
| **Computer Vision & AI** | `OpenCV` `PyTorch` `ONNX Runtime` `TensorRT` `YOLO` `PatchCore` |
| **Backend & Systems** | `FastAPI` `WebSocket` `SQLite` `PostgreSQL` `Docker` `Ollama` `Qdrant` |
| **Web & Mobile** | `React` `Next.js` `React Native` `Expo` `Flutter` `Riverpod` |
| **Engineering Practices** | `Git` `Multithreading` `Debugging` `MVVM` `Unit Testing` |

## Research & Awards

| Year | Achievement |
| --- | --- |
| **2026** | **금상**, 한국정보기술학회(KIIT) 하계 대학생 논문경진대회 — Instruction-Tuned LLM에서 DPO의 효과와 한계 |
| **2025** | **은상**, 한국정보기술학회(KIIT) 추계 대학생 논문경진대회 — 저속노화 특화 LLM 파인튜닝 |
| **2025** | **KCI 등재 학술지 논문 게재** — 모바일 기부 플랫폼의 투명성 향상 연구 |
| **2024–2025** | LG Aimers 6기 과정 수료 |

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=minwoo1119&show_icons=true&hide_border=true" height="155" alt="GitHub stats" />
</div>

<details>
<summary>GitAnimals</summary>
<br />
<div align="center">
  <a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=minwoo1119&utm_content=farm">
    <img src="https://render.gitanimals.org/farms/minwoo1119" width="700" alt="GitAnimals farm" />
  </a>
</div>
</details>
