# Header
## General
- Request URL: http://frrss.efamily.f.scourt.go.kr/ds/report/1811/info/json.do?_=1556194525794
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
- _: 1556194525794

## Response
```
{
   "Dashboard":{
      "Title":" 선호하는 출생자 이름 현황(지역)",
      "Chart":[

      ],
      "PieChart":{
         "DataSource":"dcea0891-75fa-4cbd-b40f-72986a16abf6",
         "Seq":"c69819d4-795d-4e25-8b00-5059be247da0",
         "Title":"선호하는 출생자 이름 현황",
         "Values":{
            "ColNm":"건수",
            "ChartType":"Pie",
            "FormatStr":"#,#.##"
         },
         "Arguments":{
            "ColNm":"전체비율",
            "SortType":[

            ]
         }
      },
      "Grid":{
         "DataSource":"7cbe6546-89a8-4378-b7d6-16f4bcd93d36",
         "Seq":"6f0712c6-1395-46c9-a294-614b0afce7ab",
         "Title":"선호하는 출생자 이름 현황",
         "Columns":[
            {
               "ColNm":"순위",
               "ColCaption":"순위",
               "DataType":"Numeric",
               "ColType":"DIM",
               "FormatStr":[

               ],
               "SortType":[

               ],
               "Order":"0"
            },
            {
               "ColNm":"이름",
               "ColCaption":"이름",
               "DataType":"String",
               "ColType":"DIM",
               "FormatStr":[

               ],
               "SortType":[

               ],
               "Order":"1"
            },
            {
               "ColNm":"전체비율",
               "ColCaption":"전체비율",
               "DataType":"String",
               "ColType":"DIM",
               "FormatStr":[

               ],
               "SortType":[

               ],
               "Order":"2"
            },
            {
               "ColNm":"건수",
               "ColCaption":"건수",
               "DataType":"Numeric",
               "ColType":"MEA",
               "FormatStr":"#,###",
               "SortType":[

               ],
               "Order":"3"
            }
         ],
         "Hide":{
            "ColNm":"정렬",
            "ColCaption":"정렬",
            "SortType":[

            ]
         }
      },
      "PivotGrid":[

      ],
      "LayOut":"CG",
      "ReportMasterInfo":{
         "id":1811,
         "name":"선호하는 출생자 이름 현황(지역)",
         "type":"OrgPortal",
         "datasetJson":{
            "DATASET_ELEMENT":[
               {
                  "DATASET_SEQ":"7cbe6546-89a8-4378-b7d6-16f4bcd93d36",
                  "DATASET_NM":"선호하는 출생자 이름 현황(그리드)",
                  "DATASRC_ID":"1261",
                  "DATASRC_TYPE":"DS",
                  "DATASET_TYPE":"DataSetSQL",
                  "SHEET_ID":[

                  ],
                  "wise_sql_id":"1811-0"
               },
               {
                  "DATASET_SEQ":"dcea0891-75fa-4cbd-b40f-72986a16abf6",
                  "DATASET_NM":"선호하는 출생자 이름 현황(그래프)",
                  "DATASRC_ID":"1261",
                  "DATASRC_TYPE":"DS",
                  "DATASET_TYPE":"DataSetSQL",
                  "SHEET_ID":[

                  ],
                  "wise_sql_id":"1811-1"
               }
            ]
         },
         "paramJson":[
            {
               "PARAM_NM":"@MultiCandType",
               "PARAM_CAPTION":"조회유형",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"MULTI_CAND",
               "DATASRC_TYPE":[

               ],
               "DATASRC":[

               ],
               "CAPTION_VALUE_ITEM":[

               ],
               "KEY_VALUE_ITEM":[

               ],
               "DEFAULT_VALUE":[

               ],
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":"DT",
               "MULTI_CAND_ST_YEAR":"2008",
               "VISIBLE":"Y",
               "MULTI_SEL":"N",
               "WIDTH":"700",
               "ORDER":"1",
               "UNI_NM":"@MultiCandType",
               "DS_ID":[

               ],
               "ALL_YN":"N",
               "WHERE_CLAUSE":[

               ],
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":[

               ],
               "SORT_TYPE":[

               ],
               "wiseVariables":[

               ]
            },
            {
               "PARAM_NM":"@SidoCd",
               "PARAM_CAPTION":"시도",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"LIST",
               "DATASRC_TYPE":"QUERY",
               "DATASRC":"LN5yoDAGTnt/CM9v7//ahghSxDF75bWc88WQ+d86kPhr+erJeFhM3tqA+PhVA144lwJEALirZWP3vIBqEsrmvCa5e3lvQZswyAJTh8iPrr9AGzrG/LlG58jAQ7XMQP30",
               "CAPTION_VALUE_ITEM":"TEXT_VALUE",
               "KEY_VALUE_ITEM":"KEY_VALUE",
               "DEFAULT_VALUE":"[All]",
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":[

               ],
               "MULTI_CAND_ST_YEAR":[

               ],
               "VISIBLE":"Y",
               "MULTI_SEL":"Y",
               "WIDTH":"120",
               "ORDER":"2",
               "UNI_NM":"@SidoCd",
               "DS_ID":"1261",
               "ALL_YN":"N",
               "WHERE_CLAUSE":"C.SIDO_CD",
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":"N",
               "SORT_TYPE":[

               ],
               "wiseVariables":[

               ]
            },
            {
               "PARAM_NM":"@CggCd",
               "PARAM_CAPTION":"시군구",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"LIST",
               "DATASRC_TYPE":"QUERY",
               "DATASRC":"7AwMbl4UusCBNKRaiZd14gJXSfmqRbtGt88XuKeBhFIjkWhHvNqiE5YMeSjTuETNUgaFrDqd6EUdZDfmemC2N8GB6bQaVFPC9SSaLgKTphSzrAuli1KNkpRO2OtrZCq5aHnTmBRZT0HpLTaDIRwQJKXnoKfJozSwIOH/JAodREMUg6yZedNo+wprGN4vrQEdqlZghHcO6UPQB8QrOODTD0cbTx+MlDiZCcK5DY1ftVg2lzm/doCVxYun05qlzcNoQrlm2LKbcOQS9CT6YUro/mfKwJ7r7JiXiWwMtDszRpI=",
               "CAPTION_VALUE_ITEM":"TEXT_VALUE",
               "KEY_VALUE_ITEM":"KEY_VALUE",
               "DEFAULT_VALUE":"[All]",
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":[

               ],
               "MULTI_CAND_ST_YEAR":[

               ],
               "VISIBLE":"Y",
               "MULTI_SEL":"Y",
               "WIDTH":"120",
               "ORDER":"3",
               "UNI_NM":"@CggCd",
               "DS_ID":"1261",
               "ALL_YN":"Y",
               "WHERE_CLAUSE":"D.CGG_CD",
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":"N",
               "SORT_TYPE":[

               ],
               "wiseVariables":[
                  "@SidoCd"
               ]
            },
            {
               "PARAM_NM":"@UmdCd",
               "PARAM_CAPTION":"읍면",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"LIST",
               "DATASRC_TYPE":"QUERY",
               "DATASRC":"c5FWQ/UFBOOIsx2sg6DTXpJxmFiL/X1/jnjuBkWIEJq5UrLF1wuaiAMU4mzdLK1UAdc6nXldAez26nNHFS200sLKOeZ0VxrDiUk31OLZyapw8xWQ0ctpwXwc5m5F8vn7SC26Xp2jJzOfgZLU+kP7Fx4mgZbJsAY5eqTZ+pEDsWhELrfftqnn5OinbTi3q47b0H8+mY8AbqgmBX2DoydmVav+NRQp5mW5OsQAKP2LdvRmJwNs7kbE/WVEOzZ2XFYnamNDdNaOBLnB12c/bRD3MFbmYX0YiI3UR5TvKy2G7IcbSJlUxyjmprspCuyXVDdRA/+USyIJ+snJ7kwgF1kVw3NdG6RQhthNaB+cor9mKcE0ksJZ1srbxSP38uXkTIvS3JCx+f4R7GKK21N892nCU0a0Absm/g7eD+oNKZErueOmet2r/88ApeTrg8FUONYX",
               "CAPTION_VALUE_ITEM":"TEXT_VALUE",
               "KEY_VALUE_ITEM":"KEY_VALUE",
               "DEFAULT_VALUE":"[All]",
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":[

               ],
               "MULTI_CAND_ST_YEAR":[

               ],
               "VISIBLE":"Y",
               "MULTI_SEL":"Y",
               "WIDTH":"120",
               "ORDER":"4",
               "UNI_NM":"@UmdCd",
               "DS_ID":"1261",
               "ALL_YN":"Y",
               "WHERE_CLAUSE":"E.UMD_CD",
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":"N",
               "SORT_TYPE":[

               ],
               "wiseVariables":[
                  "@SidoCd",
                  "@CggCd"
               ]
            },
            {
               "PARAM_NM":"@GenderCd",
               "PARAM_CAPTION":"성별",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"LIST",
               "DATASRC_TYPE":"QUERY",
               "DATASRC":"OORMHiNNXY2ph6ZXqksSMY45HN2dzaZxWNQ/r/T1j1vEZEWLZmJxicaXkn+aJw64i2tC2KBLdeKEDv+uGJfY1FrX3FEuOQwKfHGIIxD+RuY=",
               "CAPTION_VALUE_ITEM":"TEXT_VALUE",
               "KEY_VALUE_ITEM":"KEY_VALUE",
               "DEFAULT_VALUE":"[All]",
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":[

               ],
               "MULTI_CAND_ST_YEAR":[

               ],
               "VISIBLE":"Y",
               "MULTI_SEL":"Y",
               "WIDTH":"100",
               "ORDER":"5",
               "UNI_NM":"@GenderCd",
               "DS_ID":"1261",
               "ALL_YN":"Y",
               "WHERE_CLAUSE":"F.GENDER_CD",
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":"N",
               "SORT_TYPE":[

               ],
               "wiseVariables":[

               ]
            },
            {
               "PARAM_NM":"@Odr",
               "PARAM_CAPTION":"순위",
               "DATA_TYPE":"STRING",
               "PARAM_TYPE":"LIST",
               "DATASRC_TYPE":"QUERY",
               "DATASRC":"oM7ABwAsEO20qWDXOy6eJyPGCSvHAiL/akSfUE2sEgiEIZhBa37Q+1yJu+vcsTQ7jTV0gwjTyccfPFQBUnF+qkxCy1Z/YI55KonfmV0UAxA=",
               "CAPTION_VALUE_ITEM":"TEXT_VALUE",
               "KEY_VALUE_ITEM":"KEY_VALUE",
               "DEFAULT_VALUE":"10",
               "CAPTION_FORMAT":[

               ],
               "KEY_FORMAT":[

               ],
               "CAND_DEFAULT_TYPE":[

               ],
               "CAND_PERIOD_BASE":[

               ],
               "CAND_PERIOD_VALUE":[

               ],
               "MULTI_CAND_TYPE":[

               ],
               "MULTI_CAND_ST_YEAR":[

               ],
               "VISIBLE":"Y",
               "MULTI_SEL":"N",
               "WIDTH":"100",
               "ORDER":"6",
               "UNI_NM":"@Odr",
               "DS_ID":"1261",
               "ALL_YN":"N",
               "WHERE_CLAUSE":"10",
               "HIDDEN_VALUE":[

               ],
               "DEFAULT_VALUE_USE_SQL_SCRIPT":"N",
               "SORT_TYPE":[

               ],
               "wiseVariables":[

               ]
            }
         ]
      }
   }
}
```
