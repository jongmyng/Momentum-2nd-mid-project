
### uv 커맨드

uv init
uv sync
uv add ipykernel sqlalchemy pandas polars seaborn streamlit python-dotenv

uv remove

uv sync를 중간중간 해준다.


### 가상환경 실행
source .venv/bin/activate


### ds store를 git ignore에 추가


### 내일 가서 할일
- git pull 
- 수정된 파일 수정해서 commit - > push


### git 연결
- git stage {파일이름 | . }: 커밋의 후보들 선택 
- git commit -m "message" : 실제로 커밋 (세이브포인트)
- git push  : 깃허브 업로드

- git pull : 가져오기

- git stash : 잠시 저장하기
- git stash apply : 되돌리기

- git reset --soft HEAD~1 : 커밋 1개만큼 돌리기
- git revert -m 1 abcd123 : abcd123 커밋 돌리기 
- git log --oneline : abcd123같은 해시값을 알려줌


