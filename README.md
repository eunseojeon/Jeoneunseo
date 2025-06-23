# Jeoneunseo
## test 중
### 아무거나
#### 또 아무거나
**굵게**
*기울임*
~~취소선~~
'코드처럼'
- 항목1
- 항목2
  - 하위항목
>인용
>>중첩인용
### 사진 넣어보기
<img width="191" alt="스크린샷 2025-06-05 11 56 28" src="https://github.com/user-attachments/assets/6c93576b-fd62-477c-b209-6497207129df" />

## 중요한 부분
<img width="819" alt="스크린샷 2025-06-23 12 14 20" src="https://github.com/user-attachments/assets/1cb8a1f8-8636-4e1f-b23b-5078b30961fa" />

## Markdown 연습 사이트

- https://dillinger.io/
- https://stackedit.io/
- https://markdownlivepreview.com/

## 참고 링크
- https://developer.nvidia.com/embedded
- https://github.com/WongKinYiu/yolov12
- https://dillinger.io/


# 교수님께서 올려주신거 따라해보기
## 스마트팜 프로젝트 완전 가이드

> 누구나 따라할 수 있는 아두이노 & Jetson 기반 스마트팜 구축 설명서입니다.


## 📌 프로젝트 소개

가정에서 식물을 자동으로 키우고 싶으신가요?  
이 프로젝트는 아두이노와 Jetson Orin Nano를 이용해 온도, 습도, 물공급을 자동으로 제어하는 스마트팜 시스템을 구현합니다.

---

## 📷 구성도

![스마트팜 구성도](./images/farm_diagram.png)

---

## 🛠 기술 스택

- **🧠 AI 모델**: YOLOv12 전이학습
- **🖥 임베디드 보드**: Jetson Orin Nano
- **🛒 마이크로컨트롤러**: Arduino UNO
- **💬 통신**: Serial / MQTT
- **💡 언어**: Python, C++

---

## 🔩 사용 부품

| 부품명          | 수량 | 설명                   |
|----------------|------|------------------------|
| Arduino UNO    | 1    | 센서 및 릴레이 제어용 |
| DHT11 센서     | 1    | 온습도 측정용         |
| 워터펌프        | 1    | 자동 급수용           |
| 릴레이 모듈     | 1    | 고전력 부품 제어      |
| 식물용 LED      | 1    | 광합성 조명           |

---

## ⚙️ 설치 방법

```bash
# 아두이노 IDE 설치
sudo apt install arduino

# 파이썬 라이브러리 설치
pip install pyserial
pip install opencv-python

