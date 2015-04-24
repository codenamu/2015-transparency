---
id: 8
title: How Much Shoveling We’ve Done
excerpt: How Much Shoveling We’ve Done
description:


flickr_img: /img/how-much-shovelling.png

result: http://showveling-codeforseoul.appspot.com/

documents: https://docs.google.com/document/d/1-_pjox-9EFKoJ2rRINVtfK951r1sZT7pNoKOQngoMhs/edit?usp=sharing
github: https://github.com/codeforseoul/how-much-shoveling
slack: https://codeforseoul.slack.com/messages/how-much-shovelling

team: 이두환, Andrew Min, 정순오, Christopher Tong, 임재균, 정지민
team_photo: 

---

이 프로젝트는 정부의 재정 데이터중 건설관련 비용을 지도상에 표시하여 보다 쉽게 건설관련 비용의 흐름과 유용성을 보여주려는 목적으로 정부의 예산이 집행된 공사의 집행 기관명과 위치, 총 공사비 등을 투명하게 지도 상에 시각화합니다.

### Background Idea

* 국가 재정 지출에서 지도에 표시할 수 있는 건설 등에 쓰인 지출을 구글 맵에 표시하여 지도에서 각 삽질이(건설이) 얼마나 어떻게 진행되고 있는지 시민들이 쉽게 알 수 있게 보여주는 것이 기본 아이디어였다.

* 예를 들어 DDP, 4대강 사업, 신도시, 등등의 주소, 건설 예산, 실소요 비용, 완공 시기 등의 정보를 맵에 표기하고 시민들이 그것에 대한 의견도 같이 공유 되면 좋겠다는 생각이었다.

### Purpose of the product

* KEY-01. 국가 예산에서 건설 분야에 얼마나 사용되었는지 보여준다.   
Analyze the proportion of government finances allocated to construction 
* KEY-02. 국토가 얼마나 균형적으로 개발되는지 보여준다.   
Reveal development of the whole country is in balance.
* KEY-03. 불필요한 낭비가 없는지 쉽게 파악 할 수 있게 한다.   
Identify waste in construction finances

### Specification

* 총 건설 지출을 각 특별시/도 별로 비교하여 볼 수 있게 표시한다.   
Show total construction expenses between provinces for comparison and summary.
* 건설지역을 지도에 표시하고 요약 내용을 같이 보기 좋게 표시한다.   
Pin construction site and show summary information
Summary information: Name, StartedAt, FinishedAt, Total Money Spent, Picture
* 건설지역을 목록으로 표시하고 해당 목록은 검색 옵션에 의해 필터링, 페이징 되어 표시된다. 사용자가 목록의 건설 지역을 클릭하면 해당 건설지역의 상세설명 페이지가 표시되고 지도뷰에서 위치가 이동되어 건설지역에 포커스되어 표시된다.   
There is construction sites list and user can filter list by search options and if user click the item of the list, the map view will move to that construction site.
