# 지렁이도 이해하는 머신러닝

- 1.꽃분류하는 코드(입니다.CNN으로 

  캐글에서 가져와서 작동시켜봤습니다.
  
  데이터셋은 이곳에서 다운받을 수 있습니다 . 
  https://www.kaggle.com/alxmamaev/flowers-recognition
  
  원본 주소 : https://www.kaggle.com/madz2000/flowers-classification-using-vgg19-87-accuracy
![너는 꽃이다](https://user-images.githubusercontent.com/50771738/86914609-91c4cd00-c15b-11ea-8d88-c2232d198e1c.png)
- 예측한 결과

![꽃이다 2](https://user-images.githubusercontent.com/50771738/86914668-a739f700-c15b-11ea-996f-6f8148a1d019.png)

- 2.연예인 인식하는 것으로 바꿔 봤습니다. 데이터 셋은 네이버에 있는 이미지를 크롤링해서 가져왔습니다.

  각 연예인들의 사진은 네이버 이미지 크롤러를 이용해서 가져왔습니다.

  하지만 과대적합이 발생하는것 같습니다. 
  
  Train set 정확도는 매우 높은데 , 검증 세트의
  
  정확도는 매우 낮습니다. 
  
  수정이 필요해보입니다.

  ![연예인 1](https://user-images.githubusercontent.com/50771738/87236550-f6b34800-c425-11ea-9144-f1b5b3e9fd04.png)


  ![연예인 2](https://user-images.githubusercontent.com/50771738/87236551-f74bde80-c425-11ea-93e0-ff3ac4635609.png)

  ![정확도](https://user-images.githubusercontent.com/50771738/87236605-527dd100-c426-11ea-8444-cc4b31608507.png)

