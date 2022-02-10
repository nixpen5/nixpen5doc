---
title: 2022년 2월 업데이트 히스토리
menuTitle: 2022년 2월
historyHome: 0
yearMonth: 2202
---

<pre>

<bold># 2/10 배포</bold>
=====================
<span class="box jemu">원무</span> - 모바일접수 오늘이후포함 검색조건 추가  (외래접수.모바일접수탭 참조)
<span class="box jemu">원무</span> - 똑닥예약 사용시 접수 대기자 순서   bug  (똑닥으로 예약한 시간이 도래되었을때 자동 접수 수행)
<span class="box jemu">원무</span> - 수납상세 할인액 입력시 동작 변경  (감면구분이 선택된 상태에서 할인금액 편집시 감면구분 항목값을 초기화)
<span class="box jemu">원무</span> - 감면구분 급여 비급여 감면율 항목 분리 기능 추가  (기준정보.수납관리.감면구분 메뉴 참조)
<span class="box jemu">원무</span> - 환경설정 검안오더전달 옵션 기능 추가  (환경설정.실시부서.검안오더옵션 참조)
<span class="box jemu">원무</span> - 코로나감염예방관리료 진료비세부산정내역서 본부 0원 표시
<span class="box jemu">원무</span> - SMS 문자발송 조회 (착신확인) 동작 bug  (고객관리.SMS.SMS착신확인 버튼 참조)
<span class="box jemu">원무</span> - 예약 과별출력 폰트크기 동작   bug  (예약.진료과탭.출력버튼.과별출력 메뉴 참조)
<span class="box chart">진료</span> - 차트저장시 로그 기능 변경  (저장시 입력처방 코드 기록)
<span class="box chart">진료</span> - 좌우검사 탭 명칭 변경 기능 추가  (좌우검사탭 [...] 버튼 참조)
<span class="box chart">진료</span> - 입원등록창 입원유형 Relay 동작 기능 추가  (입원등록시 차트.보험유형이 기본)
<span class="box chart">진료</span> - 처방창 검진바우처 컬러 표시 기능 추가  (검진바우처 체크시 컬러 표시, 줄단위메모 컬러가 우선)
<span class="box chart">진료</span> - 오더창 직전처방(Cyan Color) 컬러 표시 기능 변경  (오더창에서 선택한 코드에 컬러 표시)
<span class="box chart">진료</span> - 외래진료.대기탭 날짜 선택 동작 변경  (날짜항목 직접 편집 기능 지원)
<span class="box chart">진료</span> - 계산창 감면구분 콤보박스 표시방법 변경  ('직원 (보:30% 비:50%)' 형식으로 표시)
<span class="box chart">진료</span> - 계산창 감면구분 유지 기능 추가  (직전 수납의 감면구분 유지)
<span class="box chart">진료</span> - 검안오더 사용자버튼 기능 추가  (화면설정.사용자버튼설정 메뉴 참조)
<span class="box chart">진료</span> - 코로나19 감염예방관리료 10회초과시 알림 기능 추가  ('감염예방관리료I' 이 처방되고 의사 기준 10회 초과시 알림)
<span class="box diag">진단서</span> - [급여] 당뇨병환자 소모성 재료처방전(연속혈당측정용 전극용) 서식 추가  (급여서식탭 참조)
<span class="box diag">진단서</span> - '서식탭으로 이동' 메뉴 기능 추가  (서식 선택후 우클릭 메뉴 참조)
<span class="box diag">진단서</span> - 진료의뢰서 상병 리피트 룰 변경  (서류발급.의뢰서탭 참조)
<span class="box diag">진단서</span> - 코로나19 신속항원검사 음성확인서 서식 추가  (서류발급.확인서탭 참조)
<span class="box diag">진단서</span> - 영문코로나진단서 영문병원전화번호  표시 bug  (서류발급.진단서탭 참조)
<span class="box diag">진단서</span> - 영문코로나진단서 싸인 출력 위치 이동  (변경전 대비 좌측 이동)
<span class="box inspect">심사</span> - DRG등록창 청구정보 자동 생성 기능 추가  (DRG등록창.청구정보생성 체크박스 참조)
<span class="box inspect">심사</span> - 외과전문의가산 적용  (기준정보.직원정보.전문의자격.외과전문의 참조)
<span class="box inspect">심사</span> - 데이터베이스 설정창 자동실행 기능 삭제  (일정시간 대기후 자동 실행 동작 삭제)
<span class="box inspect">심사</span> - 저장만 클릭시 특정내역입력창 보기 옵션 기능 추가  (사용자설정.진료업무.열기및저장.차트임시저장옵션 참조)
<span class="box inspect">심사</span> - 특정내역창 기본 선택 동작 변경  (특정내역 기재대상 부재시 기록된 명세서단위 특정내역을 표시)
<span class="box inspect">심사</span> - 일자별 위탁기관관리창 적용일자 편집 동작 변경  (날짜항목 직접 편집 기능 지원)
<span class="box inspect">심사</span> - 환경설정 감염병조회  옵션 기능 추가  (환경설정.기준관리.DUR.감염병조회 옵션 참조)
<span class="box inspect">심사</span> - 수가정보 응급및회송료등  2란일 수 없습니다. 점검 기능 추가  (진찰료 및 입원료 항 대상 점검)
<span class="box lab">검안실</span> - 실시부서완료 버튼 표시 방법 변경  (병원에 검안실이 2개 이상일때만 표시)
<span class="box other">공통</span> - 긴급공지 클라이언트  (긴급공지 발생시 실시간 알림)
<span class="box other">[디비툴]</span> 툴설치상태.미설치건 재시도 동작  bug  (툴설치중 중단한 경우, 다음 실행시 재시도 수행)
<span class="box other">[Scan]</span> LiveUpdate 기능 추가
<span class="box other">[PosVision]</span> 영상 저장 파일 크기 변경  (변경전 대비 약 10% 사이즈로 저장)
<span class="box other">[CaptureManager]</span> Window 마지막위치 저장  (프로그램 종료시 마지막 위치 기록)
<span class="box other">[DBMaker]</span> 변경된 스키마 적용  
<span class="box other">[KIOSK 5.0]</span> 신용카드 투입시 즉시 결제 옵션 기능 추가  (환경설정.기본.수납옵션 참조)
<span class="box other">[고시]</span> DRG 고위험임산부집중관리료 별도산정  (고위험임산부 본인부담률 5%)
<span class="box other">[고시]</span> B014 연장승인미신청자 본인부담계산룰 변경  (외래 30% 산정, 특정기호 F023 자동 수록)


