# 인텔리제이에서 git commit template 만들어서 사용하기

- [Plug in Download 와 사용 방법](https://plugins.jetbrains.com/plugin/9364-commit-message-template)

## 템플릿 적용하기

- 플러그인 설치
- 템플릿 파일 적용
  - ![commit](images/commit.PNG)
- 커밋 창에서 Commit Message Template 버튼 클릭
  - ![commit1](images/commit1.PNG)

## git commit template sample

> `#` 은 커밋 메시지에서 주석 역할이라 신경 쓰지 않아도 된다.

조직에서 commit 작성법을 규칙으로 만들고 그 규칙을 template 으로 이용할 파일로 만들어 배포하면, 여러 사람이 커밋한 메시지 틀이
한 사람이 한 것처럼 동일하므로 효과적이다.

- Sample

```
<label>:<title>

# 제목의 길이는 최대 40글자까지 한글로 간단 명료하게 작성 
# 제목을 작성하고 반드시 빈 줄 한 줄을 만들어야 함
# 제목에 .(마침표) 금지 
# <label> 리스트 
# feature : 새로운 기능 
# bug : 버그 수정 
# update : 비즈니스 로직 변경 
# docs : 문서 (문서 추가, 수정, 삭제) 
# test : 테스트 
# refactoring : 리팩토링
# etc : 기타 변경사항 

<description> 
# 내용의 길이는 한 줄당 60글자 내외에서 줄 바꿈. 한글로 간단 명료하게 작성 
# 어떻게 보다는 무엇을, 왜 변경했는지를 작성할 것 (필수) 

<issue-number> 
# 연관된 이슈 첨부, 여러 개 추가 가능
```

## References.

> https://jeong-pro.tistory.com/207
