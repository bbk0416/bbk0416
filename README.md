# 배병권 — Vulnerability Management / Security Engineer

육군 정보통신·사이버보안 실무 경험을 바탕으로 **취약점 식별 → 조치 추적 → 재검증 → 증빙**까지 이어지는 보안 운영과, 이를 코드·연구로 재현하는 작업을 해왔습니다.

## Core evidence

- 취약점 **1,138건 식별**
- **1,054건 조치 완료 확인**, 조치율 **92.6%**
- KVE 식별번호 **3건**
- Computers & Security 171 (2026), Article 105085 **단독저자**
- CCE 2023 공공부문 준우승
- CyberNet 2023 한국 우승팀 참가
- Locked Shields 2023 참가

## Selected projects

### [VulnFlow](https://github.com/bbk0416/vulnflow)
Local-first vulnerability-remediation closeout workspace. Nessus·OpenVAS·CSV·XLSX 결과를 가져와 finding/asset 정규화, KEV·EPSS·자산 맥락 기반 우선순위, 담당자·기한·조치·재검증·승인·증빙 흐름을 다룹니다. 현재 **Free Public Beta**입니다.

### KillWeb
Computers & Security에 게재된 단독저자 연구와 재현 아티팩트입니다. 보안 텔레메트리를 MITRE ATT&CK 기반 조사 그래프로 구성하고 재현 가능한 평가 절차를 다룹니다. 제품 상용화가 아니라 **출판 연구와 재현성 자료**가 핵심입니다.

- [논문 DOI](https://doi.org/10.1016/j.cose.2026.105085)
- [재현성 자료(OSF)](https://osf.io/gzs7k/)

### [BreachScope](https://github.com/bbk0416/BreachScope)
Windows Event Log 중심의 DFIR/triage 도구입니다. 정규화 → 규칙 탐지 → 상관분석 → 시나리오 → 케이스 → 리포트 흐름을 구현합니다. 현재 평가는 합성·통제 데이터 기반이며 실제 기업 환경의 탐지 정확도를 주장하지 않습니다.

### VulnSignal
CISA KEV·EPSS·CPE를 활용한 vulnerability-intelligence 포트폴리오 MVP입니다. 조직별 자산·watchlist·alert, API key scope/rotation, audit event, PostgreSQL/Alembic, Docker staging을 구현했습니다. **Production SaaS 또는 고객 검증 완료 상태는 아닙니다.**

## Role-specific supporting work

- **MCP-Guard** — MCP 기반 AI Agent 실행경계·정책 Blind Spot 검증 PoC, 2026 공모전 제출본 동결
- **AuditSeal-CT** — ESP32-S3 기반 USB 감사 동글 프로토타입. 펌웨어·USB 네트워크·증적 봉인 구조 구현. 실기기 E2E 검증은 별도 완료 전까지 주장하지 않습니다.
- **ORACLE-ZERO** — 합성 환경에서 방어조치 전후 공격경로를 비교하는 결정론적 counterfactual cyber-world MVP. 실제 침해확률 예측 모델이 아닙니다.

## Public portfolio

[BBK Security Portfolio](https://bbk0416.github.io/bbk-security-portfolio/)

> 공개 자료에는 검증 가능한 범위만 표시합니다. 합성 테스트·로컬 검증과 실제 사용자·실환경 검증을 구분하며, 비공개 군 내부자료·개인정보·취약점 원문은 공개하지 않습니다.
