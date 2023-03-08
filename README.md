# 가계부 서비스 #1

## 체크리스트

<details>
<summary>구현 요소 구조도</summary>

![가계부 기능](https://user-images.githubusercontent.com/60080167/223045069-169bbf61-90bb-4807-9d3b-d7a5cefbd2f6.png)
</details>

<br>

### 메인 페이지 UI
1. 헤더(header)
    - [x] 연월을 가운데
    - [x] 로고, 이동 탭을 좌우에 위치시키기
    - [ ] 연도를 월 위에 작은 폰트로, 영문 월 표시를 아래 작은 폰트로 위치시키기
    - [ ] 내역 아이콘만 밝게, 나머지는 어두운 색으로 처리
2. 내역 입력바
    - [ ] 입력란 가로 정렬하기
    - [ ] 입력란 사이 구분선 넣기
    - [ ] 라벨을 입력칸 위에 넣기
    - [ ] 확인 버튼(비활성)
3. 수입지출 내역
    1. 상단 내용 요약
        - [ ] 총 건수를 좌측에 배치
        - [ ] 수입, 지출 액수를 우측에 배치
        - [ ] 수입, 지출 액수 앞 체크박스 배치
    2. 내역
        1. 일별 내역
            - [ ] 요약: 일자를 좌측, 내역을 우측에 배치
            - [ ] 카테고리는 타원형에 색 채우기, 텍스트 컬러 #FCFCFC
            - [ ] 금액을 가장 오른쪽 배치
            - [ ] 각 칼럼별 간격을 어떻게 할지 고민
        2. 전체 구성
            - [ ] 최신 내역이 위로 오도록 배치

### 월 이동 기능
- [ ] 월별 내역을 생성
- [ ] 수입 지출 내역에 월별 데이터를 연동
- [ ] 수입 지출 내역 계산 확인
- [ ] 좌우 이동 버튼에 이벤트리스너 넣기

### 새로운 내역 입력
- 일자
    - [ ] 최초 렌더링 시 오늘 날짜 자동입력
- 금액
    - [ ] +- 버튼 : 토글 찾아보기
    - [ ] 3 * x + 1 자리 입력할 때마다 쉼표 추가
- 내용
- 결제수단
    - [ ] 클릭하면 드롭다운 패널 등장
    - [ ] x버튼 클릭하면 알림창 띄우기
        - [ ] 클릭시 아이콘을 줄였다 늘려 클릭되는 느낌 주기
        - [ ] 배경 딤 처리
    - [ ] 추가하기 누르면 입력 모달창 띄우기
- 분류
    - [ ] 수입, 지출에 따라 다른 목록 보여주기

## 학습 계획

1. 월요일 : 시멘틱 태그, CSS 레이아웃 학습
2. 화요일 : 메인페이지 UI 구현
3. 수요일 : UI 마무리, 내역 입력 기능 설계
4. 목요일 : 내역 입력 기능 구현, 월 이동 설계
5. 금요일 : 월 이동 구현

