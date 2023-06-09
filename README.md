## opensw23-team_YSPark

## Team introduction(Individual team)
  구성원 : 1
  박윤성 / 202011296  / leader
  
  
## Topic Introduction:
해당 주제는 사람의 표정을 딥러닝하여 사람의 감정을 표현하는 것을 목표로 삼고 있는 Emotion Detection입니다.<br>
Emotion Detection을 위해 사용된 주요 기술로는 CNN(Convolutional Neural Networks)이 있습니다.<br>
Emotion Detection에서 CNN은 밝기, 경계와 같은 특징을 바탕으로 사람의 표정을 구분합니다.<br>
이 소스코드에서는 사람의 표정을 angry, disgust, fear, happy, neutral, sad, surprise로 구분합니다.<br><br><br>
 내가 사용한 소스코드 :  https://github.com/mr-mamun-50/Emotion_Detection-Deep_learning.git<br>
  
  
## Results:
  
원본-놀라움        <br>
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/03ad82ae-9636-4c7e-914f-7671def44b33


적용-놀라움      <br>

https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/c0f36c04-6d16-4c5b-a541-6b3773bcceca






https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/b1d046ce-0950-4dbe-bb04-6483d6b6472a

https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/e243864a-92a7-47df-9e5e-65addf15fe2a






  
  
## Analysis/Visualization : 
[  undefined](https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/a23aa42c-d65e-42c6-9ec3-8334dc7b14fb)
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/7a038285-fde1-4384-8bd1-95fc0533760a
잠만보 인형과 같이 인간이 아닌 경우는 적용이 안됨
  
  
## Installation : 


*이 환경은 windows 에서 실행하였습니다.<br>

우선 git clone을 통해 repository를 복사합니다.<br>
다음 package들은 terminal안에 설치되어야하는 package들이며, 만약 없을 경우 다음의 명령어를 입력하면 됩니다.

pip install numpy<br>
pip install opencv-python<br>
pip install keras<br>
pip install --upgrade tensorflow<br>
pip install pillow<br>
pip install streamlit<br>

Emotion Detection test file을 실행하기 위해서 다음 명령어를 입력하면 됩니다. <br>

streamlit run streamlit_app.py<br><br>

이 명령어는 Emotion Detection을 할 수 있는 Streamlit web application을 실행시킵니다.
이 application에서 동영상 파일을 업로드 하여 emotion detection을 하면 됩니다.<br><br>

streamlit 에 들어간 뒤, sample 파일 안에 있는 사람의 표정이 담긴 임의의 동영상을 선택합니다<br>
![image](https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/12fea0d9-4073-4993-9a53-59501b3542ce)

결과가 나오는 것을 확인 할 수 있습니다.
![image](https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/00a74244-8e4f-4a88-adca-6ad63564afad)
  
## Presentation :
다 :)

Email
GitHub
📂 전체 글 수 871 개
C/C++/C#
C ++ (164)
C++ STL & 표준 (13)
C++ 연습 문제 패키지 (33)
C++ Boost.Asio 네트워크 (4)
C # (31)
C (2)
Coding Test
알고리즘 구현 (with C++) (15)
프로그래머스 (150)
백준 (35)
코딩 테스트 강의 (3)
코드업 (12)
Unity
유니티 강의1 (66)
유니티 강의2 (38)
유니티 강의3 (61)
유니티 강의4 (15)
내 유니티 문서 (51)
UE4
언리얼 블루프린트 강의 1 (40)
언리얼 블루프린트 강의 2 (5)
언리얼 C++ 강의 1 (3)
언리얼 C++ 책 (3)
내 언리얼 문서 (12)
에러 메모 (1)
CS
알고리즘 강의1 (2)
알고리즘 강의2 (15)
C 자료구조 강의 1(1)
C 자료구조 강의 2(11)
네트워크 (3)
Server
C# 유니티 서버 (2)
DB
MySQL (7)
프로그래머스 SQL (29)
etc
Blog Dev (18)
디자인 패턴 (15)
Blender (1)
Git & Github (6)
비주얼 스튜디오 (1)
블록체인 암호화폐 (3)


[Github 블로그] 유튜브 동영상 삽입하기
 Date: 2020.05.31    Updated: 2020.05.31
 카테고리: Blog

 태그: HTML jekyll Liquid minimal-mistake Blog

첫번째 방법. HTML 태그 사용 : <iframe> 유튜브 영상에 마우스 오른쪽 클릭을 하면 소스 코드 복사라는 항목이 나오는데 그것을 눌러 소스를 복사한 후 포스트 파일에 붙여넣으면 끝! HTML의 iframe태그로 이루어진 코드가 나온다.

<iframe width="956" height="538" src="https://www.youtube.com/watch?v=kmwdVX5cqPI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
https://www.youtube.com/watch?v=kmwdVX5cqPI
