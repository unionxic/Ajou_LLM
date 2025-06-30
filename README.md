![Project Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📝 프로젝트 소개
웹 환경에서 실시간으로 변화하는 신조어를 감지하고 문맥에 맞는 해석을 제공하는 Chrome Extension입니다.

## 🎯 주요 기능
- 🔍 실시간 신조어 감지
- 🤖 AI 기반 의미 생성 및 해석
- 💬 직관적인 팝업 인터페이스
- 📚 개인화된 학습 시스템

## 🛠️ 기술 스택
- **Frontend**: TypeScript, React, Chrome Extension API
- **Backend**: FastAPI, PostgreSQL, Redis
- **AI/ML**: OpenAI GPT-4, spaCy, RunPod GPU
- **Infrastructure**: Railway, GitHub Actions

## 📊 프로젝트 목표
- 신조어 감지 정확도: F1 Score ≥ 0.85
- 응답 속도: ≤ 1초

## 🚀 개발 환경 설정
### 사전 요구사항
- Node.js 18+
- Python 3.11+
- Git

### 설치 및 실행
```bash
# 레포지토리 클론
git clone https://github.com/unionxic/Ajou_LLM.git
cd Ajou_LLM

# Frontend 설정
cd frontend
npm install
npm run dev

# Backend 설정 (새 터미널)
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload




