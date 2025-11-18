# Agent Quest - AI 에이전트 설계 학습 플랫폼

> 게임처럼 즐겁게 배우는 AI 에이전트 설계 교육 앱

[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)](https://developer.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 📱 프로젝트 소개

**Agent Quest**는 모바일 환경에서 AI 에이전트 설계를 게임화된 방식으로 학습할 수 있는 안드로이드 교육 플랫폼입니다. 

### 🎯 핵심 컨셉
- **게임화된 학습**: 레벨, XP, 배지 시스템으로 동기부여
- **모바일 최적화**: 언제 어디서나 5-10분 마이크로 러닝
- **실전 중심**: 테스트 케이스 기반 객관적 역량 평가
- **단계적 학습**: System Prompt부터 Multi-Agent까지 체계적 학습 경로

---

## ✨ 주요 기능

### 📚 10단계 학습 시스템
| 레벨 | 학습 개념 | 난이도 |
|------|----------|--------|
| 1-2 | System Prompt, Structured Output | ⭐ |
| 3-4 | Function Calling, Error Handling | ⭐⭐ |
| 5-6 | RAG, Chain of Thought | ⭐⭐⭐ |
| 7-8 | Multi-Agent, State Management | ⭐⭐⭐⭐ |
| 9-10 | Advanced Orchestration, Self-Reflection | ⭐⭐⭐⭐⭐ |

### 🎨 터치 최적화 UI
- 카드 기반 워크플로우 편집기
- 스와이프, 탭, 드래그 제스처 지원
- 한 손 조작 가능한 레이아웃
- Material Design 3 가이드라인 준수

### 🏆 게임화 요소
- **일일 미션**: 매일 3개 챌린지 제공
- **소셜 기능**: 친구 순위 비교, 솔루션 공유
- **보상 시스템**: 코인, 에너지, 경험치
- **배지 컬렉션**: 완벽주의자, 속도광, 효율왕 등

### 📊 평가 시스템
- 공개/히든 테스트 케이스 자동 평가
- 실시간 피드백 및 힌트 제공
- 개념별 숙련도 추적
- 전국/전세계 순위

---

## 🏗️ 기술 스택

### Frontend (Android)
```
- Language: Kotlin, Java
- UI Framework: Jetpack Compose
- Architecture: MVVM + Clean Architecture
- DI: Hilt
- Network: Retrofit2 + OkHttp
- Local DB: Room
- Async: Coroutines + Flow
```

### Backend
```
- API Server: FastAPI (Python)
- Database: PostgreSQL
- Cache: Redis
- Vector DB: Pinecone (RAG)
- Auth: Firebase Authentication
- Push: Firebase Cloud Messaging
```

### AI/ML
```
- Agent Runtime: Anthropic Claude API
- Evaluation: OpenAI GPT-4
- Framework: LangChain, LangGraph
- Embeddings: OpenAI text-embedding-3
```

---

## 📚 RAG 지식베이스

프로젝트에서 사용하는 RAG 시스템의 지식 소스:

### AI 에이전트 프레임워크
1. **LangChain 공식 문서 및 튜토리얼**
   - 출처: [LangChain Docs](https://python.langchain.com/)
   
2. **LangGraph 에이전트 오케스트레이션 가이드**
   - 출처: [LangGraph Docs](https://langchain-ai.github.io/langgraph/)

3. **Anthropic Claude API 문서**
   - 출처: [Anthropic Docs](https://docs.anthropic.com/)

4. **OpenAI API 및 GPT 모델 활용 가이드**
   - 출처: [OpenAI Docs](https://platform.openai.com/docs)

### RAG 연구 논문
5. **Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks**
6. **Leveraging Passage Retrieval with Generative Models for Open Domain QA**
7. **BEIR: A Heterogeneous Benchmark for Zero-shot Evaluation of Information Retrieval Models**
8. **Lost in the Middle: How Language Models Use Long Contexts**
9. **Retrieval-Augmented Generation for Large Language Models: A Survey**
10. **Compressing Context to Enhance Inference Efficiency of Large Language Models**
11. **RECOMP: Improving Retrieval-Augmented LMs with Compression and Selective Augmentation**
12. **Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection**
13. **Corrective Retrieval-Augmented Generation**
14. **Modular RAG: Transforming RAG Systems into LEGO-like Reconfigurable Frameworks**
15. **Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models**
16. **Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts**
17. **Ragas: Automated Evaluation of Retrieval Augmented Generation**
18. **From Local to Global: A Graph RAG Approach to Query-Focused Summarization**

### 추가 리소스
19. **벡터 데이터베이스 (Pinecone, Chroma) 활용 가이드**
20. **Multi-Agent 시스템 설계 패턴 (CrewAI, AutoGen)**
21. **프롬프트 엔지니어링 베스트 프랙티스**
22. **Function Calling 및 Tool Use 패턴 예제**
23. **AI 에이전트 평가 메트릭 및 테스트 방법론**

---

## 🎨 UI/UX 디자인

### 컬러 팔레트
- **Primary**: `#10b981` → `#059669` (Emerald Green Gradient)
- **Success**: `#4ade80` (Green)
- **Error**: `#ef4444` (Red)
- **Background**: `#f8f9fa` (Light Gray)

### 타이포그래피
- **Font**: Nunito (둥글고 친근한 느낌)
- **Heading**: 24px, Bold
- **Body**: 14px, Regular
- **Caption**: 12px, Regular

### UI 컴포넌트
- **버튼**: 12px 둥근 모서리, 그라디언트 배경
- **카드**: 2px 테두리, 그림자 효과
- **칩**: 20px 둥근 모서리, 투명 배경

자세한 디자인 가이드는 [UI/UX 목업](docs/ui-mockups/agent_quest_ui_mockup.html)을 참조하세요.

---

## 👥 팀

**2025년 새싹 해커톤 (SeSAC Hackathon)**

- 팀명: Agent Quest Team
- 팀원: [김대건, 나민재 이름 추가]

---

## 📞 문의

- 이메일: contact@aisc.ac
- 공식 웹사이트: [agentquest.com](https://agentquest.com)

---


<div align="center">

**Agent Quest와 함께 AI 에이전트 마스터가 되어보세요!**

Made by Agent Quest Team

</div>
