# PC ROOM

# 주요기능
- Admin<br> 
컴퓨터 고장시 상태제한, 회원관리(조회, 삭제, 수정), 채팅(웹소캣이용), 
제품(음식) 등록 및 수정, 삭제, 조회<br> 주문음식처리(주문완료 등 상태변경),
통계(일일, 월별, 연별 판매추이를 보여줌)</br> 
- Kiosk <br> 
결제기능, 좌석 선택시 해당좌석을 다른 사람이 이용하지 못하게 제한함.<br> 
화면에 현재 이용하고 있는 Client를 보여주며 시간이 감소하는 모습을 띄움. </br>  
- Client <br> 
로그아웃, 로그인, 자리이동, 일시정지(자리이동 및 일시정지는 멀티스레드를 사용하여 구현), 음식 주문, 채팅(웹소캣이용) 기능 구현 <br> 
PC방에서 이용하는 순서에 맞게 프로그램을 개발하였으며, 3가지 프로젝트를 만들어 해당 기능을 구현하였음.</br> 

# 시연영상
- "pc방 동영상.mp4"로 파일첨부


## 1. 개요
### 1.1. 목적
- 피시방 이용자 및 관리자의 편의성 증진

### 1.2. 프로그램 사용자
- 피시방 이용자 (손님)
- 피시방 관리자 (피시방 대표, 아르바이트생)

## 2. 개발 일정
- 기간 : 2021.11.05 ~ 2021.11.10  
- History

|날짜|내용|
|----|----|
|2021.11.05|주제 선정 <br>화면 구성 및 화면 구조도 작성<br>Front 초안 제작(Scenebuilder)</br>Logo 제작 및 논의<br>controller 구조도 제작</br>|
|2021.11.06|Database 설계 <br> Scenebuilder 화면전환 구현</br>|
|2021.11.07|Kiosk 기능구현|
|2021.11.08|Admin 기능구현|
|2021.11.09|Client 기능구현|
|2021.11.10|최종점검|

  
## 3. 개발 환경
- 운영체제 : Windows10  
- Teck Stack : Java, Javafx, My-sql,Tomcat, Eclipse, SceneBuilder, Git  

## 4. 화면 설계도  
![화면 구성도](https://user-images.githubusercontent.com/87436495/142762712-17313b47-4608-425c-9294-7437abf2d847.PNG)

## 5. Controller 구조도  
### 5.1. Project : Kiosk  
![kiosk](https://user-images.githubusercontent.com/87436495/142762315-4e65330e-3ecb-44f2-a4cf-8633015ab73e.PNG)

### 5.2. Project : Admin  
![admin](https://user-images.githubusercontent.com/87436495/142762378-92cf73c5-05f9-44b3-9453-a6a155ac5840.PNG)

### 5.3. Project : Client  
![client](https://user-images.githubusercontent.com/87436495/142762387-c6fa9b56-8aa5-4e9d-b09e-cb1bcbbe68b7.PNG)

## 6. DB 구조도  
- Table : Total 7EA  
![211119_erd](https://user-images.githubusercontent.com/87436495/142559102-8652b249-c012-49e9-bef6-6fde86fbe444.png)
