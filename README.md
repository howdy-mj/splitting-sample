코드 스플리팅
벨로퍼트 '리액트를 다루는 기술'

19장: 코드 스플리팅

---

### state를 활용한 코드 스플리팅

- Class형 컴포넌트
- 매번 state로 컴포넌트 선언
- `yarn build`하면 `build/static`안에 `3.chunk.js`에서 확인 가능

### React.lazy와 Suspense 사용

- 함수형 컴포넌트
- 네트워크 탭에서 Slow 3G로 바꾼 후 실행하면, 'loading...'이 보임
