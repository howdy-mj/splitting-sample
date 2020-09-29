코드 스플리팅
벨로퍼트 '리액트를 다루는 기술'

19장: 코드 스플리팅

---

### state를 활용한 코드 스플리팅

- Class형 컴포넌트
- 매번 state로 컴포넌트 선언
- `yarn build`하면 `build/static`안에 `3.chunk.js`에서 확인 가능

### React.lazy와 Suspense 사용

- https://reactjs.org/docs/code-splitting.html#reactlazy
- 함수형 컴포넌트
- 네트워크 탭에서 Slow 3G로 바꾼 후 실행하면, 'loading...'이 보임
- SSR 미지원

### Loadable Components 사용

- 서드파티 라이브러리 `yarn add @loadable/component`
- https://loadable-components.com/docs/getting-started/
- SSR 지원
- 렌더 전 필요할 때 스플리팅 된 파일 불러오기 가능
