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



적용-기쁨      <br>

https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/d3e69a20-4d3b-4200-b5c8-15bf91cbfbc7

적용-화남     <br>
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/5c0a09cf-0998-4dba-8798-a05993fbe39d

  
  
## Analysis/Visualization : 
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/b1d046ce-0950-4dbe-bb04-6483d6b6472a (45도 각도 원본)
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/e243864a-92a7-47df-9e5e-65addf15fe2a (옆모습 원본)
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/75f42375-5711-4805-bdf4-c139c96243c8 (45도 각도 감정인식)
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/17fc3c9d-2632-4c17-a412-99f63aab3ca0 (옆모습 감정인식)
<br><br>
분석결과 사람의 얼굴표정은 약 45도 정도까지만 분석이 되고, 측면부의 경우에는 감정인식이 잘 안되는 것을 확인 할 수 있었습니다.

https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/a1b77224-9684-468e-aa54-7b3b4422876f (잠만보 인형 감정인식)
<br><br>
잠만보 인형과 같이 인간이 아닌 경우 또한 감정인식이 잘 안되는 것을 확인 할 수 있었습니다.
<br><br>
개선되었으면 좋겠는 점에 대해 설명하겠습니다.
1. 다양한 감정을 표현 할 수 있었으면 좋겠습니다. 이 소스코드에서는 6개의 감정만을 사용하는데, 더 다양한 감정을 사용한다면 더 좋았을 것입니다.
2. 인간 뿐만 아니라 다양한 생명체의 감정을 인식할 수  있었으면 좋겠습니다. 또한 얼굴의 일부분만 나오더라도, 감정을 유추할 수 있다면 더 좋았을 것입니다.
3. 감정의 변화를 기록할 수 있었으면 좋겠습니다. 사람의 감정의 변화를 기록한다면, 좀 더 응용할 수 있는 범위가 늘어날 것입니다.

  
  
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
https://youtu.be/kmwdVX5cqPI
