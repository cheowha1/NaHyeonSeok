# GIT과 GITHUB 
## GIT

-GIT : **분산** 버전 관리 시스템
-GITHUB : 원격 GIT 저장소 

### local Git

- 저장소 생성
git init

-git 설정
```bash
git config user.name"NaHyeonSeok"
git config user.email cheowha1@naver.com
# 공용 git 설정을 하려면 -g
# 예) git config -g user.name 이름
```

- git 상태 확인
```bash
git status
```

- staging
```bash
git add .
```

- 저장소에 반영 (commit)
```bash
git commit -m "First commit"
```

- 상태 확인과 로그 확인
```bash
git status # 상대 확인
git log # 로그 확인
```

### Local Git to GITHUB
- GitHub 에서 저장소 생성
-저장소 주소
    -https://github.com/cheowha1/NaHyeonSeok.git

    -원격지 등록
    ```bash
    git remote add origin https://github.com/cheowha1/NaHyeonSeok.git
    # git remote add 저장소이름 저장소주소
-push
```bash
git push -u origin master # 첫번째 푸시
```
