# KickSquad

# 🚴🏻‍YOLOv5를 활용한 실시간 전동킥보드 운전자 모니터링 및 주차 인식 서비스

<img src = "https://user-images.githubusercontent.com/105634994/186194963-ce5b364a-406b-4519-8ccb-fc4dabbd55fd.png" width="10%" height="10%">

*'KickSquad🚴' is a  detection system.*



# 시연연상

https://youtu.be/3cgrlUfnrHA



 ## 01. 프로젝트 소개
 - 최근 퍼스널 모빌리티 주행과 관련된 문제가 증가함에 따라 공유 전동킥보드 이용 시 안전운전에 대한 필요성이 중요하게 되었다. <br> 이에 본 서비스는 공유 전동킥보드 운전자의 주행 영상을 분석하여 운전자 주의의무(헬멧 착용 및 동반 탑승 여부)를 수행할 수 있도록 도움을 주고자 한다.


## 02. 프로젝트 특장점
- 기존 스마트 관제 시스템들은 CCTV를 통해 정해진 구역만 감지했지만 본 서비스는 주행 시작부터 종료까지 사용자의 헬멧 착용 및 동반탑승을 파악할 수 있음.
 - 공유 전동킥보드 실시간 카메라를 이용하여 이용자가 직접 자신의 주행 영상을 확인할 수 있음에 따라 안전운전에 대한 인식을 높임.
 - 실시간 전동킥보드 운전자 모니터링 기능을 사용하여 헬멧 착용과 동반탑승을 감지하여 사용자가 규칙을 잘 지켰을 때 포인트 별 순위를 보여줌으로써 사용자의 적극적 참여 유도.
 
## 03. 프로젝트 개발 내용
데이터 수집
 - Roboflow의 Hard hat workers dataset
 - 헬멧, 얼굴 및 전동킥보드 사진 구글 이미지에서 크롤링
 - 헬멧 착용/미착용 안면 및 전동킥보드 사진 직접 촬영
 
데이터 전처리
 - Roboflow를 통한 Helmet, Head와 Scooter 라벨링
 - Roboflow를 통한 이미지 회전 및 gray-scale 기능을 이용한 데이터 증강

웹 구축 및 기능 구현
 - Spring을 활용하여 웹 서비스와 DB 연동
 - 지도 API를 통한 전동 킥보드 위치 시각화
 - HTML, CSS, Swiper를 활용한 웹 사이트 구축 및 동적 페이지 구성
 - Javascript, jQuery를 통한 비동기 방식으로 웹 애플리케이션 구현
 
 ![KakaoTalk_20221124_120448943](https://user-images.githubusercontent.com/105634994/203686098-9f67a117-ff05-4715-9271-f2a67666c1d8.png)
 ![KakaoTalk_20221124_120503025](https://user-images.githubusercontent.com/105634994/203686209-42b05542-e942-48d5-b78a-c105519580d3.png)
 ![KakaoTalk_20221124_120513683](https://user-images.githubusercontent.com/105634994/203686239-5edcf5a1-35d6-4ec3-a075-82b3ec0ede7c.png)
 ![KakaoTalk_20221124_120525139](https://user-images.githubusercontent.com/105634994/203686255-fe32497d-6264-4a27-9604-4febc480c5f5.png)
 ![KakaoTalk_20221124_120533431](https://user-images.githubusercontent.com/105634994/203686330-5ce84fb5-048e-4be3-8cb5-00faedacbe49.png)
 ![KakaoTalk_20221124_120541317](https://user-images.githubusercontent.com/105634994/203686345-bfa294c9-09ea-47ab-9957-6532a554743b.png)
 ![KakaoTalk_20221124_120546777](https://user-images.githubusercontent.com/105634994/203686364-f2fba37a-2bb7-4e37-a452-d1855edf8d4f.png)
 ![KakaoTalk_20221124_120555654](https://user-images.githubusercontent.com/105634994/203686391-d2b2be7e-84bb-47ad-81ea-e0e046a224ae.png)
 ![KakaoTalk_20221124_120838987](https://user-images.githubusercontent.com/105634994/203686407-dc9d8019-38b7-4a2a-978d-08758d27549c.png)


 
 
 ## ⚡TEAM⚡
   
    😋 Junyoung Park(Team Leader) : https://github.com/
    
    🕵🏼‍♀️ Chulwoong Choi(Team Member) : 
    
    🙈 Yurim Kim(Team Member) : 
  
    👩🏻‍🚀 Taemin Noh(Team Member) : 
    
    😎 Hyunwoo Choi(Team Member) : 
    
    
    


## 🏊🏼‍♂️Tech Stack
### *Version Control*
    Github

### *Frontend*
    Web Page : Html, CSS, JS, jQuery
    Web Server : Tomcat, flask

### *Backend*
    Framework : Spring

### *DB*
    MySQL
 

## Postion

- UI&IX 설계
- Ajax 을 이용한 비동기 페이지 구현




## ❤System Architecture❤


## 🛴DEMO


## 📌Web-Site
