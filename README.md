# likelion_hackathon

# 멋쟁이사자처럼 해커톤

### 채팅 기능 구현

## ERD 다이어그램
![멋사11기 해커톤 erd](https://github.com/leegy21/likelion_hackathon/assets/102893824/55776434-5284-4a63-8d48-17937aeb1c09)

<br>
<br>
<br>

## 실행 화면

+ postman, MySQL Workbench, Docker(mysql) 사용
+ websocket-stomp는 postman에서 지원하지 않기 때문에 **apic** (구글확장프로그램)을 이용
+ webSocket-Stomp은 테스트 시 http://localhost:8080/ws-stomp 로 연결된다
+ 아래 사진은 왼쪽, 오른쪽 서버를 둘 다 켜서 각각 유저1, 유저2로 접속한 모습
+ 유저1이 채팅을 보내면 양쪽 서버에 뜬다

![멋사11기 해커톤 채팅](https://github.com/leegy21/likelion_hackathon/assets/102893824/ab636e9c-aa5b-4c0d-b37f-1da2290fbc7c)
