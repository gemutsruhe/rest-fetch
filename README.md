# 프로젝트명 : RestFetch

## 개요
  자율주행 로봇을 활용하여 침대 밑의 물건을 찾아주는 로봇 서비스

## 기능
1. Observer
  - 침대 밑을 지속적으로 촬영하여 떨어진 물체 전송
2. Fetcher
  -  자율주행 기반 물건 회수
3. App
  -  떨어진 물건 확인, 회수 명령
  -  Fetcher, Observer 관리
4. Server
  -  떨어진 물체 식별 (미구현)
  -  SSE 활용 실시간 데이터 전송

## 개발 환경
  -  Front : Android(Kotlin, Compose)
  -  Back : Spring Boot, Spring Security, MySQL, Redis
  -  Embedded : ESP32-CAMN, STM32, ESP8266
  -  Design: Figma

### App
##### Mockup
<div>
 <img src="https://github.com/user-attachments/assets/7a54b693-c745-4514-b6a5-d6009bcf652f" alt="App1" width="180px">
 <img src="https://github.com/user-attachments/assets/1721191c-f7e6-4305-9837-cb7a4287a5a3" alt="App2" width="180px">
 <img src="https://github.com/user-attachments/assets/9ee8c76b-ce7f-4775-8876-931629bed672" alt="App3" width="180px">
 <img src="https://github.com/user-attachments/assets/28bd4d30-de46-4b72-bf3c-1a1fea1de507" alt="App4" width="180px">
 <img src="https://github.com/user-attachments/assets/e1b0c2d2-35fa-47ec-abea-d1de24d8eee5" alt="App5" width="180px">
</div>


## Architecture
![image](https://github.com/user-attachments/assets/3d1aa652-992d-46ae-8ee5-6f1e00aa1c8d)
