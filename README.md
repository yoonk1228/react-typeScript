# 'https://github.com/yoonk1228/react-typeScript'

## React typeScript
```
npx create-react-app react-ts --template typescript
```

## git commit
`.gtimessage.txt`

## typeScript 라이브러리
```
npm i --save react react-dom typescript
npm i --save-dev @types/react @types/react-dom @types/node
```

## eslint 설치
```
npm install -D eslint
npx eslint --init

✔ How would you like to use ESLint? · problems 
✔ What type of modules does your project use? · commonjs 
✔ Which framework does your project use? · react 
* ✔ Does your project use TypeScript? · No / Yes 
✔ Where does your code run? · browser 
✔ What format do you want your config file to be in? · JavaScript 
* The config that you've selected requires the following dependencies: 
eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest 
✔ Would you like to install them now with npm? · No / Yes

별표 친것은 Yes 해야함
출처: https://koras02.tistory.com/106 [Koras02코딩웹]
```

## 추가 플러그인 설치
```
// 리액트 관련
// npm i -D eslint-config-airbnb-base # 리액트 관련 규칙 X
npm i -D eslint-config-airbnb # 리액트 관련 규칙 O

// airbnb 플러그인에서 만든 관련 규칙 사용
npm i -D eslint-plugin-react eslint-plugin-react-hooks
npm i -D eslint-plugin-jsx-a11y eslint-plugin-import eslint-plugin-prettier eslint-config-prettier
```
* eslint-plugin-import: ES6의 import, export 구문을 지원해주는 필수 플러그인
* eslint-plugin-react: React 규칙이 들어있는 플러그인
* eslint-plugin-react-hooks: React Hooks 규칙이 들어있는 플러그인
* eslint-plugin-jsx-a11y: JSX요소의 접근성 규칙에 대한 정적 검사 플러그인

출처: https://koras02.tistory.com/106 [Koras02코딩웹]