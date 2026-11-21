# Nerdinary-Hackathon

- 일정: 2026-11-21 ~ 2026-11-22 / 무박 2일 해커톤
- Medical: 제외
- 템플릿: 1.0.0 / 준비일: 2026-10-27
- 현재 범위: 공통 지침·행사 자료와 집중 세션 MVP v0.12와 기능명세·정책서 v0.11 초안
- 저장소: [Nerdinary-Hackerton20261121-5Team/Nerdinary-Hackathon](https://github.com/Nerdinary-Hackerton20261121-5Team/Nerdinary-Hackathon) · 조직 소유 · 비공개 · 기본 브랜치 main
- Git 초기화·첫 커밋·업로드 완료. [.local 개인 설정](.gitignore)은 공유 대상에서 제외한다.
- 생성·검증 근거: [저장소 초기 설정 기록](docs/start/REPOSITORY_SETUP.md)
- 작업 위치·이관 범위: [2026-11-21 조직 저장소 이관 기록](docs/start/REPOSITORY_MIGRATION_2026-11-21.md)

## 처음 시작하기

1. [공통 AI 지침](AGENTS.md)을 읽는다.
2. [참여 안내](docs/start/README.md)와 [최초 질문](docs/start/ONBOARDING.md)을 확인한다.
3. 식별명·역할·세부 담당·이번 작업을 답한 뒤 개인 역할 파일을 설정한다.
4. [Plan 안내](docs/Plan/README.md)에서 필요한 원본·백업을 찾아 읽는다.

AI 도구가 AGENTS.md를 자동으로 읽는지는 도구별로 확인해야 한다.
자동으로 읽지 않는 도구에는 루트 AGENTS.md를 먼저 읽도록 명시한다.
문서상의 범위 제한은 도구의 파일 접근 권한을 기술적으로 강제하지 않는다.

## 문서 입구

- [집중 세션 MVP — v0.12](docs/Plan/PROJECT.md)
- [집중 세션 기능명세 — v0.11](docs/Plan/FEATURES.md)
- [집중 세션 정책서 — v0.11](docs/Plan/POLICIES.md)

- [공식 행사 안내 수집 결과 — 2026-11-19](docs/event/2026-11-19/README.md)
- [해커톤 주제와 팀 선택 — 권태 + 공부 × 덜어내기](docs/event/2026-11-21/THEME.md)
- [PM 역할 지침](docs/PM/README.md)
- [Design 역할 지침](docs/Design/README.md)
- [Coding 역할 지침](docs/Coding/README.md)
- [빈 양식](docs/templates/README.md)
- [설정과 검증 기록](docs/start/VERIFICATION.md)

## 원본과 보관

기획·정책·배정·검토 기록은 Notion, 디자인은 Figma의 현재 적용본을 우선한다.
[Notion 프로젝트 페이지](https://app.notion.com/p/Nerdinary-Hackathon-5Team-41fc0efa070a80aeb91fe456673f9d3b?source=copy_link)와
[Figma 디자인 파일](https://www.figma.com/design/4VjwoVdisHzCDZABuDMMc4/NerdinaryHackathon5team?node-id=0-1)을 시작 링크로 등록했다.
자료별 연결과 접근 확인 범위는 [원본 목록](docs/start/SOURCES.yaml)에서 관리한다.
GitHub는 공통 지침·코드·기술 연결 계약의 원본이며 Plan 사본의 보관소가 된다.
온라인 원본에 접근하지 못하면 최신 원격 main의 docs와 백업 기록을 확인한다.
Notion 공통 시작 문서의 [조회 사본](docs/Plan/WORKSPACE.md)과 집중 세션 문서 3종을 로컬에 보관했다. 원격 main 반영 여부와 조회 범위는 별도로 확인한다.
원격에 저장되어 있다는 이유만으로 빈 양식을 온라인 원본의 백업이라고 부르지 않는다.

개발 코드와 실행 설정은 기술 스택을 정한 뒤 docs 밖에 둔다.
실제로 확인하지 않은 설치·실행 명령은 이 README에 만들어 넣지 않는다.

## 현재 준비 상태

[팀 인원 구성](docs/PM/TEAM_COMPOSITION.md)은 PM 1명·Design 1명·Web 3명·Server 2명, 총 7명으로 확인했다.
팀의 주제 조합은 **권태 + 공부 × 덜어내기**로 사용자 확인을 받았다. 사용자 안내에 따라 2026-11-21 16:20 이후 주제 변경이 불가능하다.
앱 중심이며 웹에서도 세션을 실행한다. 공부 중 내 원조각은 내 복원도대로, 다른 사람의 원조각은 그 사람의 진행도와 관계없이 최대 블러로 보인다. 데모 카메라는 본인 전용 미리보기와 모의 감지에 쓴다.
개설자가 세션 생성 시 조립용 분할 비율을 정한다. 1/4이면 원조각 하나당 4개다. 공동 조립 시작 시 타인용 최대 블러를 풀고, 각 소유자가 집중 시간에 복원한 만큼만 팀 전체에 보여준다. 공동판에서는 각자 자기 조각만 옮길 수 있고, 모든 조각이 제자리에 놓이면 팀이 통과한다. 잘못 놓으면 해당 조각만 드래그 직전 위치로 돌아가고 소유자는 바로 다시 놓을 수 있다. 방 종료 시 사진·결과를 폐기한다. 이미지 필터는 검토 중이다.
비회원 코드 입장과 랜덤 매칭을 먼저 진행한다. 랜덤 매칭 대상은 개설자가 랜덤 참가를 허용한 대기방의 빈자리다. 로그인과 마지막 세션으로의 계정 자동 복귀는 후순위다. 집중 종료 시 부재한 참가자 몫의 조각은 마지막 복원 모습으로 정답 칸에 자동 배치한다.
Notion 공통 시작 문서에 인원·주제·협업 상태를 반영했다. Design은 GitHub를 사용할 수 있어야 한다는 전제 없이 Notion·Figma에서 협업한다.
Design 외 다른 팀원은 Discord·GitHub 초대 완료로 사용자 확인을 받았다. 초대 수락·접속 여부는 미확인이다.
Notion의 MVP·기능명세·정책서와 공통 시작 문서의 조회 사본을 로컬에 보관했다. 기능별 발췌는 [기능 사본 목록](docs/Plan/features/README.md)에 있다.
세부 규칙은 사용자 확인·현재 안·작성자 제안·미정으로 구분한다. 문서는 작업 중이며 개발 전달·기능 테스트 완료를 뜻하지 않는다.
개인 역할 파일은 최초 참가자의 답변 후 각자 만든다.
