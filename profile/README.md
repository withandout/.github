# 🏃‍♂️ WithandOut - 최종 PJT

SSAFY 10기 1학기 최종 프로젝트 - WithandOut

## 📍 WithandOut - 개요

**기간**
2023.11.16(목) ~ 2023.11.24(금)

**프로젝트 소개**
현재 본인의 주변 지역에서 함께하면 좋은 운동 프로그램을 사람들과 함께 할 수 있도록 만든 플랫폼

## 🧑‍💻 프로젝트 구성원

<table>
  <tr>
    <td align="center">
        <a href="https://github.com/youngkimi">
            <img src="https://avatars.githubusercontent.com/u/139294219?v=4" width="100px;" alt=""/>
            <br />
            <sub>
                <b>김영섭</b>
                <br/>
                <b>백엔드 총괄</b>
            </sub>
        </a>
        <br />
    </td>    
    <td align="center">
        <a href="https://github.com/Lainlnya">
            <img src="https://avatars.githubusercontent.com/u/93235981?v=4" width="100px;" alt=""/>
            <br />
            <sub>
                <b>***</b>
                <br/>
                <b>프론트엔드 총괄</b>
            </sub>
        </a>
        <br />
    </td>
 </tr>
</table>

## 🚩 주요 기능

1. **로그인**
   - 세션 스토리지를 기반으로 한 로그인 기능
   - 로그인된 사용자의 경우 URI를 통해 로그인 페이지로 이동 불가 기능
2. **회원가입**
   - 아이디 및 닉네임 중복 확인 기능
   - 이미지 업로드 기능
3. **파티 참여 신청**
   - 동네 인증이 완료된 사용자에 한해 해당 동네에 만들어진 파티 리스트 확인 기능
   - 파티 리스트 클릭시 각 파티에 대한 정보 확인 기능
   - 클릭된 파티의 리더 네임카드 확인 기능
   - 파티 참여 신청 클릭시 동네 인증이 완료된 사용자에 한해 해당 파티의 리더에게 파티 신청 알람 발송 기능
   - 본인이 참여하고 있는 파티를 제외한 파티 리스트 확인 기능
   - 신청하기 클릭시 클릭된 파티를 제외한 파티 리스트 확인 기능
4. **파티 생성**
   - 동네 인증이 완료된 사용자에 한해 파티 생성 가능 기능
   - 본인을 리더로 한 파티 생성 기능
   - 파티 최대 인원 조정 기능
   - 이미지 업로드 기능
5. **참여중인 파티**
   - 현재 참여 중인 멤버 확인 기능
   - 멤버별 운동 로그 확인 및 랭킹 확인 기능
   - 등록된 이벤트 신청 및 취소 기능
   - 갤러리 확인 기능
6. **마이페이지**
   - 공공 데이터 API 서비스를 이용한 위치 기반 날씨 기능 구현
   - vuetify를 활용한 달력 라이브러리 사용과 파티의 이벤트 표시 기능 구현
   - 현재 운동 로그를 기반으로 한 cheerup 문구 표시 기능 구현
   - 참여 중인 파티 정보 확인 기능
   - 개인 네임 카드 확인 및 소개글 수정 기능
7. **NavBar**
   - 파티의 리더에게 오는 초대 알람 확인 및 수락, 거절 기능
   - 현재 위치와 카카오맵 API를 활용한 동네 인증 기능
   - 로그아웃 기능
   - 마이페이지로 이동 기능

## 🚩 주요 기술

1. Language

   - Java 8
   - Javascript

2. Framework

   - Springboot 2.7.17
   - Vue 3.3.8

3. Library

   - fontawesome
   - pinia
   - vuetify
   - v-calender
   - vue-router
   - vue-geolocation-api

4. DB

   - MySQL 8.0.32

5. OS

   - mac OS

6. BackEnd
   - Swagger

## 🔖 협업 툴

- GitHub
  1. dev 브랜치 작업으로 작업이 끝난 기능에 대해 main으로 merge
- Notion

  1. API 명세서 작성
  2. Debug 리스트 작성
  3. 간트 차트를 통한 일정 관리
  4. 프론트엔드 기능 리스트 관리

- MatterMost
- Figma
  1. 와이어프레임
  2. mock up 구현
- Google SpreadSheets
  1. 기능 명세서 작성

## 상세 화면

### 로그인

<img width="1512" alt="login" src="https://github.com/withandout/withandoutBE/assets/93235981/87970d1c-8d9a-4c18-87db-0ccebd60ddcf">

### 회원가입

<img width="1510" alt="signup" src="https://github.com/withandout/withandoutBE/assets/93235981/822f0d1f-9aa9-4722-8f1e-a8146a2ee88a">

### 메인페이지

메인페이지에서 동네 인증하는 화면
<img width="1512" alt="main_town" src="https://github.com/withandout/withandoutBE/assets/93235981/ac8c92f5-cd9a-4b25-be0b-b2ade5653cff">

메인페이지에서 알림 확인
<img width="1512" alt="main_alarm" src="https://github.com/withandout/withandoutBE/assets/93235981/f0b94d23-98a0-4e56-83f1-ec82f1094670">

메인페이지에서 현재 예정된 이벤트 확인
<img width="1512" alt="main_calander" src="https://github.com/withandout/withandoutBE/assets/93235981/293666ef-95c5-47dd-ac38-20d524a47f32">

메인페이지에서 개인 네임카드 수정 화면
<img width="1512" alt="main_modify" src="https://github.com/withandout/withandoutBE/assets/93235981/d89db47c-dd92-477c-9bc3-38014cc46b5f">

메인페이지에서 날씨 API 확인 화면
<img width="1512" alt="main_weather" src="https://github.com/withandout/withandoutBE/assets/93235981/ea817fdb-d629-4d1c-9a32-946a2840d165">

### 파티 생성

<img width="1512" alt="make_party" src="https://github.com/withandout/withandoutBE/assets/93235981/5dda253e-cce9-409b-b04e-88b9b83ddd79">

### 파티 신청

파티 신청 리스트 및 현재 클릭된 파티의 정보, 리더 정보 확인
<img width="1512" alt="join_party" src="https://github.com/withandout/withandoutBE/assets/93235981/843e298d-8023-4ad0-9df3-6e85a25965b9">

파티 신청시 보여줄 파티 신청 정보 확인
<img width="1511" alt="join_info" src="https://github.com/withandout/withandoutBE/assets/93235981/0757053a-50df-4cbe-b61f-1fddb4fc3f4d">
