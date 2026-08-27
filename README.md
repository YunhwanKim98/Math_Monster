# Math Monster Hunter

## 구성
- `index.html`: 브라우저에서 실행하는 게임 프로토타입
- `elementary.json`: 초등 훈련장 DB
- `middle1_1.json` ~ `middle3_2.json`: 중학교 DB
- `high1_1.json` ~ `high3_2.json`: 고등학교 DB
- `all_13_databases.json`: 13개 DB 통합본

각 DB는 단원별 100개 문제 유형을 갖습니다. 숫자를 랜덤 생성하여 문제를 만드는 구조입니다.

## 실행
브라우저 보안 정책 때문에 `file://`로 직접 열면 JSON fetch가 차단될 수 있습니다.
폴더에서 간단한 로컬 서버를 실행하세요.

Python이 설치되어 있다면:
`python -m http.server 8000`

그 다음 브라우저에서 `http://localhost:8000` 접속.

## 주의
현재 프로토타입의 문제 생성기는 대표적인 산술/대수형을 우선 구현했습니다.
교과서·교육과정에 맞춘 100개 유형 각각의 정교한 생성기와 고등학교 과목별 실제 단원 체계는 다음 개발 단계에서 확장하는 것이 적합합니다.
