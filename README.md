# 독일 여행 독일어 학습 플랫폼

6월 29일부터 7월 9일까지의 독일 및 스위스 로드 트립을 위한 실용적인 독일어 회화 학습 웹사이트입니다.

## 🌟 주요 기능

- **9개 카테고리**: 공항, 렌터카, 숙소, 식당, 길 찾기, 쇼핑, 국경 통과, 긴급 상황, 기본 표현
- **52개 필수 표현**: 여행 상황별 실용적인 독일어 회화
- **플립 카드 학습**: 한국어와 독일어를 번갈아 보며 학습
- **발음 학습**: 브라우저 TTS를 활용한 원어민 발음 듣기
- **퀴즈 기능**: 배운 표현을 퀴즈로 복습하고 실력 확인
- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모두 지원

## 🎨 디자인 철학

따뜻한 교육적 디자인으로 언어 학습의 불안감을 줄이고 긍정적인 학습 경험을 제공합니다.

- **색상**: 코랄(Coral), 소프트 틸(Teal), 골든 옐로우(Golden Yellow)
- **타이포그래피**: Fredoka(헤딩) + Open Sans(본문)
- **상호작용**: 부드러운 애니메이션과 직관적인 UI

## 🚀 GitHub Pages에서 배포하기

### 1단계: 저장소 생성
GitHub에서 새로운 저장소를 생성합니다. 저장소 이름은 `{username}.github.io` 또는 원하는 이름으로 설정할 수 있습니다.

### 2단계: 파일 업로드
이 폴더의 모든 파일을 저장소에 업로드합니다.

```bash
git init
git add .
git commit -m "Initial commit: German conversation learning platform"
git branch -M main
git remote add origin https://github.com/{username}/{repository}.git
git push -u origin main
```

### 3단계: GitHub Pages 설정
1. 저장소의 Settings로 이동
2. Pages 섹션에서 Branch를 `main`으로 설정
3. 저장소 루트를 Source로 선택
4. Save 클릭

### 4단계: 배포 완료
몇 분 후 `https://{username}.github.io/{repository}` 또는 `https://{username}.github.io`에서 사이트에 접근할 수 있습니다.

## 📁 파일 구조

```
.
├── index.html           # 메인 HTML 파일
├── assets/              # CSS, JavaScript 번들
│   ├── index-*.css
│   └── index-*.js
├── __manus__/           # 분석 도구 (선택사항)
└── README.md            # 이 파일
```

## 🛠️ 기술 스택

- **Frontend**: React 19 + Tailwind CSS 4
- **라우팅**: Wouter
- **UI 컴포넌트**: shadcn/ui
- **음성 합성**: Web Speech API (TTS)
- **번들러**: Vite

## 💡 학습 팁

1. **카드 학습**: 각 카드를 클릭하여 한국어와 독일어를 번갈아 보세요
2. **발음 연습**: 독일어 카드의 "발음 듣기" 버튼으로 원어민 발음을 들어보세요
3. **반복 학습**: 같은 표현을 여러 번 반복해서 읽고 말해보세요
4. **퀴즈 복습**: 각 카테고리의 퀴즈로 학습한 내용을 확인하세요

## 📱 지원 기기

- 데스크톱 (Chrome, Firefox, Safari, Edge)
- 태블릿 (iPad, Android)
- 모바일 (iPhone, Android)

## 🎯 여행 일정

- **기간**: 2026년 6월 29일 ~ 7월 9일
- **경로**: Frankfurt → Bad Kissingen → Leipzig → Baden-Baden → La Chaux-de-Fonds → Heidelberg → Frankfurt
- **총 거리**: 약 2,000km
- **여행자**: 4명

## 📝 라이선스

MIT License

## 🙏 감사의 말

이 학습 플랫폼은 실제 여행 준비를 위해 만들어졌습니다. 즐거운 여행 되세요!

**Gute Reise! (좋은 여행 되세요!)**
