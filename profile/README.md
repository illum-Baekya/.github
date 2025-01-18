<div align="center">

# 소상공인을 위한 상권분석 앱 : 새터

## 📋 프로젝트 소개

**소상공인을 위한 상권분석 앱**은 창업을 준비하는 소상공인들에게<br> 데이터 기반의 상권 분석 인사이트를 제공하여<br> 성공적인 비즈니스 결정을 지원하는 모바일 애플리케이션입니다.

---

## 🎯 주요 목표

### 1. **창업 성공률 향상**
데이터 기반 의사결정으로<br> 실패 가능성을 줄이고 성공 가능성을 높입니다.<br>
✅ 취업난 해소

### 2. **지역경제 활성화**
창업을 통한 소상공인 증가로<br> 지역 경제의 균형 발전에 기여합니다.<br>
✅ 수도권 집중 해소

### 3. **세대 간 경제 균형**
고령층이 경제활동에 재참여할 수 있는 기회를 제공하여<br> 경제 격차를 줄이고 지역 경제를 활성화합니다.<br>
✅ 고령화 해소

### 4. **시간과 비용 절감**
상권 조사 과정을 간소화하여<br> 창업 준비 시간과 비용을 줄입니다.

### 5. **사용자 친화적 경험**
모바일 애플리케이션을 통해<br> 간편한 상권 분석 경험을 제공합니다.

---

## 📌 주요 기능

### 1. 조건 선택
🧍‍♂️ **유동인구**<br>
👨‍💼 **직장인구**<br>
🏡 **주거인구**<br>
🏪 **주변 업소 종류 및 개수**<br>
💰 **평균 매출**<br>
💵 **소득**<br>

### 2. 결과 확인
**리스트** 형태로 조건별 상권 데이터 제공 및 추천률(%) 제공 <br>
네이버지도와 연동하여 상권 위치 및 상세 정보를 지도에서 바로 확인 가능

---

## 📊 데이터 및 API 정보

| 카테고리              | 데이터 출처 및 API 이름                                                                                         | 설명                                                                                         |
|-----------------------|----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| **유동인구**          | [서울특별시 빅데이터 캠퍼스](https://bigdata.seoul.go.kr/data/selectSampleData.do?r_id=P213&sample_data_seq=73&tab_type=&file_id=&sch_text=%EC%84%9C%EC%9A%B8%EC%8B%9C+%ED%96%89%EC%A0%95%EB%8F%99%EB%8B%A8%EC%9C%84+%EC%9B%94%EB%B3%84+KT+%EC%9C%A0%EB%8F%99%EC%9D%B8%EA%B5%AC&sch_order=U&currentPage=1) | 행정동별 유동인구 데이터를 제공합니다.                                                    |
| **직장인구**          | [빅데이터 경찰 플랫폼](https://www.bigdata-policing.kr/product/view?product_id=PRDT_83)                       | 직장인구 관련 상세 데이터를 제공합니다.                                                    |
| **주거인구**          | [SGIS API](https://sgis.kostat.go.kr/developer/html/newOpenApi/api/dataApi/census.html#searchPopulation)      | 행정구역별 인구수 및 평균 나이를 반환합니다.                                                |
|                       | [행정동별 연령별 인구현황](https://jumin.mois.go.kr/ageStatMonth.do#none)                                     | 행정동별 연령별 인구현황을 제공합니다.                                                     |
|                       | [주거인구](https://www.bigdata-map.kr/search/1845969)                                                        | 주거인구 관련 데이터를 제공합니다.                                                        |
| **주변 업소 종류 및 개수** | [소상공인시장진흥공단_상가(상권)정보_API](https://www.data.go.kr/data/15012005/openapi.do#/tab_layer_prcuse_exam) | 상권 내 업소 종류 및 개수를 제공합니다.                                                    |
|                       | [SGIS API - 업종별 통계](https://sgis.kostat.go.kr/developer/html/newOpenApi/api/dataApi/census.html#company) | 업종별 통계 데이터를 제공합니다.                                                          |
| **평균 매출**          | [공정거래위원회 API](https://www.data.go.kr/data/15110302/openapi.do)                                        | 지역별 업종별 평균 매출액을 제공합니다.                                                    |
| **소비 / 소득**        | [통계청 지역소득 통계](https://kostat.go.kr/statDesc.es?act=view&mid=a10501010000&sttr_cd=S011001)           | 주거인구 기준 지역 소득 데이터를 제공합니다.                                              |
|                       | [국민연금공단_연령별 가입종별 평균소득월액](https://www.data.go.kr/data/15094029/fileData.do)                | 국민연금 가입자의 연령별 평균 소득 데이터를 제공합니다.                                     |
|                       | [전국 시군구 단위 평균 소득](https://kimhongsi.tistory.com/entry/%EA%B3%B5%EA%B0%84-%EC%9E%90%EB%A3%8C-2024-%EC%A0%84%EA%B5%AD-%EC%B5%9C%EC%8B%A0-%EC%8B%9C%EA%B5%B0%EA%B5%AC-%EA%B0%95%EC%9B%90%ED%8A%B9%EB%B3%84%EC%9E%90%EC%B9%98%EB%8F%84-%EC%A0%84%EB%B6%81%ED%8A%B9%EB%B3%84%EC%9E%90%EC%B9%98%EB%8F%84-%EB%8C%80%EA%B5%AC%EA%B4%91%EC%97%AD%EC%8B%9C-%EA%B5%B0%EC%9C%84%EA%B5%B0-%ED%8F%AC%ED%95%A8) | 시군구 단위 평균 소득 데이터를 제공합니다.                                                |
| **상권 / 상가 업소**    | [소상공인시장진흥공단 API](https://www.data.go.kr/data/15012005/openapi.do)                                  | 상권 및 상가 업소 정보를 제공합니다.                                                      |
|                       | [문화빅데이터 플랫폼](https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=75ab3e79-6f9b-4d80-934b-07746d384096) | 2024년 11월 기준 상권 데이터를 제공합니다.                                               |
---

## 🛠️ 기술 스택

<table align="center">
  <thead>
    <tr>
      <th align="center">⚙️ Backend</th>
      <th align="center">🎨 Frontend</th>
      <th align="center">📊 AI</th>
      <th align="center">☁️ Deployment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top" align="center">
        <img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/jpa-007396?style=flat-square&logo=&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/security-6DB33F?style=flat-square&logo=&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/jjwt-000000?style=flat-square&logo=&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/opencsv-00599C?style=flat-square&logo=&logoColor=white"/>
      </td>
      <td valign="top" align="center">
        <img src="https://img.shields.io/badge/flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
      </td>
      <td valign="top" align="center">
        <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/numpy-013243?style=flat-square&logo=numpy&logoColor=white"/><br>
        <img src="https://img.shields.io/badge/arima-0091EA?style=flat-square&logo=&logoColor=white"/>
      </td>
      <td valign="top" align="center">
        <img src="https://img.shields.io/badge/aws-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>

</div>
