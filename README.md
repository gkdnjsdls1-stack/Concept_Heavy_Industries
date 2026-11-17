# 개념중공업 작업지시서

초·중·고 수학·국어·과학을 사무실 시뮬레이션으로 다시 공부하는 단일 파일 웹앱입니다.
빌드 과정 없이 `index.html` 하나로 동작합니다.

## 파일
- `index.html` — 앱 전체 (HTML + CSS + JS)
- `vercel.json` — Vercel 정적 배포 설정
- `README.md` — 이 문서

## 배포 (GitHub → Vercel)
1. GitHub에서 새 저장소를 만들고 위 파일 3개를 올립니다.
2. Vercel 대시보드 → **Add New → Project** → 그 저장소를 선택합니다.
3. Framework Preset은 **Other**, Build Command와 Output Directory는 비워 두고 **Deploy**를 누릅니다.
4. 이후 `index.html`을 수정해 커밋하면 자동으로 다시 배포됩니다.

## 주의
- 학습 기록은 브라우저 `localStorage`에 저장됩니다. 주소(도메인)가 바뀌면 기록이 따로 시작되므로,
  이전 주소에서 **마이페이지 → 사원증·백업 → 내보내기**로 복사해 새 주소에서 **가져오기** 하세요.
- 글꼴(Noto Sans KR / Noto Serif KR)은 Google Fonts에서 불러옵니다.
