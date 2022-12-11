# mongodb-
mongoose를 활용한 유저 생성, 댓글 작성 기능 구현
NOSQL을 처음 사용한 실전 연습 프로젝트
html은 외부 자료를 이용.
그 외의 app.js, route 폴더 등의 user.js와 같은 js 파일들은 구현 완료 했음

public/mongoose.js : 사용자 로딩, 댓글 로딩 기능을 구현

route/comments.js : 댓글의 정보 가져오기, 댓글 추가, 수정, 삭제 라우터를 구현
route/user.js : user의 정보 가져오기, user가 작성한 댓글 로딩, user 생성 구현

schemas/comments.js : nodejs DB의 comment 스키마를 생성
schemas/user.js : nodejs DB의 user 스키마를 생성


연습 과정이라 탄탄하다고 말을 할 수는 없는 수준이지만 연습과정에서 sql을 사용하지 않는 장점을 엿볼 수 있었다.
허나, populate 기능을 사용함으로서 몽고디비의 자율성을 파괴하는 모순점을 이해하기 어려웠다.
