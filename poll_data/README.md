# 총선 지역구 여론조사 자료


## 여론M 지역구 여론조사 자료 (메타정보)

[여론M](https://poll-mbc.co.kr/poll2024/)에서 집계된 723개의 여론조사들에 대해, [여론조사중앙선거여론조사심의위원회](https://www.nesdc.go.kr/portal/bbs/B0000005/list.do?menuNo=200467)에 게시된 주요 메타정보들을 덧붙여 table형식으로 제공합니다.

* 여론M에서는 735개의 여론조사를 게시하고 있다고 되어 있지만, 일부 양자대결/다자대결 조사가 중복해서 게시된 것으로 보입니다. 이들을 제외했습니다.
    - 여심위에 등재된 22대 총선 관련 여론조사 전체는 2023년 3월 30일 이후 대략 1900여개가 넘습니다. 여기에서 여론M에서 집계한 여조들만 붙였습니다 (필요하신 분은 전체 메타 정보도 게시할 수 있습니다).
* 혼합 여론조사결과들떄문에 일부 열이 Nested구조가 있어서, 부득불 자세한 자료는 nested tibble형식의 R자료구조를 갖고 있습니다.
* [미디어리서치의 수원병 조사](https://www.nesdc.go.kr/portal/bbs/B0000005/view.do?nttId=14639&menuNo=200467&searchTime=&sdate=&edate=&pdate=&pollGubuncd=VT025&searchCnd=&searchWrd=&pageIndex=5)의 메타정보는 현재 여심위에서 확인할 수가 없습니다.
* 일부 여론조사는 지역구조사와 비례조사나 다른 현안조사가 쪼개서 여심위 게시판에 다른 시점에 등록됐는데, 가장 빠른 등록일을 기준으로 결합하려고 했습니다.
* 일부 여론조사에서 여론M에서 제시된 조사시작시점이 여심위와 다르게 (하루차이) 되어 있는 경우가 있었습니다.

* [MBC_polls.rds](MBC_polls.rds): R의 RDS형식으로 중앙선거여론조사심의위원회의 메타정보들이 붙임으로 들어가 있습니다.
* [MBC_polls_longform.tsv](MBC_polls_longform.tsv): 후보자/정당/여조지지율을 long-form으로 붙인 것입니다.
* [MBC_polls_longform.tsv](MBC_polls_wideform.tsv): [선거결과형식](../election_data/2024_지역구_wideform_partyonly.tsv)과 마찬가지로 정당만 뽑았으며, 무소속후보는 개인이 한 정당으로 처리했습니다.

본 자료들은 여론M에서, AAPOR응답률을 계산하는데 필요한 접촉률을 뽑기 위해서 작업하다가 나온 산출물입니다. 각종 집계자료들의 무결성이나 기타 법적권리들은 모두 여론M과 중앙선거여론조사심의위원회에 문의해주세요.

## 전국 여론조사 자료 (메타정보)
