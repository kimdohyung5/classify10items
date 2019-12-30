# classify10items

1. 개요 <br>
    10개의 item을 pytorch로 cnn학습을 시키고, 학습된 결과물인 pt화일을 추출하여 <br>
    향후에 웹에서 inference가 잘 되는지 테스트를 진행한다.<br>
    10개의 item : ant, bear, bee, cat, dog, horse, lion, monkey, pig, spider<br><br><br>
2. 작업 순서 <br>
   ㄱ. 웹을 통해서 이미지 획득작업을 진행한다.<br>
   ㄴ. item별로 일정갯수(300개) 이상이 모이면 원본데이터로 별도로 보관을 한다.<br>
   ㄷ. 데이터 부풀리기(data augmentation)를 향후에 데이터가 별로 없을 경우 학습이 원활할 수 있도록 한다.<br>
   ㄹ. 모델을 선택하고 hypter parameter tuning작업을 위한 실험코드를 작성한다.<br>
   ㅂ. validation accuracy가 높은 pt화일을 선택하여 export한다.<br>
   
