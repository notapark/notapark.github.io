---
title:  "Node.js 소개"
excerpt: "Node.js 기본 정리"

categories:
  - nodejs
tags:
  - nodejs
last_modified_at: 2019-11-08T01:07
---
```
git
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/notapark/testApp.git
git push -u origin master
```
1. 개요
- 구글 크롬 웹 브라우저에 탑재된 V8자바스크립트엔진 > 브라우저가 아닌 곳에서 사용 가능 하도록 만듬
- 이벤트 기반 비동기 처리 : 싱글스레드가 비동기로 처리 순서에 상관없이 처리 가능
- 장점 : 구글이 자바스크립트 엔진을 개선 할수록 더욱 빨리짐
- 단점 : app 실행에 문제가 생기면 전체 어플리케이션에 영향을 받음
- 활용 : ebay, linked in , electron 크로스 플랫폼 : atom, vscode, slack

2. 설치
https://nodejs.org/ko/

3. 기본 명령어
```
node
console.log('hello world');
```


```
function test() {
  console.log("notice the blank line before this fun  tion?");
}
```

```

app.set('port', process.env.PORT || 80);

var server = app.listen(app.get('port'), function() {
  console.log('서버가 ' + server.address().port + ' 포트에서 실행중!!!');
});
```
