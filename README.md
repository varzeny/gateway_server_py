# gateway_server_py
fastapi로 구현된 일종의 api, app 게이트웨이 서버입니다. 독립된 복수의 자잘한 기능들을 통합 배포하기 위해 만들어졌습니다. 자잘한 기능들에 매번 asgi서버를 붙이지 않아도 됩니다. 사실 엔진엑스도 필요 없다는걸 깨달았지만, 다른 앱과 서버들을 위해서 일단은 리버스프록시로 엔진엑스를 사용합니다.
