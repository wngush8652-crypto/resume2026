# 📑 resume2026

## 👤 About Me
> **"언제나 사용자의 시선에서 고민하고, 더 나은 화면과 흐름을 만들기 위해 치열하게 파고듭니다."**

안녕하세요! 사용자 경험(UX)을 가장 중요하게 여기며 주도적으로 성장하고 있는 프론트엔드 개발자 준비생 마주현입니다. 무엇이든 주도적으로 배우려는 태도를 바탕으로 끊임없이 파고들며 기술적 한계를 극복해 나가고 있습니다.

### 📍 관심사 & 취미
* **🌸 UX 중심 설계**: 단순 기능 구현을 넘어 직관적인 UI와 매끄러운 화면 흐름을 치열하게 고민합니다.
* **📺 주도적 문제 해결**: 비전공 특유의 끈기로 에러 로그 분석과 공식 문서를 파고들며 해결책을 찾아냅니다.

---

## 🔗 Links
* **GitHub Repository**: [wngush8652-crypto/resume2026](https://github.com)
* **Live Demo**: [이력서 웹사이트 보러가기](https://wngush8652-crypto.github.io/resume2026/)

---

## ⚒️ Tech Stack (배우고 있는 것)
* **Markup & Styling**: `HTML5`, `CSS3` (Flexbox, Media Queries)
* **Scripting & Framework**: `JavaScript (ES6+)`, `React`
* **Design & Tools**: Figma (Dev Mode), Canva, Chrome DevTools
* **Deployment**: GitHub Pages

---

##  Key Features
* **반응형 브레이크 포인트 완벽 준수**: Mobile(320px~), Tablet(768px~), Desktop(1024px~), Large(1280px~) 디바이스별 레이아웃 최적화
* **웹 접근성 및 표준 검증**: Chrome Lighthouse를 활용한 세부 요소 스타일링 및 가독성 보정
* **Figma 워크플로우**: Canva 디자인 PDF를 피그마 레이어로 변환 후 가이드라인에 맞춘 오차 없는 퍼블리싱

---

##  Directory Structure
```text
resume2026/
├── index.html          # 웹 표준 시맨틱 태그 기반 메인 마크업
├── style.css           # 반응형 미디어 쿼리가 포함된 메인 스타일
├── reset.css           # 브라우저 간 크로스 브라우징을 위한 초기화 CSS
├── profile.jpg         # 메인 프로필 이미지
└── dessert.jpg         # 프로젝트 포트폴리오 섹션 이미지
```

---

##  Troubleshooting
* **GitHub Pages 배포 후 404 에러 해결**
  * *문제*: 배포 후 CSS 및 이미지 리소스를 찾지 못해 레이아웃이 완전히 깨지는 현상 발생
  * *원인*: HTML 내 파일 연결 주소가 절대 경로(`/`)로 지정되어 발생
  * *해결*: 상대 경로(`./`) 표기법으로 전면 수정 및 파일명 대소문자 매칭을 통해 안정적인 라이브 서버 개시 완료
