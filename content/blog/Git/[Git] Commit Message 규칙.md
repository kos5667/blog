# [GIT] commit message 규칙

생성 일시: 2023년 6월 2일 오후 2:51
최종 편집 일시: 2023년 6월 2일 오후 2:52
태그: 기타

오늘은 nextstep에서 다른 개발자들이 commit한 메세지를 보다가, 규칙이 있는 것을 보고 정리하게되었다.

나도 해당하는 규칙을 지키고 싶고, 적용하는 습관을 갖으려고 보기 쉬운곳에 작성하게 되었다.

### Commit Message 규칙  7가지

1. 제목과 본문을 빈 행으로 구분한다
2. 제목을 50글자 내로 제한
3. 제목 첫 글자는 대문자로 작성
4. 제목 끝에 마침표 넣지 않기
5. 제목은 명령문으로 사용하며 과거형을 사용하지 않는다
6. 본문의 각 행은 72글자 내로 제한
7. 어떻게 보다는 무엇과 왜를 설명한다

Commit Message 구조

```markdown
type(타입) : title(제목)

body(본문, 생략 가능)

Resolves : #issue, ...(해결한 이슈 , 생략 가능)

See also : #issue, ...(참고 이슈, 생략 가능)
```

Commit Message 타입(type)

1. feat : 새로운 기능 추가
2. fix : 버그 수정
3. Docs : 문서 수정
4. Style : 스타일 관려 코드
5. refactor: 코드 리팩토링
6. test : 테스트코드, 리팩토링 테스트 코드 추가
7. CHORE: 빌드, 패키지 매니저 수정

해당하는 링크를 참조하여 작성하였습니다.



> 출처
>
> [Git Commit Message 규칙](https://jason-api.tistory.com/89)
>
> https://www.coby-blog.co.kr/69e5333c-2398-4321-aba1-719681c95555
