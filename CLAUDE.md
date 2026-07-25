# research-dashboard — 연구 실적 대시보드

> **워크스페이스 공통 계약.** 전체 작업 지도와 공통 규칙은 `~/research-agent/WORKSPACE.md`.

## 이 저장소는

논문 실적을 시각화하는 대시보드(`index.html` + `papers.json`, CILT 과제용 `cilt.html` + `cilt_papers.json`).
**데이터 갱신은 research-agent의 `/실적` 스킬이 담당한다.** 여기서 JSON 스키마를 임의로 바꾸면 홈페이지 쪽 연동이 깨진다.

## 시작 절차

1. `git pull` 을 먼저 실행한다.

## 세션 시작 위치

프로젝트 에이전트·훅 없음. 어디서 열어도 무방하다. 실적 반영은 `lab`에서 `/실적`이 표준 경로.

## 커밋 규칙

- 작업 완료 시마다 커밋 + 푸시. 메시지는 한국어로 간결하게.
