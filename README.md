# 2019-07-25-OSS개발자포럼과 함께하는 국민대학교 SW 여름 캠프

### 주최 : 과학기술정보통신부
### 주관 : IITP, 국민대학교, OSS개발자포럼


-처음 시작하는 Git + GitHub 활용하기 - 박희찬

## 버전 관리 도구?
  -> 하나의 프로그램을 지속적으로 업데이트! <br>
     !문제점! <br>
        1. 개발 이력(언제 무엇을 어떻게 바꿨는지) 확인
        2. 이전 버전으로 되돌릴 때
        3. 여러 개발자의 작업이 합쳐질 때 일어나는 충돌
<br>=> 버전 관리 도구로 해결!

    버전 관리 도구별 비교는 강의자료(15~) 참고

# Git 기초 명령어 소개

## git 명령어 기본 틀
  $ git <command> <option> <args>
    ex) git commit -m "커밋 메시지 작성"
        커밋 메시지를 한번에 지정하여(옵션) 커밋한다(명령어)

        git push origin master --force
        origin(입력값)을 master(입력값)으로 강제로(옵션) push한다(명령어)

        기본 명령어들의 기능 설명은 강의자료(31~) 참고

## Commit(커밋) 과정
  (강의자료 37쪽 참고)

  1) 사용자가 작업중인 공간(에디터?)에서 파일에 추가/삭제/수정 작업이 실행됨
      -> git add -a  /  수정된 모든 사항들을 스테이지에 올린다
      -> git add .   /  삭제를 제외한 모든 수정사항을 스테이지에 올린다
      -> git add -u  /  새 파일 생성을 제외한 모든 수정사항을 스테이지에 올린다
  2) 스테이지 영역(개발자 컴퓨터)













  /git init -> git 저장소를 만들어줌(마스터 브랜치)
