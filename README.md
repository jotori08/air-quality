# ☀️ 도시의 공기질 데이터
## 📃 데이터셋 소개
- 사우디아라비아 도시 지역에서 수집된 대기질 측정값
- 데이터 출처: https://www.kaggle.com/datasets/srisyra02/air-quality-dataset/data

## 📊 속성 정보
| 속성명 (영문) | 속성명 (한글) | 설명 |
| :--- | :--- | :--- |
| `PM2.5` | **초미세먼지** |
| `PM10` | **미세먼지** |
| `NOx` | **질소산화물** |
| `NO2` | **이산화질소** |
| `SO2` | **아황산가스** |
| `VOCs` | **휘발성유기화합물** |
| `CO` | **일산화탄소** |
| `CO2` | **이산화탄소** |
| `CH4` | **메테인** |
| `Temperature` | **온도** |

## ✅ 구글 코랩에서 데이터 업로드 및 불러오기
```python
!git clone https://github.com/jotori08/air-quality.git

import pandas as pd
df = pd.read_csv('/content/air-quality/air quality.csv')
```
