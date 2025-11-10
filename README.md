# Ergo-n-Sphere

**Ergo-n-Sphere**는 Pollux가 개발한 **Ergon Platform**의 공개 진입점입니다.  
플러그인 기반 자동화 환경을 중심으로, 다양한 엔진·도구·SDK·Agent 생태계를 하나의 Sphere로 연결합니다.

---

## 🧭 개요

Ergo-n-Sphere는 **Ergon Platform의 오픈 허브(Entry Portal)** 역할을 수행합니다.  
이곳에서는 Ergon의 구조, 주요 컴포넌트, Agent 개발 가이드, 다운로드 경로를 확인할 수 있습니다.

Ergon은 **Physical AI 기반의 자동화 시스템**으로,  
데이터·시뮬레이션·운영의 전 주기를 통합 관리하는 플랫폼입니다.

---

## 🧩 구성 요소

| 구성 | 설명 | 리포지토리 |
|------|------|-------------|
| **Ergon Engine** | Agent 실행·제어 런타임 | [pollux-ai/ergon-engine](https://github.com/pollux-ai/ergon-engine) |
| **Ergon CLI** | 명령행 인터페이스, 엔진 제어 | [pollux-ai/ergon-cli](https://github.com/pollux-ai/ergon-cli) |
| **Ergon Dev Tool (EDT)** | Agent 빌드·패키징 도구 | [pollux-ai/ergon-dev-tool](https://github.com/pollux-ai/ergon-dev-tool) |
| **Ergon Core SDK** | Agent 개발용 최소 SDK | [pollux-ai/ergon-core-sdk](https://github.com/pollux-ai/ergon-core-sdk) |
| **Agent Hub Backend / Frontend** | Agent 레지스트리 및 배포 관리 | [pollux-ai/agent-hub-backend](https://github.com/pollux-ai/agent-hub-backend) / [pollux-ai/agent-hub-frontend](https://github.com/pollux-ai/agent-hub-frontend) |
| **Ergon Common** | 엔진/CLI 공용 모듈 | [pollux-ai/ergon-common](https://github.com/pollux-ai/ergon-common) |
| **Agent Common** | Agent용 공용 모듈 | [pollux-ai/agent-common](https://github.com/pollux-ai/agent-common) |
| **Ergon Agent Templates** | Agent 템플릿 모음 | [pollux-ai/ergon-agent-templates](https://github.com/pollux-ai/ergon-agent-templates) |
| **Pollux E2E / Ergon-Pollux E2E** | 시나리오 기반 통합 테스트 | [pollux-ai/pollux-e2e](https://github.com/pollux-ai/pollux-e2e) / [pollux-ai/ergon-pollux-e2e](https://github.com/pollux-ai/ergon-pollux-e2e) |
| **Docs (Public/Internal)** | 문서/가이드 허브 | [pollux-ai/ergon-docs-public](https://github.com/pollux-ai/ergon-docs-public) / [pollux-ai/ergon-docs-internal](https://github.com/pollux-ai/ergon-docs-internal) |

---

## ⚙️ 설치 및 시작

Ergon 플랫폼의 모든 구성 요소는 **CLI**와 **Engine**을 통해 동작합니다.

```bash
# CLI 다운로드
curl -L https://github.com/pollux-ai/ergon-cli/releases/latest/download/ergon -o ergon
chmod +x ergon

# 버전 확인
./ergon --version
````

엔진 및 Agent를 연동하려면 다음 문서를 참고하세요:
👉 [Ergon Docs Public](https://github.com/pollux-ai/ergon-docs-public)

---

## 🧠 철학

> “Physical Intelligence in Motion.”

Pollux는 **Physical AI** 개념을 바탕으로,
현실(Physical Space)과 디지털 시뮬레이션(Digital Twin)을 통합한 설계 자동화를 구현합니다.
Ergon은 이러한 철학의 실행체계로,
Metaphysics(형이상학) → Nomos(제약 및 법칙) → Digital Twin(현실 시뮬레이터) → Omniverse(통합 공간)으로 이어지는 Pollux의 핵심 계층을 물리적으로 실현합니다.

---

## 🌐 문서 및 리소스

| 항목        | 링크                                                                                                                  |
| --------- | ------------------------------------------------------------------------------------------------------------------- |
| 개발자 가이드   | [ergon-docs-public/DEVELOPER_GUIDE.md](https://github.com/pollux-ai/ergon-docs-public/blob/main/DEVELOPER_GUIDE.md) |
| 아키텍처 개요   | [ergon-docs-public/ARCHITECTURE.md](https://github.com/pollux-ai/ergon-docs-public/blob/main/ARCHITECTURE.md)       |
| 설치 가이드    | [ergon-docs-public/QUICKSTART.md](https://github.com/pollux-ai/ergon-docs-public/blob/main/QUICKSTART.md)           |
| Agent 템플릿 | [ergon-agent-templates](https://github.com/pollux-ai/ergon-agent-templates)                                         |

---

## 🪐 Pollux Ecosystem

Ergo-n-Sphere는 Pollux의 전체 생태계 중 **Operation Layer**를 구성합니다.

| 계층                | 설명                        |
| ----------------- | ------------------------- |
| **Event Horizon** | 메타데이터 및 휴리스틱 서버           |
| **Nomos**         | 제약/규칙 기반 해석 및 AI 시뮬레이션 엔진 |
| **Metaphysics**   | 물리 모델링 및 시뮬레이션            |
| **Ergo-n-Sphere** | 운영/플러그인 실행 계층             |
| **Omniverse**     | 시각화 및 통합 공간               |

---

## 📄 License

© 2025 Pollux Inc. All rights reserved.
This repository is open for reference but subject to the Pollux proprietary license.

---

**마지막 업데이트:** 2025-11-11
**Author:** Pollux AI Research & Engineering
