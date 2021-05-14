# Graduation-Project-2021-

## 과제 개요  
### 과제 명  
컨테이너 터미널 내 이송 차량의 미래 교통 상황을 고려한 최적 주행 경로 추천 시스템
  
### 과제 배경  
컨테이너 터미널 작업 상황에 따라 터미널 특정 구역에 내부 이송 차량이 몰려 고통 체증이 발생할 수 있다. 이를 고려해 교통 체증이 발생할 것으로 예상하는 구역을 피해 모든 내부 이송 차량이 최적 주행 경로를 찾아 컨테이너 터미널의 생산성을 향상하고자 한다.

## 과제 목표
본 졸업 과제의 시스템을 사용해 무인 자동차 내부 이송 차량을 주행 시켰을 때 내부 이송 차량의 작업 처리 속도 향상으로 전체 컨테이너 터미널 내부의 작업 효율 향상을 목표로 한다.

## 과제 설계
작업 할당된 차량이 목적지까지 가는 경로를 결정하기 위해 한 정점에서 모든 정점까지의 최단경로를 구하는 다익스트라 알고리즘을 사용한다.하지만 이 경로는 현재 도로의 교통 상황을 반영하지 못한다. 따라서 이 알고리즘으로 구성된 경로에 모델을 적용한다. 모델은 경로에 속한 링크의 속력을 예측해 미래 교통 상황을 고려한 최단 시간으로 갈 수 있는 경로를 찾는다. 

## 역할 분담  
```
공동 : Neural Network 스터디, 모델 개발, 보고서 및 발표 준비
박지영 : 시뮬레이터 코드 분석, 모델 평가, 설계 문서 작성
이소연 : 라우터 코드 분석, 안전성 및 성능 평가, 오류 수정 및 문제점 파악
```
