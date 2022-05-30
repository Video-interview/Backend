[![Willbe](https://user-images.githubusercontent.com/60756023/170631952-4dbb8e21-0636-4980-a9be-67724597bc1d.png)](https://willbedeveloper.com)

## Why Will-Be ?

### 요즘 화상 면접 안보는 곳 있나요? WillBe와 함께 준비해볼까요 👨‍💻

<br />
면접을 연습한 적은 있지만, 본인의 모습을 직접 녹화해 보신 적 있으신가요?<br>
긴장하면 나오는 목소리 톤🗣, 어울리지 않는 제스처 등 소리내어 연습하는 것만으로 알 수 있을까요?<br>
윌비와 함께 내가 모르는 나의 면접 습관을 알고 강점은 더 강하게 약점은 기록하며 보완해보세요💪💪

<br/>

### 📆 프로젝트 기간

- 2022.04.29 ~ 2022.06.03

<br/>

###  🐾 Project Members 

<table>
   <tr>
    <td align="center"><b><a href="https://github.com/llama-ste">🦙 안동현</a></b></td>
    <td align="center"><b><a href="https://github.com/AlgoRoots">🦤 박성혜</a></b></td>
    <td align="center"><b><a href="https://github.com/limjae">🦣 임재현</a></b></td>
    <td align="center"><b><a href="https://github.com/catalinakim">🐩 김경현</a></b></td>
    <td align="center"><b><a href="https://github.com/Juri-Lee">🦖 이주리</a></b></td>
  </tr>
  <tr>
     <td align="center"><a href="https://github.com/llama-ste"><img src="https://user-images.githubusercontent.com/90495580/169259372-a923afea-a898-4bca-9504-7d073d6ffab8.jpeg" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/AlgoRoots"><img src="https://user-images.githubusercontent.com/90495580/169259379-a913dd30-fa7f-4309-af30-9bd94c9608a6.png" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/limjae"><img src="https://user-images.githubusercontent.com/90495580/169259387-0e3b59ad-5882-458a-9a2b-2ccac2d696ae.png" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/catalinakim"><img src="https://user-images.githubusercontent.com/90495580/170095150-bcdacb00-ac2a-42eb-98b5-c67e05352832.jpeg" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/Juri-Lee"><img src="https://user-images.githubusercontent.com/90495580/169259405-ba67e49d-8b01-405f-b0c8-12c6054b7577.png" width="100px" /></a></td>
  </tr>
  <tr>
    <td align="center"><b>🍄 React</b></td>
    <td align="center"><b>🍄 React</b></td>
    <td align="center"><b>🌱 Spring</b></td>
    <td align="center"><b>🌱 Spring</b></td>
    <td align="center"><b>🌱 Spring</b></td>
  </tr>
</table>

<br/>
<br/>


## Service Architecture

![WillBe-service_architecture](https://user-images.githubusercontent.com/88864019/170158157-eb5066ef-93dc-42a4-9407-4cfac15d4b76.jpg)

<br/>
<br/>

## 🛠 Tools

#### Backend

<p>
  <img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
   <img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
   <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
   <br>
   <img src="https://img.shields.io/badge/java 8-007396?style=for-the-badge&logo=java&logoColor=white">
   <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=FFmpeg&logoColor=white">
   <img src="https://img.shields.io/badge/Json Web Tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
</p>

#### Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" > 
   <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>

#### Dev tools

<p> 
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
</p>

<br>
<br>

## Backend 주요 기술 및 Flow chart✨ 

### 🔐 로그인 : JWT 토큰 방식, Spring security, Java Mail sender

카카오를 통한 소셜로그인으로 간단하게 가입할 수 있어요. 이메일 회원가입에서는 유효한 이메일만 가입할 수 있도록 중복확인과 더불어 이메일 인증 링크 방식을 도입했어요. 또한 JWT 토큰 인증 방식을 통해 다중서버에서도 유저를 재인증할 필요가 없어요. 

  <img src="https://user-images.githubusercontent.com/22388388/170816612-1547cb9e-092a-400e-8422-2176eabb3a6f.png" width="90%" height="90%">
<!--![detail structure](https://user-images.githubusercontent.com/22388388/170816612-1547cb9e-092a-400e-8422-2176eabb3a6f.png) -->


### 📹 📀 동영상 저장,변환 및 업로드 : S3,Lambda, Elastic Load balancer

동영상 촬영후 업로드 버튼을 누르면 기다릴 필요없이 다른 서비스 이용이 가능해요. 유저가 기다리는 시간을 최소화하고 동영상 처리시간을 빠르게 할 수 있도록, 여러대의 서버를 loadbalancer를 통해 관리하고 있어요.

  <img src="https://user-images.githubusercontent.com/22388388/170919933-2b964eeb-c5dd-4913-a083-94cf4e03dd3d.png" width="90%" height="90%">
<!-- ![detail structure (1)](https://user-images.githubusercontent.com/22388388/170816567-6b35c99d-ab24-4951-a8ff-edc7b57207a5.png) -->


### 👑 주간 면접왕, 오늘의 질문, 핫한 카테고리 관리 : spring batch

spring batch를 사용해, 효율적으로 필요한 서비스 데이터를 산출하고 있어요. 데이터들은 히스토리처럼 쌓여 서비스 통계📊에 사용할수 있답니다!


<br/>
<br/>

## ☁️ ERD 

![Will be](https://user-images.githubusercontent.com/60756023/170617716-62ecda77-34cd-4465-948a-18ed707fd0e5.png)
<br>
<br>

## 🔥 Trouble Shooting

#### 🚨 Issue 1
### 동영상 변환 처리⌛

A. 사용자가 영상을 찍어 올리면 클라이언트에서 온 요청이 반횐될 때까지 대기시간 발생하고,
동영상이 처리 중일 때 다른 사용자들의 요청이 지연되는 현상이 발생했어요<br>
<br>
클라이언트 요청이 수행되고 응답이 올 때까지 너무 긴 시간이 소요되며, 동영상이 처리 중일 때 다른 사용자들의 요청이 지연되는 현상이 발생했어요.
<br>
🛑 cause : <br>
- 영상의 확장자를 변환하는 과정이 동기로 처리되고 있어 문제가 발생되고 있었어요.

#### 🚥 solution :
- 동영상 변환 과정을 @async 어노테이션을 통해 비동기로 처리하여 변환 요청이 올 때 변환 과정을 기다리는 과정 생략했어요.
- 해당 영상은 동영상 변환 도중 사용자들은 피드백 페이지 목록에서 인코딩이 진행되고 있음을 보여주도록 처리했어요.
<br>
<br>
B. 동영상 처리시 서버 관련 문제<br>
<br>
동영상 변환 처리 중 서버의 전체적인 응답 속도가 지연되거나 서버가 다운되는 현상이 발생 했어요.
<br> 

🛑 cause: <br>
- 사용중인 EC2인스턴스 t2.micro 사양의 한계로 문제가 발생하고 있었어요. 현재 서버의 가용 RAM은 1GB인데 FFmpeg 라이브러리를 사용하면 하나의 영상을 처리하는 도중 평균 100 MG의 RAM을 사용했어요. 

#### 🚥 solution : 
- 동영상 변환 과정은 상대적으로 많은 자원을 소모하므로 API서버와 분리하여 개별적인 EC2 인스턴스에 동영상만을 처리하는 서버를 추가로 설치하여 따로 처리하도록 변경했어요.
<hr/>

#### 🚨 Issue 2
### Thumbnail 처리 🚧  

<br>
피드백을 작성시 클라이언트에서 Thumbnail을 추출하여 S3에 저장하면 <br>
AWS Lambda를 사용하여 해당 이미지를 4:3으로 crop하는 동안 사용자가 이미지를 정상적으로 확인 할 수 없는 문제가 발생했어요.  
<br> 

🛑 cause: <br>
- S3에서 썸네일이 저장되는 이벤트가 발생하면 그때부터 lambda가 실행되기 때문에 지연 시간이 발생해요. <br> 
   따라서 lambda의 동작이 완료되기 전에는 썸네일이 정상적으로 보이지 않는 문제가 . 

#### 🚥 solution :
- 썸네일 이미지 크기 조정이 완료 되지 않으면클라이언트에 is_thumbnail_converted 항목을 만들어서 false로 응답해주도록 수정했어요.

<hr/>
#### 🚨 Issue 3
### 인터뷰 삭제 🚧  

<br>
사용자가 인터뷰 게시물 1개를 삭제할 경우, 인터뷰 테이블에서는 해당 인터뷰 ID의 레코드는 삭제하면서 <br>
그 인터뷰가 주간 면접왕인 경우, 주간 면접왕 테이블에서는 삭제하지 않으려고 했어요.
<br> 

🛑 cause: <br>
- 주간 면접왕 테이블에 인터뷰ID가 @ManyToOne으로 연관관계 매핑되어 있었어요. 

#### 🚥 solution :
- step 1: 스택오버플로우에 나와있는 방법들을 다 시도해 보았지만, 인터뷰 레코드 조차도 삭제가 안되는 등 인터뷰 테이블에서만 삭제되지 않았어요.
- step 2: 면접왕 클래스의 인터뷰 필드를 인터뷰 타입에서 Long타입으로 바꿔주고, 연관관계 없이 인터뷰ID만 저장하게 변경했어요.

<br/>
<br/>
<br/>

## 🚀 부록

### ⭐ Error Code

![에러코드-](https://user-images.githubusercontent.com/60756023/170940249-6a7ec37d-710b-4489-8367-acc450f60e43.png)
