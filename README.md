### 데이터셋
- 귤과 오렌지 구분
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/citrus.csv
```
-  아이리스
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/iris.csv
```

- [펭귄 데이터](https://raw.githubusercontent.com/devdio/flyai_datasets/main/penguins.csv)
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/penguins.csv
```
- 인디언 당뇨병 데이터
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/diabetes.csv
```

- 펭귄 데이터 (허깅페이스)
```
참고 : https://huggingface.co/datasets/methodidacte/penguins
```
```python
from datasets import load_dataset

dataset = load_dataset("methodidacte/penguins")
```
- 삼성전자 주가
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/samsung.csv
```
  
- 캘리포니어 집값
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/california_housing_train.csv
```
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/california_housing_test.csv
```
- 비디오게임 판매량
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/vgsalesGlobale.csv
```
- 구글 플레이스토어 데이터
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/googleplaystore.csv
```

- Data Jobs
구글드라이버에서 공유
```
!gdown https://drive.google.com/uc?id=1QhadpOVehfSCkRWydOje1SxhNrXP39Uh -O ./data_jobs.csv
```

- 컬럼명 테스트용
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/columns_name_test.csv
```


- 은행 고객 데이터
```
https://raw.githubusercontent.com/devdio/flyai_datasets/main/churn_bank.csv
```
```
*  CustomerId: 데이터 세트 내에서 개별 고객을 추적하고 차별화하는 데 사용할 수 있습니다.
*  Surname: 이름
*  CreditScore: 신용도 평가
*  Geography: 지역
*  Gender: 성별
*  Age: 나이
*  Tenure: 일반적으로 고객이 은행과 거래한 연도 또는 개월 수를 나타냅니다.
*  Balance: 특정 시점에 고객의 은행 계좌에 있는 금액을 반영합니다
*  NumOfProducts: 상품의 개수
*  HasCrCard: 신용카드를 가지고 있는지 아닌지 
*  IsActiveMember: 활성 회원(1)인지 아닌지(0)
*  EstimatedSalary: 고객의 소득 수준에 대한 근사치
*  Exited: 고객이 은행에서 이탈했는지(1) 또는 이탈하지 않았는지(0)
```

### 라이브러리
- Matplotlib 한글화
[koreanize-matplotlib](https://github.com/ychoi-kr/koreanize-matplotlib)
```
https://github.com/ychoi-kr/koreanize-matplotlib
```  

## VSCode Extension
- Rainbow CSV by mechatroner
- Edit CSV by janisdd

## Colab 환경 
2024-06-10
```
keras==2.15.0
matplotlib==3.7.1
numpy==1.25.2
opencv-contrib-python==4.8.0.76
opencv-python==4.8.0.76
pandas==2.0.3
scikit-image==0.19.3
scikit-learn==1.2.2
seaborn==0.13.1
tensorboard==2.15.2
tensorboard-data-server==0.7.2
tensorflow @ https://storage.googleapis.com/colab-tf-builds-public-09h6ksrfwbb9g9xv/tensorflow-2.15.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl#sha256=a2ec79931350b378c1ef300ca836b52a55751acb71a433582508a07f0de57c42
tensorflow-datasets==4.9.5
tensorflow-hub==0.16.1
```
##### 끝
