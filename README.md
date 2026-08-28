# ListeningMind Skills · 배포

[ListeningMind](https://www.listeningmind.com) 검색 데이터로 마케팅 분석 리포트를 만드는
Claude / ChatGPT / Gemini 용 스킬 배포 저장소입니다.

## 다운로드

| 스킬 | 설명 |
|---|---|
| [pathfinder-report.zip](./pathfinder-report.zip) | 검색 여정(CDJ) 분석 리포트 |
| [queryfinder-report.zip](./queryfinder-report.zip) | 연관 쿼리 기회 분석 리포트 |
| [clusterfinder-report.zip](./clusterfinder-report.zip) | 검색 클러스터 지형 분석 리포트 |

공개 중인 버전은 [`PUBLISHED.json`](./PUBLISHED.json) 을 참고하세요.

## 설치

1. 위에서 zip 을 내려받습니다.
2. Claude Desktop · claude.ai · ChatGPT · Gemini 중 사용하는 환경의 스킬 업로드 화면에서
   zip 을 그대로 올립니다.
3. 분석을 요청하면 스킬이 필요한 입력(API 키·시드 키워드·국가)을 채팅으로 물어봅니다.

## 사전 조건

- **ListeningMind `LM-API-KEY`** — 없으면 [DaaS 안내](https://www.listeningmind.com/ko/daas)
  에서 '전문가와 상담하기' 를 진행해 주세요.
- python3 (표준 라이브러리만 사용 · pip 불필요)
- 네트워크 송신 허용 · `listeningmind-data-api.ascentlab.io`

## 안내

- 이 저장소는 **배포 산출물만** 담습니다. 개발 소스는 별도 저장소에서 관리합니다.
- 스킬 실행 중 대화 기록이 사내 로깅 서버로 전송됩니다. 자세한 내용은 각 zip 안
  `SKILL.md` 의 로깅 규약 절을 참고하세요.

---
© AscentKorea
