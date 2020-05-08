# Amazon_Review_Classification
Amazon_Review_Classification Assignment by NLP class in SKKU

### 아마존 리뷰 분류기 입니다.
    여러가지 조합을 사용해보았지만 Naive Bayes 와 CountVectorizer를 사용하는 것이 효과가 제일 좋았습니다.

    train.csv 와 test.csv는 각각 훈련용 데이터, test용 데이터입니다.

    각각의 긍정과 부정으로 라벨링 되어있는 아마존의 영문 리뷰를 학습하여 test데이터로 성능을 확인하는 코드입니다.


### train and test csv모형
    영문 리뷰 - 라벨 의 구조로 구성되어 있습니다.

    라벨의 경우 "pos"와 "neg"로 이뤄져 있습니다.

    파일에도 적어놓았지만 pos와 neg를 그대로 사용하지 않고 0과 1로 변경하여 사용하였습니다.


### 보완할 점
    딥러닝을 사용하지 않았고, 파라미터 조정만으로는 폭발적인 성능의 향상을 기대하기 힘들다
