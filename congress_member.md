# 국회의원 정보 API
#### 공식 사이트 : https://goo.gl/BDZpRA

Base URL : http://apis.data.go.kr/9710000/NationalAssemblyInfoService/

## (1) getMemberCurrStateList

```
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

## (2)getMemberDetailInfoList

```
	/**
	 * Operation(Eng) : getMemberDetailInfoList	 * Operation(Kor) : 국회의원 상세 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (3)getJungDangMemberCurrStateList

```
	/**
	 * Operation(Eng) : getJungDangMemberCurrStateList	 * Operation(Kor) : 소속정당별 국회의원 목록 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getJungDangMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (4)getCommMemberCurrStateList

```
	/**
	 * Operation(Eng) : getCommMemberCurrStateList	 * Operation(Kor) : 소속위원회별 국회의원 목록 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getCommMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (5)getElectionNumberCurrStateList

```
	/**
	 * Operation(Eng) : getElectionNumberCurrStateList	 * Operation(Kor) : 당선횟수별 국회의원 목록 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getElectionNumberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (6)getLoOrProporMemberCurrStateList

```
	/**
	 * Operation(Eng) : getLoOrProporMemberCurrStateList	 * Operation(Kor) : 당선방법별 국회의원 목록 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getLoOrProporMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (7)getLocalMemberCurrStateList

```
	/**
	 * Operation(Eng) : getLocalMemberCurrStateList	 * Operation(Kor) : 지역별 국회의원 목록 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getLocalMemberCurrStateList [] {
	 	"deptCd":"9770703",
	 }
```

## (8)getMemberNameInfoList

```
	/**
	 * Operation(Eng) : getMemberNameInfoList
	 * Operation(Kor) : 국회의원 이름 검색
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberNameInfoList [] {
	 	"deptCd":"9770703",
	 }
```

## (9)getPolySearch

```
	/**
	 * Operation(Eng) : getPolySearch
	 * Operation(Kor) : 정당 검색
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getPolySearch [] {
	 	"deptCd":"9770703",
	 }
```

## (10)getLocalSearch

```
	/**
	 * Operation(Eng) : getLocalSearch
	 * Operation(Kor) : 지역 검색
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getLocalSearch [] {
	 	"deptCd":"9770703",
	 }
```

## (11)getMemberSchedule

```
	/**
	 * Operation(Eng) : getMemberSchedule
	 * Operation(Kor) : 의사 일정 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberSchedule [] {
	 	"deptCd":"9770703",
	 }
```

## (12)getCommitAction

```
	/**
	 * Operation(Eng) : getCommitAction
	 * Operation(Kor) : 상임위 활동 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getCommitAction [] {
	 	"deptCd":"9770703",
	 }
```

## (13)getMemberRoomNotice

```
	/**
	 * Operation(Eng) : getMemberRoomNotice
	 * Operation(Kor) : 의원실 알림 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberRoomNotice [] {
	 	"deptCd":"9770703",
	 }
```

## (14)getMemberRoomEvent

```
	/**
	 * Operation(Eng) : getMemberRoomEvent
	 * Operation(Kor) : 의원실 행사 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberRoomEvent [] {
	 	"deptCd":"9770703",
	 }
```

## (15)getMemberRoomRecruitment

```
	/**
	 * Operation(Eng) : getMemberRoomRecruitment	 * Operation(Kor) : 의원실 채용 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberRoomRecruitment [] {
	 	"deptCd":"9770703",
	 }
```

## (16)getPressAticle

```
	/**
	 * Operation(Eng) : getPressAticle
	 * Operation(Kor) : 언론기사 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getPressAticle [] {
	 	"deptCd":"9770703",
	 }
```

## (17)getFieldSketch

```
	/**
	 * Operation(Eng) : getFieldSketch
	 * Operation(Kor) : 현장스케치 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getFieldSketch [] {
	 	"deptCd":"9770703",
	 }
```

## (18)getMemberAuthor

```
	/**
	 * Operation(Eng) : getMemberAuthor
	 * Operation(Kor) : 의원저서 정보조회
	 */
	 Fields
	 {
	 	deptCd : '부서코드',
	 }
	 
	 Record Example
	 getMemberAuthor [] {
	 	"deptCd":"9770703",
	 }
```
