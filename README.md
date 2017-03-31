## C9 <-> Github 연동
* C9.io에서 blank workspace 생성
* git 초기화 및 remote repository 설정
* `--force`를 이용해 remote repository overwrite
```

bobkim:~/workspace $ git config  --global user.name "espozbob"                                                                                                                                    
bobkim:~/workspace $ git config  --global user.email "espozbob@gmail.com"                                                                                                                         
bobkim:~/workspace $ git init
Initialized empty Git repository in /home/ubuntu/workspace/.git/
bobkim:~/workspace (master) $ git remote add origin git@github.com:espozbob/espozbob.github.io.git
bobkim:~/workspace (master) $ git add .
bobkim:~/workspace (master) $ git commit -m "Initial commit"
[master (root-commit) 945ae3a] Initial commit
 1 file changed, 18 insertions(+)
 create mode 100644 README.md
bobkim:~/workspace (master) $ git push --force origin master

```