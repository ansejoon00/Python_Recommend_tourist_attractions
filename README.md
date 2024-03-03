# Recommend tourist attractions
> **구글 맵 API를 사용해서 사용자가 원하는 관광지 정보를 크롤링 하여 여행 일정을 구성해 주는 앱**

<div align="center">
<img width="143" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/195948c5-04a4-473a-86d0-4fd559ca85b8">
<div align="left">

---

## 프로젝트 소개
> 로그인 기능을 통해 **보안성**을 높이고 관리자가 회원관리를 할 수 있게 하여 API 제한을 확인함.

> 여행에 기본인 날짜 선택부터, 사용자 정보, 나라 등 정보를 받고 거리 계산을 통해 **유럽 여행 일정을 생성함.**

> 사용자가 잘못된 값 입력, 궁금한 정보 등 다양한 테스트를 통해 **오류를 최소화**했음.

## Stacks 🐈

### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)

### Data Base
![SQLITE](https://img.shields.io/badge/sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScriipt-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=black)

### Communication
![KakaoTalk](https://img.shields.io/badge/Kakao_Talk-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

---
## 화면 구성 📺
<div align="center">

| 로그인 페이지 | 회원가입 페이지 |  
| :-------------------------------------------: | :------------: |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/a977b657-e5fb-4f11-875c-22f7ae5de50e"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/9c55ae9a-a04f-4eb6-b4fe-26ee31c39d43"> |
| 비밀번호가 일치할 때 | 비밀번호가 일치하지 않을 때 |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/64a88052-05c9-4d91-9935-9be833e4de7b"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/31a1eed2-dd01-4ef2-bbf3-9f676efa46f5"> |
| 시작 / 끝 날짜 | 사용자 정보 입력 |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/454f180c-f8ce-4cd8-9083-8a4662e8fa9d"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/b37b9dd5-92b8-4416-bd00-b690579564b6"> |
| 나라 선택 | 지역 선택 |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/8a00b807-065a-45b2-bc90-f922b388cb5f"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/ecbfefd9-086c-40d5-8c28-d086ec5a40d3"> |
| 사용자별 관광지 추천 및 관광지 선택 | 관광지에 대한 정보 알기 |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/1bcbe26e-dcd8-4d02-933a-e347e083afed"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/4c38da71-dec2-40d4-a55f-f549d99865d9"> |
| 숙소 입력 | 교통수단 선택 | 
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/a27658ed-a467-411b-b87d-5525df51a548"> |<img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/8a3ba785-c8a1-4eec-b806-e675ffad3198"> |
| 최종 결과 | 여러 오류 상황에 대비한 메시지 |
| <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/1e7270ee-e847-431b-8bf7-115853d57cfa"> | <img width="400" alt="image" src="https://github.com/ansejoon00/Python_Recommend_tourist_attractions/assets/156414896/82a19de5-5f1e-4db4-8672-92e0c1523265"> |

<div align="left">

---
## 아키텍처

### 디렉터리 구조
```bash
├── static
│   ├── css
│   │   ├── 1_login.css
│   │   ├── 2_signup.css
│   │   ├── 3_select_period.css
│   │   ├── 4_information.css
│   │   ├── 5_select_location.css
│   │   ├── 6_select_sleep.css
│   │   ├── 7_select_move.css
│   │   └── 9_result_table.css
│   │
│   └── js
│       ├── 5_select_location.js
│       ├── 7_select_move.js
│       └── 9_result_table.js
│       
├── templates
│   ├── 1_login.html
│   ├── 2_signup.html
│   ├── 3_select_period.html
│   ├── 4_information.html
│   ├── 5_select_location.html
│   ├── 6_select_sleep.html
│   ├── 7_select_move.html
│   ├── 7_select_move_last.html
│   └── 9_result_table.html
│
├── Flow_Chart-Recommend tourist attractions.drawio.png : 순서도
│
├── README.md : 리드미 파일
│
├── Travel.db : Data Bases
│
└── app.py : 실행 파일
