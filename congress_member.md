# 국회의원 정보 API
#### 공식 사이트 : https://goo.gl/BDZpRA

Base URL : http://apis.data.go.kr/9710000/NationalAssemblyInfoService/

## (1) getMemberCurrStateList

```js
	/**
	 * Operation(Eng) : getMemberCurrStateList	 
	 * Operation(Kor) : 국회의원 현황 조회	 
	 */
	 Fields
	 getMemberCurrStateList
	 {
	 	deptCd : '부서코드',
	 	num : '식별코드',
	 	empNm : '한글이름',
	 	hjNm : '한자이름',
	 	engNm : '영문이름',
	 	reeleGbnNm : '당선횟수',
	 	origNm : '선거구',
		jpgLink : '의원사진 파일 경로'
	 }
	 
	 Record Example
	 getMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 	"num":"2685",
	 	"hjNm":"姜起潤",
	 	"engNm":"KANG Gi Yun",
	 	"empNm":"강기윤",
	 	"reeleGbnNm":"초선",
	 	"origNm":"경남 창원시성산구",
	 	"jpgLink":"http://www.assembly.go.kr/photo/9770703.jpg"
	 }
	
```
