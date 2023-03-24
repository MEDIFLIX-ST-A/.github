# 큐시즘 27기 기업 프로젝트 동아 ST 대시보드 과제(FrontEnd)
- <b>기술스택</b> : React.js
- <b>기능설명</b>
1. 페이지 전체 개요<br><br>
![image](https://user-images.githubusercontent.com/104711336/227545876-f7732b0c-fc32-481f-9d89-1fae41342126.png)
<br>
2. 세부기능<br><br>
- Header (화면 상단)<br>

화면 오른쪽에 있는 <b>> 메디플릭스, >동아ST</b> 를 누르면 해당 페이지로 바로 이동할 수 있습니다.<br>
이는 관리자 업무 중 콘텐츠 관리 및 또 회사에서의 다른 업무의 효율을 높여줍니다. <br>
<br>
- Sidebar
  - left<br>
  ![image](https://user-images.githubusercontent.com/104711336/227540750-c8e96677-a54d-49dd-a546-6ce71c931ab2.png)<br>
  대시보드의 주 기능을 한눈에 볼 수 있도록 업무에 있어서 세부적인 기능들은 왼쪽 사이드바를 통해 해당 업무 페이지에서 편하게 작업할 수 있도록 메뉴를 만들었습니다.<br>
  - right<br>
  ![image](https://user-images.githubusercontent.com/104711336/227546328-7a6230cd-50dc-4193-9a92-ca519511afdc.png)![image](https://user-images.githubusercontent.com/104711336/227548807-9ee89fd5-ab85-42e2-b06d-ecff988bc902.png)


  관리자 업무 페이지이다 보니 관리자들의 현재 접속 상태와 업무 리스트를 생성했습니다. 해당 사이드바는 버튼 클릭시 화면에 나타나고, 사라지도록 동적 기능을 추가하여 메인 컨텐츠의 영역을 조금 더 넓힐 수 있도록 구성하였습니다. <br>
<br>

- Main Contents<br>
  - 서비스 방문수/유저수/활성사용자수<br>
  ![image](https://user-images.githubusercontent.com/104711336/227546534-df78adc2-440d-4b8c-93aa-a79218e8d75e.png)

    최대 일주일 전까지의 회원의 가입 및 방문 현황을 한눈에 파악할 수 있는 그래프입니다.<br>
  - 서비스 규모 CHECK<br>
  ![image](https://user-images.githubusercontent.com/104711336/227546726-3d81797f-5600-4453-a4e8-1604f0b50d12.png)

    매일 수치가 새롭게 업데이트되어 현재 메디플릭스의 서비스 현황을 한눈에 파악할 수 있습니다. <br>
   - 조회수 TOP 컨텐츠<br>
   ![image](https://user-images.githubusercontent.com/104711336/227546867-53f1084f-1964-4949-8775-1abaa672f154.png)

   일간, 주간, 월간, 연간 조회수 상위 3개의 컨텐츠를 썸네일과 함께 화면에 보여줍니다. 상단에 있는 버튼을 클릭하면 원하는 기간 동안의 상위 top3 컨텐츠를 한 눈에 파악 가능합니다. <br>
   - ON AIR 콘텐츠 관리<br>
   ![image](https://user-images.githubusercontent.com/104711336/227547030-cfaeb66d-fa71-45ee-8ba0-28e4c982634e.png)

   라이브 방송 중인, 혹은 할 예정인 콘텐츠들을 화면에 띄워줍니다.<br>
   - 의학 전공별 비중<br>
   ![image](https://user-images.githubusercontent.com/104711336/227547176-c67c2dad-add5-408d-96a5-1801f7feb3a4.png)

   회원 및 컨텐츠의 전공 상위 6개 과의 분포 현황을 도넛파이차트로 표현하였습니다. 차트의 label에서 원하는 과를 클릭하면 해당 과를 제외한 분포 또한 볼 수 있습니다.<br>
   - 지역별 비교<br>
   ![image](https://user-images.githubusercontent.com/104711336/227547302-8852b940-a083-46d8-88d6-476d086fbc14.png)

   일간 접속 유저 및 신규 회원의 평균 시청기간을 막대 그래프로 표현하였습니다. 상위, 하위 지역 2개씩 빨간 색으로 표현하여 가시적인 효과를 주었습니다. <br>
   기본적으로 화면에 보여지는 그래프는 기존 유저의 정보이며 신규 회원의 정보를 보고싶으면 상단에 있는 스크롤을 옆으로 옮기면 됩니다.
