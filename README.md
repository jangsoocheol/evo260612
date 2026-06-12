# 🧬 하디-바인베르크 법칙 탐구 시뮬레이터

고등학교 생물 수업을 위한 **하디-바인베르크 법칙** 인터랙티브 교육 웹앱입니다.  
전제 조건이 깨질 때 집단의 대립유전자 빈도와 유전자형 빈도가 어떻게 달라지는지 시각적으로 탐구할 수 있습니다.

---

## 📚 다루는 주제

| 모듈 | 전제 조건 위반 요인 | 주요 내용 |
|------|------------------|-----------|
| ① 평형 기본 | (이상적 조건) | p², 2pq, q² 빈도 및 세대별 평형 유지 |
| ② 유전적 부동 | 소집단 | 무작위 샘플링 오차, 고정·소실 |
| ③ 자연선택 | 적합도 차이 | 선택 계수(s), 우세 계수(h)에 따른 빈도 변화 |
| ④ 돌연변이 | 돌연변이 | 전향·역돌연변이율에 따른 돌연변이 평형 |
| ⑤ 유전자 흐름 | 이주 | 집단 간 대립유전자 빈도 동질화 |
| ⑥ 비무작위 교배 | 근친교배 | 이형접합체 감소, 동형접합체 증가 |

---

## 🚀 로컬 실행

```bash
# 1. 저장소 클론
git clone https://github.com/YOUR_USERNAME/hardy-weinberg-app.git
cd hardy-weinberg-app

# 2. 패키지 설치
pip install -r requirements.txt

# 3. 앱 실행
streamlit run app.py
```

브라우저에서 `http://localhost:8501` 이 자동으로 열립니다.

---

## ☁️ Streamlit Community Cloud 배포

1. 이 저장소를 GitHub에 **public**으로 업로드합니다.
2. [share.streamlit.io](https://share.streamlit.io) 에 로그인합니다.
3. **New app** → 저장소 선택 → `app.py` 지정 → **Deploy** 클릭.
4. 자동으로 URL이 생성됩니다 (예: `https://yourapp.streamlit.app`).

> `requirements.txt`가 루트에 있으면 별도 설정 없이 의존성이 자동 설치됩니다.

---

## 🗂️ 파일 구조

```
.
├── app.py            # 메인 Streamlit 앱
├── requirements.txt  # 패키지 목록
└── README.md         # 이 파일
```

---

## 🛠️ 기술 스택

- **Streamlit** — 웹앱 프레임워크
- **Plotly** — 인터랙티브 그래프
- **NumPy / Pandas** — 수치 시뮬레이션

---

## 📖 라이선스

MIT License — 교육 목적 자유 사용 가능
