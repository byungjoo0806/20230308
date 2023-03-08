# git 다시 해보기
# 새 저장소 만들기
- git init

# 파일 전부 스테이징
- git add .

# 커밋 매시지 작성
- git commit -m "작업 내용"

# github 원격저장소 연결
- git remote add origin "https://github.com/byungjoo0806/20230308.git"

# 파일 업로드
- git push origin main

# 브랜치 영역을 나눠보자

# 브랜치는 저장소의 작업 공간

- master는 최종 작업물 / 다른 브랜치를 만들어서 여럿이서 
작업을 하거나 혼자 작업할때 작업의 내용을 나눠서 작업하고 최종 작업물로 병합한다.

- master(v0.1) -> dev -> dev -> dev -> master 병합(v0.2)

- master -> dev1, dev2 -> dev1, dev2 -> dev1, dev2 -> dev1 + dev2 -> dev1 + master