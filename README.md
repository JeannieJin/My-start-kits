# Classroom Hub Starter Kit

초등학교 담임교사를 위한 학급 허브 웹앱 스타터 키트입니다.
학생/교사 로그인 분기, 학급 공용 정보, 개인 일정, 과제 제출 체크를
빠르게 구현할 수 있도록 설계되었습니다.

## 🔧 기술 스택
- Next.js (App Router) + TypeScript
- Tailwind CSS + shadcn/ui
- Supabase (Auth, Database, RLS, Edge Functions)
- react-responsive
- use-local-storage-state
- usehooks-ts

## ⭐ 주요 기능
- 교사 / 학생 역할 기반 로그인 및 화면 분기
- 학생 화면
  - 오늘의 시간표
  - 선생님 전달사항
  - 주요 참고 링크
  - 개인 일정(2026 달력 TODO)
  - 과목별 과제 카드 + 제출 여부 체크
- 교사 화면
  - 학생 명단 관리 (전학생 추가, 전출생 아카이브 처리)
  - 시간표 / 전달사항 / 링크 / 과제 편집
  - 과제 제출 현황 확인

## 🎯 설계 특징
- 학생 삭제 대신 **전출 처리(비활성/아카이브)** 방식 사용
- Supabase RLS를 활용한 학급 단위 데이터 보호
- MVP 1 범위에 맞춘 최소 기능 중심 설계

## 🧭 용도
- 학교 수업용 웹앱 프로토타입
- 교사 주도 학급 관리 도구
- Supabase + Next.js 실습용 스타터 키트
