---
title: 2022년 4월 업데이트 히스토리
menuTitle: 2022년 4월
historyHome: 0
yearMonth: 2204
---

<pre>

# 4/11 배포
=====================
<span class="box jemu">원무</span> - 카드단말기.싸인패드 이용한 개인정보활용동의  (기준정보.개인정보활용동의설정.동의서서명방법.싸인패드 참조)
<span class="box jemu">원무</span> - 싸인패드 개인정보활용동의 서명 동작 변경  (동의서창.개인정보활용동의 버튼 클릭시 싸인패드 동작)
<span class="box jemu">원무</span> - 개인정보활용동의 삭제 기능 추가 (외래접수.개인정보정보동의 창에서 동의내역을 우클릭하여 삭제)
<span class="box jemu">원무</span> - 개인정보활용동의서 기록 방식 변경  (저장 또는 거부중 최종 1건만 보관)
<span class="box jemu">원무</span> - 외래접수.검안오더 연결병명 누락 증상 bug
<span class="box jemu">원무</span> - 입원등록창에 퇴원 동시 등록 기능 추가 (입원정보탭.입원등록창.퇴원 항목 선택 후 저장 시 입퇴원 동시 처리)
<span class="box jemu">원무</span> - 입원진료.계산창에서 진료완료 버튼 동작   bug  (입원진료.계산창에서 진료완료시 수납데이터 발생하지 않게)
<span class="box chart">진료</span> - 정신과 차트 보기 옵션 기능 추가  (외래진료.화면설정.화면디자인에서 환자메모 컨텐츠 추가하여 사용)
<span class="box chart">진료</span> - 특정동작에서 증상 표시 안되는 증상   bug  (2건 이상 기록된 일자의 차트를 반복 호출 시 증상이 표시되지 않는 bug)
<span class="box chart">진료</span> - 처방창에서 묶음처방코드 변경 동작 bug  (묶음코드에 속한 수가코드를 재입력(코드 Enter) 시 발생 bug)
<span class="box chart">진료</span> - 증상정렬 옵션일때 묶음증상 정렬 적용 (증상정렬 옵션 사용 시 처방창.증상의 묶음 상태를 해제 및 정렬하여 차트 저장)
<span class="box chart">진료</span> - 증상 모음장 그룹 더블클릭시 일괄추가 옵션 기능 추가 (사용자설정.진료업무.증상편집옵션.증상 모음장 그룹 더블클릭 시 일괄 추가 옵션 참조)
<span class="box chart">진료</span> - 진료대기목록 보류 컬러를 검사상태별로 표시 ('E>' : Green, 'E<' : Orange)
<span class="box chart">진료</span> - 좌우검사 큰화면보기 단축키 추가 (외래진료.화면설정.단축키설정.큰화면보기 참조)
<span class="box inspect">심사</span> - 환경설정 등록되지 않은 수가 입력시 라이브러리 기준 추가 옵션 기능 추가 (환경설정.계산및산정.처방옵션.등록되지 않은 수가 입력 시 라이브러리 기준추가 옵션 참조)
<span class="box inspect">심사</span> - 작은청구조회시 실행제한시간 변경 (프로그램 시작후 동작시 간헐적 오류발생 증상)
<span class="box inspect">심사</span> - 심사창에서 전달메모 반복 표시   bug  ([접수보기] 버튼 클릭시 전달메모창이 반복 팝업되는 증상)
<span class="box lab">검안실</span> - 차트삭제후 검안실 대기목록 남아있는 증상 bug  (차트 삭제시 검안실 대기목록 남지 않도록)
<span class="box lab">검안실</span> - 오더 삭제 동작 bug (오더 모두 삭제 후 검안실 대기목록 남지 않도록)
<span class="box other">통계</span> - 기간별처방통계 결과에 증상 포함   bug  
<span class="box other">공통</span> - 내메뉴관리 검안실 추가 (사용자.내메뉴관리.지원부서탭 참조)
<span class="box other">공통</span> - 화면전환시 전달메모 표시 동작  변경 (외래진료에서 전달메모 창 팝업 확인 후 외래접수로 이동 시 전달메모 창 팝업되지 않도록)
<span class="box other">[LabViewer]</span> 영상비교창 Drag 기능 추가 (영상 확대 후 마우스 Drag 시 대상 방향으로 화면 이동)
<span class="box other">[LabViewer]</span> ImageView - 검사결과 보기 기능 추가 ([...]버튼에서 좌우검사 결과보기 클릭하여 표시할 1건의 검사 장비 선택)
<span class="box other">[LabViewer]</span> EyeView - 오늘 날짜의 검안결과 컬러 표시  기능 추가  (오늘날짜의 결과를 구분하여 표시)
<span class="box other">[LabViewer]</span> EyeView검사결과 - 전일자결과 수정 동작 변경  ('일자(차수)' 헤더 더블클릭 시 수정 모드 변경)
<span class="box other">[LabViewer]</span> 검사장비실행 버튼 동작 변경  (검사장비실행 버튼 클릭시 화면정리)
<span class="box other">[LabViewer]</span> 좌우검사 결과지 출력 기능 추가 (좌우검사 데이터 우클릭.좌우검사 결과지 출력 (A4) 메뉴 참조)
<span class="box other">[LabViewer]</span> 모니터 LastValue 기능 추가 (마지막으로 프로그램이 종료된 모니터 위치를 저장하여 재실행 시 적용)
<span class="box other">[LabViewer]</span> 선택탭 LastValue 기능 추가 (마지막 선택 탭 저장하여 프로그램 재실행 시 적용)
<span class="box other">[LabViewer]</span> 펜차트 - 중분류 서식그룹 기능 추가 (기준정보.펜차트 메뉴 참조)   
<span class="box other">[LabViewer]</span> 펜차트 - 서식그룹 선택하여 새차트 작성 기능 추가 (펜차트 상단에서 대분류 선택 후 중분류 더블클릭하여 새 차트 작성)


