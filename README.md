# kakao_melon_project



### Kakao arena - Melon Playlist Continuation



#### 프로그램 소스코드 설명
* 라이브러리 불러오기
    + pandas 와 numpy이는 데이터를 불러오고 전처리를 하는 과정에서 사용하였습니다.
    + re는 데이터 전처리과정에서 정규표현식을 적용하기위해 사용하였습니다.
    + datatime 과 time은 프로그램이 동작하는 과정을 시간으로 확인하기 위함으로 사용하였습니다.
    + json은 최종 결과물을 json파일형식으로 저장하기 위해 사용하였습니다.
    + CountVectorizer는 Cosine_similarity를 돌리기위해 데이터를 count를 이용하여 백터화시키기 위해 사용하였습니다.
    + cosine_similarity는 백터화된 데이터를 cosine_similarity(코사인 유사도)를 측정하여 데이터간의 유사도 측정하기 위해 사용하였습니다.
``` python
import pandas as pd
import numpy as np
import re 
import time 
import datetime
import json
from scipy import stats
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.metrics.pairwise import cosine_similarity
```
