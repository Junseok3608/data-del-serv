# (예비창업자를 위한 서울시 상권분석 서비스)

- 서울시에서 창업을 희망하는 예비창업자를 대상으로 한 서비스
- 창업에 앞서 필요한 상권분석 정보를 쉽고 간편하게 얻을 수 있는 서비스

## 프로젝트 구성 안내

- `예비창업자의 쉽고 간편한 정보 획득을 목표로 구성`

- `서울시 일반음식점 인허가 정보를 활용하여 검색, 지역, 업종, 상호 등 세부 조건에 따라 필요한 정보 제공 서비스`

## 1. 프로젝트 소개

**어떠한 데이터셋와 도구 및 기술을 사용했는지에 대한 설명과 엔드유저에게 보이는 웹서비스에 대한 소개**

- 사용하려는 데이터(제안된 데이터 중 하나 또는 선택한 다른 데이터 세트)를 명시, 이에 대한 설명
서울시 일반음식점 인허가 정보: https://data.seoul.go.kr/dataList/OA-16094/A/1/datasetView.do;jsessionid=F64EF0EE3383EA9A6CD3009A73448EB6.new_portal-svr-21
업종별(한식, 일식, 중식 등) 음식점 정보, 인허가정보, 영업코드,영업상태, 소재지, 지번주소, 도로명주소, 사업장명 등의 데이터 포함.

- 기술 스택 (python, d3, pandas, jupyter, javascript, MySQL 등)
python, MONGODB, javascript, SQL, DEVELOPER, 태블로
- 사용된 라이브러리 (numpy, matplotlib, wordcloud 등)

- 웹서비스에 대한 자세한 개요
예비창업자의 상권분석에 필요한 정보를 제공함.
정보를 제공함에 있어 복잡하지 않은 간편한 조작을 목표로 하며 서비스 이용자에게 가장 유의미하며 화급한 정보를 우선적으로 살펴볼 수 있게 함
(창업을 희망하는 지역에 경쟁 업체가 얼마나 되는지 여부, 창업을 희망하는 업종의 분포와 지역별 점포, 상호명의 중복 여부 등)
간편한 요약랭킹으로 지역별 음식점 랭킹 정보를 제공하여 창업을 위한 상권분석에 도움을 더함

## 2. 프로젝트 목표

**데이터 분석 결과로 도출되는 인사이트와 웹서비스의 해결과제에 대한 논의 (50자 이상)**

- 프로젝트 아이디어 동기
배달 시간, 배달 업종 등 데이터의 분석 방향 논의 과정에서 이용자를 중심으로 논의가 진행되며 프로젝트에 포함될 데이터 정보를 가장 필요로 하는 이용자로 '예비창업자'가 선정
'예비창업자'는 창업 전 상권분석이 필요하기 때문에 체크박스, 드롭다운, 선택자 방식 등으로 쉽고 간편하게 원하는 정보를 탐색할 수 있는 서비스 제공하고자 함

- 문제를 해결하기 위한 특정 질문 명시
(서울시)'예비창업자'가 창업을 목표로 정보를 탐색하고자 할 때 가장 화급을 다투는 정보는 무엇인가?
'예비창업자'가 부수적으로 알고 싶은 정보들은 어떠한 것들이 있는가?
'예비창업자'에게 유의미한 정보는 어떠한 것이 있는가?

- 데이터를 통해 탐색하려는 문제를 구체적으로 작성
서울 시 지역으로 구분하여 구별 동별 영업점의 분포 정보
업종별 분류를 통해 특정 업종이 많거나 적은 지역의 정보
상호명 검색을 통해 특정 업종 혹은 특정 지역에서의 상호명 정보
지역구별 랭킹 정보를 통해 지역별로 가장 많은 업종과 적은 업종의 정보
기타 지역, 업종, 상호를 통해 탐색 가능한 문제들

## 3. 프로젝트 기능 설명

**웹서비스의 유용성, 편의성 및 시각화의 실용성에 대한 설명**

- 주요 기능 (주된 활용성) 및 서브 기능
상황에 따른 예비창업자를 위한 상권분석정보 제공
특정 지역을 정한 예비창업자: 특정 지역 내에 어떤 업종이 가장 많거나 적은지 탐색 가능
특정 업종을 정한 예비창업자: 특정 업종이 유행하는 지역, 소외된 지역 탐색 가능
특정 상호명을 정한 예비창업자: 특정 상호명이 많은 지역, 업종 탐색 가능
특정 지역이나 업종을 정하지 않은 예비창업자: 특정 지역 내 업종 분포 높은 경우, 낮은 경우로 사업 방향

- 프로젝트만의 차별점, 기대 효과
예비창업자에게 쉽고 편하게 유의미한 정보 제공


## 4. 프로젝트 구성도

- 와이어프레임/스토리보드 추가
![n_storybo](/uploads/0e5336cd5259107847f7af4a67d86191/n_storybo.png)

## 5. 프로젝트 팀원 역할 분담

| 이름 | 담당 업무 |
| ------ | ------ |
| 국진호 | 팀장/데이터 분석 |
| 김준석 | 프론트엔드 개발 |
| 이무용 | 백엔드 개발 |


**멤버별 responsibility**

1. 팀장 & 데이터분석

- 기획 단계: 문제 해결 아이디어 도출, 데이터 분석으로 해결하고자 하는 문제 정의, 기획서 작성
- 개발 단계: 팀원간의 일정 등 조율 + 데이터 분석
- 수정 단계: 스크럼 진행, 코치님 피드백 반영해서 수정, 발표준비

2. 프론트엔드

- 기획 단계: 큰 주제에서 문제 해결 아이디어 도출, 와이어프레임 작성
- 개발 단계: 와이어프레임을 기반으로 구현, UI 디자인 완성
- 수정 단계: 피드백 반영해서 프론트 디자인 수정, 발표준비

 3. 백엔드

- 기획 단계: 데이터 분석을 통해 해결하고자 하는 문제를 정의
- 개발 단계: 웹 서버 사용자가 직접 백엔드에 저장할수 있는 기능 구현, 데이터 베이스 구축 및 API 활용, 데이터 분석 개념 총동원하기
- 수정 단계: 코치님 피드백 반영해서 분석/ 시각화 방식 수정

## 6. 버전

- 프로젝트의 버전 기입
7b46931edf00507010637fdaf3cf3343c04a4d7c: 초기
bec4db7674e8df744360a46e6d787d207cee2ec3: 데이터추가
89864d9a0b50ad45e879dda98d41883d1b9e76cc: 프론트, 백 추가
502a3808c9ebf7fa7a28daa28181ad0e53c703f4: ajax
d9fd038bacdd946a84086ff2ac6cd1fb8d4ef6f4: now

## 7. FAQ

- 자주 받는 질문 정리
