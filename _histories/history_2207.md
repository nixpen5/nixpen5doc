---
title: 2022년 7월 업데이트 히스토리
menuTitle: 2022년 7월
historyHome: 0
yearMonth: 2207
---

<pre>

<bold># 7/6 배포</bold>
=====================
<span class="box jemu">원무</span> - 수납대장 진료비 0원 수납 표시 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대장.[수납대장] 탭 참조
2) 검색 조건 중 [0원 수납표시] 항목 선택 후 [검색] 버튼 Click
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 예약장부 모바일 예약 표시
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 예약 화면 참조
2) 모바일 예약 건인 경우 우측 하단에 'M' 아이콘 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 미수차감 보험유형 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래수납 화면 참조
2) 미수차감 시 보험유형 발생 기준 변경
    - 변경 전 : 보험유형.[일반] 고정
    - 변경 후
        - 미수차감 대상 진료 1건 : 진료 건의 보험유형 적용
        - 미수차감 대상 진료 다건 : 보험유형.[일반] 적용
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수가정보 산정기준 청구제외 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수가정보 화면 참조
2) 수가코드 'A' 불러오기 후 [산정기준] 탭 Click
3) 적용방법(청구제외/비급여) 선택 및 기준 최대횟수 입력 후 [저장] 버튼 Click
4) 처방창에서 수가코드 'A' 입력 - [저장] 버튼 Click
5) 산정기준이 적용된 결과 확인
    - 최대 횟수를 초과하지 않은 경우 : 변경 사항 없음
    - 최대 횟수를 초과한 경우 : 산정기준 설정에 따라 청구제외 또는 비급여 처리
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 계산창 마약류 처방 조회 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 마약류 수가 처방 후 [저장] 버튼 Click
3) 계산창의 [마약류 처방] 버튼 Click - 투약정보 창 표시
4) 이미 투약정보가 작성된 상태인 경우 기능 변경
    - 변경 전 : 새 입력 창 표시 (작성 상태와 무관)
    - 변경 후 : 이전에 작성한 투약정보 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 보험유형.보훈무자격자 저장시 메시지 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) [보훈무자격자] 환자 차트 불러오기 후 [저장] 버튼 Click
    - 변경 전 : 점검창에서 무자격자 오류 표시
    - 변경 후 : 오류 표시되지 않음
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수가검색 메뉴 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료차트] 탭 참조
2) 처방창에서 수가코드 'A' 의 [코드] 칸 Right Click - [수가 검색] 메뉴 클릭
3) 수가검색 창의 [닫기] 버튼 Click - 수가코드 'A' 가 삭제되는 증상 패치
</th>
    </tr>
</table>
<span class="box chart">진료</span> - Xray 탭에서 지시 후 지시된 오더 색상표시 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[Xray] 탭 참조
2) 미지시 오더 건에 색상 표시되는 증상 패치
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 처방창 묶음코드 삭제 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료차트] 탭 참조
2) 묶음코드의 타이틀에서 Space Key 후 Enter Key 시 삭제되지 않는 증상 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 비급여 퇴장방지의약품 사용장려비 산정룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 퇴장방지의약품이 비급여일 경우 사용장려비 산정 제외
</th>
    </tr>
</table>

<span class="box other">통계</span> - 제약회사별처방통계 크기보기 검색 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[제약회사별처방통계] 탭 참조
2) [크게보기] 버튼 Click - [제약회사명] 항목 기준 검색
3) 내역을 Double Click 하여 해당 제약사의 통계 확인
</th>
    </tr>
</table>
<span class="box other">통계</span> - 검사결과지 출력 설정 적용 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 의무기록.[검사결과지] 탭 참조
2) 검사결과지 목록 조회 후 [PDF] 또는 [출력] 버튼 Click
3) 출력물에 설정한 출력 조건이 적용되지 않는 오류 패치
</th>
    </tr>
</table>

<span class="box lab">검사실</span> - 검사결과 복사 붙여넣기 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실.[검사결과] 탭 참조
2) [일자별] 항목 선택
3) 검사 목록 중 일자가 표시된 줄에서 Right Click - [검사결과 복사] 메뉴 클릭
4) 복사된 검사결과 문자열 붙여넣기 수행
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 검사결과 검사항목 항목 너비 조정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실.[검사결과] 탭 참조
2) [...] 버튼 Click - [검사항목 너비 크게] 메뉴 선택
    - 선택해제 상태 : [검사항목] 영역 너비 기본
    - 선택 상태 : [검사항목] 영역 너비 넓음
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 대기목록에서 오더시간 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실.[대기자] 탭 참조
2) 대기자 내역에 [오더시간] 항목 추가
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 의뢰결과 가져오기 항목명 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 실시부서.[엑셀 수탁 업무] 화면 참조
    - 변경 전 : 의뢰일자
    - 변경 후 : 처방일자
</th>
    </tr>
</table>

<span class="box other">[KIOSK 5.0]</span> - 접수마감시간 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[기본] 화면 참조
2) 접수옵션.[접수마감사용(평일/토요일)] 항목 선택
3) 접수옵션.[접수마감시간(평일/토요일)] 항목 설정 후 [저장] 버튼 Click
4) [접수] 버튼 색상 확인
    - 마감 시간 이내 : Blue 색상 표시
    - 마감 시간 초과 : Gray 색상 표시
5) [접수] 버튼 Click 동작 확인
    - 마감 시간 이내 : 접수 수행
    - 마감 시간 초과 : 접수 불가 안내 메시지 표시
</th>
    </tr>
</table>
<span class="box other">포스비전</span> - 차트 저장 후 화면 유지 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) [Setup] 버튼 Click - [Patient Relay] 옵션 참조
2) [Do not clear after saving the chart] 항목 선택
3) 차트 프로그램에서 외래진료 화면 정리 (초기화) 시 포스비전 동작 확인
    - 선택 : 변경 사항 없음 (차트번호 유지)
    - 선택 해제 : 초기화 (차트 프로그램과 동일)
</th>
    </tr>
</table>
</pre>