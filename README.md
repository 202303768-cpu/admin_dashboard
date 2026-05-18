# 📊 업무 종합 대시보드

> 사내 업무를 한 화면에서 관리하는 올인원 관리자 대시보드

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 📋 할 일 관리 | 우선순위·마감일 기반 할 일 추가/완료/삭제 |
| 📅 캘린더 | 월간 일정 표시 및 일정 추가 |
| ⏳ D-Day | 주요 일정 카운트다운 |
| 📄 문서 생성기 | 기안서·결재문서·출장보고서 등 자동 생성 |
| 📜 사내 규정 | 연차·출장·복무 등 규정 검색 |
| 📈 KPI 차트 | 업무 현황 및 성과 지표 시각화 |
| 🌗 다크/라이트 모드 | 테마 전환 지원 |
| 💬 빠른 메모 FAB | 실시간 메모 저장 |

## 🚀 실행 방법

별도 설치 없이 브라우저에서 바로 실행됩니다.

```bash
open admin_dashboard.html
```

## 🌐 GitHub Pages 배포

1. GitHub 저장소 → **Settings** → **Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `(root)` 선택 후 **Save**
4. 접근 URL:
   ```
   https://<username>.github.io/<repo-name>/
   ```

## 🛠️ 기술 스택

- **HTML5 / CSS3 / Vanilla JS** — 단일 파일
- **Chart.js 4.4.1** — KPI 차트
- **Noto Sans KR** — 한국어 최적화 폰트
- **LocalStorage** — 데이터 로컬 저장

## 📁 파일 구조

```
📦 admin-dashboard
 ┣ 📄 admin_dashboard.html
 ┣ 📄 README.md
 ┣ 📄 .gitignore
 ┗ 📄 LICENSE
```

## 📝 라이선스

MIT License
