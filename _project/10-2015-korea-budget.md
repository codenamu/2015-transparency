---
id: 10
title: 2015 우리나라 세출 예산 
excerpt: 2015 우리나라 세출 예산 
description:

flickr_img: /img/2015-korea-budget.png

result: http://beta.codenamu.org/2015-korea-budget
documents: https://github.com/codenamu/2015-korea-budget/blob/gh-pages/README.md
github: https://github.com/codenamu/2015-korea-budget
slack: https://code-namu.slack.com/messages/transparency/

team: 김강민, 홍영택
team_photo: 

---

우리나라 기획재정부가 운영하고 있는 [디지털예산회계시스템](https://www.digitalbrain.go.kr)에 공개된 2015년도 세출 예산 데이터를 활용해서 [트리맵](http://en.wikipedia.org/wiki/Treemapping) 형식으로 시각화해 봤습니다. 올해 예산안은 작년 12월 2일 화요일 국회 본회의 의결을 거쳐 확정되었는데 1995년 이후 19년만에 헌법이 정한 법정기일내 예산안을 처리한 것이라고 합니다. 올해 예산안 관련해서 [국회에서 확정된 2015년 예산 주요내용](http://www.mosf.go.kr/news/news02.jsp?actionType=view&hdnTopicDate=2014-12-02&runno=4092582) 보도자료나 [재정혁신타운](http://www.budget.go.kr) 웹사이트에서 더 상세한 정보를 확인 수 있습니다.

## 프로젝트에 대하여

이 프로젝트는 재정 투명성을 위해 정부와 시민이 협업하기 위한 [2015 투명 재정 프로젝트](http://transparency.codenamu.org)의 일환으로 추진했습니다. 2월말 아이디어톤을 시작으로 5개의 시민 팀이 만들어졌고 아이디어를 계속 발전시켜가며 중간 공유회를 거쳐 3월말 해커톤에서 3개의 결과물이 나왔습니다. 이 프로젝트를 리드했던 TFT의 결과물 중 하나가 이 시각화입니다.

## 해외 사례

백악관이 2016 회계년도 예산 데이터를 공개했습니다. 개발자나 데이터 사용자를 위해서는 깃헙에 CC0 퍼블릭 도메인이라는 라이선스로 공개하고 일반 사용자를 위해서는 사람들이 많이 사용하는 블로그 서비스인 medium에 알기 쉽게 요약해서 공개했습니다. 이 사례의 특징은 용도별로, 실용적으로 예산 데이터를 공개, 공유했다는 점입니다. 우리나라 정부도 이런 방식으로 시민들과 소통할 수 있게 되기를 바라는 마음으로 미약하지만 시도해봤습니다.

- [DATA: github](https://github.com/WhiteHouse/2016-budget-data)
- [MAGAZINE: medium](https://medium.com/budget-document)
- [정부 게시물](http://www.whitehouse.gov/interactive-budget)

## 데이터

[디지털예산회계시스템](https://www.digitalbrain.go.kr) > 재정 통계 > 예산 현황 > 세출/지출 > [소관-회계-사업별 세출예산](https://www.openfiscaldata.go.kr/tdata/V2Z23N9F5U8V1FWU8C9S4164409)

예시)   
소관,회계,사업,본예산(백만원)   
감사원,일반회계,감사연구활동경비,0000   
감사원,일반회계,감사활동경비,00000   
감사원,일반회계,국제교류협력강화,00   

데이터 관련해서 한 가지 아쉬운 점은 [소관-회계-사업별 세출예산](https://www.openfiscaldata.go.kr/tdata/V2Z23N9F5U8V1FWU8C9S4164409) 페이지에 방문해보면 알 수 있는데 각 부처별로 조회를 해야만 해서 하나씩 수합해서 csv로 가공하는 작업을 해야했습니다. 개발자 등 데이터를 다루는 사람들을 위해 이런 정보는 하나로 정리해서 서비스를 하면 좋겠습니다.

또한 이 데이터를 조회해보시면 알 수 있지만 각 부처들의 사업별 예산을 큰 단위로 1단계만 조회할 수 있습니다. 더 조사를 해보니 부처별로 예산 각목 명세서를 공개하는데 제대로 공개한 부처는 몇 개 밖에 없고 대부분 공개되어 있지 않습니다.

마지막으로 예산과 관련해서 [국회예산정책처](http://www.nabo.go.kr)에서 매년 [2015년도 예산안 분석 종합](http://www.nabo.go.kr/Sub/01Report/01_01_Board.jsp?funcSUB=view&bid=19&arg_cid1=0&arg_cid2=0&arg_class_id=0&currentPage=0&pageSize=10&currentPageSUB=0&pageSizeSUB=10&key_typeSUB=subject&keySUB=2015&search_start_dateSUB=&search_end_dateSUB=&department=0&department_sub=0&etc_cate1=&etc_cate2=&sortBy=reg_date&ascOrDesc=desc&search_key1=&etc_1=0&etc_2=0&tag_key=&arg_id=5305&item_id=5305&etc_1=0&etc_2=0&name2=0)과 같은 보고서를 발간하고 있습니다. [예산정책처 "유사·중복 사업 예산 1천687억원 달해"](http://www.yonhapnews.co.kr/politics/2014/11/04/0505000000AKR20141104075000001.HTML) 이런 기사에서도 볼 수 있듯이, 이 보고서 안에는 정부가 제출한 예산안을 분석해서 유사, 중복사업에 대한 의견(46p)과 함께 연례적 집행실적 부진사업 분석에 대한 내용도 확인할 수 있습니다.

## 시각화 도구

[d3js](http://d3js.org) - [Zoomable Treemap](http://mbostock.github.io/d3/talk/20111018/treemap.html).   
[위키 갤러리](https://github.com/mbostock/d3/wiki/Gallery)에서 더 많은 예시를 찾아볼 수 있습니다.

## 참고 링크
- http://bl.ocks.org/davetaz/9954190
- http://data.gov.uk/dataset/home-office-flight-data/resource/a65aa73a-4062-4eec-ad59-0bd881316f4d

## 기여자
- 데이터: 김강민
- 개발: [홍영택](http://mozo.kr)
