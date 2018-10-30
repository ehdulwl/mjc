# git 명령어

## 전역 설정 정보 조회
> git config--global--list
## 전역 설정 정보 삭제시키기

> git config --global --unset-all user.email
> git config --global --unset-all user.name

## 새로운 저장소 초기화하기
> git init

## 저장소 복제하기
> git clone <저장소 url>

## 새로운 원격 저장소 추가하기
> git remote add <원격 저장소> <저장소 url>

## 새로운 파일 git에 등록시키기(staging)
> git add <파일>

## 현재까지 작업한 내용 저장하기
> git commit -m “<메시지>”

## 원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기
> git fetch <원격 저장소>

## 원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기
> git pull <원격 저장소>

## 새로운 로컬 브랜치를 원격 저장소에 푸싱하기
> git push <원격 저장소> <지역 브랜치>

***
# Markdown 문법

## 제목 Headers
* #으로 시작하는 텍스트.
* #은 하나부터 여섯개까지 쓸 수 있고, #이 늘어날때마다 제목의 수준은 내려간다.

## 인용 Blockquotes
* >으로 시작하는 텍스트.
* 줄 하나하나마다 엔터치지 않고 그냥 한 문단이 길게 이어져 있는 경우에 문단의 맨 앞에 한 번만 > 기호를 넣어줄 수도 있다.

## 코드 블럭 Code Blocks
* '''혹은 ~~~코드 첫 줄과 마지막 줄에 Back quote(')또는 물결(~)3개 삽입

## 인라인 코드 Inline Code Blocks
* '(Back quate)로 감싸진 텍스트

## 강조 Emphasis
* 기울여 쓰기(italic): *또는 _로 감싼 텍스트
* 굵게 쓰기(bold): **또는 __로 감싼 텍스트

## 수평선 Horizontal Rules
* -또는 *또는 _을 3개 이상 작성 
* (단, -을 사용할 경우 header로 인식할 수 있으니 이전 라인은 비워두어야 한다.)

## 링크 Links
* 외부 링크 External Links
> * [링크](http://example.com "링크 제목") 인라인 링크
> * [링크 1][1] [1]: http://example1.com/ "링크제목1" 참조 링크
> * <example.com/> <example@example.com> url 링크

* 내부 링크 Internal (Anchored) Links
> * [링크](#id) 내부 링크

## 리스트 List
* 순서 있는 리스트 ordered lists
> * No. 숫자 다음 .을 찍는다. (적힌 숫자랑 상관없이 순서대로 번호가 매겨진다./
* 순서 없는 리스트 Unordered List
> * *,+,-으로 시작


