# 🧭 AI Ethics Agent

> **AI 서비스의 윤리적 리스크를 자동 진단**하고, **EU AI Act (2024)** 및 **ALTAI** 기준에 따라 **근거 기반(grounded) 개선 권고안**을 생성하는 에이전트

[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](#)

---

## ✨ Overview

**AI Ethics Agent**는 AI 법제 문서(EU AI Act, ALTAI 등)와 서비스 기술 문서를 **결합 분석**하여,
- 핵심 **윤리/규제 리스크 식별**
- 조항/근거 **출처가 명시된 개선 권고안 자동 생성**
- **우선순위/난이도/영향도** 기반의 구현 로드맵 제안

을 목표로 합니다.

> EU는 **2024년 8월 AI Act를 발효**, **2025년 2월부터 단계적 규제를 시행**하고 있습니다. 이에 따라 기업의 **신뢰성·투명성·책임성** 입증 요구가 급증하고 있으나, 많은 조직이 **평가 기준과 필수 증적(문서) 체계**를 명확히 파악하지 못하고 있습니다. 본 프로젝트는 이 **정보 비대칭**을 해소하는 도구입니다.

---

## 🧩 Key Features

- **Grounded Risk Assessment**  
  입력(서비스 설명/모델 카드/데이터 시트)을 바탕으로 **EU AI Act / ALTAI 매핑** 및 리스크 레벨 산정.

- **Evidence-Linked Recommendations**  
  각 리스크에 대해 **관련 조항(근거)**, 요구 증적(문서/로그/프로세스), **개선 가이드** 자동 제시.

- **Hybrid Retrieval (RAG)**  
  법령/가이드/사례 문헌을 **BM25 + Dense** 혼합 검색으로 정밀 인용.

- **Actionable Output**  
  JSON(구조화 산출), Markdown/PDF(리포트) 동시 생성. 대시보드 연동 용이.

---
