<div align="center">

# 📐 딥러닝을 위한 수학 — Study

**로널드 크노이젤 《딥러닝을 위한 수학》(제이펍)** 을 정리하며<br>
각 장의 개념을 **Google Colab 노트북**으로 직접 구현·시각화하는 개인 스터디 저장소

<!-- ⚠️ 아래 배지의 YOUR-ID / YOUR-REPO 를 본인 GitHub 계정·저장소 이름으로 바꿔주세요 -->

[![Book](https://img.shields.io/badge/book-Math_for_Deep_Learning-red.svg)](https://www.yes24.com/product/goods/111086874)
[![Publisher](https://img.shields.io/badge/publisher-Jpub-orange.svg)](https://jpub.tistory.com/)
[![Python](https://img.shields.io/badge/python-3.10+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/made%20with-Jupyter-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1L7BtIuGK9AcAz4XtNJCLX0b-usbHBOLt?usp=sharing)
[![Progress](https://img.shields.io/badge/progress-1%2F11%20chapters-yellow.svg)](#-챕터-목록)
[![Last Commit](https://img.shields.io/github/last-commit/YOUR-ID/YOUR-REPO.svg)](https://github.com/YOUR-ID/YOUR-REPO/commits)
[![Stars](https://img.shields.io/github/stars/YOUR-ID/YOUR-REPO.svg?style=social)](https://github.com/YOUR-ID/YOUR-REPO/stargazers)

</div>

---

신경망을 "라이브러리 호출"이 아니라 **확률 · 통계 · 선형대수 · 미분**의 언어로 이해하는 것을 목표로 합니다.
모든 실습은 **Google Colab**에서 진행하며, 각 노트북은 책의 절(section) 단위로
`개념 요약 → 수식 정리 → NumPy/SciPy 구현 → 시각화` 순서로 구성됩니다.

---

## 📚 책 정보

<table>
  <tr>
    <td rowspan="9" width="200" align="center">
      <img src="assets/book.jpg" width="180" alt="딥러닝을 위한 수학 표지"/>
    </td>
    <td><b>제목</b></td>
    <td>딥러닝을 위한 수학 <br><sub>신경망 수학 기초부터 역전파와 경사하강법까지</sub></td>
  </tr>
  <tr>
    <td><b>원서</b></td>
    <td><i>Math for Deep Learning: What You Need to Know to Understand Neural Networks</i> (No Starch Press, 2021)</td>
  </tr>
  <tr>
    <td><b>저자</b></td>
    <td>로널드 크노이젤 (Ronald T. Kneusel)</td>
  </tr>
  <tr>
    <td><b>옮긴이</b></td>
    <td>류광</td>
  </tr>
  <tr>
    <td><b>출판사</b></td>
    <td>제이펍 (제이펍의 인공지능 시리즈 39)</td>
  </tr>
  <tr>
    <td><b>출간일</b></td>
    <td>2022년 8월 8일</td>
  </tr>
  <tr>
    <td><b>페이지</b></td>
    <td>380쪽</td>
  </tr>
  <tr>
    <td><b>ISBN</b></td>
    <td>9791192469225</td>
  </tr>
  <tr>
    <td><b>링크</b></td>
    <td>
      <a href="https://www.yes24.com/product/goods/111086874">예스24</a> ·
      <a href="https://product.kyobobook.co.kr/detail/S000061532888">교보문고</a> ·
      <a href="https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=298579204">알라딘</a> ·
      <a href="https://nostarch.com/math-deep-learning">원서(No Starch Press)</a> ·
      <a href="https://github.com/rkneusel9/MathForDeepLearning">원서 예제 코드</a>
    </td>
  </tr>
</table>

---

## 🗂 챕터 목록

각 챕터 폴더의 `README.md`에 절 단위 노트북과 **Colab 실행 링크** 표가 정리되어 있습니다.

| # | 챕터 | 주요 내용 | 상태 |
|:--:|:--|:--|:--:|
| 01 | [실습 환경 설정](./Ch01_실습환경설정) | NumPy · SciPy · Matplotlib · scikit-learn 설치와 기본 사용법 | ⬜ |
| 02 | [확률 1부](./Ch02_확률1) | 표본공간, 확률의 법칙, 결합확률과 주변확률 | ⬜ |
| 03 | [확률 2부](./Ch03_확률2) | 확률분포(이산·연속), 베이즈 정리 | ⬜ |
| 04 | [통계](./Ch04_통계) | 데이터의 종류, 요약통계량, 분위수·상자그림, 결측자료, 상관관계, 가설검정 | 🟡 |
| 05 | [선형대수 1부](./Ch05_선형대수1) | 스칼라 · 벡터 · 행렬 · 텐서와 텐서 산술 연산 | ⬜ |
| 06 | [선형대수 2부](./Ch06_선형대수2) | 정방행렬, 고윳값·고유벡터, 벡터 노름과 거리, PCA, SVD와 유사역행렬 | ⬜ |
| 07 | [미분](./Ch07_미분) | 기울기, 도함수, 극값, 편미분, 그래디언트 | ⬜ |
| 08 | [행렬 미분](./Ch08_행렬미분) | 행렬 미분 공식과 항등식, 야코비 행렬, 헤세 행렬 | ⬜ |
| 09 | [신경망의 데이터 흐름](./Ch09_신경망의데이터흐름) | 데이터 표현, 전통적 신경망과 CNN에서의 데이터 흐름 | ⬜ |
| 10 | [역전파](./Ch10_역전파) | 역전파의 원리, 손으로 계산하기, 완전연결 신경망, 계산 그래프 | ⬜ |
| 11 | [경사하강법](./Ch11_경사하강법) | SGD, 운동량(momentum), 적응적 경사하강법 | ⬜ |
| — | 부록 | 더 나아가기 | ⬜ |

> 상태 표기 — ⬜ 예정 · 🟡 진행 중 · ✅ 완료

---

## ▶️ Colab에서 실습하기

모든 노트북은 **Google Colab 기준**으로 작성되어 있어 별도의 설치 없이 바로 실행할 수 있습니다.

1. 위 챕터 목록에서 원하는 챕터 폴더로 이동합니다.
2. 챕터 `README.md`의 표에서 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1L7BtIuGK9AcAz4XtNJCLX0b-usbHBOLt?usp=sharing) 배지를 클릭합니다.
3. Colab에서 `런타임 → 모두 실행`으로 노트북을 실행합니다.

<details>
<summary>GitHub 노트북을 Colab에서 여는 방법 (링크 규칙)</summary>

```
https://colab.research.google.com/github/{GitHub-ID}/{저장소}/blob/main/{경로}/{파일명}.ipynb
```

또는 Colab의 `파일 → 노트북 열기 → GitHub` 탭에서 저장소 주소를 붙여 넣어도 됩니다.

</details>

<details>
<summary>로컬에서 실행하고 싶다면</summary>

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install numpy scipy matplotlib scikit-learn jupyterlab
jupyter lab
```

</details>

### 사용 패키지

| 패키지 | 용도 |
|:--|:--|
| NumPy | 데이터 표현 및 텐서 연산 |
| SciPy | 확률 분포 · 가설 검정 |
| Matplotlib | 시각화 |
| scikit-learn | 예제 데이터셋 및 검증용 구현 비교 |

> Colab에는 위 패키지가 모두 기본 설치되어 있습니다. 추가 패키지가 필요한 노트북은 첫 셀에 `!pip install` 을 포함합니다.

---

## 📁 저장소 구조

```
딥러닝을위한수학/
├── README.md
├── LICENSE
├── assets/
│   └── book.jpg                  # 책 표지 이미지
├── Ch01_실습환경설정/
│   └── README.md                 # 절 목록 + Colab 링크 표
├── ...
└── Ch04_통계/
    ├── README.md
    ├── 1_데이터의종류.ipynb        # 4.1
    └── figure/
        └── 그림4-1.jpg            # 본문 그림 · 직접 그린 도식
```

### 네이밍 규칙

- 챕터 폴더 : `Ch{두 자리 번호}_{주제}` (예: `Ch05_선형대수1`)
- 노트북 파일 : `{절 번호}_{절 제목}.ipynb` (예: `2_요약통계량.ipynb`)
- 그림 : 각 챕터 폴더의 `figure/` 아래에 모음

---

## ✍️ 정리 원칙

- **수식은 반드시 손으로 한 번 유도한 뒤** 노트북에 LaTeX으로 옮겨 적습니다.
- 라이브러리 함수를 쓰기 전에 **NumPy로 직접 구현**해 보고, 그 결과를 라이브러리 결과와 비교합니다.
- 개념마다 **"왜 딥러닝에서 이게 필요한가"** 를 한 줄로 남깁니다.
- 예시는 가능한 한 **그림/그래프로 시각화**하여 직관을 확인합니다.

---

## 📌 참고

- 이 저장소는 개인 학습 목적의 정리본이며, 책의 본문을 그대로 옮긴 것이 아닙니다.
- 모든 내용의 저작권은 원저자와 출판사에 있습니다. 자세한 내용은 반드시 원서를 참고해 주세요.
- 원서 예제 코드: <https://github.com/rkneusel9/MathForDeepLearning>