<bold># 2/8 배포</bold>
=====================
<span class="box chart">진료</span> - 당일 특정내역 기록존재시 팝업 옵션 동작  bug  (사용자설정.진료업무.열기및저장.특정내역입력창보기옵션 참고)


<bold># 2/3 배포</bold>
=====================
<span class="box lab">검사실</span> - 결과만보기옵션에서 '--' 입력시 Negative 문구 입력 기능 추가 ('--' 또는 '++' 입력후 enter)
<span class="box chart">진료</span> - 외래진료.진단서 실행후 소견이 보이지 않는 증상 bug  (외래진료 진단서 버튼 참조)
<span class="box diag">진단서</span> - 채용신체검사서(일반) 기타검사 항목 입력 길이 변경  (검사서식탭 참조)
<span class="box inspect">심사</span> - 특정오더 환자조회 Crush bug  (내역조회.특정오더환자조회 메뉴 참조)


<bold># 2/2 배포</bold>
=====================
<span class="box other">[고시]</span> 2022년 2월 3일 코로나19 신속항원검사 ‘감염예방관리료’ 수가 등록  (자동 실행)
<span class="box other">[고시]</span> 2022년 1월 26일 ‘SARS-CoV-2 항원검사 [일반면역검사]-간이검사’ 수가 등록 (자동 실행)
<span class="box other">[고시]</span> ‘감염예방관리료 본인부담면제 적용
<span class="box other">[고시]</span> ‘SARS-CoV-2 항원검사 [일반면역검사]-간이검사’ 본인부담면제 적용


</pre>