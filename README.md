# Color-Guessing-Game
## 목차
## 1. 팀원 및 담당 업무 
## 2. 과제 요약
## 3. 과제 개요 
###    1) 과제 개요
###    2) 과제 배경 
###    3) 과제 선택 동기
## 4. 과제 목표 및 내용
###    1) 정량적/정성적 목표 
###    2) 과제 내용 
## 5. 결과물
###    1)예상 결과물
###    2)기대효과 및 활용방안 
## 6. 수행일정 및 작업 도구 
## 7. 참고문헌
---
## 1 팀원 및 담당 업무 
            
<img width="494" alt="화면 캡처 2022-05-19 185337" src="https://user-images.githubusercontent.com/102898911/169266317-71e25b07-325a-4fd1-9c25-e238211257b9.png">


## 2 과제 요약 

본 프로젝트는 자바스크립트 언어를 사용하여 문제에 나타난 RGB값을 통해 색상을 맞추는 게임을 구현한다. if 문과 for문, 배열을 사용하는 과정에서 한 학기동안 학습한 내용을 복기하는 동시에 함수를 새로 생성하여 문제 중 정답과 오답을 클릭하였을 때의 이벤트를 처리하거나 각각의 사각형에 다른 색깔을 지정하는 등 평소에 수행해보지 않은 기능에 도전을 할 수 있는 기회가 될 것이다. 또한 간단히 색상을 맞추는 기능 뿐만 아니라 다양한 기능을 추가하여 보다 더 재밌는 게임을 구현할 수 있을 것이라고 예상된다. <br/> <br/> <br/> 




## 3 과제 개요 
### 1) 과제 개요 <br/> <br/> <br/>    


