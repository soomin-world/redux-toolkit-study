### redux toolkit

- slice API :reducer, action value, action creator를 한번에 사용가능.
- 별도의 설정없이 devtools 사용가능
- thㅕnk devtool, immer 등등의 패키지가 있음

### thunk

- redux middleware? action이 리듀서로 전달되기전 작업을 삽입가능. (비동기처리시 사용)
- thunk는 redux middleware중 가장 많이 사용됨.
- createAsyncThunk를 통해 생성가능
- 첫번째 인자, action value, 두번째 인자 함수
