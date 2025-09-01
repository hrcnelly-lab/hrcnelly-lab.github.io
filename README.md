# Gemini AI 여행 앨범 메이커

AI 기술을 활용하여 여행 사진을 자동으로 분석하고 아름다운 앨범을 만들어주는 웹 애플리케이션입니다.

## ✨ 주요 기능

- **AI 이미지 분석**: Gemini AI가 사진을 자동으로 분석하여 카테고리와 태그 생성
- **스마트 분류**: 음식, 풍경, 인물, 건축물, 야경 등으로 자동 분류
- **날짜별 정리**: EXIF 데이터를 활용한 촬영 날짜 자동 감지 및 그룹핑
- **반응형 디자인**: 모바일과 데스크톱 모두에서 최적화된 사용자 경험
- **실시간 편집**: 캡션과 카테고리를 실시간으로 수정 가능
- **앨범 내보내기**: HTML 형태로 완성된 앨범을 다운로드

## 🚀 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **AI Integration**: Google Gemini 2.5 Flash API
- **Image Processing**: EXIF.js
- **Data Storage**: IndexedDB (브라우저 로컬 저장소)
- **Responsive Design**: Mobile-first 접근법

## 📱 사용법

1. **사진 업로드**: 드래그 앤 드롭 또는 파일 선택으로 최대 60장까지 업로드
2. **AI 분석**: Gemini AI가 자동으로 사진을 분석하고 분류
3. **편집 및 정리**: 카테고리와 캡션을 필요에 따라 수정
4. **앨범 생성**: 완성된 여행 앨범을 HTML 파일로 내보내기

## 🌐 라이브 데모

[GitHub Pages에서 확인하기](https://jmisun-lab.github.io/my-prototype/)

## 📁 프로젝트 구조

```
my-prototype/
├── index.html          # 메인 애플리케이션 파일
├── README.md           # 프로젝트 설명서
└── .git/               # Git 저장소
```

## 🔧 설치 및 실행

1. 저장소 클론
```bash
git clone https://github.com/jmisun-lab/my-prototype.git
cd my-prototype
```

2. 로컬에서 실행
```bash
# Python 3 내장 서버 사용
python -m http.server 8000

# 또는 Node.js http-server 사용
npx http-server
```

3. 브라우저에서 `http://localhost:8000` 접속

## 📋 요구사항

- **브라우저**: Chrome, Firefox, Safari, Edge (최신 버전)
- **인터넷 연결**: Gemini AI API 호출을 위해 필요
- **JavaScript**: 활성화 필요
- **이미지 형식**: JPEG, PNG, GIF, WebP 등 지원

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 🙏 감사의 말

- [Google Gemini AI](https://ai.google.dev/) - 이미지 분석 API 제공
- [Tailwind CSS](https://tailwindcss.com/) - 스타일링 프레임워크
- [EXIF.js](https://github.com/exif-js/exif-js) - 이미지 메타데이터 추출

## 📞 문의

프로젝트에 대한 질문이나 제안사항이 있으시면 [Issues](https://github.com/jmisun-lab/my-prototype/issues)를 통해 연락해 주세요.

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
