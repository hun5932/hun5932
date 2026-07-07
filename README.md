# 유승훈 (Seunghun Yu)

금융 클라우드 인프라 운영 실무자 — 운영관리
실무로 검증된 것과 학습으로 채워가는 것을 구분해 기록합니다.

📍 Seoul · 📧 yshun1595@gmail.com

---

### Quick Links

| | |
|---|---|
| 📄 **Portfolio** | [hun5932.github.io/YuSeunghun_Portfolio](https://hun5932.github.io/YuSeunghun_Portfolio/) — 인프라 운영 × AI 서비스 기획 통합 포트폴리오 |
| 🔧 **Infra Lab** | [hun5932/infra-lab](https://github.com/hun5932/infra-lab) — 미들웨어 · Kubernetes · SLA 모니터링 핸즈온 랩 3종 |
| 📝 **Research** | [Zenodo DOI: 10.5281/zenodo.21006608](https://doi.org/10.5281/zenodo.21006608) — 개인 학술논문 (학제간 연구, 트랜스포머 어텐션 분석 포함) |

---

## Infra Lab 시리즈

금융권 클라우드 운영 도메인(SLA 관리 · ITSM · 미들웨어 · Kubernetes · 모니터링)을 로컬에서 직접 재현하며 정리하는 학습 랩입니다. 공개 표준과 합성 데이터만 사용합니다.

| 랩 | 주제 | 하이라이트 |
|---|---|---|
| [web-was](https://github.com/hun5932/infra-lab/tree/main/web-was) | NGINX · Tomcat · Apache 3계층 — 설치·구성·TLS·장애 5종·버전 패치 | 단일 인스턴스 패치 순단 1.2초 실측, 세션 깨짐 vs ip_hash 실증 |
| [k8s-oss](https://github.com/hun5932/infra-lab/tree/main/k8s-oss) | Kubernetes 위 오픈소스 스택 (Deployment·StatefulSet·probe) | rolling update **순단 0** — 위 랩과 실측 대비로 "무중단 = 아키텍처" 확인 |
| [observability](https://github.com/hun5932/infra-lab/tree/main/observability) | SLA 계산기(Python) + Prometheus · Grafana · 알람 | up==0 알람 pending→firing 라이프사이클 실증 |

> 심화 학습(Redis 세션 외부화, HPA 등)은 계속 진행 중입니다.

## 학습 주제

- SLA 가동률 · 허용 다운타임 · 이상치 탐지 로직의 코드화 (99.9% = 월 43.2분)
- web/WAS 미들웨어의 구성 · 장애 양상 · 패치, 그리고 무중단의 조건
- Kubernetes 오브젝트(Deployment vs StatefulSet · probe · PVC)와 선언형 운영
- Prometheus 기반 다운타임 감지와 알람 설계

## 연구 · 문서화

- 개인 학술논문 — 자기참조 구조에 관한 학제간 연구 (시각 · 청각 · 논리 · 계산 4영역, 트랜스포머 어텐션 분석 포함)
  → [Zenodo DOI: 10.5281/zenodo.21006608](https://doi.org/10.5281/zenodo.21006608) · [분석 코드](https://github.com/hun5932/self-reference-possibility-of-mind)
- 개인 지식관리 시스템(Obsidian 기반 1,200+ 문서) — 업무 지식 체계화·버전 관리 방법론

## Other

- 📷 [500px.com/seunghunyu](https://500px.com/seunghunyu) — Photography
- 🎬 [템플스테이 프로그램 소개 영상](https://youtu.be/Sv5RCnyo37E) — 직지사 템플스테이 팀장(외국인 실무자) 시절 기획·운영
