# Python Study for Computational Physics

프로그래밍 물리학 실습에서 작성한 Python/Jupyter Notebook 자료를 정리한 저장소입니다.  
기초 Python 문법부터 수치 계산, 데이터 시각화, Monte Carlo 시뮬레이션, 수치 미분/적분, 데이터 피팅까지 물리 문제를 계산적으로 다루는 과정을 담고 있습니다.

This repository contains Python and Jupyter Notebook materials from computational physics practice.  
It covers the process of solving physics and mathematics problems with code, from basic Python syntax to numerical methods, visualization, Monte Carlo simulation, numerical differentiation/integration, and data fitting.

## Repository Overview

이 저장소는 수업 실습, 연습문제, 과제 노트북으로 구성되어 있습니다.

The repository is organized into lecture practice notebooks, exercise solutions, homework notebooks, and supporting data files.

| Category / 구분 | Description / 내용 |
| --- | --- |
| `CP_*.ipynb` | Lecture practice notebooks by date |
| `CP_EX*.ipynb` | Exercise solutions |
| `CP_HW*.ipynb` | Homework solutions and experiment results |
| `Data Folder/` | Example data used for fitting, statistics, and function calculations |

## Topics

- Python 기본 문법, 리스트/딕셔너리, 반복문과 함수
- NumPy를 활용한 배열 계산과 벡터화
- Matplotlib 기반 그래프 작성 및 결과 시각화
- 난수 생성과 Monte Carlo 방법
- Taylor 급수와 특수함수 계산
- 수치 미분, 수치 적분, Euler method
- Pandas를 활용한 데이터 처리
- SciPy를 활용한 curve fitting 및 수치 계산
- 물리/수학 문제를 코드로 모델링하고 결과를 해석하는 연습

English summary:

- Basic Python syntax, lists/dictionaries, loops, and functions
- Array computation and vectorization with NumPy
- Data visualization with Matplotlib
- Random number generation and Monte Carlo methods
- Taylor series and special function calculations
- Numerical differentiation, numerical integration, and Euler method
- Data processing with Pandas
- Curve fitting and numerical computation with SciPy
- Modeling physics/math problems in code and interpreting the results

## Tech Stack

- Python
- Jupyter Notebook / Google Colab
- NumPy
- Matplotlib
- Pandas
- SciPy
- Scikit-learn
- Seaborn

## How to Run

1. 저장소를 클론합니다.

```bash
git clone https://github.com/Rucolagwg/python-study.git
cd python-study
```

2. Jupyter Notebook 또는 Google Colab에서 원하는 `.ipynb` 파일을 엽니다.

```bash
jupyter notebook
```

3. `Data Folder/`의 텍스트 데이터가 필요한 노트북은 데이터 파일 경로가 올바른지 확인한 뒤 실행합니다.

For notebooks that depend on text files in `Data Folder/`, make sure the data path is correct before running the cells.

## Notes

각 노트북은 프로그래밍 물리학 수업을 따라가며 작성한 실습 기록입니다.  
단순한 코드 실행 결과뿐 아니라, 수치적 방법이 물리 문제를 어떻게 근사하고 해석하는지 확인하는 데 초점을 두었습니다.

These notebooks are study records from a computational physics course.  
The focus is not only on running code, but also on understanding how numerical methods approximate and explain physical problems.
