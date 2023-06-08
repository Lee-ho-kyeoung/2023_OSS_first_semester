# 2023_OSS
## 2023 OSS 수업
* * *
### 3주차 git   
### 이미지 
  
![](../img/kau.png)
   
### 링크   
[LMS](https://lms.kau.ac.kr/login.php)   
#### ProGit 링크   
[ProGit](https://git-scm.com/book/ko/v2)   
##### 주요 git 명령어   
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함킬 때 사용
    + git add <file name>   
* commit
* git reset HEAD <file> : stage된 파일을 unstaged로 변경
* git checkout -- <file> : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림 
* branch
* merge
* status
* log
    + 예) git log --oneline --decorate --graph --all
* * *
### 2주차 숙제   
```bash
#!/bin/sh
filePath=$(find /home/kau2 -name "w2_homework.txt" 2>/dev/null)

echo "----------"
echo "name :"

echo " "
echo "----------"
echo "student id :"

echo "----------"
echo " "
echo "file path :"
echo $filePath
echo " "
echo "----------"
echo "line number :"
cat $filePath | wc -l
echo " "
echo "----------"
echo "last line :"
tail -1 $filePath
```  
## 마크다운
### 목록
#### 번호 있는 목록 : 내림차순 정렬
1. 첫 번째
3. 세 번째
2. 두 번째
#### 번호 없는 목록 : *, -, +
* 첫 번째   
- 세 번째   
+ 두 번째
* * *
* 빨강
  * 녹색
    * 파랑
### 강조   
*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~
