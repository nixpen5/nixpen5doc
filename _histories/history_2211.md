---
title: 2022년 11월 업데이트 히스토리
menuTitle: 2022년 11월
historyHome: 0
yearMonth: 2211
---

<pre>

<bold># 11/10 배포</bold>

<span class="box chart">진료</span> - 수납대기 목록에 0원 수납 표시 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[진료업무] 화면 참조
2) 보기옵션.[수납대기 목록에 0원 수납 표시] 항목 선택 후 [저장] 버튼 Click
3) 외래진료.[수납] 탭의 환자 목록 확인
    - 설정 상태 : 0원 수납 환자 표시
    - 설정 해제 : 0원 수납 환자 미표시
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 영문예방접종증명서2 양식변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 증명서.[영문예방접종증명서2] 화면 참조
2) 상단 문구 변경 및 백신 아래 줄 선 표시
</th>
    </tr>
</table>

<span class="box other">통계</span> - 진료통계.기간별처방통계 주상병 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[기간 별 처방 통계] 탭 참조
2) [주상병명] 항목 추가
    - 변경 전 : [진료과], [진료의], [차트번호] .. [보험유형]
    - 변경 후 : [진료과], [진료의], [차트번호] .. [보험유형], [주상병코드], [주상병명]
</th>
    </tr>
</table>
<span class="box other">통계</span> - 내원경로별환자현황 통계 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 인원통계.[내원경로 별 환자 현황] 탭 참조
</th>
    </tr>
</table>
<span class="box other">통계</span> - 기간별처방통계 투여량 오류 bug  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[기간 별 처방 통계] 탭 참조
2) 퇴장방지 의약품인 경우 [투여량] 항목이 증가되어 표시되는 오류 패치
</th>
    </tr>
</table>

<span class="box lab">방사선실</span> - 메디컬스탠다스 ResOrderTab방식 PACS 오더 취소 오류 패치
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[전처방] 탭 참조
2) 오더 취소 시 PACS Cancel Order 수록 규칙 변경
</th>
    </tr>
</table>

<span class="box other">[KIOSK 5.0]</span> 수납 후 세부산정내역서 출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[기본] 화면 참조
2) 수납 옵션의 [수납 후 진료비 세부산정내역서 출력], [진료비 세부산정내역서 출력여부 확인] 항목 선택 후 [저장] 버튼 Click
3) 진료비 수납 후 [진료비 세부산정내역서] 출력물 선택

<a href="/images{{page.url}}/1.png" target="_blank"><img src="/images{{page.url}}/1.png" alt=""></a>[ 진료비 세부산정내역서 선택 화면 ]

<a href="/images{{page.url}}/2.png" target="_blank"><img src="/images{{page.url}}/2.png" alt=""></a>[ 진료비 세부산정내역서 출력물 화면 ]
</th>
    </tr>
</table>

<span class="box other">[NTalk]</span> 원내 메신저 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[N Talk 설정] 화면에서 [사용] 항목 선택 및 파일 업로드 경로 지정 후 [저장] 버튼 Click
2) 로컬설정.[기본] 화면에서 [내부 네트워크 IP] 항목 입력 후 [저장] 버튼 Click
3) 로컬설정.[N Talk 설정] 화면에서 [프로그램 시작 시 자동 실행] 항목 선택 후 [저장] 버튼 Click
4) 프로그램 재실행하여 NTalk 화면 확인
<a href="/images{{page.url}}/3.png" target="_blank"><img src="/images{{page.url}}/3.png" alt=""></a>
[ NTalk 메신저 화면 ]
</th>
    </tr>
</table>

<bold># 11/08 배포</bold>
===================== 
<span class="box notice">[고시]</span> 2022년 11월 2차 약가 등록 (자동 실행) 

<bold># 11/03 배포</bold>
===================== 
<span class="box jemu">원무</span> - 재접수시 확인창
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면에서 환자 불러오기 후 [접수] 버튼 Click
2) 접수창에서 [접수] 버튼 Click
3) 동일한 의사로 접수한 건이 존재하는 경우 재접수 진행 확인 창 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수구분 검진연동시 일반적용 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[접수] 화면 참조
2) 초재진.[접수구분 검진 연동 시 일반 적용] 항목 선택 후 [저장] 버튼 Click
3) 외래접수 화면에서 환자 불러오기 후 [접수] 버튼 Click
4) 접수창에서 [검진연동] 에 해당하는 접수구분을 선택 시 보험유형.[일반] 자동 선택
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 대기자를 보류로 변경 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 탭 참조
2) 대기 목록 Right Click 하여 [진료진행상태 변경] 메뉴 선택
    - 진료 보류 상태 : [진료대기] 상태로 변경하는 메뉴 표시
    - 진료 대기 상태 : [진료보류] 상태로 변경하는 메뉴 표시
</th>
    </tr>
</table>

<span class="box chart">진료</span> - '-전체-' 선택한 상태에서 묶음 편집 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[Rt] 화면 참조
2) [진료과] 또는 [의사] 항목이 '전체' 로 선택되어 있는 경우 묶음 편집 오류 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 요일반검사 체크시 서비스 제외
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 본인부담구분.[서비스] 가 아닌 수가를 기준으로 요일반검사 적용하도록 기능 변경
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 인슐린 원외주사 처방 시 총처방일수 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 인슐린 원외처방일수가 총처방일수에 반영되도록 오류 패치
</th>
    </tr>
</table>

</pre>