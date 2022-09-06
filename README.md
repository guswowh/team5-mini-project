# 🤝 미니 프로젝트
#### NEEDMONEY 💰 
당신을 위한 대출상품 추천 앱 NEED MONEY

## 📌 프로젝트 개요
#### 프로젝트 기간
- 2022년 08월 23일(화) ~ 2022년 09월 06일(화)

#### 프로젝트 목표
- 백엔드와 협으로 어플리케이션 개발
- 필요한 API를 백엔드에 요구하고 그에 맞게 어플리케이션을 개발할수 있도록 한다.

####
- 노션 주소 : https://www.notion.so/81378e58f37346c69565fe626c82d728
- 프론트엔드 팀레포지토리 깃헙주소 : https://github.com/BullWooStar/team5-mini-project

#### 배포 주소


<br />

## 🙋🏻 팀원 소개



| [양예진](https://github.com/yejine2)       | [최효근](https://github.com/BullWooStar)               | [이화정](https://github.com/Hwa-J)                | [조현재](https://github.com/guswowh) | [최수연](https://github.com/boksooni)                                            
| --------------------------------------------------- | ------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- 
| 카트페이지 / ui-카드,버튼 / 홈페이지 / 헤더   | 전체상품보여주기 / 검색상품보여주기 / 상품필터링 | 맞춤 상품 페이지 / 프로모션 페이지 / 로딩 | 로그인 페이지 / 회원가입 페이지 | 헤더 / 네비게이션바 / ui-gnb |
 

<br />

## 프로젝트 내용

### ⭐️ 주요 기능

<img width="500" alt="스크린샷 2022-09-06 오후 4 46 59" src="https://user-images.githubusercontent.com/99630188/188577064-5339135d-f054-4526-af11-866b9c033923.png">

홈페이지 화면



#### 로그인 / 회원가입

<img width="500" alt="스크린샷 2022-09-06 오후 4 41 48" src="https://user-images.githubusercontent.com/99630188/188576518-69548640-7498-45fb-b800-77b5bcbb4044.png">
<img width="500" alt="스크린샷 2022-09-06 오후 4 42 29" src="https://user-images.githubusercontent.com/99630188/188576531-98d3603d-916f-4564-b90b-46afd88979c5.png">

- 회원가입 후 로그인시 토큰값을 받아와 쿠키에 저장합니다.
- 로그인이 안됐을시 홈페이지, 로그인, 로그아웃 페이지 이외에는 접근하지 못합니다.
 
 <br />


 #### 회원 맞춤 추천 상품
 
 <img width="500" alt="스크린샷 2022-09-06 오후 4 49 21" src="https://user-images.githubusercontent.com/99630188/188577518-9ec4a9c3-ff33-4856-bd4d-05790b7a9abc.png">

- 회원가입시 입력했던 나이, 직업을 바탕으로 회원에게 맞는 추천상품을 출력합니다.
- 추천상품의 총합을 구해서 신청가능한 대출 상품 종합을 회원에게 보여줍니다



#### 모든 상품 및 검색 상품

<img width="500" alt="스크린샷 2022-09-06 오후 4 41 48" src="https://user-images.githubusercontent.com/99630188/188578096-f063fe65-3875-4d01-bfc3-44d07436a76f.png">

<img width="500" alt="스크린샷 2022-09-06 오후 4 52 22" src="https://user-images.githubusercontent.com/99630188/188578175-09b8596a-de36-4c1a-8118-cc7416eca338.png">

- 전체상품으로는 신청할 수 있는 모든 상품을 볼 수 있고 검색상품으로는 상품의 이름을 검색하면 해당 이름이 들어간 모든 상품을 볼 수 있습니다.
- 필터로는 직업별로 상품을 분류하고 대출금액, 금리 별로 오름,내림차순을 할 수 있습니다.



#### 프로모션 상품

<img width="500" alt="스크린샷 2022-09-06 오후 4 58 48" src="https://user-images.githubusercontent.com/99630188/188579517-0cb36dff-c1f8-4c71-848f-c633314b5938.png">

- 프로모션 상품으로는 서버에서 무작위로 뽑은 랜덤 추천 상품을 보여줍니다.



#### 장바구니

<img width="500" alt="스크린샷 2022-09-06 오후 4 59 37" src="https://user-images.githubusercontent.com/99630188/188579769-88378a9f-3501-419e-bcaa-bb4710518611.png">

<img width="500" alt="스크린샷 2022-09-06 오후 4 59 42" src="https://user-images.githubusercontent.com/99630188/188579787-46501108-25ce-4948-861c-e149640966d5.png">

- 상품페이지의 상품카드에서 + 버튼을 누르면 개인 카트에 상품이 추가가 됩니다.
- 전체삭제 및 개별 삭제가 가능하며 신청하기 완료시 장바구니가 비워집니다.

 <br />

### 🛠 기술 스택
- Front 
  - React.js
  - Create React App
  - Redux Tool Kit
  - React-Router
  - Styled Component
  - Axios
  - Eslint

<br />

### 🌳 설계도 및 유저플로우

설계도
https://www.figma.com/files/recent?fuid=1120606089959726851
<img width="1051" alt="스크린샷 2022-09-06 오후 5 08 06" src="https://user-images.githubusercontent.com/99630188/188581501-c53e48bd-4bcf-4ebd-9f9a-d72e64d711e4.png">

유저플로우
https://www.figma.com/file/qDSvNjjgCBk8ez7YzfzGlx?embed_host=notion&kind=&node-id=0%3A1&viewer=1
<img width="1840" alt="스크린샷 2022-09-06 오후 5 07 42" src="https://user-images.githubusercontent.com/99630188/188581534-6d9e7f75-989d-45c7-8a7a-209dedd10824.png">

<br />

## 팀 프로젝트를 진행하며...

#### 양예진

백엔드와 함께하는 팀 프로젝트는 처음이라서 우여곡절이 많았습니다. 이번 프로젝트를 통해서 백엔드분들과 소통하는 것을 배운 것 같습니다. 또한 원활한 협업을 위해서는 문서화가 중요하다는 것을 몸소 느꼈습니다. 

#### 최효근

#### 이화정

#### 최수연

#### 조현재
