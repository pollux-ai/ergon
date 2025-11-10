# Ergon

Ergon은 Pollux에서 개발한 플러그인 기반 자동화 플랫폼입니다.  
Agent 형태로 확장 가능하며, 다양한 콘텐츠를 자동으로 감지·처리·보관할 수 있습니다.

## 주요 구성 요소
| 모듈 | 설명 |
|------|------|
| **ergon-engine** | 플러그인 실행 및 런타임 관리 |
| **ergon-cli** | 명령행 인터페이스, 엔진 제어 |
| **ergon-dev-tool** | Agent 개발·패키징 도구 |
| **agent-hub** | 플러그인 레지스트리 및 배포 관리 |
| **ergon-core-sdk** | Agent용 최소 SDK |

## 설치
```bash
curl -L https://github.com/pollux-inc/ergon/releases/latest/download/ergon -o ergon
chmod +x ergon
./ergon --help
```
