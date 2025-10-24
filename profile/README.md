
<div align="center">
<img src="https://github.com/user-attachments/assets/dedac5d9-a66a-4452-b021-b0b950d93080" width="80%"/>

# 💰 딱쿠(Takku)
### 소상공인을 위한 AI 기반 펀딩형 쿠폰 플랫폼
> “소상공인은 상품만 올리세요 — **AI가 대신 홍보하고 판매해드립니다.**”

---

</div>

## 🧠 About Takku

> 소상공인이 상품을 등록하면, AI가 자동으로 홍보 콘텐츠를 생성하고  
> 소비자는 펀딩을 통해 **합리적인 가격으로 쿠폰을 선구매**할 수 있습니다.  
> 빠른 정산과 간편한 사용 경험을 통해 **로컬 비즈니스의 디지털 전환**을 돕습니다.

---

<div align="center">
<img src="https://github.com/user-attachments/assets/af0291d6-cf8d-4f94-b02a-4303d3460c06" width="80%"/>
</div>

---

## 🌟 Our Projects

| Project | Description | Tech Stack |
|----------|--------------|-------------|
| [💰 Takku (Main Service)](https://github.com/takku-project/takku) | Spring 기반의 펀딩 쿠폰 플랫폼 <br>AI 자동 홍보 & 펀딩형 쿠폰 발행 기능 | Spring, MyBatis, JSP, OracleDB, Groq API, Iamport |
| [🤖 Takku AI API](https://github.com/takku-project/takku-ai-api) | FastAPI 기반의 AI 백엔드 <br>리뷰 요약(TextRank) & 추천 시스템(TF-IDF+태그 기반) | FastAPI, Python, scikit-learn, Oracle, TextRank |

---

## 🔍 주요 기능

### 💸 펀딩형 쿠폰 시스템
- 목표 수량 달성 시 펀딩 성공 → 사전 수익 확보
- QR 기반 쿠폰 사용으로 비용 절감 및 편의성 향상

### 🧠 AI 자동 홍보
- Groq API 활용 → 상품 정보 기반 마케팅 문구 자동 생성
- SNS/스토리텔링 중심 콘텐츠로 차별화된 마케팅 제공

### 🎯 개인화 추천
- 사용자 활동/지역 기반 맞춤 펀딩 추천
- AI 기반 취향 분석 확장 가능

### 📈 통계 대시보드
- 플랫폼 전체 및 상점별 매출 통계 시각화
- 펀딩 참여 현황, 트래픽, 매출 흐름 등 데이터 분석 제공

---

## 🧩 Architecture Overview

```

Takku-Organization
├── takku/              # Spring 기반 메인 웹 서비스
│   ├── 펀딩, 쿠폰, 결제, 관리자 기능
│   └── Groq API, Iamport, Solapi 연동
│
└── takku-ai-api/       # FastAPI 기반 AI 서비스
├── /recommend/{user_id}  # 개인화 추천
└── /summary/{product_id} # 리뷰 요약

```

---

## 🛠️ Tech Stack

### 💻 Backend
<p>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/MyBatis-005B9A?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/OracleDB-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"/>
</p>

### 🎨 Frontend
<p>
  <img src="https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/>
</p>

### 🤖 AI & API
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq_API-1F1F1F?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Iamport_(PortOne)-00B2FF?style=for-the-badge&logo=paypal&logoColor=white"/>
  <img src="https://img.shields.io/badge/SOLAPI-4A154B?style=for-the-badge&logo=sms&logoColor=white"/>
</p>

### 🧰 Tools
<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
</p>

---

## 👥 Team Members

> 전원 **풀스택 개발자**로 구성된 팀입니다.  
> 각자 맡은 영역을 기반으로 협력하며, 프로젝트 전 과정을 함께했습니다.

| 최원정(팀장) | 최은진 | 한진호 | 김세연 | 최희정 |
|-------------|--------|--------|--------|--------|
| ![Pic_20250602_121053](https://github.com/user-attachments/assets/6582a9b7-ff56-42ef-a008-221f85c37345) | ![Pic_20250605_123618](https://github.com/user-attachments/assets/e4f45eea-2acd-4c17-a922-75c4b254c343) | ![Pic_20250602_125551](https://github.com/user-attachments/assets/f7d62064-c427-4b6b-9388-840fc01e3e3c) | ![Pic_20250602_010119](https://github.com/user-attachments/assets/eb1bc6e3-034c-4cc2-97b9-f6e18440418b) | ![Pic_20250602_121403](https://github.com/user-attachments/assets/76910895-064a-47d1-8654-7108c29a77f3) |

---

## 🧭 Vision

> **“AI로 소상공인의 비즈니스 성공을 돕는 플랫폼”**  
> Takku는 단순한 쿠폰 서비스가 아니라,  
> **로컬 비즈니스의 지속 가능한 성장 생태계**를 목표로 합니다.


