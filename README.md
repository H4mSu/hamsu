# 마크다운 공부!
인용구사용
```
인용구사용은 ```~~ ```입니다.
```
취소선<br>
~~ㅇㅇㅇ~~
```
~~ㅇㅇㅇ~~
```
테이블 사용<br>
이름|나이|학교
--|--|--|
방준하| 24 |계명대 |
__

1. ㅇㅇㅇㅇ 들여쓰기
    - 탭은 한번만 누를것
        - 두번누르면 안되는듯?
        - 하이폰 스페이스바 생활화 할것

    

# 깃 허브 업로드 순서
1.수정후 저장 M 생성
```
```
2.add를 사용하자
```
git add . -> 모두 업로드
git add 파일명 -> 해당 파일만 업로드
```
3.commit 사용
```
git commit -m "깃에 올라오는 버젼 설정" 
git commit - 현재 상태 저장
```
4.로그 한번 확인
```
git log
```
5.push로 허브에 올리기
```
git push origin master
```

# 깃 다운로드 
1.깃 클론 클릭<br>
2.깃 클론 명령어 작성
```
git clone https://github.com/Jgone2/markdown.git
```

# html 한번에 나오는 커맨드
```
! + tab 사용하면 head, body 가 바로 나온다
```

# 깃 리모트 변경
기존 리포지토리 깔끔하게 pull /push
```
git pull
git add.
git commit -m "clean push"
git push
```

기존 리포지토리 remote 제거S
```
git remote remove origin
```

새 리포지토리 remote 추가
```
git remote add origin https://~~~
```
