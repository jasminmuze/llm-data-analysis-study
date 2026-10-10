# Chapter 05 데이터 전처리 실습 과제

서울대학교 LLM 데이터 분석 강의의 Chapter 05 실습 제출물입니다.

## 제출물

- [실습 노트북](chapter05/chapter05.ipynb)
- 답안 템플릿과 분석 결과는 노트북 마지막에 작성했습니다.

## 데이터 및 실행

원본 실습 데이터는 `practice/chapter05/data/raw/`에 포함되어 있습니다. 실행 코드는 `src/`와 `scripts/`에 있습니다.

Python 3.10 이상과 pandas를 설치한 뒤 저장소 최상위 폴더에서 실행할 수 있습니다.

```bash
python -m pip install pandas
python -m scripts.preprocess_data
```

노트북은 저장소 최상위 폴더를 기준으로 경로를 설정합니다. 결과 CSV와 요약 보고서는 `data/processed/` 및 `reports/`에 저장됩니다.

## 출처

원본 강의 실습 코드와 데이터: [GilbertMoon/llm-data-analysis-course](https://github.com/GilbertMoon/llm-data-analysis-course/tree/main/practice/chapter05)
