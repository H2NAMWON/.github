# :rocket: SSAFY 12th BackEnd 관통 프로젝트

<img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"> <img src="https://img.shields.io/badge/node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white"> 
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white"/>
<img src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/>

# 1\. 프로젝트 소개

## 프로젝트 명 : BaroMap (바로 지도)

- **목적**: 배리어 프리 ([장애인](https://namu.wiki/w/%EC%9E%A5%EC%95%A0%EC%9D%B8) 및 [노인](https://namu.wiki/w/%EB%85%B8%EC%9D%B8) 등 [사회적 약자](https://namu.wiki/w/%EC%82%AC%ED%9A%8C%EC%A0%81%20%EC%95%BD%EC%9E%90)들이 편하게 살아갈 수 있게 물리적인 장애물, 심리적인 벽 등을 제거)한 관광지 제공
- **대상 사용자**:
  - **주요 타겟**: 40~60대 사용자들이 친구들 혹은 더 연장자와 함께 여행을 계획하는 사용자.
  - **일반 타겟**: 여행을 계획하거나 새로운 여행지를 찾는 모든 연령층의 사용자.
- **사용 기술**: Spring Boot, Vue.js, MySQL, 관광지 API, GPT API.

[Notion 링크](https://www.notion.so/Team-Project-Template-137d455a8a558032b911d7d2ea22941b)

## 개발자

| 팀장   | 팀원   |
| ------ | ------ |
| 하지원 | 한승남 |

# 2\. 주요 기능 소개

## A. 메인 페이지: AI 기반 여행 코스 추천

- **맞춤형 검색 및 필터 기능**
    - 장애 유형(예: 휠체어 접근성, 청각 장애 지원 등)에 따라 여행지를 검색하고 필터링할 수 있는 기능.
- **지역 기반 맞춤형 코스 제공**
    - 사용자가 검색한 지역 정보를 바탕으로 GPT API를 활용하여 맞춤형 여행 코스를 제공합니다.
- **지도 위 루트 표시**
    - 추천된 여행 코스를 지도에 시각화하여 이동 경로와 소요 시간을 한눈에 확인할 수 있습니다.
- **코스 상세 정보**
    - 각 관광지의 상세 정보, 운영 시간, 연락처 등을 제공합니다.

## B. 교통약자를 위한 편의 기능 제공

- **접근성 정보 제공**
    - 휠체어 이용이 가능한 경로와 시설 정보를 제공합니다.
    - 교통약자를 위한 편의 시설이 있는 관광지와 숙박 시설을 추천합니다.
    - 대여소 위치와 가장 가까운 주차장과

## C. 지역별 특산물 및 명소 추천

- **데이터베이스 기반 특산물 정보 제공**
    - 지역별로 등록된 특산물과 명소 정보를 제공합니다.
    - 해당 지역에서 꼭 가봐야 할 곳들과 인기 키워드를 제공합니다.
 
# 3\. 프로젝트 구성

## 1. 아키텍처

![image](https://github.com/user-attachments/assets/dfedb6a7-c709-466b-88da-e63602fee7cc)

## 2. ERD

![image](https://github.com/user-attachments/assets/6068a04f-06c5-45cb-b1ac-354e35af06aa)

## 3. FlowChart

![image](https://github.com/user-attachments/assets/dc05529e-f783-4c69-8fd4-8daa5c1c9b03)

## 4. Gantt Chart

![image](https://github.com/user-attachments/assets/aad1ca39-efcd-4f18-8ef3-7377ab201bf0)






