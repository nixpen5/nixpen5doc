---
title: 2023년 8월 업데이트 히스토리
menuTitle: 2023년 8월
historyHome: 0
yearMonth: 2308
---

<br>

## 고시

- 고시 - 2023년 8월 약가툴 (자동 실행)
- 고시 - 2023년 8월 수가툴 (자동 실행)
- 고시 - 2023년 8월 치료재료툴 (공지사항의 **미설치 툴** 에서 개별 설치)
- 고시 - 의뢰 받은 의료기관 자보 청구 방법
    - 의뢰 받은 기관은 외래 명세서에 `MJ006` **의뢰한 의료기관 기호 / 의뢰 일자**, `MT015`  **69** 를 기재합니다.
    - 의뢰한 기관은 입원 명세서에 `MJ006` **의뢰 받은 의료기관 기호 / 의뢰 일자** 를 기재합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/1.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/1.png">
        </a>
    </td>
</table>

<br>

## 새로운 기능

- 원무 - 바로 접수 기능 추가
    - 접수업무 사용자 설정에서 **바로 접수 우선 사용** 옵션을 설정합니다.
    - 접수 화면 하단에서 **바로 접수** 시 확인 창 팝업 없이 즉시 접수를 수행합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/2.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/2.png">
        </a>
    </td>
</table>

- 원무 - 환자 수납내역 보기 기능 추가
    - 접수 화면 디자인 설정에서 **수납내역** 컨텐츠를 추가합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/3.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/3.png">
        </a>
    </td>
</table>