<bold># 4/6 배포</bold>
=====================
<span class="box diag">진단서</span> - 진료확인서1 진료일자가져오기창  팝업룰 변경  (필요시만 팝업)
<span class="box inspect">심사</span> - 신속항원검사 청구시 MX999 자동 수록 (MX999 - '"H/재택치료')
<span class="box other">[SmartCheck]</span> 실시간 사전점검중 멈춤 현상 bug  (건강보험/의료급여 외래만 점검)


<bold># 4/5 배포</bold>
=====================
<span class="box inspect">심사</span> - 외국인 성명길경우 청구조회 동작 bug    
<span class="box other">[고시]</span> 코로나 대면진료 분리청구    
<span class="box other">[고시]</span> 신속항원검사 의사별 100회 초과시 알림 기능 추가
<span class="box other">[고시]</span> 코로나19 외래진료센터


<bold># 4/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 검안오더시 연결수가 수록 동작 bug  (외래접수.검안오더창에서 지시할경우 연결수가 적용되게)
<span class="box jemu">원무</span> - DRG 소절개 본인부담금  (별도보상항목 종별가산 적용)
<span class="box jemu">원무</span> - 진료대기설정값 풀림 증상 bug  
<span class="box chart">진료</span> - 입원진료.계산창에서 진료완료 버튼 동작 bug  (진료완료시 수납오더 발생하지 않게)
<span class="box chart">진료</span> - 처방점검창 표시 이후 계산창에서 InsertKey 동작 bug  (변경후 출력버튼 동작하고 계산창 닫힘)
<span class="box chart">진료</span> - 검안실오더 추가 발생시 실시부서진행상태 적용룰 변경  
<span class="box other">[고시]</span> 신속항원검사 양성 확인 조건 변경  (변경후 신속항원검사 'D662097*' 처방 여부 기준)
<span class="box other">[고시]</span> 코로나19 대면진료관리료  (코드 : AH240, AH241  주의 : 타질환 진료시 차트 추가)
<span class="box other">[고시]</span> 코로나19 감염예방관리료 한시적 지원 종료  (4/4일 부터 사용불가 : AH321, AH322, AH323, AH324)

</pre>