# Python과 OpenCV를 이용한 Drone Programming ✈︎

## 0. 실행 환경 세팅🛠
### 1) Python 설치
### 2) Pycharm 설치
Python 최신버전 설치 후 pycharm 최신버전 설치 -> pycharm 실행 후 새 프로젝트 만들기 -> venv 가상환경이 만들어졌다면 해당 파일들을 venv 파일로 옮기기

*파일 실행 전 pycharm에서 djitellopy, cvzone 패키지 설치하기*
### 3) 컴퓨터와 드론 연결
드론 전원을 키고 드론 불빛이 주황색으로 깜박거리면 노트북과 tello 와이파이와 연결, 이후 프로그램 실행하면 드론이 동작함.

## 1. 코드 설명
### 1) [Object Detection](https://github.com/GoalToUs/Drone-Programming/tree/main/Object%20Detection)
물체 인식을 위한 데이터로는 모델 구조와 가중치 값을 저장해둔 pb 파일을 사용한다. 이 데이터를 바탕으로 인식된 물체의 이름, 정확도를 드론으로 촬영하는 화면에 적용시킨다. 


### 2) [Face Tracking](https://github.com/GoalToUs/Drone-Programming/tree/main/Face%20Tracking)
