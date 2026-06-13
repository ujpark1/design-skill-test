# Skill Test

에이전트 디자인 스킬을 실제 UI에 적용해본 인터랙티브 데모 모음.

## 라우트

| 경로 | 내용 |
| --- | --- |
| `/` | 데모 목록 랜딩 |
| `/emil` | **Emil Design Engineering** — 모션/마이크로 인터랙션 craft. 같은 화면을 ① 애니메이션 없음 → ② 잘못된 애니메이션 → ③ 제대로 다듬은 버전으로 3-way 비교 (라이트/다크 토글 지원) |

## /emil 데모 구성

- `emil/index.html` — 3-way 비교 (iframe 3개 + 차이 설명 표)
- `emil/without-none.html` — 애니메이션 없음
- `emil/without.html` — 잘못된 애니메이션 (안티패턴)
- `emil/with.html` — Emil 원칙 적용

총 17개 컴포넌트(버튼·모달·드롭다운·토스트·툴팁·카드 + 토글·탭·아코디언·세그먼트·홀드삭제·스피너·드로어·복사·좋아요·이미지리빌)를 다룹니다.

## 출처

- [emilkowalski/skill](https://github.com/emilkowalski/skill)
- [animations.dev](https://animations.dev)

순수 정적 사이트 — 빌드 스텝 없음. Vercel 정적 배포.
