# Paw Diary

사진과 심박 기록을 바탕으로 반려견의 하루를 강아지 말투의 사진일기 한 편으로 만드는 서비스.

## 현재 상태

초기 폴더·패키지 구조와 인수인계 문서만 준비되어 있습니다. 실행 가능한 서버, 모델, 웹 화면, 빌드 설정은 아직 없습니다.

## 다른 노트북에서 시작하기

```sh
git clone https://github.com/rladntlr/paw-diary.git
cd paw-diary
```

Codex에서 이 폴더를 열고 다음 순서로 읽어주세요.

1. [AGENTS.md](AGENTS.md): 작업 가이드
2. [프로젝트 맥락](docs/PROJECT_CONTEXT.md): 목표, 결정 사항, 제약
3. [구조](docs/ARCHITECTURE.md): 서비스 책임과 데이터 흐름
4. [다음 작업](docs/NEXT_STEPS.md): 구현 순서와 완료 기준

다음 노트북의 Codex에 전달할 시작 메시지:

> AGENTS.md와 docs/의 문서를 먼저 읽어줘. 현재는 구조만 준비된 단계야. 내 환경의 Python과 GPU를 확인하고, 사진 한 장을 해석하는 AI 실험부터 같이 진행하자. 기존 코드가 있는지 먼저 확인하고, 필요한 모델과 의존성을 정하기 전에 실험 방법을 설명해줘.

## 디렉터리

```text
backend/   Java / Spring Boot 서비스 백엔드
ai/        Python AI 실험 및 FastAPI 추론 서비스
frontend/  웹 클라이언트 (프레임워크 미정)
docs/      기획·구조·인수인계 문서
data/      데이터 안내와 작은 가상 예제
```

첫 목표: 사진 3~5장과 촬영 시각으로 하루 일기 한 편을 만들고 웹에서 확인합니다. 이후 심박 기반 장면 선택, 실제 기기 연결, 앱으로 확장합니다.
