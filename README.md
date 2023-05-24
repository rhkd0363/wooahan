# 우아한\_우리 아이 한글교육

- [👩‍🏫 기획스토리](#기획스토리)
- [🐧서비스 소개](#서비스-소개)
  - [🎬소개 영상](https://youtu.be/J-3l2x72w9I)
  - [🎥 시연 영상](https://youtu.be/lUgPmpVr7Ck)
  - [💗 뛰어쓰기](#-뛰어쓰기)
  - [🧡 그림찾기](#-그림찾기)
  - [💛 한글방울](#-한글방울)
  - [💚 끝말기차](#-끝말기차)
  - [💜 보상카드](#-보상카드)
  - [💙 게임선택 & 설정](#-게임선택 & 설정)
  - [🤎 로그인](#-로그인)
- [개발관련](#-개발관련)
- [문서](#문서)
- [팀원소개](#팀원-소개)

## 👩‍🏫 기획스토리

- <우아한>은 게이미피케이션 요소를 통해 어린이가 한글에 흥미를 가지고 놀이로 학습할 수 있도록 돕습니다.
- 장 피아제는 놀이를 어린이의 지적 발달과 관련시켜서 해석한 대표적인 학자로서 놀이는 유아의 경험을 능동적이고 즐겁게 통합하는 과정으로 어린이는 여러 가지 놀이를 통해서 세계를 경험하고 가장 순수하게 동화와 조절을 이루어나간다고 하여 놀이의 교육적 기능을 강조하였습니다.
- 놀이 중심의 한글 교육은 어린이의 인지 발달, 언어 발달 단계에 맞으므로 학습자의 발달 특성에 맞는 한글 교육을 할 수 있습니다. 또한 어린이들은 신체적인 움직임이 많은 활동을 선호합니다.
- 이러한 놀이 교육의 장점을 누릴 수 있도록 어린이의 접근이 쉬운 모바일 어플리케이션으로 제작해 집에서 쉽게 한글 놀이교육이 가능하도록 구현하였습니다.
- 우아한은 7세 이상 한글을 배우고 있는 어린이를 대상으로 하는 서비스 입니다.

<br>

## 🐧서비스 소개

<br>

## 🎬[소개 영상](https://youtu.be/J-3l2x72w9I)

## 🎥[시연 영상](https://youtu.be/lUgPmpVr7Ck)

<br>

<img src="https://drive.google.com/uc?export=view&id=1U7IZEYXGKBNWWorBDZHOUnQ3Ld_uQWnB" width="600px" height="300px" title="로딩" alt="로딩"></img><br/>

<br>

### 💗 뛰어쓰기

- 한글 문장에서 띄어쓰기가 필요할 때 뛰는 행동을 하도록 접목시켜 띄어쓰기 학습을 도와주는 교육용 게임
  - TTS를 이용해 한글 문장을 읽어주고 띄어쓰기가 적용되어야 할 부분에서 뛰는 행동을 하면 가속도센서를 이용해 움직임을 감지하여 게임이 진행된다.
  - 한글을 배우기 시작하는 주 연령층인 5세~7세는 단어와 형태소를 구분적으로 인식하지 못하고 문장 전체를 받아들인다. 따라서 화면에 문장을 보여주고 소리로 단어의 구분을 알려주어 한글의 구성을 공부할 수 있도록 한다.

<img src="https://github.com/rhkd0363/wooahan/assets/62332870/242fbd8f-7858-4c17-a9cf-9935a98aef99" width="600px" height="300px" title="뛰어쓰기" alt="뛰어쓰기"></img><br/>

### 🧡 그림찾기

- 단어가 주어지면 해당 단어와 일치하는 그림을 선택하는 게임
  - 좌우 방향 버튼을 터치하거나 기기의 중력센서를 사용해 기울임을 감지하고 좌우 방향을 판단하여 캐릭터를 해당하는 그림으로 이동시켜 게임을 진행한다.
  - 그림를 선택하면 정답 유무를 알려주고 선택한 그림에 해당하는 단어를 TTS를 이용해 읽어준다. 

<img src="https://github.com/rhkd0363/wooahan/assets/62332870/4e042c54-0fa5-443a-80bd-15713210cd61" width="600px" height="300px" title="그림찾기" alt="그림찾기"></img><br/>

### 💛 한글방울

- 가운데 사진 하나가 주어지고 단어 4개 중 일치하는 단어를 선택하는 게임.

<img src="https://github.com/rhkd0363/wooahan/assets/62332870/95b1afa9-e3e7-4db0-bb8d-c1dc47a7d054" width="600px" height="300px" title="한글방울" alt="한글방울"></img><br/>

### 💚 끝말기차

- 주어진 글자와 일치하는 끝 글자를 가진 단어를 선택하는 게임.

<img src="https://github.com/rhkd0363/wooahan/assets/62332870/337c68b0-188e-40ea-bc9f-83b5d79e45f9" width="600px" height="300px" title="끝말기차" alt="끝말기차"></img><br/>

### 모든 게임은 동작에 따라 단어를 읽어주고, 단어의 이해를 돕기 위한 사진을 보여준다.

### 💜 보상카드

- 게임을 완료하면 보상으로 별을 얻고, 별 5개를 모으면 보상카드를 얻을 수 있다.
- 보상카드를 얻은 후 도감 페이지에 들어가 지금까지 얻은 카드를 모아볼 수 있다.

<img src="https://drive.google.com/uc?export=view&id=1rBZN424RartycUz1CX-TLGVm68i4CeeC" width="600px" height="300px" title="보상카드 획득" alt="보상카드"></img><br/>

<img src="https://drive.google.com/uc?export=view&id=1I72ALXiZUeVuPkm4bwtjrmEtgzGRUTPM" width="600px" height="300px" title="보상카드 획득" alt="보상카드"></img><br/>

<img src="https://drive.google.com/uc?export=view&id=1DEYMZtFazc77Hd9WTSv2l9iIaTX-vLWA" width="600px" height="300px" title="도감" alt="도감"></img><br/>

### 💙 게임선택 & 설정

- 무한캐러셀을 이용해 화면을 스와이프 하여 게임을 선택할 수 있다.
- 설정화면을 통해 난이도를 선택하고 소셜로그인을 진행할 수 있다.

<img src="https://github.com/rhkd0363/wooahan/assets/62332870/d233a7a6-82c8-45c4-8de1-83c4830fe385" width="600px" height="300px" title="캐러셀" alt="캐러셀"></img><br/>
### 🤎 로그인

- 안드로이드 기기 ID를 이용해 로그인하지 않은 이용자도 서비스를 이용할 수 있지만, 기기변경 시 보상 카드를 연동하려면 로그인을 하여 회원이 되어야 한다.
- 소셜로그인 (구글 로그인, 카카오 로그인) 으로 회원가입 및 로그인을 할 수 있다.

<br>

## 📚 개발관련
- 하이브리드 앱(안드로이드 코틀린 + 리액트)
  - 안드로이드 기기의 센서를 사용
  - 웹뷰를 통해 리액트로 구성된 웹페이지에서 게임을 진행
- 하이브리드 앱을 선택한 이유
  - 네이티브 앱의 경우 변경사항이 생길 때마다 스토어 버전 업데이트 심사
  - 웹의 경우 센서를 사용할 수 없어 행동을 접목한 게임 개발에 어려움이 존재
  - 위와 같은 이유로 모바일 앱의 장점인 센서를 사용하고, 웹의 장점인 즉각적인 업데이트를 위해 하이브리드 앱을 선택

<br>


### 🖥 개발환경
<div align = "center" style="font-size:30px">
  <h1>🛫 Co-work tool 🛬</h1>
<br>
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira Software&logoColor=white">
<img src="https://img.shields.io/badge/Mattermost-0058CC?style=for-the-badge&logo=Mattermost&logoColor=white">
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=GitLab&logoColor=white">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
<br>
</div>
<br>

<div align = "center" style="font-size:30px">
  <h1>✨ Front End Stack ✨</h1>
<br>
<img src="https://img.shields.io/badge/react-skyblue?style=for-the-badge&logo=react&logoColor=white">
<img src="https://img.shields.io/badge/redux-b22af7?style=for-the-badge&logo=redux&logoColor=white">
<img src="https://img.shields.io/badge/createreactapp-09D3AC?style=for-the-badge&logo=createreactapp&logoColor=white">
<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
<br>
<img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
<img src="https://img.shields.io/badge/threejs-000000?style=for-the-badge&logo=threedotjs&logoColor=white">
<img src="https://img.shields.io/badge/blender-F5792A?style=for-the-badge&logo=blender&logoColor=white">
<img src="https://img.shields.io/badge/android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
<img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  
</div>

<br>


---

## 문서

### [🔌 기능명세서](/docs/%EA%B8%B0%EB%8A%A5%EB%AA%85%EC%84%B8%EC%84%9C.md)

### [🔑 API명세서](/docs/api.md)

### [💾 ERD](/docs/ERD.md)

### [🎠 Figma](/docs/figma.md)

### [🎨 아키텍쳐](/docs/%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90.md)

### [📜 포팅메뉴얼](/exec/%EC%9A%B0%EC%95%84%ED%95%9C_%ED%8F%AC%ED%8C%85_%EB%A7%A4%EB%89%B4%EC%96%BC.pdf)

### [🔮시연시나리오](/exec/%EC%9A%B0%EC%95%84%ED%95%9C_%EC%8B%9C%EC%97%B0%EC%8B%9C%EB%82%98%EB%A6%AC%EC%98%A4.pdf)

<br>

## 팀원 소개

![팀원](/docs/images/%ED%8C%80%EC%9B%90%EC%86%8C%EA%B0%9C.png)
