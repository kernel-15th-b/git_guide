# git_guide  

### 기본 설정
- 이름하고 이메일 설정
git config --global user.name "John Doe"  
git config --global user.email johndoe@example.com

### 서버에서 받기
git clone https://github.com/kernel-15th-b/ras-linux-4.14.git

### 변경사항 스테이징 하기
- 전체 스테이징  
git add . 
- 특정파일 스테이징  
git add README.md

### 변경사항 확정
- 커밋  
git commit -m "무엇무엇 수정함"
- 커밋 취소  
git reset HEAD^

### 서버에 올리는법
- 원격 레포지트리 등록  
git remote add origin https://github.com/kernel-15th-b/ras-linux-4.14.git
- 서버에 올리기  
git push origin master

### 서버 수정사항 받기  
git pull origin master
