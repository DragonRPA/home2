# DragonRPA Enterprise IR & DX Landing Page

기업 IR 컨설팅 및 엔터프라이즈 디지털 전환(DX)·RPA 자동화 솔루션 소개를 위한 고성능 반응형 랜딩 페이지입니다.

---

## 🚀 프로젝트 특징

- **초경량 & 빌드 무의존성**: 순수 HTML5, CSS3, Vanilla JavaScript로 구성되어 별도의 `npm install`이나 복잡한 빌드 과정 없이 즉시 배포 및 로컬 실행 가능
- **완벽한 반응형 디자인**: 모바일, 태블릿, 와이드 데스크톱까지 모든 기기 해상도에 최적화
- **인터랙티브 기능**:
  - 스크롤 연동 글래스모피즘(Glassmorphism) 헤더 및 스무스 스크롤 네비게이션
  - 모바일 슬라이드 드로어 메뉴
  - 반응형 상담 문의 팝업 모달 (키보드 ESC 및 백드롭 지원)
  - 뷰포트 진입 스크롤 트리거 애니메이션
  - 플로팅 상단 바로가기(Back to Top) 버튼
- **GitHub Pages 즉시 배포 지원**: GitHub Pages 루트 경로 및 상대 경로 최적화

---

## 🌐 GitHub Pages 배포 방법 (초간단 2단계)

### 방법 1: GitHub Settings에서 1분 만에 활성화하기 (가장 추천)

1. 이 저장소([DragonRPA/home2](https://github.com/DragonRPA/home2))로 이동합니다.
2. 상단 메뉴에서 **Settings** (설정) 탭을 클릭합니다.
3. 좌측 사이드바에서 **Pages** 메뉴를 선택합니다.
4. **Build and deployment** 섹션의:
   - **Source**: `Deploy from a branch` 선택
   - **Branch**: `main` 브랜치 선택, 폴더는 `/(root)` 선택 후 **Save** 클릭
5. 1~2분 후 상단에 표시되는 배포 주소(`https://dragonrpa.github.io/home2/`)로 접속하면 즉시 웹사이트가 라이브됩니다!

---

### 방법 2: GitHub Actions 자동 배포 (선택 사항)

- 저장소 내 `.github/workflows/pages.yml` 파일이 포함되어 있습니다.
- **Settings > Pages > Source**에서 `GitHub Actions`를 선택하시면, 코드가 푸시될 때마다 GitHub Actions가 자동으로 페이지를 빌드 및 배포합니다.

---

## 📁 디렉토리 구조

```
DragonRPA-home2/
├── .github/
│   └── workflows/
│       └── pages.yml     # GitHub Actions 배포 워크플로우
├── css/
│   └── style.css         # 반응형 스타일시트
├── js/
│   └── main.js           # 모달, 드로어 메뉴, 스크롤 인터랙션
├── index.html            # 메인 웹 페이지 마크업
└── README.md             # 프로젝트 안내 및 배포 가이드
```

---

## 💻 로컬 미리보기

- [index.html](file:///d:/01.AntiGravity/%EB%AA%A8%EB%B0%A9%ED%99%88%ED%8E%98%EC%9D%B4%EC%A7%80/index.html) 파일을 웹 브라우저(Chrome, Edge 등)로 직접 더블클릭하여 열거나, VS Code의 Live Server 확장을 통해 실시간으로 확인하실 수 있습니다.