### RGB               


                    ![image](https://user-images.githubusercontent.com/102898911/169229250-0d13dece-59d4-4420-89d4-d4190b376c60.png)

RGB란 빛의 3원색인 빨간색, 녹색 ,파란색을 의미한다. RGB 방식은 빨간색 , 녹색, 파란색을 적절하게 섞어서 영상 혹은 이미지를 표현하는 방식이다. RGB 는 컴퓨터의 모니터 화면이나 스마트폰의 화면, 텔레비전, 그리고 프린터에서 컬러로 인쇄를 하는 등 색을 표현할 때 주로 사용된다. 모니터 화면은 화소라고 하는 아주 작은 사각형이 여러 개 모여서 만들어진다. 이때 각 화소는 노란색, 빨간색, 파란색의 세 가지의 조합으로 만들어진다. 화소 하나는 바이트(byte) 라는 단위를 사용하여 빨간색의 1바이트, 파란색의 1바이트, 초록색의 1바이트로 구성된다. 따라서 1바이트는 2^8 즉 0부터 256의 257단계의 색을 표현할 수 있게 된다. 


### RGB의 사용
#### -웹디자인
![image](https://user-images.githubusercontent.com/102898911/169234124-48b323d8-8768-48c3-93bc-8cc93773d558.png) <br/><br/><br/>
포토샵을 비롯해 많은 웹디자인 툴이 색을 사용할 때 RGB 값을 사용하고 있다. 다양한 웹디자인 툴들이 RGB 채널을 기본 채널로 사용하고 있다.<br/><br/><br/>  <br/><br/>

### -모니터 

![image](https://user-images.githubusercontent.com/102898911/169234459-58ecf4ca-5ce0-4555-b02e-921becab586f.png)

TV, 컴퓨터를 비롯해 우리가 사용하는 모니터화면은 수백만개의 아주 작은사각형인 화소로 이루어져 있다. 화소 하나는 빨간색, 파란색, 초록색의 1 바이트로 구성된다. 이때 RGB값을 0에서 255로 조절해 256단계의 색을 나타낼 수 있다. 모니터 화면은 화소라고 하는 아주 작은 사각형이 여러 개 모여서 만들어진다. 이때 각 화소는 노란색, 빨간색, 파란색의 세 가지의 조합으로 만들어진다. 화소 하나는 바이트(byte) 라는 단위를 사용하여 빨간색의 1바이트, 파란색의 1바이트, 초록색의 1바이트로 구성된다. 따라서 1바이트는 2^8 즉 0부터 256의 257단계의 색을 표현할 수 있게 된다.<br/><br/><br/><br/>

### 2) 과제 배경

RGB 값은 웹디자인, 사진, 프로그래밍, 모니터 등 다양한 분야에서 사용되고 있다. 특히나 흑백이 아닌 컬러로 대부분의 정보를 표현하는 현재의 시대에서 RGB 값을 아는 것은 매우 중요하다. 모든 RGB 값을 아는 것은 불필요하지만 대표적으로 많이 사용되는 색상들의 RGB 값을 대략적으로 알아 두는 것은 프로그래밍 뿐만 아니라 다양한 분야에서 큰 도움이 될 것이다.<br/><br/><br/> 

### 3) 과제 선택 동기 

RGB 값은 웹디자인, 컴퓨터 텔레비전 등의 모니터 화면, 웹디자인, 그래픽스를 활용한 많은 프로그래밍 등에서 색상을 표현할 때 널리 쓰이는 방식이다. 그러나 RGB 값을 많이 접해보지 못한 경우에는 RGB 값이 주어졌을 때 혹은 원하는 색상을 RGB 값을 직접 넣어 사용하고자 할 때 어려움이 있을 수 있다. 이러한 어려움을 보다 재미있게 해결할 수 있도록 RGB 색상을 맞추는 게임 개발을 계획하였다. <br/> <br/><br/>


## 4 과제 목표 및 내용

### 1) 정량적/정성적 목표 

### 정량적 목표 

1. 게임을 실행하였을 때 기본적으로 여러 문제가 제시되고 문제를 풀면 다음 문제로 자연스럽게 넘어가도록 한다. 

2. 문제의 선지 위에는 바를 하나 만들어 문제의 정답을 맞추었을 땐 바 중앙에 정답이라고 출력 되고, 틀렸을 땐 다시 시도하라는 글이 출력 되도록 한다. 

3. 바의 왼쪽에는 다시 시작할 수 있도록 NEW GAME 버튼을 만들고 버튼을 누르면 다른 새로운 문제와 새 게임이 시작되도록 한다.<br/><br/>

### 정성적 목표 

1. 실제 회화나 그림에서 색상을 섞는 것과 컴퓨터에서 색상을 섞는 것은 어떠한 차이가 있는지 알아본다.

2. RGB 값의 개념을 이해하고 컴퓨터 상에서 RGB 색을 섞게 된다면 어떠한 다양한 색이 만들어지는지 확인해본다. 



### 2) 과제 내용

RGB 값을 이용한 색상 추측 게임 프로젝트를 통하여 소프트웨어 내에서 색상을 다루는 법을 알고, 컴퓨터에서 색상을 섞는 것과 실제 회화, 그림 등에서 색상을 섞는 것과는 어떠한 차이점이 있는 지 알아본다. 그리고 컴퓨터 상의 색상을 특정 하는 가장 일반적인 방법인 RGB값에 대한 이해에 초점을 맞추어 알아본 뒤 자바스크립트를 사용하여 RGB 값을 이용한 색상 추측 게임을 구현해본다. <br/><br/><br/>

## 5 결과물 

### 1) 예상 결과물 

RGB값 이해를 바탕으로 (R,G,B) 순의 임의의 숫자 값을 제시하고 문제의 밑에는 객관식 형태(4지선다형)로 색상을 제시하여 어떠한 색인지 추측하여 정답을 맞출 수 있도록 결과물을 만들 예정이다. 가능하다면 상,중,하 난이도와 제한 횟수를 초과하여 문제를 틀릴 경우 종료되며 문제를 맞춘 횟수까지 같이 출력 될 수 있도록 구현할 것이다. <br/> <br/>


### 2) 기대 효과 및 활용 방안 


RGB 값을 이용한 색상 추측 게임을 통해 RGB 값에 대한 이해를 게임으로 즐겁고 쉽게 다가가 배울 수 있을 것을 기대하고, 색상 추측 게임에서 변형하여 색맹 테스트나 어린이들의 색깔 공부를 위한 교육용 게임 등 다양하게 활용할 수 있을 것이다. <br/> <br/>





























## 6 수행일정 및 작업 도구 

### 1) 수행일정 <br/><br/>



<img width="519" alt="화면 캡처 2022-05-19 152206" src="https://user-images.githubusercontent.com/102898911/169237154-ff1798b4-f4a1-4ebc-92bb-a18f265eff16.png"> <br/><br/>



### 2) 작업 도구 <br/><br/>



<img width="511" alt="화면 캡처 2022-05-19 164549" src="https://user-images.githubusercontent.com/102898911/169240626-9ce8b063-ac9c-482f-a311-32ea0d473556.png"> <br/><br/>
<br/>



## 7 참고문헌

Colin Ware(2012), 데이터 시각화 인지과학을 만나다 , 최재원(역) , 의왕 : 에이콘 , 2015 <br/>
Nisikubo Yaseuhiko(2006), 알기 쉬운 디스플레이 기술의 기초, 박재우(역), 서울 : 광문각, 2007 <br/>
최윤철 & 임순범, 컴퓨터그래픽스 배움터, 생능출판, 파주, 2003











