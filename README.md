# Adsense Media Site

검색 의도 기반 애드센스 정보형 정적 사이트입니다.

## 구성

- `index.html`: 메인 페이지
- `articles/`: 검색 의도형 샘플 글
- `pages/`: 소개, 개인정보처리방침, 문의
- `assets/css/style.css`: 전체 디자인
- `assets/js/app.js`: 모바일 메뉴, 키워드 점수 계산기
- `sitemap.xml`, `robots.txt`: 검색엔진 기본 설정
- `.github/workflows/pages.yml`: GitHub Pages 배포 워크플로
- `vercel.json`: Vercel 배포 설정

## 배포 전 수정

`robots.txt`와 `sitemap.xml`의 `https://example.com`을 실제 도메인으로 교체하세요.

## 로컬 확인

```bash
npm install
npm run check
npm start
```

## GitHub 업로드

```bash
git init
git add .
git commit -m "Initial adsense media site"
git branch -M main
git remote add origin https://github.com/<OWNER>/<REPO>.git
git push -u origin main
```
