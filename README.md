# hello-world
git 및 github 공부용

브랜치 해볼려고 새롭게 적은거
신기하군

## 병합하기
head 브랜치에 변경사항이 없고
병합 대상 브랜치가 헤드로부터 시작된 경우
아주 쉽게 병합 가능 = fast-forward

## 병합하기 2
- 헤드 브랜치에 추자적인 커밋이 생기는 경우
- 진짜 병합이 필요해진다.
- 충돌이 안 나면 좋은데, 충돌이 나도 겁내지 말자.

## 오늘의 기분

- 내 기분과는 달리 하늘이 푸르르다.

## 커밋 되돌리기

### reset 사용하기

- 장점 : 쉬워요.
- 단점1 : 커밋이 날아간다.
- 단점2 : 강제 푸시가 필요하다.

### branch 만들어서 되돌리기

- reset과는 달리 내용이 사라지지 않는다.
- 장점 : 쉽다.
- 단점 : 트리가 지저분해진다.

### revert

- 역시 커밋은 없어지지 않는다.
- 장점 : 가장 정석적
- 단점 : 충돌이 일어날 수 있다.
