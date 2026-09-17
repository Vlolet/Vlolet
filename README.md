<div align="center">

# 이유준 · Vlolet

AI를 전공했고, 모델·장치·데스크톱 앱·서버가 실제로 함께 동작하는 과정을 다룹니다.  
불편이 반복되면 작은 도구나 인프라를 직접 만들어 해결하는 편입니다.

<p>
  <a href="mailto:yjl.vlolet@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/%EC%9D%B4%EC%9C%A0%EC%A4%80/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://vlolet.tistory.com/"><img src="https://img.shields.io/badge/Tistory-000000?style=flat-square&logo=tistory&logoColor=white" alt="Tistory"></a>
</p>

</div>

## 👋 소개

고등학교 때 RoboCup 축구 로봇을 만들며 C로 하드웨어를 제어하기 시작했습니다. 대학에서는 AI를 전공했고, 이후에는 학습한 모델을 Raspberry Pi와 모바일 칩에서 실행하거나 카메라·센서·서버·클라이언트를 연결하는 작업으로 관심을 넓혔습니다.

최근에는 VEDA 팀 프로젝트에서 Raspberry Pi VMS 서버와 Windows Qt 관제 클라이언트를 주로 맡았습니다. 개인 작업은 제가 실제로 겪은 불편에서 시작하는 경우가 많습니다. 파일과 비밀번호를 관리하려고 홈랩을 구성했고, 여러 PC에서 작업을 이어 가거나 코딩 에이전트의 대화 맥락을 관리하는 도구도 만들고 있습니다.

## 🔭 최근 작업

### VEDA 전기차 주차 관리·화재 대응 시스템

카메라 4대, Raspberry Pi, STM32, Windows 클라이언트를 연결한 팀 프로젝트입니다. 저는 Raspberry Pi 서버와 Qt VMS의 설계·구현을 주로 맡고, 장치 사이의 통신 규격을 함께 정리했습니다.

- [Windows Qt VMS Client](https://github.com/VEDA-NoC/Qt-Client) — 4채널 실시간 영상, Timeline·Playback, 이벤트와 장치 제어
- [Raspberry Pi VMS Server](https://github.com/VEDA-NoC/RPI-Server) — 영상 수집·녹화, RTSPS live, SQLite Timeline, HTTPS Control API
- [Interface & Protocol](https://github.com/VEDA-NoC/pi-stm-rs485-protocol) — Camera–RPI–Qt–STM32 연결 규격

### Context Keeper

코딩 에이전트와 진행하던 메인 작업이 디버깅이나 짧은 조사에 묻히지 않도록, 대화를 분리했다가 필요한 결과만 가져오는 개인 프로젝트입니다. 현재는 첫 MVP의 범위와 상태 모델을 정리하고 있습니다.

- [Repository](https://github.com/Vlolet/context-keeper)

## 🧰 Tech Stack

### Systems & Embedded

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt">
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake">
  <img src="https://img.shields.io/badge/Make-A42E2B?style=flat-square&logo=gnu&logoColor=white" alt="Make">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
  <img src="https://img.shields.io/badge/Arm-0091BD?style=flat-square&logo=arm&logoColor=white" alt="Arm">
  <img src="https://img.shields.io/badge/FreeRTOS-1177AA?style=flat-square&logo=freertos&logoColor=white" alt="FreeRTOS">
  <img src="https://img.shields.io/badge/Yocto%20Project-000000?style=flat-square&logo=yoctoproject&logoColor=white" alt="Yocto Project">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" alt="FFmpeg">
  <img src="https://img.shields.io/badge/GStreamer-FF3131?style=flat-square&logo=gstreamer&logoColor=white" alt="GStreamer">
  <img src="https://img.shields.io/badge/OpenSSL-721412?style=flat-square&logo=openssl&logoColor=white" alt="OpenSSL">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
</p>

### AI & Computer Vision

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=yolo&logoColor=white" alt="YOLO">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
</p>

### Infrastructure & Backend

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Nginx%20Proxy%20Manager-F15833?style=flat-square&logo=nginxproxymanager&logoColor=white" alt="Nginx Proxy Manager">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/systemd-000000?style=flat-square&logo=systemd&logoColor=white" alt="systemd">
  <img src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale">
</p>

### Applications & Tools

<p>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="Visual Studio Code">
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira">
</p>

## 🧭 주요 프로젝트

| 프로젝트 | 기간 | 작업 |
| --- | --- | --- |
| [VEDA Linux Remote Control](https://github.com/Vlolet/VEDA_Linux_Project) | 2026.06.02 - 06.05 (4일) | Ubuntu 클라이언트에서 Raspberry Pi 장치를 제어하는 C 기반 TCP 프로그램 |
| 강원Tripy | 2025.04 - 2025.10 | 애플리케이션 프론트엔드 개발, 원스토어 배포와 스토어 커뮤니케이션 |
| 위험 소리 감지 및 알림 앱 | 2025.03 - 2025.05 | 소리 분류 모델 학습, Qualcomm 칩 기반 모바일 환경 최적화, 앱 기능 구현 |
| Raspberry Pi–홈서버 자율주행 | 2024.08 - 2024.11 | 모델과 주행 알고리즘 구현, 장치와 홈서버의 처리 역할 분리 |
| RoboCup Junior Soccer Lightweight | 2018 - 2019 | 2018년 하드웨어, 2019년 C 기반 제어 소프트웨어 담당 |

## 🎓 Education & Training

**학력**

- **2022.03–2026.02** 한성대학교 AI응용학과 학사

**교육과정**

- **2026.03–2026.09** Vision's Edge Device Academy 4기 수료
- **2025.01–2025.02** LG Aimers 6기 Data Intelligence 수료

## 🏆 Awards & Certifications

- **2026.09** VEDA 4기 우수 훈련생상
- **2026.09** VEDA 4기 프로젝트 최우수상 — 팀 NoC
- **2025.11** TOPCIT 수준 3
- **2019.08** 제3회 한국창의코딩대회 RoboCup Junior Soccer Lightweight 연구일지상
- **2018.08** 제2회 한국창의코딩대회 RoboCup Junior Soccer Lightweight 연구일지상
