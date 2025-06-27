# be12-404Error-EduLink



## 📌 프로젝트 주제 
### EduLink: 혁신적인 학습 관리 플랫폼
<div align="center">
    <img src="./images/readme_images/service.png" /> <br>
</div>

빠르게 증가하는 국비지원 부트캠프 수요에 맞춰 학습 환경의 질적 향상을 목표로 개발된 EduLink는 기존 LMS(HRD-Net)의 한계를 보완합니다.   

이 플랫폼은 단순 출결 확인을 넘어 커리큘럼 관리, 공지사항 통합, 학습 성과 분석 등 다양한 기능을 통해 학습 효율을 극대화합니다.   

수강생들은 EduLink를 통해 학습 전반을 체계적으로 관리하고 편리하게 활용할 수 있습니다.

[프로젝트 개요 보기](https://github.com/museongkim0/edulink/wiki/1.-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B0%9C%EC%9A%94)

### 프로젝트 목표

<details>
<summary>프론트엔드 프로젝트 목표</summary>

- 직관적이고 편리한 UI/UX를 통해 학습자와 강사, 매니저가 쉽게 접근하고 활용할 수 있는 프론트엔드를 설계합니다.
- 학습 진도, 과제 제출 상태, 평가 결과를 시각적으로 확인할 수 있는 대시보드를 개발합니다.
- 권한에 따라 다르게 대시보드를 다르게 구성하여 사용자 구분에 적합한 기능을 제공합니다.

</details>

<details>
<summary>백엔드 프로젝트 목표</summary>

- EduLink 서비스의 백엔드 서버를 구현하고, 이전에 개발한 프론트엔드 서버와 연결합니다.
- 기본적인 기능 구현에서 나아가 여러 시나리오 기반으로 성능을 테스트하고 개선합니다.
- 구현된 기능의 문제점을 효율적으로 보완하기 위해 고도화합니다.

</details>


<details>
<summary>데브옵스 프로젝트 목표</summary>

- EduLink 서비스에서 Jenkins, Kubernetes, Ansible을 활용하여 코드 변경부터 배포까지의 CI/CD 프로세스를 자동화하고, 블루/그린 배포 방식을 통해 무중단 배포를 실현합니다.
- Ansible을 이용해 Elasticsearch와 MongoDB의 설치 및 관리를 자동화함으로써 일관된 환경을 유지하고 운영 효율성을 높이는 것을 목표로 합니다.
- 디스코드 알림과 빠른 롤백 메커니즘을 도입하여 시스템 안정성을 보장하고 사용자 경험을 지속적으로 유지하는 데 중점을 둡니다.

</details>

## 💡팀

<div align=center>
  <img src="./images/readme_images/team.png" /> <br>
    <h3>한화시스템 BEYOND SW캠프 </h3>
    <p>12기 미니 프로젝트 <strong>팀 404Error</strong></p>
</div>



## 🤚 404Error 팀원
<div style="display: flex; justify-content: center;">
  <table  align="center">
    <tbody>
      <tr>
        <td align="center"><a href="https://github.com/museongkim0" style="text-decoration: none; color: lightgray;"><img src="./images/팀원소개/ms.jpg" width="100px;" height="100px;" background-size="cover;" alt=""/><br /><sub><b> 🐯 김무성</b></sub></a><br /></td>
        <td align="center"><a href="https://github.com/kuj7882" style="text-decoration: none; color: lightgray;"><img src="./images/팀원소개/yj.jpg" width="100px;"  alt=""/><br /><sub><b> 🐶 김유진</b></sub></a><br /></td>
        <td align="center"><a href="https://github.com/GoodLeaf" style="text-decoration: none; color: lightgray;"><img src="./images/팀원소개/jy.png" width="100px;" height="100px;" alt=""/><br /><sub><b> 🐺 김정엽</b></sub></a><br /></td>
        <td align="center"><a href="https://github.com/gunha0405" style="text-decoration: none; color: lightgray;"><img src="./images/팀원소개/gh.jpg" width="100px;" alt=""/><br /><sub><b> 🐱 오건하</b></sub></a><br /></td>
        <td align="center"><a href="https://github.com/leewoojin12" style="text-decoration: none; color: lightgray;"><img src="./images/팀원소개/wj.jpg" width="100px;" alt=""/><br /><sub><b> 🦁 이우진</b></sub></a><br /></td>
      </tr>
    </tbody>
  </table>
</div>

<!--
## ⭐ 접속 주소

**서비스 접속 주소**<br>
<a href="http://www.edulink.kro.kr">www.edulink.kro.kr</a><br>
<details>
<summary>테스트 계정</summary>

- 학생 : student@test.com
- 강사 : instructor@test.com
- 매니저 : manager@test.com
- 비밀번호 : qwer1234
</details>
-->

## 🔧 기술 스택

프론트엔드  
![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) 
![pinia](https://img.shields.io/badge/Pinia-f7d336?style=for-the-badge&logo=pinia&logoColor=white) 
![NginX](https://img.shields.io/badge/NginX-009639?style=for-the-badge&logo=nginx&logoColor=white)  

백엔드  
![](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring-Boot&logoColor=white) ![](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-%232F7D32.svg?style=for-the-badge&logo=json-web-tokens&logoColor=white) 

DB<br>
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) 

AWS 클라우드  
![](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white) 
![](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white) 
![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white) 

데브옵스(CI/CD) <br>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) 
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)<br>
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%23d24939.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Ansible](https://img.shields.io/badge/ansible-%231a1918.svg?style=for-the-badge&logo=ansible&logoColor=white)

협업 툴  
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-%232C2E3A.svg?style=for-the-badge&logo=figma&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-00599C?style=for-the-badge&logo=discord&logoColor=white) 



## 🖥️ 시스템 아키텍쳐

### ☁️ AWS 시스템 아키텍처

<img src="./images/readme_images/sys_arc.png" style="width:100%;"/>

- 기능 테스트를 위한 서비스 접속 주소는 AWS 시스템 아키텍처를 통해 배포됩니다.

### 🏁 최종 시스템 아키텍처

<img src="./images/readme_images/devops_sys_arch.png" style="width:100%;"/>


## 👩‍💻 소프트웨어 아키텍처
 
 <img src="./images/readme_images/sw_arc.png" style="width:100%;"/>

- 유지보수성과 확장성을 위해 MVC(Model-View-Controller)와 레이어드 아키텍처(Layered Architecture)를 적용하여 역할을 명확히 분리하고, 코드의 가독성과 재사용성을 높였습니다.

## 📃 API 명세서
<a href="http://www.edulink-back-api.kro.kr:8080/swagger-ui/index.html">API 명세서</a>

## 📝 기획 & DB구성 프로젝트
[기획 & DB구성 프로젝트 깃헙 링크](https://github.com/beyond-sw-camp/be12-1st-404Error-EduLink)

## 🎨 프론트엔드 프로젝트
[프론트엔드 프로젝트 깃헙 링크](https://github.com/beyond-sw-camp/be12-2nd-404Error-EduLink)

## ⚙️ 백엔드 프로젝트
[백엔드 프로젝트 깃헙 링크](https://github.com/beyond-sw-camp/be12-3rd-404Error-EduLink)

## 🚀 데브옵스 프로젝트
[데브옵스 프로젝트 깃헙 링크](https://github.com/beyond-sw-camp/be12-4th-404Error-EduLink)
