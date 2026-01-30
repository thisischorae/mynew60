[README.md](https://github.com/user-attachments/files/24957471/README.md)
# 조금 다른, 나의 환갑 - 랜딩페이지

66년생 말띠를 위한 특별한 환갑 책 랜딩페이지입니다.

## 📖 소개

"조금 다른, 나의 환갑"은 60년을 누군가의 엄마, 누군가의 아내로 살아온 분들을 위한 책입니다.
이제는 '나'로 살아갈 시간, 인생 2막을 시작하는 초대장입니다.

## 🎨 디자인 특징

- 책 표지의 생동감 있는 컬러(오렌지, 청록, 보라) 반영
- 완벽한 모바일 최적화 (반응형 디자인)
- 부드러운 스크롤 애니메이션
- 명확한 CTA (Call-to-Action) 버튼

## 🚀 배포 방법

### GitHub Pages로 배포하기

1. 이 repository를 fork 하거나 다운로드
2. GitHub에 새 repository 생성
3. 파일 업로드:
   - `mynew60.html`
   - `book_cover.jpg`
4. Settings → Pages → Source를 'main' 브랜치로 설정
5. 배포 완료! `https://[username].github.io/[repo-name]/mynew60.html`

### 커스텀 도메인 설정 (선택사항)

1. 도메인 구매 (예: mynew60.com)
2. DNS 설정에서 GitHub Pages IP 추가
3. GitHub repository Settings → Pages → Custom domain 입력
4. CNAME 파일 추가

## 📱 파일 구조

```
.
├── mynew60.html          # 메인 랜딩페이지
├── book_cover.jpg        # 책 표지 이미지
└── README.md            # 이 파일
```

## 🔧 커스터마이징

### 구매 링크 변경
`mynew60.html` 파일에서 다음 URL을 찾아 수정:
```html
href="https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=369888253..."
```

### 색상 변경
CSS에서 주요 색상:
- 오렌지: `#FF6B35`, `#FF8C42`
- 청록: `#5BCEFA`
- 보라: `#9370DB`, `#7B68EE`

### 이미지 교체
`book_cover.jpg`를 같은 이름의 다른 이미지로 교체

## 📊 성능 최적화

- ✅ Google Fonts preconnect
- ✅ 반응형 이미지 (clamp 사용)
- ✅ CSS 애니메이션 (GPU 가속)
- ✅ Lazy loading 애니메이션
- ✅ SEO 메타태그
- ✅ Open Graph 태그 (SNS 공유)

## 🎯 타겟 독자

- 66년생 말띠 (2026년 환갑)
- 50~60대 여성
- 인생 2막을 준비하는 분들

## 📈 Google Analytics 연동 (권장)

`mynew60.html`의 `<head>` 태그 안에 추가:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🛠️ 기술 스택

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript
- Google Fonts (Noto Sans KR)

## 📞 지원

문의사항이 있으시면 이슈를 등록해주세요.

## 📄 라이선스

이 프로젝트는 개인 사용 목적으로 제작되었습니다.

---

**🎉 "조금 다른, 나의 환갑"으로 새로운 시작을 응원합니다!**
