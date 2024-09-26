# Coffee-Shop


## 커피 전문점 상품 정보 사이트

이 웹사이트는 커피 전문점에서 제공하는 다양한 음료, 브레드, 그리고 MD 상품에 대한 포괄적인 정보를 제공합니다. 

<br><br>
### 📖 DISCRIPTION

각 메뉴와 상품에 대한 설명뿐만 아니라, 커피의 원두와 그 특징, 그리고 커피에 대한 기본적인 지식을 통해 고객들이 더 나은 커피 경험을 즐길 수 있도록 돕습니다. 

커피를 사랑하는 이들에게 최고의 선택을 제공하기 위한 모든 정보를 이곳에서 확인할 수 있도록 도와줍니다.


<br><br>

#### ⭐ Technologies Used
> Language
- HTML5
- css3
- Javascript
> Tool
- Editplus
- 알드라이브
  
<br><br>

#### UX / UI
-	라디오버튼의 체크 상태를 확인 하고 메뉴를 종류별로 출력하기 위해 라디오버튼에 입력이 들어올 때 onclick = function을 통해 어떤 리스트가 체크 되어있는지 확인함
-	라디오버튼의 체크상태에 따라서 분류된 메뉴들을 iframe안에 표현하고 분류되어 나타나는 메뉴의 이미지들은 각각 div태그 안에 들어가고 모든 이미지를 inline-block으로 정리함
- 각 이미지는 style태그 안에서 이미지의 hover시 테두리를 변하게 style을 지정해줌
-	onclick시 img의 alt값을 가지고 function에 가서 alt값에 따라 해당 메뉴의 상세정보를 찾아 alert를 통해 설명해주는 창을 생성함
-	`<meta>` 태그 사용으로 브라우저 검색이 용이함
-	`<img>` 태그의 alt 속성을 사용하여 이미지를 분류하여 설명함
-	`<Iframe>` 태그를 통해 메뉴를 보여줌으로 메뉴의 구성을 쉽게함



---
### 📖 Pages View

<br>

#### ⭐ 메인 페이지

![main](https://github.com/user-attachments/assets/a92023b8-0622-4206-bbaa-8f0fab5523f4)

- 사이트에서 보여주고자 하는 메뉴에 대해 이미지를 표시 및 바로가기 제공
- 헤더에 표시한 메뉴바를 통해 페이지 이동

<br><br>

#### ⭐ 음료 페이지

![coffee](https://github.com/user-attachments/assets/e92aabd4-f586-48a1-86ab-de7f48a91312)

- 판매중인 음료 리스트를 표시
- COFFEE, ADE, FLATCCINO, BLEANDING TEA 로 구분
- 각 메뉴는 클릭 시 메뉴에 대한 간략 정보를 팝업으로 표시
- 예시 - 화이트 초콜릿 모카 이미지 선택 시
<img src ="https://github.com/user-attachments/assets/019f8b0d-dfc8-4c31-9cfb-539f4018bbe3" width=50%/>

<br><br>

#### ⭐ 브레드 페이지

![bread](https://github.com/user-attachments/assets/306b680c-9cf6-47a3-94e9-cac6d77ca066)

- 음료 페이지와 동일하게 판매중인 브레드 리스트 표시
- BREAD, DESSERT, COOKIE 로 구분
- 각 메뉴는 클릭 시 메뉴에 대한 간략 정보를 팝업으로 표시

<br><br>

#### ⭐ 기획 상품 페이지

![md](https://github.com/user-attachments/assets/1430d480-23a6-4138-b9a5-82791037bb13)

- 판매중인 기획 상품 리스트를 표시
- 각 상품은 클릭 시 상품에 대한 간략 정보를 팝업으로 표시

<br><br>

#### ⭐ 원두 관리 페이지

![beans](https://github.com/user-attachments/assets/a16f0283-85fa-4694-ba36-fb9eee888686)

- 사용되는 원두의 종류 및 각 원두의 정보를 표시
- 해당 커피 전문점에서의 원두 블렌딩 방식에 대해 설명

<br><br>

#### ⭐ 커피 정보 페이지

![potency](https://github.com/user-attachments/assets/4b3ec2bb-967e-420a-b334-d961ab73c76e)

- 커피의 정의, 효능, 부작용을 설명하여 고객에서 권장하는 섭취 방식을 설명 

<br><br>


---
### 📖 CODE View

#### ⭐ MenuBar - nav

![image](https://github.com/user-attachments/assets/dc01a5dc-a1d6-4250-998f-f4710319494e)

-	메인화면에서 상단에는 메뉴바로 구성되어 있고 메뉴바의 왼쪽에 있는 이미지는 초기화면으로 돌아가기 위한 링크
-	메뉴바는 스크롤을 내려도 상단에 고정된 채 표시
-	메인화면을 포함한 모든 창에는 하단에 작게 메뉴바와 copylight가 표시됨 속성은 topmenu의 스타일을 사용


<br><br>

#### ⭐ Product List

![image](https://github.com/user-attachments/assets/0a40fb71-aa23-416f-9153-d91e4e70f83d)

-	초기 라디오버튼은 coffee버튼에 checked된 것으로 정함
-	라디오버튼내의 다른 체크박스를 입력하면 function output 을 통해 어느 요소가 체크되었는지 여부를 확인하고 체크된 요소를 찾으면 그 요소에 해당하는 이미지들을 가진 html을 iframe안에 링크 시켜 이미지들을 표시한다. 

<br><br>

#### ⭐ Product Information

![image](https://github.com/user-attachments/assets/350aaf3b-121f-475f-8fa2-548b027ea143)

-	정보를 얻고자 하는 이미지를 선택하고 클릭했을 때 onclick을 통해 이미지의 alt 값이 function check의 obj에게 전달됨
-	전달받은 매개변수를 검사하면서 해당 메뉴의 alt값과 동일한 키를 가진 if문을 실행하여 text에 메뉴의 대한 설명을 저장시킴
-	검사가 끝나면 저장되어 있는 text값을 alert를 통해 창에 출력하여 보여줌 
-	각 메뉴에 따라 다른 설명을 가지고 check에 따라 text값은 초기화.

<br><br>


