> **[LIKELION]** TECHIT BACK-END SCHOOL 8기

![image](https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/oneclick_donation.png)

- 프로젝트 기간: 2024.03.13 ~ 2024.04.04
- Team: Oneclick_Donation 🤍

---


### 🎖️  팀원 소개
<br>
<div align="center"> 
<table>
    <tr>
        <td align="center">
            <a>
            </a>
                <img src="https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/profile.png" width="100px" />
        </td>
        <td align="center">
            <a>
                <img src="https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/bagjuyun.png" width="100px" />
            </a>
        </td>
        <td align="center">
            <a>
                <img src="https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/chi.png" width="100px" />
            </a>
        </td>
        <td align="center">
            <a>
                <img src="https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/images.png" width="100px" />
            </a>
        </td>
    </tr>
    <tr>
        <td align="center">
            <b>김소은</b>
        </td>
        <td align="center">
            <b>박주윤</b>
        </td>
        <td align="center">
            <b>정치헌</b>
        </td>
        <td align="center">
            <b>김기현</b>
        </td>
    </tr>
  <tr>
        <td align="center">
            <b>팀장</b>
            <br>
            - 회원가입 <br>
            - 관리자 <br>
            - Toss API <br>
            - 프론트 
        </td>
        <td align="center">
            <b>팀원</b>
            <br>
            - 모금 제안 <br>
            - 캠페인 소식 <br>
            - 게시판 기능 <br>
            - Toss API
        </td>
        <td align="center">
            <b>팀원</b>
            <br>
            - 마이페이지
        </td>
        <td align="center">
           <b>팀원</b>
            <br>
            - 로그인 <br>
            - OAuth2
        </td>
    </tr>
</table>
</div>
<br>

---

### ✨ 프로젝트 소개


- `Oneclick_Donation`은 경제에 기여하기 위한 프로젝트로 기부자와 수혜자 간의 연결을 강화하고, 기부 과정을 투명하고 효율적으로 만들기 위해 만들어 졌습니다. 
- 이 서비스는 기부자가 쉽게 기부할 수 있는 결제 시스템과 기부 캠페인을 관리할 수 있는 기능을 제공하여, 기부 문화를 활성화하고 사회적 가치를 창출하는 것을 목표로 합니다.


### 👩🏻‍💻 기술 스택 

#### &nbsp;　[ DB ]
&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>

#### &nbsp;　[ Backend ]

&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/Java 17-FF160B?style=flat-square&logo=java&logoColor=white"/>&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=springsecurity&logoColor=white&color=darkgreen"/>&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/JsonWebToken-000000?style=flat-square&logo=JSON Web Tokens&logoColor=white"/>&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/JPA-088142?style=flat-square&logo=jpa&logoColor=white"/>

#### &nbsp;　[ Frontend ]

&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white">&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=CSS3&logoColor=white&color=darkblue">&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=black">&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white"/>

#### &nbsp;　[ Etc... ]

&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/>

### 📝 프로젝트 설계 및 기획


<strong>ERD</strong>

![ERD](https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/ERD.png)


<br>


<strong>이벤트 스토밍</strong>

![event](https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/event.png)



<br>


<strong>구조도</strong>

![event](https://github.com/likelion-backend8th-5team/Oneclick_Donation/blob/main/OneclickDonation/assets/gujodo.png)

<br>
<br>

## 주요 기능 설명

### 회원가입

사용자는 회원가입을 진행할 수 있습니다.

- 아이디와 비밀번호를 제공하여 회원가입을 할 수 있습니다.
- 추가적인 이메일 인증을 통해 회원가입을 진행 할 수 있습니다.
- OAuth로 회원가입을 할 수 있습니다.

### 사용자 관리 및 인증

JWT를 이용해서 인증 및 권한을 진행할 수 있습니다.

- 4가지의 사용자가 존재합니다.(비활성, 개인, 단체, 관리자)
- 비활성 사용자는 읽기의 권한만 존재합니다.
- 개인 사용자는 단체 사용자로 추가 정보를 입력하여 전환 신청을 할 수 있습니다.
- 관리자는 단체 사용자 전환 신청 목록을 확인하고, 승인 또는 거절할 수 있습니다.

### 기부 및 모금 캠페인 관리

- 사용자(단체)는 새로운 모금 캠페인을 등록할 수 있습니다.
- 사용자(단체)는 등록한 모금 캠페인을 수정하거나 삭제할 수 있습니다.
- 모금 캠페인의 상태(진행 중, 종료)를 관리합니다.
- 관리자는 새로운 모금 캠페인을 승인 또는 거절할 수 있습니다.
- 거절된 경우 이유를 사용자(단체)에게 안내합니다.

### 기부 홈페이지

모금 중, 모금 종료 페이지가 존재합니다.

- 모금 중에서는 현재 진행 중인 캠페인을 볼 수 있습니다.
- 모금 종료에서는 모금 캠페인 상태가 종료인 캠페인을 볼 수 있습니다.
- 사용자는 모금 캠페인이 진행 중인 캠페인의 상세 페이지에서 기부하고, 댓글을 달 수 있습니다.

### 결제 시스템 (Toss Payments)

사용자는 Toss Payments를 통해 기부할 수 있습니다.
- 결제가 이루어지면 모금 현황이 자동으로 갱신됩니다.

