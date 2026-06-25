# 말랑(Malang) - AI 기반 상황별 소통 학습 서비스 반응형 랜딩페이지

AI와의 대화를 통해 다양한 상황별 커뮤니케이션을 연습하고, 어려운 비즈니스 표현을 쉬운 표현으로 해석해 주는 에듀테크 서비스 **말랑(Malang)**의 반응형 랜딩페이지입니다.

## 🛠️ 기술 스택 및 개발 규칙

- **구조**: HTML5 (시맨틱 마크업 준수)
- **스타일**: CSS3 (Vanilla CSS, CSS Custom Variables, Flexbox, Grid Layout)
- **외부 라이브러리 미사용**: JavaScript, Tailwind CSS, Bootstrap, 외부 UI 라이브러리를 일절 사용하지 않고 순수 HTML/CSS로만 구현되었습니다.
- **클래스 네이밍**: BEM(Block-Element-Modifier) 컨벤션을 기반으로 한 유지보수성이 뛰어난 구조 설계.

## 📁 프로젝트 구조

```text
/
├── index.html
├── css/
│     └── style.css
│
├── images/
│     ├── logo.svg
│     ├── hero.svg (일러스트레이션)
│     ├── mascot.svg (캐릭터 마스코트)
│     └── icons/
│           ├── ai.svg
│           ├── translation.svg
│           ├── recommend.svg
│           ├── quiz.svg
│           ├── meeting.svg
│           ├── boss.svg
│           ├── customer.svg
│           ├── interview.svg
│           ├── school.svg
│           └── conflict.svg
│
└── README.md
```

## 🎨 디자인 시스템 적용 사항

- **Primary Color**: `#86D5C3` (Mint) / **Hover**: `#5BBEA6`
- **Secondary Color**: `#EAF9F5` (Soft background)
- **Background Color**: `#F8FFFD`
- **Border**: `#E5E7EB`
- **Typography**: Pretendard Font 패밀리 연동
- **Radius**: `20px` 공통 적용
- **Shadow**: `0 12px 40px rgba(0,0,0,.08)` 부드러운 그림자 효과
