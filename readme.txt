# Scene-Spec (씬스펙)

> **영상·미디어 제작자를 위한 로케이션 환경 데이터 워크스페이스 & 공간 솔루션**

"가서 찍어보니 해가 넘어가고, 소음 때문에 대사 녹음이 안 된다?"  
촬영 전에 햇빛·소음·전기를 미리 확인하고 도면에 장비를 배치해보는 **스마트 로케이션 솔루션**입니다.

---

## 🚀 프로젝트 개요 (Overview)
기존의 공간 대관 앱들은 "사진만 예쁘고 촬영 환경 정보는 없다"는 치명적인 한계가 있습니다. **Scene-Spec**은 영상 제작진이 매번 현장에서 겪는 리스크(햇빛 위치 오류, 주변 소음, 전력 차단)를 사전에 완벽히 데이터로 검증하고 해결하기 위해 기획된 웹 대시보드 플랫폼입니다.

---

## ✨ 주요 기능 및 로드맵 (Key Features)

1. **환경 데이터 사전 검증 (Environment Data)**
   - 기상청 일조량 계산식 및 채광 피크타임(남서향 입사각 등) 분석
   - 주변 소음 데시벨(dB) 및 공사장·도로 소음 리스크 사전 진단
   - 전력 공급 용량(kW) 및 분전반 안정성 체크
2. **2D 도면 장비 배치 시뮬레이터 (2D Simulator)**
   - 드래그 앤 드롭(Drag & Drop) 방식으로 스튜디오 도면 위에 카메라, 조명, 녹음 장비 배치
   - 스태프 간 실시간 도면 공유 및 동선 최적화
3. **공간 원스톱 대관 & 인증 뱃지 (One-Stop Booking)**
   - 전력 및 소음 정밀 측정이 완료된 스튜디오 검색 및 안전 결제 연동
   - 환경 검증 인증 뱃지 시스템 부여
4. **장비 대여점 & 스태프 연계 (Partners & Crew)**
   - 인근 장비 렌탈샵(카메라, 조명, 지미집 등) 즉시 견적 연동
   - 전문 촬영 감독(DP) 및 조명 감독(Gaffer) 매칭 서비스

---

## 🛠️ 기술 스택 (Tech Stack)
- **Frontend / UI:** Single-file HTML5, Tailwind CSS (CDN), FontAwesome Icons, Vanilla JavaScript
- **Architecture:** Responsive SaaS Dashboard Design (Dark Theme Optimized)
- **Deployment:** GitHub Pages Ready (`index.html`)

---

## 📦 GitHub 배포 방법 (Deployment Guide)

본 프로젝트는 **단일 HTML 파일(`index.html`)** 구조로 제작되어 있어 GitHub에 즉시 배포할 수 있습니다.

1. 본 레포지토리에 `index.html` 파일을 루트 디렉토리에 업로드합니다.
2. GitHub 레포지토리의 **Settings** 메뉴로 이동합니다.
3. 좌측 메뉴에서 **Pages**를 선택합니다.
4. **Build and deployment** 섹션의 **Branch**를 `main` (또는 `master`), `/ (root)`로 설정한 후 **Save**를 누릅니다.
5. 잠시 후 생성되는 GitHub Pages URL을 통해 웹 대시보드를 바로 확인할 수 있습니다!

---

## 💡 화면 구성 미리보기
- **대시보드 요약 (Dashboard):** 핵심 지표 및 4단계 로드맵 인터페이스
- **환경 데이터 검증:** 스튜디오별 채광/소음/전력 시뮬레이션
- **도면 시뮬레이터:** 인터랙티브 장비 배치 캔버스
- **공간 대관:** 검증된 스튜디오 카드 및 예약 시스템
- **장비·스태프 연계:** 제휴 렌탈샵 및 전문가 매칭 패널

---
© 2026 Scene-Spec Project. All rights reserved.