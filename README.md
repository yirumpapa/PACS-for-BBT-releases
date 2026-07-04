# PACS for BBT — DICOM Viewer for Bronchial Branch Tracing

> 🇰🇷 한국어 안내는 아래에 있습니다.

**PACS for BBT** is a free chest-CT viewer built for practicing **Bronchial Branch Tracing (BBT)** — drawing bronchial branch diagrams for bronchoscopy planning. It works with chest-CT **DICOM files** (load a DICOM series folder to get started).

### ⬇️ Download

[![Download for Windows](https://img.shields.io/github/v/release/yirumpapa/PACS-for-BBT-releases?style=for-the-badge&label=Download%20for%20Windows&color=2f81f7)](https://github.com/yirumpapa/PACS-for-BBT-releases/releases/latest)

**→ [Download the latest version](https://github.com/yirumpapa/PACS-for-BBT-releases/releases/latest)** — grab `PACS-for-BBT.exe`, no installation, just run it. (Windows 10/11, 64-bit)
This link always serves the newest version, so it never changes.

> ⚠️ On first run, Windows SmartScreen may warn about an unknown publisher. Click **More info → Run anyway**.

> [!IMPORTANT]
> **Load AXIAL-plane DICOM data only.** Put a single axial series in the folder — the coronal and sagittal views are reconstructed automatically from it. If axial, coronal, and sagittal series are mixed in one folder, loading will fail or produce a corrupted volume.

![PACS for BBT screenshot](images/screenshot-main.png)

*Tracing an airway with dots connected into a smooth 3D curve (green), and viewing the CT cross-section perpendicular to it. The four edges are color-coded (top red, right yellow, bottom cyan, left violet) — and the cutting-plane rectangle in the Axial/Coronal/Sagittal views uses the same colors, so you can instantly read how the section is oriented in 3D. Orientation labels (e.g. Left-Superior) update live as you scroll.*

### Key features
- **Three synchronized planes** (Axial / Coronal / Sagittal) with distance measurement, 3D sphere/ellipsoid annotation, and per-plane window presets (Lung / Bone / Soft)
- **Airway tracing** — use the Dots tool to place dots along a bronchus, then connect them into a smooth 3D curve
- **Perpendicular cross-sections** — view CT sections perpendicular to the traced airway; the cutting plane follows the curve, and the main views show where it cuts
- **Color-coded orientation** — the four edges of the section and the matching cutting-plane rectangle are color-coded, so you can instantly tell how the section is oriented in 3D
- **Worklist** for switching between multiple studies, with per-study annotations
- Built-in user manual (English / Korean) with PDF export

### 🆕 What's new
- **v1.2.0** — ⭐ **Color-coded cross-section orientation**: the four edges of the section and the matching cutting-plane rectangle in the main views share the same colors, so you can instantly tell how the section is oriented in 3D. Also: a new **Dots tool** (selectable sizes + a preview at the cursor tip), **right-click drag = Window/Level**, and "Clear All" now fully resets.
- **v1.1.0** — **Airway tracing**: place dots along a bronchus → connect them into a smooth 3D curve → open the **perpendicular cross-section viewer** (scroll along the curve, live orientation labels, sync to the Axial/Coronal/Sagittal views). Plus the worklist and the built-in user manual (EN/KO).

*Full details on the [Releases page](https://github.com/yirumpapa/PACS-for-BBT-releases/releases).*

### ⚠️ Disclaimer
**For educational & training use only.** This software is NOT an approved or certified medical device (including SaMD) and has not been cleared by any regulatory authority (FDA / CE / MFDS). It must NOT be used for clinical diagnosis, treatment, or patient care.

---

# 🇰🇷 한국어

**PACS for BBT**는 기관지내시경을 위한 **기관지 가지 추적(BBT) 다이어그램 그리기 연습**용 무료 흉부 CT 뷰어입니다. 흉부 CT **DICOM 파일**을 사용합니다 (DICOM 시리즈 폴더를 불러와서 시작).

### ⬇️ 다운로드

[![Download for Windows](https://img.shields.io/github/v/release/yirumpapa/PACS-for-BBT-releases?style=for-the-badge&label=Download%20for%20Windows&color=2f81f7)](https://github.com/yirumpapa/PACS-for-BBT-releases/releases/latest)

**→ [최신 버전 다운로드](https://github.com/yirumpapa/PACS-for-BBT-releases/releases/latest)** — `PACS-for-BBT.exe`를 받아 바로 실행하면 됩니다. 설치 불필요. (Windows 10/11, 64비트)
이 링크는 항상 최신 버전을 제공하므로 주소가 바뀌지 않습니다.

> ⚠️ 처음 실행 시 Windows SmartScreen 경고가 뜰 수 있습니다. **추가 정보 → 실행**을 누르세요.

> [!IMPORTANT]
> **AXIAL(축상면) DICOM 데이터만 넣어야 합니다.** 폴더에 axial 시리즈 하나만 넣으세요 — coronal/sagittal 은 axial 로부터 자동으로 생성됩니다. 한 폴더에 axial·coronal·sagittal 시리즈가 섞여 있으면 로딩이 실패하거나 영상이 깨집니다.

![PACS for BBT 스크린샷](images/screenshot-main.png)

*기관지를 따라 점을 찍어 부드러운 3D 곡선(초록)으로 연결하고, 그 곡선에 수직인 CT 단면을 보는 모습. 네 변이 색으로 구분되고(위 빨강, 오른쪽 노랑, 아래 시안, 왼쪽 보라), Axial/Coronal/Sagittal 화면의 절단면 사각형도 같은 색을 써서 단면이 3D에서 어느 방향인지 바로 읽힙니다. 방향 라벨(예: Left-Superior)은 스크롤에 따라 실시간 갱신됩니다.*

### 주요 기능
- **3평면 동시 보기** (Axial / Coronal / Sagittal) — 거리 측정, 3D 구/타원 주석, 평면별 창 프리셋(Lung / Bone / Soft)
- **기관지 추적** — Dots 도구로 기관지를 따라 점을 찍고 부드러운 3D 곡선으로 연결
- **수직 단면 보기** — 추적한 기관지에 수직인 CT 단면을 곡선을 따라가며 확인, 메인 화면에 절단면 위치 표시
- **색으로 구분되는 방향** — 단면의 네 변과 절단면 사각형이 같은 색으로 구분되어, 단면이 3D에서 어느 방향인지 한눈에 파악
- **워크리스트** — 여러 스터디 전환, 스터디별 주석 저장
- 내장 사용 설명서 (한국어/영어, PDF 저장 가능)

### 🆕 변경 내역
- **v1.2.0** — ⭐ **색으로 구분되는 단면 방향**: 단면의 네 변과 메인 뷰의 절단면 사각형이 같은 색을 써서, 단면이 3D에서 어느 방향인지 한눈에 파악됩니다. 그 외: 새 **Dots 도구**(크기 선택 + 커서 팁 미리보기), **우클릭 드래그 = Window/Level**, "Clear All" 완전 초기화.
- **v1.1.0** — **기관지 추적**: 기관지를 따라 점 찍기 → 부드러운 3D 곡선으로 연결 → **수직 단면 뷰어**(곡선 따라 스크롤, 실시간 방향 라벨, Axial/Coronal/Sagittal 연동). 워크리스트, 내장 사용 설명서(한/영) 포함.

*자세한 내용은 [릴리스 페이지](https://github.com/yirumpapa/PACS-for-BBT-releases/releases)에서 볼 수 있습니다.*

### ⚠️ 주의
**교육·훈련 전용입니다.** 승인·인증된 의료기기가 아니며(SaMD 포함), 어떤 규제기관(FDA/CE/MFDS)의 허가도 받지 않았습니다. 임상 진단·치료·환자 진료에 사용할 수 없습니다.
