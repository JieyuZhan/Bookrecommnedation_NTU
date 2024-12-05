# Book Recommendation System

## Project Overview)
This Book Recommendation system is based on the book you read, and the system will  recommned for the similar book for you.
This is a practicing project for student in National Taiwan University.This project aiming to using KNN method to recommend a book based on you have been read.
## Dataset Information
- **Data source**：Book-Crossing dataset form kaggle: https://www.kaggle.com/datasets/ra4u12/bookrecommendation
-  Data ：BX-Books.csv, BX-Users.csv, BX-Book-Ratings.csv
- **Columns**：
  - ISBN
  - used_id
  - rating
  - title
  - author
  - year
  - publisher
  - url

## Installation and Setup

### Requirements
- Python 3.8+
- Pandas
- Numpy
- Jupyter Notebook (optional)


## 使用說明 (Usage)

### 資料載入
```python
import pandas as pd
from pathlib import Path

books = pd.read_csv(Path('data') / 'BX-Books.csv', 
                    sep=";", 
                    on_bad_lines='skip', 
                    encoding='latin-1')
```

