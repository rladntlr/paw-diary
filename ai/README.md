# AI

Python 실험과 FastAPI 추론 서비스 자리입니다. 모델, 의존성, 실행 코드는 아직 없습니다.

```text
app/
  api/        내부 API
  schemas/    요청·응답 형식
  services/   사진 분석·일기 생성 흐름
  inference/  모델 로딩·추론
  core/       환경 설정
experiments/  사진 한 장부터 시작하는 실험
tests/        필요 시 API 계약·실패 처리 검증
```

가상환경은 이 디렉터리의 `.venv/`로 만드는 방향을 제안합니다. Python 버전과 모델을 선택한 뒤 의존성을 고정하고 실행 명령을 추가하세요.

처음에는 `experiments/`에서 모델 출력부터 확인합니다. FastAPI 생성 전에 관찰 사실과 글 생성의 입력·출력 형식을 정하세요. GPU 사양은 확인되지 않았습니다. 가중치와 실제 사진을 저장소에 올리지 마세요.
