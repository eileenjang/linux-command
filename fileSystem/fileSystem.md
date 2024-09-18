## 현재 위치를 확인하는 pwd
- print working directory
```
$ pwd
/Users/i1234
```

## 디렉터리를 만드는 mkdir
- make directory
- mkdir 디렉터리명
```
$ cd ~
$ mkdir linuxTest
$ cd linuxTest
$ mkdir a b c d
```

## 디렉터리를 이동하는 cd
- change directory
- cd [이동할 디렉터리명]
- cd ~ (홈 디렉터리로 이동)
- cd .. (상위 디렉터리로 이동)

## 디렉터리의 파일 리스트를 조회하는 ls
- list
- 현재 위치 기준 디렉터리 조회: ls
- 특정 디렉터리 조회: ls [디렉터리 위치]
- 숨김 파일 및 파일 사이즈도 함께 조회: ls - alh
```
$ cd ~/linuxTest/a
$ touch aFile1 && touch .aFile2
$ ls
aFile1
$ ls -alh
aFile1
.aFile2
```

## 디렉터리/파일의 구조를 확인하는 tree
- 일반조회: tree
- 디렉터리까지만 조회: tree -d
- 숨김파일까지 조회: tree -a
- 깊이 지정 조회: tree -L {깊이}

## 디렉터리/파일을 복사하는 cp
- copy
- 파일 복사: cp [원본파일] [대상위치]
- 다른 이름으로 복사: cp [원본파일] [위치와 파일명]
- 디렉터리 복사: cp -r [원본위치] [대상위치]
- 현재 디럭테리로 복사: cp -r [원본위치] .

## 디렉터리/파일을 이동하는 mv
- move
- 파일/디렉터리를 이동: mv [원본위치] [새위치]

## 디렉터리/파일을 찾는 find
- 파일/디렉터리 찾기: find [찾을위치] -name [파일/디렉터리명]

## 디렉터리/파일을 삭제하는 rm
- remove
- 파일 삭제: rm [삭제할 파일 위치]
- 디렉터리 삭제: rm -r [삭제할 디렉터리 위치]
- 파일 강제 삭제: rm -rf [삭제할 파일 위치]
```
$ rm -rf *
$ ls
```
