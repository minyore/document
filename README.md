### git command

git clone
```javascript
git clone [git clone URL]
```

git remote
```javascript
git remote -v // 저장소 위치 확인

pwd // 현재 디렉토리 위치 확인
cd [dirtory name] // 해당 디렉토리 이동
cd / // root 디렉토리 이동
cd .. // 상위 디렉토리 이동
cd ~ // 홈 디렉토리 이동
cd - // 이전 경로로 이동
ls // 현재 위치 파일 목록 조회
rm - r [dirtory name] // 해당 디렉토리 삭제
mkdir [dirtory name] // 디렉토리 생성 
```

git branch
```javascript
git checkout -b [branch name] // branch 생성 이동
git branch -d [branch name] // branch 삭제
```

git push
```javascript
git push -u origin [branch name] 
git push
git fetch --all
git pull [branch name]
git merge [branch name]
git merge --abort // 병합 취소
```

git commit
```javascript
git log --oneline
git commit -m "message"
git rebase origin/master
// git checkout [work branch]
// git rebase origin/master
// git checkout [origin/master]
// git merge [work branch]
```

git config
```javascript
git config --list
git config --global user.name "[user name]"
git config --global user.email "[user email]"
```
