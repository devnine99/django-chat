# 장고 channels를 이용하여 채팅서버 구현

## Project 요약
- 장고(3.0.1)의 MVT 패턴 활용  
- channels 공식문서를 보고 채팅 구현 
- docker로 redis 서버 실행
- local 환경에서 sqlite3 사용


### Chat(채팅)
- 채팅페이지 입장 시 서와와 웹소켓으로 연결
- 메세지 입력 시 웹소켓을 통해 채팅방에 연결된 클라이언트에게 메세지 전송
