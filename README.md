# Rescorla-Wagner-model(학습 곡선)

* desc : 학습심리학 과목을 들으며 RW model에 대하여 해당 이슈에 대한 그래프 그려보기 (2020.10)
* 사용 프로그램 및 기술
  * python
  * Colab(주피터 노트북)
  
* 참고 논문 : [RW model의 성공한 모델과 실패한 모델](https://github.com/mong-head/Rescorla-Wagner-model/blob/master/documents/miller-1995-advanced%20questions.pdf)
* 과제 설명 : [과제 설명](https://github.com/mong-head/Rescorla-Wagner-model/blob/master/documents/%EA%B3%BC%EC%A0%9C%EC%84%A4%EB%AA%85_R-W%20model%20assignment%202020.pdf)
* 개인 보고서 : [그래프와 그에 대한 개인적인 생각](https://github.com/mong-head/Rescorla-Wagner-model/blob/master/documents/R-W%20model_graphs_and_my_descriptions.pdf)
* 코드 : [RW model-mine](https://github.com/mong-head/Rescorla-Wagner-model/blob/master/rescorla_wagner_model.ipynb)

## RW model 짧게 설명

RW모델은 V의 변화를 구하는 모델(학습곡선)

* ∆V = αβ(λ − ΣV)
  * V : CS,US 둘의 연합 강도
  * λ(=Vmax) : CS,US의 최대 연합 강도. 쉽게 생각하면 둘이 100% 연합되었다고 생각하면 됨(CS,US 둘다 있다면 람다는 보통 1)
  * β : learning rate 
  * ΣV : 전체 연합 강도. 가령 CS1,CS2가 US와 함께 pair되려고 한다면, CS1의 V1,CS2의 V2를 합한 것(ΣV=V1+V2).

## 결과

1. Conditioned inhibition

![image](https://user-images.githubusercontent.com/52481037/98978268-0fab4180-255d-11eb-9dcf-f88ef53aeb78.png)


2. Overexpectation

![image](https://user-images.githubusercontent.com/52481037/98978275-133ec880-255d-11eb-8267-217d4fa8b41e.png)
![image](https://user-images.githubusercontent.com/52481037/98978282-15a12280-255d-11eb-80e0-e1b2d67439d7.png)


3. Second-order conditioning 

![image](https://user-images.githubusercontent.com/52481037/98978294-19cd4000-255d-11eb-93fd-d3ca49756ba1.png)


4. Sensory preconditioning 

![image](https://user-images.githubusercontent.com/52481037/98978304-1cc83080-255d-11eb-915d-39435e2b6e73.png)


5. Supernormal conditioning

![image](https://user-images.githubusercontent.com/52481037/98978315-20f44e00-255d-11eb-95eb-09cfa55a2a96.png)
![image](https://user-images.githubusercontent.com/52481037/98978330-281b5c00-255d-11eb-81ed-c5daa8c05429.png)


6. Excitatory conditioning without the US 

![image](https://user-images.githubusercontent.com/52481037/98978339-2baee300-255d-11eb-84d7-96cd74cd4674.png)


7. Optional question

![image](https://user-images.githubusercontent.com/52481037/98978351-30739700-255d-11eb-8108-9a76cc18c636.png)
