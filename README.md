# 간단 계산기

스마트폰과 컴퓨터에서 사용하는 한국어 사칙연산 계산기입니다.

- 앱 파일: `calc/index.html`
- 접속 주소: https://informin.github.io/calc/ (계산기 폴더로 자동 이동)
- 계산기 직접 주소: https://informin.github.io/calc/calc/
- 덧셈, 뺄셈, 곱셈, 나눗셈, 소수와 음수 입력
- 곱셈·나눗셈 우선 계산, 0 나누기 오류 안내
- 키보드: 숫자 및 `+ - * / .`, Enter 계산, Esc 초기화, Backspace 삭제
- 외부 라이브러리, API 키, 서버 없이 브라우저 안에서 계산

일반적인 JavaScript 숫자를 사용하며 결과는 유효숫자 12자리로 반올림합니다. 큰 정수나 정밀 회계 계산 용도로 설계되지 않았습니다.

## GitHub Pages 설정

저장소 Settings → Pages → Source: Deploy from a branch → Branch: main, /(root) → Save.

이후 main 브랜치의 `calc/index.html`을 수정하면 자동 배포됩니다. 루트의 `index.html`은 `calc/`로 이동하는 안내 파일입니다.