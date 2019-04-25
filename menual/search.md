# Header
## General
- Request URL: http://frrss.efamily.f.scourt.go.kr/ds/report/condition/query.do
- Request Method: POST
- Status Code: 200 OK
- Remote Address: 211.241.67.102:80
- Referrer Policy: no-referrer-when-downgrade

## Response Headers
- Connection: Keep-Alive
- Content-Type: application/json;charset=UTF-8
- Date: Thu, 25 Apr 2019 11:37:51 GMT
- Keep-Alive: timeout=2, max=295
- Server: Apache
- Transfer-Encoding: chunked
- X-UA-Compatible: IE=Edge

## Request Headers
- Provisional headers are shown
- Accept: */*
- Content-Type: application/x-www-form-urlencoded; charset=UTF-8
- Origin: http://frrss.efamily.f.scourt.go.kr
- Referer: http://frrss.efamily.f.scourt.go.kr/ds/report/view.do
- User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.103 Safari/537.36
- X-Requested-With: XMLHttpRequest

## Form Data
- pid: 1801
- uid: 999999
- dsid: 1261
- dstype: DS
- mapid: bf62187f-c964-4047-89fd-99015b051a5e
- sqlid: 1801-0
- params: {"@MultiCandType":{"value":["YM"],"type":"STRING","defaultValue":""},"@MultiCandStDt":{"value":["201904"],"type":"STRING","defaultValue":""},"@MultiCandEdDt":{"value":["201904"],"type":"STRING","defaultValue":""},"@SidoCd":{"value":["11","26"],"type":"STRING","defaultValue":"[All]","whereClause":"C.SIDO_CD"},"@CggCd":{"value":["26440","26410"],"type":"STRING","defaultValue":"[All]","whereClause":"D.CGG_CD"},"@UmdCd":{"value":["26440-"],"type":"STRING","defaultValue":"[All]","whereClause":"E.UMD_CD"}}

## Response
```
{
   "mapid":"bf62187f-c964-4047-89fd-99015b051a5e",
   "data":[
      {
         "조회기간":"2019.04",
         "건수":124,
         "정렬":"부산광역시 강서구청",
         "읍면":"부산광역시 강서구청",
         "시군구":"부산광역시 강서구",
         "시도":"부산광역시",
         "항목":"부산광역시 강서구청"
      }
   ]
}
```
