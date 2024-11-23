# woowa-precourse-7
우아한테크코스 7기 프리코스 연습 레포지토리

|주차|레포지토리 주소|프리코스 참여 레포지토리 주소|재시도|
|---|---|---|---|
|1주차|[문자열 덧셈 계산기](https://github.com/woowacourse-precourse/kotlin-calculator-7)|[문자열 덧셈 계산기 - 프리코스](https://github.com/vvn89/kotlin-calculator-7/tree/vvn89)|[문자열 덧셈 계산기 - 재시도](https://github.com/vvn89/kotlin-calculator-7-retry/tree/vvn89)|
|2주차|[자동차 경주](https://github.com/woowacourse-precourse/kotlin-racingcar-7)|[자동차 경주 - 프리코스](https://github.com/vvn89/kotlin-racingcar-7/tree/vvn89)|[자동차 경주 - 재시도](https://github.com/vvn89/kotlin-racingcar-7-retry/tree/vvn89)|
|3주차|[로또](https://github.com/woowacourse-precourse/kotlin-lotto-7)|[로또 - 프리코스](https://github.com/vvn89/kotlin-lotto-7/tree/vvn89)||
|4주차|[편의점](https://github.com/woowacourse-precourse/kotlin-calculator-7)|[편의점 - 프리코스](https://github.com/vvn89/kotlin-convenience-store-7-vvn89)||


### git commit message
```
git commit -m "feat(): 새로운 기능 추가"
```
```
git commit -m "fix(): 버그 수정"
```
```
git commit -m "docs(README): 구현할 기능을 README에 추가"
```
```
git commit -m "style(.): 컨벤션에 맞춰 코드 포맷팅 변경"
```
```
git commit -m "test(): 테스트 코드 추가"
```
```
git commit -m "refactory(): 코드 리팩토링"
git commit -m "refactory(): 코드 개선"
```
```
git commit -m "chore: gitignore 파일 수정"
```

### 테스트 실행 명령어
```
./gradlew clean test
```

### Gradle JDK
`settings` - `Build Tools` - `Gradle` - `Gradle JDK` - 21 버전으로 변경

### Gradle 빌드 시 'Permission Denied 오류
실행 파일에 실행 권한이 없을 때 발생함.
```
chmod +x ./gradlew
```
권한 부여 후 명령어 재입력

### 재시도 레포지토리 만드는 순서
1. 로컬 클론으로 프로젝트 다운 받기
2. 새로운 레포지토리 만들기
3. 로컬 프로젝트의 remote 연결 끊기
```
git remote remove origin
```
4. 만든 레포지토리에 로컬 프로젝트 연결하기
```
git remote add origin https://github.com/vvn89/${새로운 레포지토리 이름}.git
git branch -M main
git push -u origin main
```




# 진행 순서
1. 프로젝트 fork 후 나의 레포지토리 생성하기
2. fork한 레포지토리를 내 컴퓨터로 clone하기
```
git clone https://github.com/${깃 아이디}/${저장소 아이디}.git
ex) git clone https://github.com/woowacourse/java-baseball.git
```
3. 브랜치 생성하기
```
git checkout -b {본인 아이디}
ex) git checkout -b vvn89
```
4. 기능 구현하기
5. 기능 구현 commit 하기
```
git status // 변경된 파일 확인
git add -A(또는 .) // 변경된 전체 파일을 한번에 반영
git commit -m "메시지" // 작업한 내용을 메시지에 기록
```

6. 본인 원격 저장소에 올리기
```
git push origin 브랜치이름
ex) git push origin vvn89
```
7. github에서 Pull Request 보내기
- 브라우저에서 github 저장소에 접근
- 브랜치를 작업 브랜치로 변경 vvn89
- 브랜치 오른쪽에 있는 "New pull request" 버튼 클릭





