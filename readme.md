기본지식들
=========


환경세팅
====
Mac
--
- [Setup Homebrew](https://whitepaek.tistory.com/3)
- [Setup JDK](https://velog.io/@jsoh/%EC%98%A4%EB%9D%BC%ED%81%B4-JDK%EB%A5%BC-%EC%82%AD%EC%A0%9C%ED%95%98%EA%B3%A0-OpenJDK-11-%EC%84%A4%EC%B9%98)
- [Setup Maven]()
- Setup Git
    - $ brew install git
    - $ git config --global user.name "abcd" // git user name
    - $ git config --global user.email abcd@abcd // git user email

Linux
--
- 휠 속도 개선

```sh
$ sudo apt install imwheel /설치
$ imwheel //실행
$ gedit ~/.imwheelrc //환경설정 파일 변경

//내용추가. 맨 끝 숫자가 높을수록 많은 스크롤링

".*"
None,      Up,   Button4, 3
None,      Down, Button5, 3

$ imwheel -k //재시작



```


Tool 사용관련
=====
VS Code 단축키
---
- 마크다운 편집기 열기 : Cmd + K V (Linux : Ctrl + Shift + V)

IntelliJ
---
- [Auto Import시 관련 패키지 가져오기 세팅](https://hjjungdev.tistory.com/102)
    - Auto Import메뉴에서 checkbox 2개 세팅
- [Lombok 세팅](https://gmlwjd9405.github.io/2018/11/29/intellij-lombok.html) - 플러그인 설치 & 'Enable annotation plugin' 체크

- 단축키
    - CMD + DELETE : 현재 커서가있는 한줄 삭제
    - CMD + D : 한 줄 복사
    - CMD + [ : 뒤로 이동
    - CMD + ] : 앞으로 이동
- Linux
    - Shift + F10 : 현재 Test 케이스 실행
    