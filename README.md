# jogaczip_codeit_boost
<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=기억%20저장%20및%20공유%20서비스%20-%20조각집&fontSize=40" />


## 📌 코드잇 부스트 동아리 데모데이 프로젝트  
프로젝트명: 기억 저장 및 공유 서비스 - "조각집" <br>
개발기간: 2024.08 ~ 2024.09
<br/> <br/>


## 🔍 주요 기능

### 1. 그룹
#### 그룹 등록
- 그룹명, 대표 이미지, 그룹 소개, 그룹 공개 여부, 비밀번호를 입력하여 그룹을 등록할 수 있습니다.

#### 그룹 수정
- 그룹 등록 시 입력했던 비밀번호를 입력하면 그룹 정보를 수정할 수 있습니다.

#### 그룹 삭제
- 그룹 등록 시 입력했던 비밀번호를 입력하면 그룹을 삭제할 수 있습니다.

#### 그룹 목록 조회
- 등록된 그룹 목록을 조회할 수 있습니다.
- 각 그룹의 정보:
  - 이미지(한 장), 그룹명, 그룹 소개, 그룹 공개 여부, 디데이(생성 후 지난 일수), 획득 배지 수, 추억 수, 그룹 공감 수
- 공개 그룹과 비공개 그룹 목록을 구분하여 조회 가능합니다.
- **정렬 및 검색 기능**:
  - 정렬: 최신순, 게시글 많은 순, 공감 순, 획득 배지 순
  - 검색: 그룹명을 기준으로 검색 가능

#### 그룹 상세 조회
- 그룹 목록에서 그룹을 클릭하면 해당 그룹의 상세 정보를 조회할 수 있습니다.
- 비공개 그룹은 비밀번호를 입력하여 조회 가능합니다.
- 상세 정보:
  - 대표 이미지, 그룹명, 그룹 소개, 그룹 공개 여부, 디데이, 획득 배지 목록, 추억 수, 그룹 공감 수
- **기능**:
  - **공감 보내기**: 클릭할 때마다 그룹의 공감 수 증가
  - 그룹에 등록된 추억 목록 표시

<br>

### 2. 게시글(추억)
#### 게시글 등록
- 닉네임, 제목, 이미지(한 장), 본문, 태그, 장소, 추억의 순간, 추억 공개 여부, 비밀번호를 입력하여 추억을 등록할 수 있습니다.

#### 게시글 수정
- 추억 등록 시 입력했던 비밀번호를 입력하면 게시글을 수정할 수 있습니다.

#### 게시글 삭제
- 추억 등록 시 입력했던 비밀번호를 입력하면 게시글을 삭제할 수 있습니다.

#### 게시글 목록 조회
- 그룹 상세 조회 시 해당 그룹의 추억 목록을 함께 조회할 수 있습니다.
- 각 게시글의 정보:
  - 닉네임, 추억 공개 여부, 제목, 이미지, 태그, 장소, 추억의 순간, 추억 공감 수, 댓글 수
- 공개 추억과 비공개 추억을 구분하여 조회 가능합니다.
- **정렬 및 검색 기능**:
  - 정렬: 최신순, 댓글 순, 공감 순
  - 검색: 제목, 태그를 기준으로 검색 가능

#### 게시글 상세 조회
- 추억 목록에서 추억을 클릭하면 상세 내용을 확인할 수 있습니다.
- 상세 정보:
  - 닉네임, 제목, 이미지, 본문, 태그, 장소, 추억의 순간, 추억 공개 여부, 추억 공감 수, 댓글 수
- **기능**:
  - **공감 보내기**: 클릭할 때마다 추억의 공감 수 증가
  - 해당 추억의 댓글 목록 표시

<br>

### 3. 댓글
#### 댓글 등록
- 닉네임, 댓글 내용, 비밀번호를 입력하여 댓글을 등록할 수 있습니다.

#### 댓글 수정
- 댓글 등록 시 입력했던 비밀번호를 입력하면 댓글을 수정할 수 있습니다.

#### 댓글 삭제
- 댓글 등록 시 입력했던 비밀번호를 입력하면 댓글을 삭제할 수 있습니다.

#### 댓글 목록 조회
- 추억을 조회할 때 해당 추억에 등록된 댓글 목록이 함께 표시됩니다.
- **댓글 정보**:
  - 닉네임, 댓글 생성 날짜, 댓글 내용

<br>

### 4. 배지
- **배지 획득 조건**:
  - 그룹은 일정 조건을 달성하면 자동으로 배지를 획득합니다.
- **배지 종류**:
  - 7일 연속 추억 등록
  - 그룹 공감 수 1만 이상
  - 추억 공감 수 1만 이상 (공감 1만 개 이상의 추억이 하나라도 있을 경우)
 
  <br><br>


## 🤝 Team
|<img src="https://avatars.githubusercontent.com/u/147029375?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/144078388?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/155574607?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|
|김한얼[@Kimhaneol12](https://github.com/Kimhaneol12) |조예림[@YeRimmm-Cho](https://github.com/YeRimmm-Cho)|최민기[@mkchoii](https://github.com/mkchoii)|
|BE |FE |BE |  

  <br><br/>

## 🛠️ 기술 스택
### ✔️Front-end
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
### ✔️Back-end
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white"><img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=SQLite&logoColor=white">

