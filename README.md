# 한빛사회적협동조합 요청서 페이지

업로드 파일
- index.html
- thanks.html
- .nojekyll

## 꼭 수정할 부분
index.html 안에서 아래 값을 바꿔야 폼 제출이 실제로 작동합니다.

1. Formspree 폼 ID
<form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">

2. 완료 페이지 주소
현재는 아래 주소로 설정되어 있습니다.
https://wanghyun.github.io/hanbit-request-form/thanks.html

## GitHub Pages 설정
- Settings
- Pages
- Source: Deploy from a branch
- Branch: main
- Folder: /root
