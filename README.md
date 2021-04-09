# Tableau

## Contents
1. [Using](#using)
2. [Overview and main features](#overview-and-main-features)
3. [Chart visualization](#chart-visualization)
4. [Use a simple view](#use-a-simple-view)
5. [Map visualization and drill down](#map-visualization-and-drill-down)
6. [Analysis practice](#analysis-practice)
7. [Dashboard, story creation and web sharing](#dashboard,-story-creation-and-web-sharing)

---------------------------------------------------------

## Using
1. Basic Data - **KOSIS** (국가 통계포털)
2. Data visualization tool - **Tableau**

---------------------------------------------------------

## Overview and main features
1. [Tableau](https://en.wikipedia.org/wiki/Tableau_Software)
    1. **다양한 데이터 소스(파일, 데이터베이스)**에 접근을 해서 데이터를 가져온 다음, 그 데이터를 잘 **처리해서 시각화**를 해주는 소프트웨어
    2. **데이터 시각화 도구**
2. 제품군
    1. **Tableau Desktop** - 1:1
    2. Tableau Server - 1:n
    3. Tableau Online - Tableau Cloud에 들어가서 사용할 수 있는 제품
3. **주요 기능**
    1. **다양한 소스 (파일 및 서버)와 연결 가능**
    2. **지도 자동 매핑 기능**
    3. **쉽고 간편하고 다양한 차트 시각화 기능**
    4. **Interactive 시각화 기능** : 매개변수 생성 - 계산된 필드 - 필터 적용
4. **Tableau Desktop** [다운로드](https://www.tableau.com/)

----------------------------------------------------------

## Chart visualization
1. [KOSIS](https://kosis.kr/publication/publicationThema.do) 국가 통계포털 Excel 데이터 사용
    - 온라인간행물 -\> "전국사업체조사"검색 -\> 시군구별 -\> 2019년기준자료 -\> 전국 Excel 다운로드
    <p align="center">
        <img src = "Images/excel.png", width="100%">
    </p>
2. **Tableau**에서 위 **Excel 파일 열기**
    - 파일에 연결 -\> Microsoft Excel
    <p align="center">
        <img src = "Images/tableau1.png", width="100%">
    </p>
    <p align="center">
        <img src = "Images/tableau2.png", width="100%">
    </p>
3. **불필요한 데이터 삭제**
    - **데이터 해석기** 사용
    <p align="center">
        <img src = "Images/data1.png", width="100%">
    </p>
    <p align="center">
        <img src = "Images/data2.png", width="100%">
    </p>
4. **워크시트**로 이동
    <p align="center">
        <img src = "Images/work1.png", width="100%">
    </p>
    <p align="center">
        <img src = "Images/work2.png", width="100%">
    </p>
5.  다양하게 **차트 생성 및 사용** <sub>Ctrl+B : 차트 줄이기, Ctrl+Shift+B : 차트 키우기</sub>
    1. '총 사업체 수' 더블 클릭 -\> **행**
        <p align="center">
            <img src = "Images/bar1.png", width="100%">
        </p>
    2. '산업분류명칭' 더블 클릭 -\> **열**
        <p align="center">
            <img src = "Images/bar2.png", width="100%">
        </p>
    3. 막대에 **색상 입히기** ('산업분류명칭'을 색상별로 보기 위해)
        - '산업분류명칭' 드래그 -\> **마크의 색상에 드랍**
        <p align="center">
            <img src = "Images/bar3.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/bar4.png", width="100%">
        </p>
    4. **행과 열 바꾸기, 내림차순 (오름차순) 정렬**
        - 행과 열 바꾸기 버튼 클릭 (또는 **Ctrl + W**)
        - 내림차순, 오름차순 버튼 클릭 또는 **우측에 산업분류명칭 우클릭하여 정렬 가능**
        <p align="center">
            <img src = "Images/bar5.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/bar6.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/bar7.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/arrange.png", width="100%">
        </p>
    5. **필터 적용**하여 전체 산업 막대(전체를 더한 값) 삭제
        1. '산업분류명칭'을 드래그해서 **필터에 드랍**
            <p align="center">
                <img src = "Images/filter1.png", width="100%">
            </p>
        2. 전체산업 해제 후 적용
            <p align="center">
                <img src = "Images/filter2.png", width="100%">
            </p>
            <p align="center">
                <img src = "Images/filter3.png", width="100%">
            </p>
    6. **차트 명 변경** (하단 시트명 변경도 동일)
        - 제목 더블 클릭하여 수정
        <p align="center">
            <img src = "Images/title1.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/title2.png", width="100%">
        </p>
    7. 사업체 수를 **퍼센트로 변경**
        - 분석 -\> 백분율 -\> 테이블
        <p align="center">
            <img src = "Images/per1.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/per2.png", width="100%">
        </p>
    8. 시트를 **복사, 붙여넣기** 하여 쉽고 다양한 차트 생성이 가능
        <p align="center">
            <img src = "Images/sheet1.png", width="100%">
        </p>
    9. 우측 상단에 **표현 방식을 이용하여 현재 차트를 다양한 차트로 변환 가능**
        <p align="center">
            <img src = "Images/another1.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/another2.png", width="100%">
        </p>
    10. **표** 내림차순
        - 값 우클릭 모두선택 -\> 마우스 Over -\> 선택
        <p align="center">
            <img src = "Images/table1.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/table2.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/table3.png", width="100%">
        </p>
        <p align="center">
            <img src = "Images/table4.png", width="100%">
        </p>
    11. **트리맵 차트**
        <p align="center">
            <img src = "Images/treemap.png", width="100%">
        </p>
    12. 저장하기
        1. 저장 : 차트만 저장
        2. **패키지 통합 문서 내보내기 : 외부에 있는 엑셀 데이터를 가져와서 차트를 작성했는데, 해당 엑셀 파일과 같이 저장하고 싶을 때 사용 (추천)**
        
---------------------------------------------------------

## Use a simple view

---------------------------------------------------------

## Map visualization and drill down

---------------------------------------------------------

## Analysis practice

---------------------------------------------------------

## Dashboard, story creation and web sharing