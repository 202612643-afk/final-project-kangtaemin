# 🛋️ 공간 맞춤형 1인 가구 배치 도우미

> **2026학년도 1학기 프로그래밍 기초와 실습 기말 프로젝트** > 방의 크기와 예산에 맞춰 최적의 가구 배치를 제안하고 관리해주는 1인 가구 특화 공간 시뮬레이션 애플리케이션입니다.

---

## 📌 프로젝트 소개
최근 증가하는 1인 가구는 제한된 주거 공간(원룸, 오피스텔 등)을 효율적으로 활용해야 하는 어려움이 있습니다. 본 프로젝트는 사용자가 방의 치수를 입력하면 가구의 최적 배치를 3D로 자동 추천해주고, 예산과 공간 제한을 실시간으로 체크하여 시행착오 없는 방 꾸미기를 도와주는 앱입니다.

## ✨ 주요 기능

### 1. 🤖 3D 레이아웃 자동 추천 (핵심 기능)
- 사용자가 입력한 방의 가로, 세로, 높이 치수를 기반으로 공간을 계산합니다.
- 침대, 책상, 옷장 등 필수 가구들의 최적 배치 조합을 알고리즘을 통해 3D 레이아웃으로 자동 제안합니다.

### 2. ⚠️ 가구 크기 제한 알림 (보조 기능)
- 방의 전체 치수를 초과하거나, 다른 가구와 동선이 겹치는 무리한 크기의 가구를 선택할 경우 실시간 경고 알림을 제공합니다.
- 배치 불가능한 상황을 사전에 방지하여 공간 낭비를 줄입니다.

### 3. 💰 실시간 예산 합산 기능 (보조 기능)
- 사용자가 배치한 가구들의 가격을 실시간으로 합산하여 보여줍니다.
- 설정한 최대 예산을 초과할 경우 알림을 주어, 예산 범위 내에서 합리적인 가구 소비를 돕습니다.

---

## 🛠️ 기술 스택 (Tech Stack)

### Development
- **Language:** [예: Kotlin / Swift / JavaScript / Dart]
- **Framework:** [예: Android Studio / Flutter / React Native / Unity]
- **3D Graphics:** [예: WebGL / Three.js / SceneKit / Filament]

### Environment & Tools
- **Version Control:** Git, GitHub
- **UI Design:** [예: Figma]

---

## 📱 서비스 화면 (Screenshots)
| 3D 레이아웃 추천 | 크기 제한 알림 | 예산 실시간 합산 |
| :---: | :---: | :---: |
| <img src="https://via.placeholder.com/200x400?text=3D+Layout" width="200"> | <img src="https://via.placeholder.com/200x400?text=Size+Warning" width="200"> | <img src="https://via.placeholder.com/200x400?text=Budget+Calc" width="200"> |
| *[설명: 3D 배치 추천 화면]* | *[설명: 경고 팝업 화면]* | *[설명: 예산 내역 화면]* |

> 💡 **Tip:** `https://via.placeholder.com/...` 부분을 실제 앱 구동 캡처 이미지 경로(`img/screen1.png` 등)로 대체하세요.
