## vscode에서 c, c++ 설정법
https://csdiary.tistory.com/2
후, 진짜 귀찮았다. 

## 실행 방법1. 엠스크립튼으로 c/c++ 코드를 컴파일하고 html 템플릿 활용하기

```
python3 -m venv .env
. .env/bin/activate
python -m http.server 8080

command + shift + b -> build
command + shift + a -> execute
emcc prime.c -o html_template.html
```

<img src="./first.png">