# jogaczip_codeit_boost
<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=기억%20저장%20및%20공유%20서비스%20-%20조각집&fontSize=40" />


## 📌 코드잇 부스트 동아리 데모데이 프로젝트  
프로젝트명: 기억 저장 및 공유 서비스 - "조각집" <br>
개발기간: 2024.08 ~ 2024.09
<br/> <br/>


## 🔍 주요 기능

### 1. 그룹
#### 그룹 등록
- 그룹명, 대표 이미지, 그룹 소개, 그룹 공개 여부, 비밀번호를 입력하여 그룹 등록 가능

#### 그룹 수정
- 그룹 등록 시 입력했던 비밀번호를 입력하면 그룹 정보 수정 가능

#### 그룹 삭제
- 그룹 등록 시 입력했던 비밀번호를 입력하면 그룹 삭제 가능

#### 그룹 목록 조회
- 등록된 그룹 목록을 조회할 수 있음
- 각 그룹의 정보:
  - 이미지(한 장), 그룹명, 그룹 소개, 그룹 공개 여부, 디데이(생성 후 지난 일수), 획득 배지 수, 추억 수, 그룹 공감 수
- 공개 그룹과 비공개 그룹 목록을 구분하여 조회 가능
- **정렬 및 검색 기능**:
  - 정렬: 최신순, 게시글 많은 순, 공감 순, 획득 배지 순
  - 검색: 그룹명을 기준으로 검색 가능

#### 그룹 상세 조회
- 그룹 목록에서 그룹을 클릭하면 해당 그룹의 상세 정보 조회 가능
- 비공개 그룹은 비밀번호를 입력하여 조회 가능 
- 상세 정보:
  - 대표 이미지, 그룹명, 그룹 소개, 그룹 공개 여부, 디데이, 획득 배지 목록, 추억 수, 그룹 공감 수
- **기능**:
  - **공감 보내기**: 클릭할 때마다 그룹의 공감 수 증가
  - 그룹에 등록된 추억 목록 표시

<br>

### 2. 게시글(추억)
#### 게시글 등록
- 닉네임, 제목, 이미지(한 장), 본문, 태그, 장소, 추억의 순간, 추억 공개 여부, 비밀번호를 입력하여 추억 등록 가능

#### 게시글 수정
- 추억 등록 시 입력했던 비밀번호를 입력하면 게시글 수정 가능

#### 게시글 삭제
- 추억 등록 시 입력했던 비밀번호를 입력하면 게시글 삭제 가능

#### 게시글 목록 조회
- 그룹 상세 조회 시 해당 그룹의 추억 목록을 함께 조회 가능
- 각 게시글의 정보:
  - 닉네임, 추억 공개 여부, 제목, 이미지, 태그, 장소, 추억의 순간, 추억 공감 수, 댓글 수
- 공개 추억과 비공개 추억을 구분하여 조회 가능
- **정렬 및 검색 기능**:
  - 정렬: 최신순, 댓글 순, 공감 순
  - 검색: 제목, 태그를 기준으로 검색 가능

#### 게득
- **배지 종류**:
  - 7일 연속 추억 등록
  - 그룹 공감 수 1만 이상
  - 추억 공감 수 1만 이상 (공감 1만 개 이상의 추억이 하나라도 있을 경우)
 
  <br><br>

## 🖥️ 화면 구성


<table>
  <tr>
    <th>그룹 목록 페이지</th>
    <th>비공개 그룹 목록 페이지</th>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/54152120-86de-4cea-9beb-c61d4ca020b5"  width="400"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/edd5b73e-b9e4-4551-8519-056dc45e3dd5" alt="비공개 그룹 목록 페이지" width="400"></td>
  </tr>
  <tr>
    <th>그룹 상세 페이지</th>
    <th>비공개 그룹 상세 페이지</th>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/439d0e72-30ac-4da8-9ec7-1c0bd70ea302" alt="그룹 상세 페이지" width="400"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/3f479266-06a8-42c6-b843-4ca78a2614a6" alt="비공개 그룹 상세 페이지" width="400"></td>
  </tr>
    <tr>
    <th>추억 올리기 페이지</th>
    <th>추억 상세 페이지</th>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/4932e3bd-90e5-44a6-8f82-5eb28e32f6ac" alt="추억 올리기 페이지" width="300"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/dfd9eeea-c2a1-4c81-8ef4-7559d141de2c" alt="추억 상세 페이지" width="300"></td>
  </tr>
</table>

  <br><br>

## 🤝 Team
|<img src="https://avatars.githubusercontent.com/u/147029375?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/144078388?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/155574607?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|
|김한얼[@Kimhaneol12](https://github.com/Kimhaneol12) |조예림[@YeRimmm-Cho](https://github.com/YeRimmm-Cho)|최민기[@mkchoii](https://github.com/mkchoii)|
|백엔드 |프론트엔드 및 배포 |백엔드 및 배포 |  

  <br><br/>

## 🛠️ 기술 스택
### ✔️Front-end
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
### ✔️Back-end
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white"><img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=SQLite&logoColor=white">
### ✔️배포
<img src="https://img.shields.io/badge/amazonwebservices-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">


