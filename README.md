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
  
https://github.com/ysungpark/opensw23-team_YSPark/assets/129364108/bce8494d-d77d-4473-bbc9-9b02e2f5ae83



  
  
## Analysis/Visualization : 
  undefined
  
  
## Installation : 
이 환경은 windows 에서 실행하였습니다.<br>
시작하기 전에, terminal안에 설치되어야하는 package들이며, 만약 없을 경우 다음의 명령어를 입력하면 됩니다.

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
  currently empty
