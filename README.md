# Deep learning 25\_2 : Assignment Readme

This repository contains my solutions to the assignments of the Deep Learning class offered by Professor Heewon Kim at Soongsil University (2nd semester, 2025).

The class is part of [RealityLab](https://reality.ssu.ac.kr/), which focuses on research in deep learning and related areas.

---

# 📘 프로젝트 개요: Style Transfer

본 프로젝트에서는 Style Transfer 모델을 구현한다.
주요 목표는 다음과 같다.

1. content image 준비

2. style image 준비

3. 전처리하여 GPU 텐서로 변환

4. SqueezeNet feature map 추출

5. content loss + style loss 함수 작성

6. 초기화된 generate image를 최적화

7. 결과 시각화

---

## ⚙️ 실습 환경 설정

1. Conda 가상 환경 생성:

```bash
conda create --name ssu_style python=3.10
conda activate ssu_style
```

2. 필수 라이브러리 설치:

```bash
pip install numpy==2.2.6
pip install opencv-python==4.12.0.88
pip install Pillow==11.3.0
pip install h5py
pip install future
pip install imageio
```
---

## 📊 결과 보고

* 본 reop를 본인 컴퓨터에 git pull하시고 필요한 파일 utils/rnn.py 등등을 완성하시오.
* 그 다음 실습한 StyleTransfer.ipynb을 제출하시요.
* git push를 하면 자동으로 과제가 제출됩니다.
**class room 제출 방법** : [https://github.com/WE-SOPT-29th-Web-Part/notice-by-Euijin-Kim] 참고
---

## ❓ 질문 방법

* 코드 실행 에러나 환경 문제: 조교 메일 문의 ([por1329@naver.com](mailto:por1329@naver.com))
* 구현 아이디어/개념 관련: 강의 자료 및 QnA 활용
* **주의:** 지정된 Conda 환경을 사용하지 않아 발생한 문제는 답변하지 않음

---

## 🚨 주의사항

* 무단 코드 복사/붙여넣기 적발 시 0점 처리
