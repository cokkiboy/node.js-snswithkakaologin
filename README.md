<h1>sns with kakaologin service 핵심정리</h1>
서버 는 요청에 응답하는 것이 핵심임무이므로 요청을 수락하든 거절하든 상관없이 반드시 응답해야 합니다. 이떄 한번만 응답해야 에러가 발생하지않습니다.
개발 시 서버를 매번 수동으로 재시작하지않으려면 nodemon을 사용하는 것이 좋습니다.
dotenv 패키지와 .env 파일로 유출되면 안되는 비밀키를 관리합시다.
라우터는 routes 폴더에, 데이터베이스느 models 폴더에, html 파일은 views 폴더에 각각 구분해서 저장하면 프로젝트 규모가 커져도 관리하기 쉽습니다.
데이터 베이스를 구성하기전에 데이터간 1:1 ,1:N,N:M 관계를 파악합시다.
middlewares/index.js처럼 라우터내에 미들웨어를 사용할수있다는 것을 기억합시다.
Passport의 인증 과정을 기억해둡시다. 특히 serializeUser와 deserializeUser가 언제호출되는지 파알하고 있어야합니다.
프론트 엔드 form태그의 인코딩 방식이 multipart일떄는 multer같은 multipart 처리용 패키지를 사용하는 것이 좋습니다.

