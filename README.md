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
<iframe width="1576" height="899" src="https://www.youtube.com/embed/kmwdVX5cqPI" title="건국대학교 오픈SW입문 팀프로젝트/ 20조" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

