---
id: 2
type: event
title: 33th Hack Night - 투명 재정 프로젝트 중간 공유회
excerpt: 33th Hack Night - 투명 재정 프로젝트 중간 공유회
tags: event
description:
website: https://docs.google.com/document/d/18UmfYPEckBekdlCaGQ2UWhf66hMflGltKKe59DDGT6M/edit?usp=sharing
flickr_album: https://www.flickr.com/photos/wowcckorea/sets/72157645816753208/with/16645449630/
flickr_img: /img/hacknight.jpg
documents: https://docs.google.com/document/d/18UmfYPEckBekdlCaGQ2UWhf66hMflGltKKe59DDGT6M/edit?usp=sharing

---

2월 28일 아이디어톤 이후 5개 팀이 2주간 코드포서울 핵나잇에서 발전시킨 프로젝트 진행 상황 및 해결해야할 문제점들을 공유했습니다. [중간 공유회 기록 문서](https://docs.google.com/document/d/18UmfYPEckBekdlCaGQ2UWhf66hMflGltKKe59DDGT6M/edit?usp=sharing)에서 전체 내용을 읽어볼 수 있습니다.

## 1팀 슈퍼스타 을!보드차트!

* 팀원: 윤혜정, 고은영, 임재균, 전석환, 배민효
* 문서: [http://bit.ly/codeacross-2015-seoul-1](http://bit.ly/codeacross-2015-seoul-1)

1. 연월일별 계약현황
2. 계약 대금별 랭킹
3. 계약 건별 랭킹
4. 연월별 검색기능

### 문제점

* 일반적으로 쓰이는 물품 이름과 조달청에 올라온 데이터에 기재된 제품명에 다소 차이가 있음.(이 부분을 어떻게 정제 할 것인가?)
* 계약업체와 금액을 밝혀야 하는 이유는 무엇인가? (정제한 데이터를 어떤 목적으로 사용해야 하는가?)
* 공공데이터 포털에서 제공한 API 확인. 슈퍼스타 ‘을’ 조달청에 데이터를 요구해야.
* 기간별 업체명, 금액, 사업명이 정제된 데이터 필요

### 질문

* API 가져와서 데이터시트를 열어보면 꾸준히 에러가 나면서 종종 데이터를 못 갖고 오는거 같더라고요.
* 용역계약 명칭들이 계속 바뀌고 달라지는 것들이 있어서 공고를 봐도 어떤 물품이나 용역을 계약한건지 가늠하기 어려운 부분들이 많아요. 이런 계약 용어들의 표준 체계나 작성 방침이 있는 건지? 있다면 어디에서 확인 할 수 있는지?
* 낙찰 데이터를 정리하다가 심각한 문제를 발견했어요. data.go.kr에서 제공하는 API로 낙찰 데이터를 가져왔는데요, 정작 낙찰 일자가 없어요. => [https://slack-files.com/T02QENMKM-F04271WC0-f695e3cd83](https://slack-files.com/T02QENMKM-F04271WC0-f695e3cd83)
* 데이터를 얻어서 가공했지만 정제가 필요한 상황입니다.


## 2팀 DIGITAL DIVIDE

* 팀원: Andrei.Russia, 조용현(Mickey).Korea, Alex.Russia, 이광춘(Victor, http://www.xwmooc.net).Korea
* 작업 공유 구글 폴더: [https://drive.google.com/folderview?id=0B9_Acd_wLWotZHItSUdMelZDTWc&usp=sharing](https://drive.google.com/folderview?id=0B9_Acd_wLWotZHItSUdMelZDTWc&usp=sharing)

주제는 교육 예산의 불평등을 보여주는게 목표로 개발자들만 함께 이야기하기 때문에 진도는 많이 나갔습니다.
교육 데이터는 파일로 수합해서 초중고대학교 주소, 공공데이터 포털의 교육 예산 데이터 api, 몇 가지는 크롤링을 통해 확보할 예정이며, OECD에서 제공하는 데이터를 확보해서 국내 상황과 비교를 시도할 예정입니다.
데이터는 크게 문제가 없고 모두 확보할 수 있을 것 같습니다.

### 2015.3.14(토) 원활한 진행을 위한 개발 미팅 진행

* 주제, 방향,  목표 결과물 정리
* 정부 담당자에게 할 추가 문의 및 요청사항 확인
* 데이터 수집 및 정제 관련  논의 (크롤링이 필요한 경우 공유)
* 분석 및 개발 플랫폼 논의 (개발보다는 플랫폼을 활용하는 방안으로 하고 유용한 플랫폼 더 검색해보기)
* R, D3/Google VIS/기타 이용가능 플랫폼(where does my money go, usahidi, etc..)
* 구현 차트 논의

### 질문

* 교육예산 및 사업들에 대한 설명과 예산서 및 집행 원천 데이터를 구할 수 있을까요?


## 3팀 스타트업

* 팀원 : Damien, Jeonghwan, Daniel, Emily, Young-Je  nn… etc
* 문서: [http://bit.ly/codeacross-2015-seoul-3](http://bit.ly/codeacross-2015-seoul-3)
* 데이터 소스 : 창조경제 브리프(NIA)
* 개발: Boostrap 기반으로 Bubble tree map / D3.js Library 등으로 데이터 시각화 예정 

창조 경제에 집행되는 예산 내역을 보려고 하는데 데이터를 찾기 힘듭니다. 창조경제 브리프 보고서를 보니 스타트업에 지원하는 현물 지원 올해 8조원이라고 합니다.

### 문제점: 
* 창조경제 브리프를 만든 담당자와 대화를 해봐야겠다. 창조경제 브리프의 백데이터에 접근할 수 있어야 앞으로 나아갈 수 있어서 현재 막혀 있다. 
* 거꾸로 2014년 기준으로 뉴스를 통해 검색해서 중복 지원된 내역을 살펴보는 방향으로 추진하고 있다.
* 외국인 개발자와 협업때문에 커뮤니케이션 문제가 있다. 


## 4팀 지방정부 재정 자립도

불참


## 5팀 How Much Shoveling We’ve Done

* 팀원: 임재균, Soonoh Jung, Andrew Min, Chris T, DooHwan Yi
* 문서: http://bit.ly/codeacross-2015-seoul-5
* 데이터 저장소: [https://drive.google.com/folderview?id=0BwWJPPNsxJL_fkVXeG9qR0J0Mmd6S1d4cElOWmxMRGQzRFhZWkd4alRGaDl1MlZzNEJCNHM&usp=sharing](https://drive.google.com/folderview?id=0BwWJPPNsxJL_fkVXeG9qR0J0Mmd6S1d4cElOWmxMRGQzRFhZWkd4alRGaDl1MlZzNEJCNHM&usp=sharing)


데이터가 완전하지는 않지만 몇 가지 api를 조합하면 원하는 데이터를 얻을 수 있다.
개발자 3명이 주축으로 진행하고 있고 2분은 좀 덜 참여하는 상황
디자이너 필요

### 문제점 및 질문

* 정부의 예산이 집행된  공사의 집행 기관명과 위치, 총 공사비 등을  투명하게 지도 상에 배치하여 비교해 보고자 합니다. 그러기 위해서는 예산과 해당 건설지역에 대한 주소가 필요합니다.
* 연도별로 건설 지역에 대한 아래 정보를 얻을 수 있을까요?
  * 건설 지역 상세 주소 또는 대강의 주소 또는 지역.
  * 건설 지역 총 사업비
  * 건설 진행 정보, 시공일, 종료일, 진척도
