---
title: 2022년 5월 업데이트 히스토리
menuTitle: 2022년 5월
historyHome: 0
yearMonth: 2205
---

<pre>

<bold># 5/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 외래영수증에 입원진료건  포함되는 bug  (영수증.외래수납현황 목록에서 입원 수납내역 제외)

<span class="box jemu">원무</span> - 전달메모 기록 존재 알림 컬러 변경  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 전달메모 존재시 : 하늘색
2) 오늘일자 전달메모 존재시 : 오렌지색
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - DRG 비급여 입원처방 발생시 영수증 비급여 수록 bug  (비급여 항목별로 영수증에 수록되게)

<span class="box chart">진료</span> - [PicShow] 영상비교창 비교모드에서 펜툴 기능 변경  (비교모드에서 펜툴 기능 지원)
<span class="box chart">진료</span> - 검사결과 항목별 결과 미표시  bug  (외래진료.검사결과탭.항목별탭 참조)
<span class="box chart">진료</span> - DrugInfo 의약품정보 검색시 발생할 수 있는 응답없음 증상   bug

<span class="box inspect">심사</span> - 중복상병 청구 제외 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.청구.청구옵션.중복상병청구제외 항목 참조
2) 중복상병 청구제외시 병명 청구코드를 기준으로 중복수록되지 않습니다.
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 청구확인 불러오기 속도 개선

<span class="box lab">검안실</span> - 대기목록 삭제 메뉴 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검안오더후 진료실에서 검안오더 코드를 모두 취소한 경우 검안대기 목록에 표시될 수 있습니다.
2) 검안대기목록에서 우클릭합니다.
3) 삭제 메뉴를 누르면 삭제확인후 삭제를 진행합니다.
4) 차트에 검안오더가 존재할 경우 삭제할 수 없습니다.
</th>
    </tr>
</table>

<span class="box other">[KIOSK 5.0]</span> 실행시 백업 파일 삭제  (업그레이드 백업파일중 불필요 파일 삭제)
<span class="box other">[KIOSK 5.0]</span> 진료의 표시 순서 bug  (기준정보.직원정보 순서변경 기능 참조)


<bold># 5/2 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 5월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 5월 3일 재택치료 관련 고시 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 병원급 재택치료 전화상담·처방형 전화상담 관리료 추가 :  AH270, AH272
2) 의원급 재택치료 전화상담·처방형 전화상담 관리료 추가 :  AH271, AH273
3) 병원급 재택치료 의료상담센터형 전화상담 관리료 추가 :  AH274, AH276
4) 의원급 재택치료 의료상담센터형 전화상담 관리료 추가 :  AH275, AH277
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 5월 3일 이후 삭제코드 사용시 알림 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 알림 대상 삭제코드 : AH233, AH234, AH237, AH238  
2) 알림 문구 : '5월 3일부로 지원이 종료되었습니다.'
</th>
    </tr>
</table>

</pre>