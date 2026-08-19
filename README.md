# Maeul-PostMan

Postman으로 한국관광공사 **국문 관광정보 서비스_GW**를 관리하는 저장소입니다.

## 구성

- `postman/collections/한국관광공사/국문 관광정보 서비스_GW/`
  - 관광정보 관련 요청 컬렉션
- `postman/environments/allen.environment.yaml`
  - Postman 환경 변수
- `postman/globals/workspace.globals.yaml`
  - 워크스페이스 전역 변수
- `.postman/resources.yaml`
  - Local View 등록 설정

## 환경 변수

`allen` 환경에는 아래 변수가 정의되어 있습니다.

- `server-url`
- `open-api-url`
- `open-api-korService2-path`
- `open-api-service-key`

실행 전에 실제 값으로 채워야 합니다.

## 포함된 요청

- 공통정보조회
- 소개정보조회
- 이미지정보조회
- 반복정보조회
- 분류체계 코드조회
- 지역기반 관광정보조회
- 위치기반 관광정보조회
- 키워드 검색 조회
- 숙박정보조회
- 행사정보조회
- 관광정보 동기화 목록 조회

## 사용 방법

1. Postman에서 이 저장소를 워크스페이스로 연결합니다.
2. `postman/environments/allen.environment.yaml`의 값을 환경에 맞게 설정합니다.
3. 필요한 요청을 선택해 실행합니다.

## 참고

- 요청 URL은 `{{open-api-url}}`, `{{open-api-korService2-path}}`, `{{open-api-service-key}}` 변수를 사용합니다.
- `New Request.request.yaml`은 새 요청 예시로 보입니다.
