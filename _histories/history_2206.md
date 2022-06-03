---
title: 2022년 6월 업데이트 히스토리
menuTitle: 2022년 6월
historyHome: 0
yearMonth: 2206
---

<pre>

<bold># 6/3 배포</bold>
=====================
<span class="box jemu">원무</span> - 대기자콜 간헐적으로 멈춤 증상 bug

<span class="box inspect">심사</span> - 특정내역 JT005(분만) 수록 방법 변경

<span class="box other">[고시]</span> 2022년 6월 수가 등록 (자동 실행)
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 적용일자 : 2022-06-06
</th>
    </tr>
<tr>
<th style=" border-spacing: 5px; font-weight: normal">2) 신설
   AH077   코로나19 통합 격리관리료-중증 면역저하자-병원
   AH087   코로나19 다인실 격리관리료-병원-1인 격리
   AH088   코로나19 다인실 격리관리료-병원-2인 격리
</th>
    </tr>
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">3) 변경  
   AH038   코로나19 감염병전담요양병원 감염예방·관리료(확진자)
   AH054   코로나19 통합 격리관리료-요양병원
   AH065   감염병전담정신병원 감염예방·관리료-확진환자
   AH225   재택치료 환자관리료-병원
   AH226   재택치료 환자관리료-의원
</th>
    </tr>
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">4) 적용기간 연장
   AH270   재택치료 전화상담·처방형 전화상담 관리료-초진-병원
   AH271   재택치료 전화상담·처방형 전화상담 관리료-초진-의원
   AH272   재택치료 전화상담·처방형 전화상담 관리료-재진-병원
   AH273   재택치료 전화상담·처방형 전화상담 관리료-재진-의원
   AH274   재택치료 의료상담센터형 전화상담 관리료-초진-병원
   AH275   재택치료 의료상담센터형 전화상담 관리료-초진-의원
   AH276   재택치료 의료상담센터형 전화상담 관리료-재진-병원
   AH277   재택치료 의료상담센터형 전화상담 관리료-재진-의원
</th>
    </tr>
</table>

<bold># 6/2 배포</bold>
===================== 
<span class="box jemu">원무</span> - 납입영수증의 총액 항목이 진료비내역서과 불일치   bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 총액, 공단부담액 항목을 영수증과 동일하게 출력
2) 소득공제대상액 항목에 실 수납액을 변경없이 반영
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 원외처방전출력 재발행  동작   bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.출력버튼.원외처방전출력 화면 참조
2) 재발행 항목 체크후 출력시 처방전 상단에  '[재발행]' 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 환불영수증 메모 기재 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료비환불건 영수증출력시 요양기관 임의활용공간에 상세내역 출력
2) 진료비환불금액, 진료비 정산금액, 정산후납부금액 출력
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 모음장 우클릭 동작 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.P/I 모음장탭 참조
2) 모음장 내역을 Click 시 처방창에 증상으로 수록됩니다.
3) 모음장 내역을 RightClick 시 처방창의 선택된 증상에 텍스트가 더해집니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - [진료정보교류] 의료기관선택 조회 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.내역조회.진료정보교류실행 메뉴 참조
2) 기관명 검색시 진료정보교류 대상 병원만 조회
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 차트유실경고 bug 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 차트 기록이 발생하지 않은 상태에서 차트 유실경고 알림이 뜨지 않는 증상 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - IA 청구코드 라이브러리에서 등록시 항목  bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수가정보 라이브러리탭 참조
2) IA101 등 수가를 라이브러리에서 추가시 '응급및회송료' 항목으로 수록
</th>
    </tr>
</table>

</pre>