# Electron_dev

## 일렉트론이란?

- 자바스크립트, HTML, CSS 를 이용하여 데스크탑 어플리케이션을 만드는 프레임워크입니다.
- Atom Shell 에서 시작하여 MIT 라이선스 오픈소스로 전환 후, Electron 으로 명칭을 전환함.
- 백엔드는 Node.js, 프론트엔드는 크로미움을 기반으로 사용함.

## 일렉트론을 사용하여 만들어진 어플리케이션

1. 슬랙
2. 아톰
3. VSCode
4. WordPress
5. Remember

## 일렉트론의 장점

1. 웹기술을 이용해 데스크탑 어플리케이션 개발이 가능.
2. 한 개의 코드로 크로스 플랫폼에서 작동하는 어플리케이션을 만들 수 있음.
3. npm 을 이용해 node package 를 사용할 수 있음.

## 일렉트로 퀵스타트

[일렉트론 퀵스타트](https://www.electronjs.org/docs/latest/tutorial/quick-start) 들어가서 일렉트론을 설치

설치

일렉트론 사용하기 위해 일렉트론 패키지 추가
```
npm install --save-dev electron
```
package.json
```json
"scripts": {
  "start": "electron .",
}
```

패키징과 배포를 위한 가장 빠른 방법은 Electron Forge 를 사용하는 것입니다.
```
npm install --save-dev @electron-forge/cli
npx electron-forge import
```

Forge의 make 를 이용하여 빌드합니다. (.exe 파일 생성)
```
npm run make
```