# Hello git

- VCS

- git

- github

1. 1교시
2. 2교시

**git을 처음 초기화** 할때는 `git init`으로 *초기화* 한다.

```python
def a():
    return 'hi'
```

```javascript
function hi(){
	return 'hi'
}
```



| title | content |
| ----- | ------- |
| 'hi'  | 'hello' |
|       |         |

독립적으로 프로젝트마다 패키지관리

`pip freeze > requirements.txt`

파이썬이 venv를 보게끔
`source venv/Scripts/activate`

git 현재 유저 이름 (서명)
`git config --global user.name`

git initialize 현재 폴더에 .git 생성
`git init`
삭제
`rm -rf .git`



변경사항 무시파일

.gitignore



.idea 무시

.gitignore 파일에 .idea 작성



git remote 저장

```
git remote add origin https://github.com/boolks/learn_git.git
```

확인

`git remote -v`

push

`git push origin master`
