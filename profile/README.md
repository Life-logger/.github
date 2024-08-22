# Life Logger

## Project Stack

### Front-end

- Vue

### Back-end

- Go

### Tool

- Github
- Figma

## Branch Strategy

브랜치 이름: `feature/#<이슈번호>-<기능명>`
              / ex. feature/#1-kakao-login
- `master`: 완성된 제품 브랜치
- `feature/yymmdd-branch-name` : 각 기능별 브랜치
- `hotfix`: 출시 버전에서 발생한 버그수정 브랜치


## Commit Message Convention

```
type: commit message
```

모든 커밋 메세지는 명령문 (현재시제) 를 사용하여 작성합니다. 모든 커밋 메세지 앞에는 다음의 `type` 을 작성합니다.

- `feat`: 새로운 기능 추가
- `fix`: 버그수정
- `docs`: 문서수정
- `style`: 코드 포매팅 등
- `refactor`: 코드 리팩토링
- `chore`: 기타 작업

feat: 구현/수정한 기능(#이슈번호)
 ex. feat: 카카오 로그인 기능 구현(#1)

이슈 : [feat] 구현/수정할 기능
 ex. [feat] 카카오 로그인 기능 구현
 
풀리퀘: [feat] 구현/수정한 기능
 ex. [feat] 카카오 계정으로  로그인 API 연동
 - 코드 리뷰
 - 커밋 번호





