res.json()의 반환 값은 promise다.
기본 res의 반환값은 Response 스트림인데,
".json()"메서드를 통해 Response(응답)스트림을 읽을 수 있다.
Response는 데이터가 모두 받아진 상태가 아니다.
.json()으로 response 스트림을 가져와 완료될 때 까지 읽는다.
다 읽은 body의 텍스트를 promise형태로 반환한다.

✨cd login/app => npm start
✨localhost/3000/login
