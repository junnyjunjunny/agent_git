# Commit Convention

## 형식

```
<type> <subject>

<body>
```

## Type 종류

- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `docs`: 문서 수정
- `style`: 코드 포맷팅, 세미콜론 누락 등 (기능 변경 없음)
- `refactor`: 코드 리팩토링
- `test`: 테스트 코드 추가/수정
- `chore`: 빌드 업무, 패키지 매니저 설정 등

## 예시

```
<feat> 로그인 기능 추가
<fix> 긴급 Fix
<docs> README에 설치 방법 추가
```

## 규칙

- Commit Message는 한글을 사용한다
- 헤더(type)는 `<`와 `>` 문자로 감싸서 작성한다 (예: `<fix> 긴급 Fix`)
- 제목은 50자 이내로 작성
- 제목 끝에 마침표를 붙이지 않음
- 본문은 어떻게보다 무엇을, 왜 변경했는지 설명
