# Next.js Todo List Project

## 프로젝트 개요

Next.js와 Supabase를 활용한 Todo List 애플리케이션입니다.

## 기술 스택

### 주요 기술:

- Next.js 15.1.3
- React 19
- TypeScript
- Material Tailwind
- Emotion
- Tailwind CSS
- Supabase

## 주요 기능

- 할 일 목록 조회/추가/수정/삭제 (CRUD)
- Supabase를 활용한 데이터 저장
- 반응형 디자인
- 다크모드 지원

## 설치 및 실행

```bash
# 프로젝트 클론
git clone https://github.com/your-username/inflearrn-supabase-todo-list.git

# 디렉토리 이동
cd inflearrn-supabase-todo-list

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

## 환경 설정

1. `.env.local` 파일을 생성하고 다음 환경변수를 설정합니다:

```env
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```
