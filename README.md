#  스마트 주차장 시스템

##  개요 (Overview)

본 프로젝트는 초음파 센서 및 조도 센서를 활용하여 **자동 차량 감지 및 주차 공간 확인이 가능한 스마트 주차 시스템**입니다.  
차량 입출입을 카운팅하고, 만차 여부를 감지하여 LED로 안내하며, LCD를 통해 실시간 정보를 표시합니다.

##  사용한 기술 및 부품

- Arduino Uno
- 초음파 센서 (Ultrasonic Sensor)
- 조도 센서 (LDR)
- 서보모터 (차단기 역할)
- LCD (16x2)
- LED (적색: 만차 표시)

##  주요 기능

- 차량 입출입 자동 감지 및 카운팅
- 주차 공간 내 차량 유무 감지 (조도 센서 기반)
- 만차 시 LED 경고등 점등
- 실시간 정보 LCD 출력
- 서보모터로 차단봉 제어

- ##  실행 방법

1. Arduino에 센서 및 모터, LCD 연결
2. 코드 업로드
3. 차량 출입 및 주차 상황에 따라 자동 제어 및 상태 표시

##  제작자

- **안예지 (Yeji Ahn)**  
  Embedded Systems, Tech University of Korea  
  Email: yejilove9001@naver.com  
  GitHub: [yejilove9001](https://github.com/yejilove9001)
