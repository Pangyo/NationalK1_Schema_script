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
	 	'deptCd':'9770703',
	 	'num':'2685',
	 	'hjNm':'姜起潤',
	 	'engNm':'KANG Gi Yun',
	 	'empNm':'강기윤',
	 	'reeleGbnNm':'초선',
	 	'origNm':'경남 창원시성산구',
	 	'jpgLink':'http://www.assembly.go.kr/photo/9770703.jpg'
	 }
	
```

## (2)getMemberDetailInfoList

```js
	/**
	 * Operation(Eng) : getMemberDetailInfoList
	 * Operation(Kor) : 국회의원 상세 정보조회
	 */
	 Fields
	 {
	 	empNm : '의원이름',
	 	hjNm : '한자이름',
	 	engNm : '영문이름',
	 	bthDate : '생년월일',
	 	polyNm : '소속정당',
	 	origNm : '선거구',
	 	sharNm : '소속위원회',
	 	reeleGbnNm : '당선횟수',
	 	electionNum : '당선대수',
	 	assemTel : '사무실전화',
	 	assemHomep : '홈페이지',
	 	assemEmail : '이메일',
	 	staff : '보좌관',
	 	secretary2 : '비서관',
	 	secretary : '비서',
	 	hbbyCd : '취미',
	 	examCd : '특기',
	 	memTitle : '약력'
	 }
	 
	 Record Example
	 getMemberDetailInfoList [] {
	 	'empNm' : '강기정',
	 	'hjNm' : '姜琪正',
	 	'engNm' : 'KANG Gi Jung',
	 	'bthDate' : '1964-12-03',
	 	'polyNm' : '새정치민주연합',
	 	'origNm' : '광주 북구갑',
	 	'sharNm' : '정무위원회',
	 	'reeleGbnNm' : '3선제19대',
	 	'electionNum' : '17,18,19대',
	 	'assemTel' : '02-788-2666',
	 	'assemHomep' : 'http://www.kanggijung.com',
	 	'assemEmail' : 'jtkim1013@na.go.kr',
	 	'staff' : '장성훈,정성학',
	 	'secretary2' : '김예지,정기조,홍돈석',
	 	'secretary' : '나원주,이열',
	 	'hbbyCd' : '등산',
	 	'examCd' : '축구',
	 	'memTitle' : '* 고흥 금산중학교 졸업 (79) * 광주 대동고등학교 졸업 (82) * 전남대학교 전기공학과 졸업 * 전남대학교 행정대학원 석사 * 전) 열린우리당 부대표 * 전) 정치개혁특별위원회 위원 * 전) 국회운영위원회 위원 * 17대 국회의원 * 국회 보건복지위원회 위원 * (재) 열린정책연구원 이사 * 진실규명과 화해를 위한 당정특위 위원 * 국민연금제도개선특위 위원 * 국회의원 축구연맹 회원'
	 }
```

## (3)getJungDangMemberCurrStateList

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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

```js
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
