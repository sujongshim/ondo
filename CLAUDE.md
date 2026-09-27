# ondo(온도) 프로젝트 지침

- 저장소: https://github.com/sujongshim/ondo (private)
- 배포 주소: https://ondo-omega.vercel.app
- Vercel projectId: prj_GXS8yVcqV5daq7Nq8Cfl1hfRCaSS
- Vercel orgId(팀): team_PqGD0pAGTdqT5sIEWH00Yg6w (sj-6217 — testbase와 같은 팀/작업공간)
- 구성: 로그인 없이 브라우저 localStorage만 쓰는 정적 HTML 단일 페이지 앱(index.html 하나). Supabase DB는 사용하지 않음(로그인 없음, 기록은 학생 브라우저에만 저장하는 원칙).
- 내용: "온도(ON:DO)" — 고3 수험생 자기주도 웹앱. 타이머, D-Day, 수면 기록, 오늘 플래너+실천 달력, 갓생 루틴+습관 달력, 2027 수능완성 단어 복습(EBS 교재에서 추출한 966개 단어·뜻·예문·페이지 내장)을 한 페이지에 담음.
- GitHub 저장소와 Vercel 프로젝트 간 자동 배포 연동은 안 되어 있음(private repo라 Vercel GitHub 연결이 실패함) — `vercel --prod` 수동 배포로 반영. testbase와 동일한 패턴.
- 팔레트/폰트: 소확앱(testbase) 스타일 참고 — 그린(#2E6B5B)·오렌지(#D9782E)·바이올렛(#6B3FA0, 단어장 전용)·스탬프레드(#D93A2B), Noto Sans KR 단일 폰트, 아이콘은 전부 이모지(FontAwesome 등 외부 CDN 아이콘 미사용).
