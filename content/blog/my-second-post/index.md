---
title: My Second Post!
date: "2015-05-06T23:46:37.121Z"
---

Node.js is a javascript runtime built on chorme's V8 javascript engine.

프론트엔드에서는 web api 의 종류 어떤게 있는지, 어떻게 api를 사용하는게 좋은지,
브라우저 환경이 어떻게 동작하는지

노드 js의 환경의 api 는?
web api
node js api

노드의 큰 특징 4가지
javascript runtime
Single Thread
non-blocking I/O
Event-driven

전형적인 서버와 노드서버의 차이점

노드단점 cpu가 무거운일 이미지나 비디오 처리할떄

REPL

브라우저에서는 window 가 글로벌 객체
노드에서는 global 이 글로벌 객체

노드 js는 컴퓨터 위에서 작동하기에 파일 시스템에 접근하기 좋다

http https

서버에서 클라에게 보내주는 status codes

idempotent

http
stateless protocol
sessions cookies

Rest API

Cors

express 는 미들웨어의 연속이다 체인이다

프로미스에서 처리하지 않는 에러는 노드서버를 중지할수있다

async await, and promiss

비동기 에러처리 promiss 를 리턴하면서 async await 하거나
async await 해야함

복잡한 서버같은경우에 여러가지 경로가 존재하기때문에 app.js 에서
전부 다 나열하는것은 가독성이 좋지않고 유지보수 안좋고
모듈성 떨어짐
app 어떤거쓰는지 큰그림 보여주고 router 안에서 필요한것 처리

사용자 로그 남기기 morgan

express middleware?

helmet 보안

api 설계
