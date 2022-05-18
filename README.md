# Check-NaverBlog-Visited

📆 제작기간 : 2021.07.10 ~ 제작중

🔨 기능설명 : 방문그래프를 숨겨놓은 네이버 블로그 방문자수 확인기.

📌 특이사항

- 개발진행중

- 현재 방문자수 확인은 가능함. `console log 및 임시텍스트`

- LINK : https://chhs2131.github.io/Check-NaverBlog-Visited/

  <br/>
  <br/>

## 🔥 해야할일!

⬜ XMLHttpRequest에 대한 CORS 문제 해결 (서버없이 가능한지..?)

⬜ inputText 스타일시트 작성

⬜ Http Status값에 따른 예외 처리

✅ JS를 이용하여, input값을 통한 특정페이지 이동로직 작성

✅ JS를 이용하여, 특정페이지 파싱 작성 (xml2json libray 이용)

✅ JS를 이용하여, 파싱한 값을 html 내부에 불러오기

⬜ BootStrap Graph를 이용하여 방문자 그래프 표시하기

⬜ 추후 Chrome 확장프로그램으로 개발 가능

<br/>

<br/>

## 🐞 오류

ajax CORS 오류

```javascript
Access to XMLHttpRequest at 'https://blog.naver.com/NVisitorgp4Ajax.nhn?blogId=ID' from origin 'https://--' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource.

Failed to load resource: net::ERR_FAILED
```



