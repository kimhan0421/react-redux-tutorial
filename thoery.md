- 리덕스와 react-redux 라이브러리 설치

```
yarn add redux react-redux
```

- redux-devtools-extension 사용하고 싶어요

* Redux DevTools는 리덕스 개발자 도구
* 크롬 확장 프로그램으로 설치해 사용 가능

```
yarn add redux-devtools-extension
```

후, 적용

```javascript
import {composeWithDevTools} form 'redux-devtools-extension'
```

브라우저의 크롬 개발자 도구 실행 후 Redux탭 열면 확인 가능
이때, State 버튼에서 리덕스 스토어 내부의 상태 확인 가능
