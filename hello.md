# hello git

## git 명령어 요약

  - clone: 원격 저장소 복사
  - add
  - commit
  - push
  
  
<!--
주석인가?

-->

## 브랜치 변경하기

  - 브랜치란: 기존 내용을 유지한 채 새로운 내용을 추가하고 싶을 때 사용한다.
  - 체크아웃: 특정 브랜치(혹은 커밋) 으로 돌아가고 싶을 때 사용.
  - 소스트리의 체크아웃: 브랜치 이름을 더블 클릭하는 것만으로 체크아웃 가능.
  - 추가 변경


## 병합하기 1

  - 헤드 브랜치에 변경사항이 없고
  - 병합 대상 브랜치가 헤드로부터 시작된 경우
  - 아주 쉽게 병합 가능 = Fast-forward
  
## 병합하기 2

  - 헤드 브랜치에 추가적인 커밋이 생기는 경우
  - 진짜 병합이 필요해 진다.
  - 충돌
  - 다른곳에서 수정


## 오늘의 기분

  - 좋음

## 충돌해결 추가

  - 중요. 중요

## 커밋 되돌리기

### reset 사용하기

  - 장점: 쉬워요
  - 단점1: 커밋이 날아간다.
  - 단점2: 강제 푸시가 필요하다.  

### branch 만들어서 되돌리기

  - reset 과는 달리 내용이 사라지지 않는다.
  - 장점: 쉽다.
  - 단점: 트리가 지저분해진다.  
    