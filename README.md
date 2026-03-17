# Science Agent Leaderboard

OpenAI GPT 기반 Agent가 과학 문제를 어떻게 해결하는지를 평가하는 Leaderboard 프로젝트입니다.

---

## 📌 프로젝트 개요

최근 LLM 기반 Agent가 빠르게 발전하고 있지만,  
단순한 모델 성능이 아닌 **Agent 설계 방식(Workflow, Tool usage, Cost, Reproducibility)**을  
체계적으로 평가할 수 있는 환경은 아직 부족합니다.

본 프로젝트는 다음을 목표로 합니다:

- Agent 기반 과학 문제 해결 능력 평가
- Benchmark 및 Evaluation 체계 설계
- Leaderboard 플랫폼 구축

---

## 🎯 프로젝트 목표 (MVP)

초기 2주 목표:

- 하나의 Challenge(Task) 정의
- Agent 실행 환경 구축
- 기본 Evaluation Metric 설계
- 간단한 Leaderboard 구성

---

## 🧠 우리가 평가하는 것

이 프로젝트는 “모델 성능”이 아니라  
👉 **Agent 설계 능력**을 평가합니다.

주요 평가 요소:

- Correctness (정답 정확도)
- Tool Usage (도구 활용)
- Cost (비용 효율성)
- Reproducibility (재현성)

---

## 🧩 프로젝트 구조

## Structure
- /challenges   → 문제 정의 (Benchmark)
- /evaluation   → 평가 로직 (Metrics, Scoring)
- /leaderboard  → 결과 저장 및 랭킹
- /docs         → 설계 문서 및 논의
- /examples     → 샘플 입력/출력

---

## 👥 팀 구성 및 역할

### 공준호
- Project Lead / Architect
- Benchmark 방향 및 구조 정의
- Leaderboard 설계

### 김보금
- Benchmark Designer
- Challenge(Task) 설계
- 문제 구조 정의

### 김가영
- Evaluation Lead
- Metric 설계
- Scoring 및 Execution Pipeline

### 박진우
- Benchmark Research
- Dataset 및 기존 benchmark 조사
- 문서화 및 분석 지원

---

## ⚙️ 프로젝트 진행 방식

- GitHub Issue 기반으로 작업 진행
- 각 영역별 Owner 중심으로 설계 및 구현
- 논의는 자유롭게 하되, 최종 결정은 Owner 기준으로 정리

---

## 📊 현재 진행 단계

- [x] 팀 구성
- [x] 역할 정의
- [ ] Challenge v1 설계
- [ ] Evaluation Metric 정의
- [ ] Execution Pipeline 구축
- [ ] Leaderboard MVP 구현

---

## 🚀 향후 방향

- 다양한 과학 문제 확장
- multi-agent benchmark 도입
- 지속적인 Leaderboard 운영

또한 Andrej Karpathy의 **AutoResearch 개념을 기반으로 한  
Autonomous Research Agent 구조도 향후 적용을 고려하고 있습니다.**

---

## 🤝 참여 방법

- Issue 확인 후 참여 가능
- Discussion 및 PR 환영합니다
