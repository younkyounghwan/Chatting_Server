# Chatting_Server
C++로 구현된 TCP/IP기반의 IOCP 채팅 서버 프로젝트입니다.
IOCP를 사용하여 효율적으로 네트워크 이벤트를 처리할 수 있도록 설계되었습니다.

## 특징
- 비동기 이벤트 기반 (IOCP)
- 멀티스레드 환경에서 다중 클라이언트 연결 및 패킷 송수신 지원
- 패킷 기반의 'send', 'recv' 처리 로직 구현
- 'Session'을 활용한 연결 관리 및 이벤트 처리
