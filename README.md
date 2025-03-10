# 1st-project-sample
### 프로그래밍과 데이터 기초 교과목 단위 프로젝트 SR(Software Requirement) 안내 
**SR(Software Requirement)** 이란 **프로젝트에서의 요구되는 것들이 무엇인지를 구체화 및 문서화하는 것**을 의미합니다. 
프로젝트에서 구현해야 할 기능에 대해 구성원 전체가 논의하고 기획한 내용을 SR에 작성하도록 합니다.
참고자료로 제공해드리는 및 아래의 READ.MD를 꼭 참고하여 SR을 작성해주세요. 



<br><br><br>


## 1. 팀 소개
### 팀명 : BMW 팀
### 팀원 소개
- 멤버 개인 깃허브 계정과 연동
<table align="center">
  <tbody>
    <tr>
      <td align="center">
        <div>
          <img src="이미지 주소 경로"width="100px;"height="100px;" alt=""/>
           <a href="https://github.com/{깃헙주소}"><div align=center>팀장 OOO</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="이미지 주소 경로"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/2kilometer"><div align=center>OOO</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="이미지 주소 경로"width="100px;"height="100px;" alt=""/>
            <a href="https://github.com/{깃헙주소}"><div align=center>OOO</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="이미지 주소 경로"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/{깃헙주소}"><div align=center>OOO</div></a>
        </div>
      </td>
    </tr>
  </tbody>
</table>

<br><br><br>

## 2. 프로젝트 개요 
### 개발 기간 
YYYY-MM-DD ~ YYYY-MM-DD
### 프로젝트 명 
요즘국산차 
### 프로젝트 소개 
'요즘 국산차' 프로젝트는 국내 시장에서의 국산차 선호도 정보를 수집하고 분석하여 사용자에게 최신 트렌드와 선호도를 제공하는 서비스입니다. 이를 통해 소비자는 현 시장 상황을 파악하고, 자신의 필요에 맞는 차량을 선택하는 데 도움을 받을 수 있습니다.
### 프로젝트 내용 
#### 프로젝트 배경 
최근 몇 년간 국내 자동차 시장에서 국산차에 대한 관심이 급증하고 있습니다. 소비자들은 다양한 정보에 접근하고자 하나, 정보의 분산 및 비체계적 제공으로 인해 적절한 선택에 어려움을 겪고 있습니다. 이에 따라, 체계적이고 종합적인 국산차 정보 제공의 필요성이 대두되었습니다.
#### 프로젝트 목표 
- **국산차 정보 검색**: 브랜드, 모델, 연식 등 다양한 기준으로 국산차 정보를 검색할 수 있습니다.
- **리뷰 및 평점 제공**: 사용자 리뷰와 평점을 통해 각 차량에 대한 자세한 정보를 얻을 수 있습니다.
- **트렌드 분석**: 현재 시장에서 인기 있는 모델과 트렌드를 한눈에 볼 수 있습니다.
- **추천 시스템**: 사용자의 선호도와 요구사항에 맞춰 차량을 추천합니다.
- **시각화 도구**: 분석 결과를 그래프, 차트 등 다양한 형태로 시각화하여 제공합니다.

<br><br><br>

## 3. WBS 
| 000님 (팀장) | 000님 | 000님 | 000님 |
|:----------:|:----------:|:----------:|:----------:|
|DB 설계<br>Streamlit 화면 구성|자동차 등록 현황 crawling|Streamlit 화면 구성|FAQ crawling|



<br><br><br>


