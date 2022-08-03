## Post Page
* Post List를 보여줄 Index Page
* 북마크? 
* Post 페이지 접속시 redux (User) isLogin = false 이면 로그인 페이지로 이동하기 추가 

## User
* 1. 서버로부터 로그인 성공과, token 정보를 받으면 쿠키에 id, username, token 보냄, 
* 2. 쿠키에 3가지 정보 저장, userSlice에 (redux) 에 isLogin = true로 변경 
* 3. Header에서 Logout 버튼 누르면 Redux ( dispatch ) 로 isLogin = false, token 지워줌 
