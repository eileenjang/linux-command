## vi 편집기 사용
- INSERT 모드(i): 문자를 편집할 수 있음
- COMMAND 모드(esc): 복사/붙여넣게, 파일저장/종료 등 작업을 할 수 있음
  - 종료(quit) :q 입력 후 enter
  - 저장(write) 및 종료 :wq 입력 후 enter
  - 저장 및 강제종료(!) :wq! 입력 후 enter

```
$ vi myfirstfile
1. i 키를 사용해 insert 모드로 전환 (하단에 --INSERT-- 표시가 나타남)
2. "Hello Vi!" 입력
3. ESC를 눌러서 Command 모드로 전환
4. :wq 입력 후 엔터를 눌러 파일 저장 및 종료

$ vi myfirstfile
1. i 키를 사용해 INSERT 모드로 전환
2. "Hello Vi!" 다음에 add text 입력
3. ESC를 눌러서 Command 모드로 전환
4. :q 입력 후 엔터를 눌러 vi 종료 시도
5. :q! 입력 후 엔터를 눌러 vi 종료

$ vi myfile
1. 파일이 변경되지 않은 것을 확인
2. :q 입력 후 엔터를 눌러 vi 종료
```
## Command 모드에서 할 수 있는 것들 1
- 줄삭제 dd
- 복사 yy
- 붙여넣기 p
- 되돌리기 u

## Command 모드에서 할 수 있는 것들 2
- 라인보기 :set number
- 텍스트 찾기 /검색 후 n 으로 탐색
- 택스트 대체 :%s/원본/대체/g