## 4. 기술 스텍
| Data Modeling | DB | Front-End |
|-------------|--------|-------------|
| ![BeautifulSoup](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![requests](https://img.shields.io/badge/requests-3776AB?style=for-the-badge&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white) | ![streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![folium](https://img.shields.io/badge/folium-77B829?style=for-the-badge&logo=folium&logoColor=white) 

<br><br><br>



## 5. 요구사항 명세서
사용자 요구사항 정의서는 고객의 요청 사항을 실제 개발에 적용할 수 있는 수준으로 요구사항을 재정의하여 기술한 문서입니다. 사용자 요구사항 정의서를 통해 프로젝트의 범위가 규정되어 불필요한 기능 개발로 인한 시간 및 자원 낭비를 방지하고 추후 프로젝트의 결과물을 회고하는 자료가 되기도 합니다. 
<br>[요구사항 명세서 템플릿 예시](https://www.notion.so/playdatacademy/0fb332c0e00246a58f63a16a14c0ef63)
<br>![image](https://github.com/user-attachments/assets/9b6ca273-2688-49d6-a517-7a1145f5018c)<br>
- 요구사항 ID : 요구사항별로 유일한 ID를 부여하여 기입합니다.<br>
- 요구사항명 : 도출된 요구사항을 요약할 수 있는 명칭을 기입합니다.<br>
- 구분 : 도출된 요구사항을 기능 / 성능 / 품질 / 인터페이스 / 데이터 / 운영 / 제약사항 중에서 선택하여 기재합니다.<br>
- 요구사항 설명 : 사용자 요구사항을 구체적이고 상세하게 기술합니다.<br>
- 중요도 : 해당 요구사항의 전체 시스템 구현 측면에서의 중요도를 기술합니다. (상, 중, 하)<br>
- 비고 : 항목에 포함되지 않으나, 고려해야 할 사항이 있으면 기술합니다.<br>


<br><br><br>

## 6. ERD 설계서
ERD는 실체(Entity), 관계(Relationship), 속성(Attribute) 간의 관계를 그래픽으로 표현한 다이어그램입니다.<br> ERD의 주된 목적은 데이터베이스의 논리적 구조를 시각화하여, 데이터와 이들 간의 관계를 쉽게 이해하고 분석할 수 있도록 돕는 것입니다. <br>주로 데이터베이스 설계의 초기 단계에서 사용되며, 요구사항 분석과 개념적 설계 과정에서 중요한 역할을 합니다. <br> 또한 ERD는 엔터티 간의 관계, 엔터티가 가지는 속성, 기본 키(Primary Key) 등 데이터의 논리적 관계에 대한 정보를 제공합니다.<br>
<br>[ ERD 설계서 템플릿 예시](https://www.erdcloud.com/d/TzHsgqxPRGzWGzytR)
<br>![image](https://github.com/user-attachments/assets/f16d790a-460d-4aec-bc43-4fdf53e6b071)



<br><br><br>


## 7. 주요 프로시저
![image](https://github.com/user-attachments/assets/92f489bb-abaf-4603-a160-b95fe4502661)

<br><br><br>




##  8. 프로젝트 결과 
- 테스트/ 시연 이미지 삽입

| 차량 소비자 증가 그래프 | 국산 차량 브랜드 순위 | 
|--|--|
| ![image](https://github.com/user-attachments/assets/46fba4e2-9b74-4713-8554-41aeb2e9397d) | ![image](https://github.com/user-attachments/assets/e20005ba-e86b-468d-9f8e-05cdd63a7861) |
| 상위 차량 브랜드의 모델 | 상위 차량 브랜드 통합 FAQ 조회 시스템 |
| ![image](https://github.com/user-attachments/assets/2c874e79-2ff6-4bb9-abc8-827d58713949) | ![image](https://github.com/user-attachments/assets/6d74b751-b781-4def-975d-44fdea5b7f18)

<br><br><br>



## 9. 개발 규칙 
**Code 작성 규칙**
- 패키지명 전체 소문자
- 클래스명, 인터페이스명 CamelCase
- 클래스 이름 명사 사용
- 상수명 SNAKE_CASE


**Git Branch 전략**
유형별로 구분하여 작성하고 Git Flow 적용
- **feat** : 새로운 기능 추가
- **fix** : 버그 수정
- **docs** : 문서 수정
- **style** : (코드의 수정 없이) 스타일(style)만 변경(들여쓰기 같은 포맷이나 세미콜론을 빼먹은 경우)
- **refactor** : 코드 리펙토링
- **test** : Test 관련한 코드의 추가, 수정
- **chore** : (코드의 수정 없이) 설정 변경

**협업 Rules**
- Discord ,Notion 활용
- 지각이나 결석은 꼭 말해주기 


<br><br><br>


## 10. 오류 해결 과정
### 페이지 로딩 시간 초과
- **문제**: 페이지 로딩 시간이 오래 걸려 타임아웃 오류 발생.
- **해결**: 로딩 시간을 연장하거나, 페이지가 로드되기 전에 필요한 데이터만 우선적으로 로드하도록 수정.

### API 응답 지연
- **문제**: 외부 API 응답이 지연되어 데이터 수집에 차질 발생.
- **해결**: 비동기 요청을 사용하여 API 응답을 기다리는 동안 다른 작업을 수행하도록 개선. 또한, 응답 지연 시 재시도 로직 추가.

### 데이터 저장 시 데이터베이스 연결 오류
- **문제**: 데이터 저장 과정에서 데이터베이스 연결 오류 발생.
- **해결**: 연결 타임아웃 시간을 늘리고, 연결 재시도 로직을 추가하여 안정성을 향상.


<br><br><br>


##  11. 한줄 회고 
데이터 수집과 분석을 통해 국산차 선호도 정보를 효과적으로 제공함으로써 소비자와 제조업체 모두에게 가치 있는 인사이트를 제공한 의미 있는 경험이었다.








