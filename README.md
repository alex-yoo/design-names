# DesignNames Project

참고사이트 링크 : https://koreanname.me/  
전자가족관계시스템 : http://efamily.scourt.go.kr/  
템플릿 : https://themeforest.net  
    - https://themeforest.net/item/oficiona-job-board-html-template/23042674?s_rank=1

# Tech Stack
- Spring boot 2.1.x
- ElasticSearch 6.6.x
- Spring batch 4.1.x
- Thymeleaf? ReactJS?

# Server Hosting
- https://www.cloudv.kr/server/metaserver.html 32.000w
![Alt text](https://monosnap.com/image/RQ5gNvIALyPshV4Q1kdW9TVC4lSEBp.png)

# 기능
1. 연도별 이름 순위
2. 이름 찾기
    - 제외 할 글자
    - 포함 할 글자
    - 성
3. 이름 길이별 순위
4. 개명 이름 순위
5. 출생아 통계
6. 성과 이름 부정 조합 단어
7. 이름 별 리뷰
8. 회원 가입
    - 구글
    - 네이버
    - 카카오
    - 페이스북
9. 회원 별 검색기록
10. 찜하기


# Todo
- (아서) 프로젝트 패키지 설계 및 구축(Spring Boot)
- (전체) 스키마 설계(Mysql)
- (루디) 크롤링 설계(Spring Batch)
- (루디) CentOS 최적화 셋팅(Linux)
- (에이든) ES 구축 및 설계(ElasticSearch)
- (에이든) View에서 사용할 통계 plugin 써치(openLibrary Search)
- (전체) View 레이아웃 구조 고민
- ...

# 정부 API
- Uri: http://frrss.efamily.f.scourt.go.kr/ds/report/query.do
- Method: POST
- FormData Example
```text
pid: 1801
uid: 999999
dsid: 1261
dstype: DS
mapid: bf62187f-c964-4047-89fd-99015b051a5e
sqlid: 1801-0
params: {"@MultiCandType":{"value":["YY"],"type":"STRING","defaultValue":""},"@MultiCandStDt":{"value":["2019"],"type":"STRING","defaultValue":""},"@MultiCandEdDt":{"value":["2019"],"type":"STRING","defaultValue":""},"@SidoCd":{"value":["11"],"type":"STRING","defaultValue":"[All]","whereClause":"C.SIDO_CD"},"@CggCd":{"value":["_EMPTY_VALUE_"],"type":"STRING","defaultValue":"[All]","whereClause":"D.CGG_CD"},"@UmdCd":{"value":["_EMPTY_VALUE_"],"type":"STRING","defaultValue":"[All]","whereClause":"E.UMD_CD"}}
```

### API 리스트
- 출생 현황
- 혼인중/혼인외 출생 현황
- 성별 출생 현황
- 다문화가정의 출생신고 현황
- 선호하는 출생자 이름 현황  

- 인지 현황
- 양자의 성별 입양 현황
- 입양특례 / 친양자 입양현황  

- 혼인 현황
- 내국인의 연령별 국제혼인 현황
- 외국인 배우자 국적별 국제혼인 현황
- 협의/재판 이혼 현황
- 내국인과 외국인의 이혼 현황  

- 사망현황
- 성별 사망 현황
- 실종선고 현황
- 부재선고 현황

- 성별 개명 현황
- 개명 시 선호하는 이름 현황
- 국적취득자가 창성한 성현황

- 사건별 처리현황
- 기간별 처리 현황
- 성별 처리 현황

- 출생아 중 단태아/다태아 현황
- 모 1인당 출산현황
- 혼인 후 출산까지의 소요시간 현황
- 국제혼인 현황
- 연령대별 혼인현황
- 이혼사건에서의 혼인유지기간 현황
- 입양자 수별 양부모 현황
- 부부의 연령 차이 현황
- 가족관계등록부상 성씨 현황

# Site Option Plugin (시간날때)
- google adsense
- google analytics
- google search