- [원무 - 접수 태블릿 앱 구글 플레이스토어 출시](https://play.google.com/store/apps/details?id=com.pointimplant.nixpen5deskx)
    - 태블릿 연동 환경 설정에서 **태블릿 사용** 옵션을 설정합니다.
    - 개인정보활용 동의 로컬 설정에서 **동의서 서식 등록** 및 **서명 영역** 을 설정합니다.
    - 태블릿 앱 `NixPen 5.0 Desk` 접수 시 진료 대기자 목록에서 즉시 확인할 수 있습니다.
- 진료 - 명세서 메모 일괄 작성 기능 추가
    - 명세서 메모 코드를 입력 `Enter` 한 상태에서 긴 내용 붙여넣기 `Ctrl + V` 시 명세서 메모 코드가 일괄 적용됩니다.
    - 속성 창 `F4` 에서 명세서 메모를 일괄 편집할 수 있습니다.
    - 병명 및 처방 사용자 설정에서 **명세서 메모 붙여넣기 시 속성 창 자동 열림** 옵션을 설정할 수 있습니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/4.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/4.png">
        </a>
    </td>
</table>

- 진료 - 검진 환자 보험 진료 기능 추가
    - 로그인 사용자가 의사인 경우 검진 환자 우클릭 시 **검진환자 보험진료** 메뉴가 표시됩니다.
    - 로그인 사용자로 **진료 의사** 가 변경되며, 당일 자격 조회 기준 **보험 유형,** 산정 기준 **초재진 구분** 이 적용됩니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/5.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/5.png">
        </a>
    </td>
</table>

- 진료 - 외래 차트 입원 전환 기능 추가
    - 입원으로 전환할 외래 차트를 불러온 후 차트 관리의 **외래에서 입원으로 전환** 메뉴를 수행합니다.
    - 당일 입원 차트가 이미 존재하는 경우 상병은 대상에서 제외됩니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/6.png" target="_blank">
            <img class="minCenterSmall" src="/images{{page.url}}/6.png">
        </a>
    </td>
</table>

- [진료 - 카메라 모바일 앱 구글 플레이스토어 출시](https://play.google.com/store/apps/details?id=com.pointImplant.nixpen5camerax)
    - 모바일 로컬 설정에서 **장치 연동** 을 설정합니다.
    - 차트 불러오기 시 카메라 모바일 앱 `NixPen 5.0 Camera` 환자 정보 동기화가 진행됩니다.
    - 카메라 앱으로 촬영한 영상을 전처방에서 즉시 확인할 수 있습니다.
- 심사 - 통계 접근 암호 관리 기능 추가
    - 암호 관리 기준정보에서 통계 접근을 위한 **사용자 암호** 를 등록합니다.
    - 암호가 등록된 경우 통계 화면 실행 시 암호 입력 창이 표시됩니다.
- 진단서 - `신경학적 검사 일반 소견서` 서식 추가
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/7.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/7.png">
        </a>
    </td>
</table>

<br>

## 개선된 기능

- 원무 - 환자 **주민번호**, **우편번호** 를 복사 `Ctrl + C` 할 수 있도록 기능 확장
- 원무 - 처방전 바코드가 원활하게 인식되도록 크기 확대
- 원무 - 병원 기준정보에서 **팩스번호** 최대 12자리 입력할 수 있도록 기능 확장
- 원무 - 차트 기록지 입퇴원 시간 출력 기능 지원
    - 차트 출력 창에서 **입원 시간, 퇴원 시간** 항목을 출력 대상으로 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/9.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/9.png">
        </a>
    </td>
</table>

- 원무 - SMS 샘플 내용을 `LMS` 를 고려하여 최대 2000자까지 입력할 수 있도록 기능 확장
- 원무 - 대기자콜 로컬 IP 설정 기능 추가
    - 대기자콜 환경 설정에서 **대기자콜 IP 공통 설정 사용** 옵션을 해제합니다.
    - 대기자콜 로컬 설정에서 연동 대상 대기자콜 IP 를 지정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/10.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/10.png">
        </a>
    </td>
</table>

- 원무 - 완료되지 않은 오더가 존재하는 경우 수납 시 알림 기능 지원
    - 수납업무 사용자 설정에서 **미완료 오더 존재 시 알림** 옵션을 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/11.png" target="_blank">
            <img class="minCenterSmall" src="/images{{page.url}}/11.png">
        </a>
    </td>
</table>

- 원무 - 기초검사 목록 우클릭 시 **복사** 하여 추가할 수 있도록 메뉴 추가
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/12.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/12.png">
        </a>
    </td>
</table>

- 원무 - 자격 조회 창의 산정특례 내역에서 특이사항을 분리하여 표시
    - **특이사항 내역** 에 당뇨병 요양비 대상자, 동일 성분 의약품 제한자, 건강보험 자격 상실자, 자가도뇨 카테터 대상자, `급여제한자` 정보가 표시됩니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/13.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/13.png">
        </a>
    </td>
</table>

- 진료 - 오더 시 실시부서 순 자동 정렬 옵션 지원
    - 병명 및 처방 사용자 설정에서 **오더 창 실시부서 순 정렬 사용** 옵션을 설정합니다.
    - 옵션 해제 후 오더 시 입력 순서로 정렬됩니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/14.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/14.png">
        </a>
    </td>
</table>

- 진료 - 전처방 표시 시작 일자 설정 기능 지원
    - 진료 환경 설정에서 **전처방 숨김 기능 사용, 전처방 표시 시작 일자** 옵션을 설정합니다.
    - 전처방 표시 시작 일자 이전 진료 내역이 전처방에 표시되지 않습니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/15.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/15.png">
        </a>
    </td>
</table>

- 진료 - 묶음 처방 시 묶음 그룹 명칭 포함 옵션 지원
    - 병명 및 처방 사용자 설정에서 **묶음 그룹명 추가** 옵션을 설정합니다.
    - 옵션 해제 후 처방 시 묶음 정보가 표시되지 않습니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/16.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/16.png">
        </a>
    </td>
</table>

- 진료 - 처방코드 에서 `Left` 시 윗 줄 **용법코드** 로 자동 이동되지 않도록 옵션 지원
    - 병명 및 처방 사용자 설정에서 **처방코드 Left Key 입력** 옵션을 설정합니다.
- 진료 - 오더 창에서 수탁 검사를 구분할 수 있도록 글자색 다르게 적용
- 진료 - 처방 시 수가 정보에서 지정한 글자색이 우선 적용되도록 기능 보완
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/17.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/17.png">
        </a>
    </td>
</table>
  
- 심사 - 수가 산정 적용 시기 설정 기능 지원
    - 제한 초과 시 적용 방법, 일 단위 최대 횟수 등이 설정된 수가 처방 시 해당 산정 조건 적용 시점을 관리합니다.
    - 계산 및 산정 사용자 설정에서 **심사 기준** 옵션을 설정할 수 있습니다.
- 심사 - 검진 진료인 경우 나이 가산을 적용할 수 있도록 옵션 지원
    - 계산 및 산정 환경 설정에서 **검진 시 나이가산 적용** 옵션을 설정합니다.
- 심사 - 차트 보험 유형이 일반인 경우 처방 시 일반가를 적용하는 기능 지원
    - 계산 및 산정 환경 설정에서 **보험 유형이 일반일 때 일반가 우선 적용** 옵션을 설정합니다.
- 심사 - 자격 조회 누락 또는 오류가 발생한 경우 심사 우클릭 시 **자격 조회** 할 수 있도록 메뉴 추가
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/18.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/18.png">
        </a>
    </td>
</table>

- 심사 - 선별급여 처방 시 비보험이 아닌 보험 수납 금액으로 발생하도록 기능 지원
    - 수납 환경 설정에서 **선별급여 보험 금액으로 발생** 옵션을 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/19.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/19.png">
        </a>
    </td>
</table>

- 심사 - 수납 대장에서 미수금 조회 시 발생액이 아닌 잔액 기준으로 검색되도록 기능 변경
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/20.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/20.png">
        </a>
    </td>
</table>

- 검사실 - 검사 수가 코드 우클릭 시 **삭제** 할 수 있도록 메뉴 추가
    - 차트에 처방된 코드는 유지되며 검사 결과 기록을 삭제합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/21.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/21.png">
        </a>
    </td>
</table> 

- 진단서 - `당뇨병 환자 소모성 재료 처방전` , `당뇨병 환자 소모성 재료 처방전(연속혈당측적용 전극용)` **보험 및 급여 서식** 으로 위치 이동
- 랩뷰어 - 선택한 영상을 즉시 출력할 수 있는 메뉴 지원
<table class="imgBox">
    <td class="imgBox">
        <a href="/images{{page.url}}/15.png" target="_blank">
            <img class="minCenter" src="/images{{page.url}}/22.png">
        </a>
    </td>
</table>

- 랩뷰어 - 좌우로 긴 영상인 경우 세로가 아닌 가로로 출력 되도록 기능 보완