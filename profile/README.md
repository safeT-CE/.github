# 🚴 safeT Project!

<div align="center">
  <img width="477" alt="image" src="https://github.com/user-attachments/assets/027be16c-2f31-4995-96ac-cb717babc8e8"></br>
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/safeT-CE&count_bg=%23FFC107&title_bg=%23555555&icon=github.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false" />
</div></br>

## SafeT
>**AI 기술을 이용한 스마트 전동킥보드 안전 시스템**</br> 
>**2024.3 ~ 2024.10**

</br>

## 프로젝트 소개
**팀명 : safeT** </br> 
**주제 : AI 기술을 이용한 스마트 전동킥보드 안전 시스템**</br> 
**개발 기간 : 2024.3.4 ~ 10.25**</br>
**safeT란? 교통 안전을 의미하는 'safety'와 전동 킥보드 손잡이를 표현한 'T'가 만나 만들어진, 전동 킥보드 안전 시스템입니다!** </br></br>
 2024년 기준, 우리나라는 전동 킥보드 사용자가 급격하게 증가함에 따라 관련 사고 또한 급증하는 사회적 문제가 대두되고 있습니다.</br>
 전동 킥보드 사용자가 도로 교통법을 지켜 안전한 운행을 하도록 시스템적 환경 조성 차원에서 해당 프로젝트를 진행하게 되었습니다.</br>
 본 프로젝트는 안면 인식 기술을 기반으로 앱에 등록된 면허 소유 이용자만 운전이 가능하도록 권한을 부여한 전동 킥보드 시스템을 제공합니다.</br> 
 더불어 안전모 착용 여부와 2인 이상 탑승 여부, 도로 구별을 통한 경고 시스템 등을 통해 안전성을 대폭 강화한 특징을 지니고 있습니다.</br>
 <br><br>


## 💁 개발팀 소개
|      박효영      |      김정은      |      이민영      |      김현진      |
|:-------------:|:-------------:|:-------------:|:-------------:|
| [@19013na](https://github.com/19013na) |  |  |  |
|      Backend       |     Frontend     |     Frontend     |   Backend   |


**✔️ 공통 AI개발**<br><br>


## 한이음 ICT멘토링, 이브와 참여 
> 🥉**2024이브와 동상 수상** </br> **https://www.youtube.com/watch?v=SRanw6_HfDg**

<br>

## 깃허브 산출물[Repositories]
> **백엔드 : https://github.com/safeT-CE/Backend**</br>
> **프론트 : https://github.com/safeT-CE/Flutter_main**

</br>

---
## 🖥️ Stack
### Used Language
<p align="left">
<img src="https://img.shields.io/badge/Java-ECD53F?style=for-the-badge&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-E52121?style=for-the-badge&logo=python&logoColor=white"/>
</p>

### Framework
<p align="left">
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-4A154B?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
</p>

### Environment
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Figma](https://img.shields.io/badge/figma-F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=Google-Colab&logoColor=white)

### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![GoogleMeet](https://img.shields.io/badge/GoogleMeet-00897B?style=for-the-badge&logo=Google%20Meet&logoColor=white)
<br>

### ❗ETC 
**[연동 리포지토리](https://github.com/safeT-CE/FE-BE-integration)** </br></br>

---
## 프로젝트 설명

### ⭐ 주요기능 
*추가적인 내용 각자 repository에서 확인 가능<br><br>


#### ◾ 얼굴 인식 및 얼굴 동일성 감지 
> **by정은 [얼굴 동일성 탐지](https://github.com/safeT-CE/FaceRecognition_JE)** <br/>

OpenCV와 face_recognition 라이브러리를 사용하여 실시간 얼굴 인식 및 비교를 수행한다.<br>
저장된 얼굴 특징 데이터를 CSV 파일로 관리하며, 카메라로 얼굴을 인식하고 인코딩하여 기준 얼굴과 비교한다.<br> 
유사도 기준에 따라 동일인을 판별하고 동일인으로 판별될 경우 얼굴 데이터 특징값을 저장한다.<br><br>
 
#### ◾ 헬멧 착용 및 2인 이상 탑승 
> **by효영 [헬멧&2인 이상 탑승 탐지](https://github.com/safeT-CE/Detection)** <br/>

헬멧 착용 감지와 2인 이상 탑승하였다는 것을 감지하기 위해 YOLOv8 모델을 이용하여 학습을 진행하였다.<br>
헬멧 착용 클래스를 roboflow에서 제공하는 데이터셋과 직접 라벨링한 데이터셋을 활용하였다.<br>
2인 이상 탑승을 감지 데이터셋은 yolov8n의 기본 데이터셋을 사용하였고, 사람이 2명 이상 감지되었을 때 결과를 출력할 있도록 하였다.<br><br>

#### ◾ 횡단보도 감지 
> **by민영 [횡단보도 주행 탐지](https://github.com/safeT-CE/Cross_my)** <br/>

횡단보도 주행을 감지하기 위해 YOLOv8을 활용해 개발하였다.<br>
또한 roboflow를 활용해서 얻은 횡단보도 데이터를 widht와 length로 라벨링하였다.<br>
length으로 인지될 때는 인도 방향에서의 진행으로 판단해 내리지 않으면 벌점을 부여하고 width일 때는 정상 주행으로 판단하였다.<br><br>

#### ◾ 주차 공간 점검 
> **by현진 [점자블록 탐지](https://github.com/safeT-CE/Parking-Detection)** <br>

킥보드 사용 후 반납 과정에서 반납 가능한 공간과 반납 불가능한 공간을 구분하기 위한 도로, 점자블록, 횡단보도 구별 기능을 YOLOv8 모델을 활용하여 학습을 진행하였다.<br> 
학습 데이터셋은 roboflow에서 제공하는 데이터셋과 추가 라벨링 데이터셋을 활용하였다.<br>
road, block, crosswalk으로 클래스를 나누어 학습을 진행하였으며 도로, 점자블록, 횡단보도가 존재하는 구역에서는 반납 버튼이 눌리지 않게 하여 사용자가 올바른 곳에 주차할 수 있도록 한다.<br><br>


### 🔘 화면구성

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
