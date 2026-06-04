# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 저장소 성격

이 디렉토리는 Obsidian 기반 개인 지식 관리(PKM) 워크스페이스다. 소프트웨어 프로젝트가 아니므로 빌드·테스트·린트 명령은 없다.

## 디렉토리 구조

```
newthing/
├── 📕CODING/
│   ├── STUDY/          # 진행 중인 프로젝트 기획 (미국 간호사 이민 커뮤니티)
│   ├── 개념정리/        # Claude Code, MCP, Skills 등 개발 도구 학습 노트
│   └── 개인공부/        # 세팅 및 프로젝트 실습 메모
├── 공고/               # 채용 공고 스크랩
└── 체크리스트.md       # 개인 할일 목록
```

## 핵심 프로젝트: 미국 간호사 이민 커뮤니티

`📕CODING/STUDY/` 아래에 기획 중인 서비스의 도메인 지식이 있다.

**서비스 개요**
- 미국 간호사 취업 이민 5단계(I-140 → 비자 불레틴 대기 → DS-260 → DQ → 대사관 인터뷰)를 추적하는 개인 타임라인 + 커뮤니티
- 닉네임 기반 가입, 단계별 날짜 입력, 타임라인 공유

**계획된 기술 스택** (`📕CODING/STUDY/설계.md` 참고)
- Supabase(Postgres) + FastAPI + LangGraph
- MCP: Supabase / Gmail / OneSignal / Context7

**핵심 도메인 용어**
- PD(Priority Date): 우선순위 날짜, I-140 승인 시 발급
- 비자 불레틴: 매월 10~15일 발표, FINAL ACTION DATES / DATES FOR FILING 두 종류
- CGFNS: 이민 서류 담당 기관 (VisaScreen 처리)
- Agency: 병원-간호사 연결 중개인

## 노트 작성 규칙

- 모든 노트는 한국어로 작성
- 기획 노트를 수정할 때는 기존 내용을 지우지 말고 보완·추가만 한다
- `체크리스트.md`는 개인 할일이므로 Claude가 임의로 수정하지 않는다
