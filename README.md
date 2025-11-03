# 💬 SmartChatEvolution_v2_Hybrid  
**Level 2 — Hybrid Chatbot + Logging Dashboard**

---

## 📘 프로젝트 개요  
이 프로젝트는 **FAQ 기반 정적 챗봇(Level 1)** 을 확장하여  
실시간 채팅, 로그 저장, 관리자 대시보드 시각화를 구현한 **하이브리드 챗봇 시스템**입니다.  

- 💬 실시간 WebSocket 채팅  
- 🗂️ 대화 로그 DB 저장  
- 📊 관리자 통계 페이지 (Chart.js)  
- 🔧 GPT API 연동 구조까지 고려한 설계  

---

## ⚙️ 기술 스택  

| 구분 | 기술 |
|------|------|
| Backend | Spring Boot 3.3.x, STOMP WebSocket, MyBatis |
| Frontend | HTML, CSS, JavaScript, Thymeleaf |
| Database | OracleDB |
| Visualization | Chart.js |
| Build Tool | Maven |
| Version Control | Git + GitHub |

---

## 🧠 주요 기능  

- **실시간 채팅 (STOMP + SockJS)**  
  사용자 간 메시지를 실시간으로 주고받는 WebSocket 구조  
  입장 / 퇴장 / 메시지 전송 이벤트 실시간 반영  

- **대화 로그 관리**  
  모든 대화가 DB에 자동 저장되며  
  관리자 페이지(`/admin/logs`)에서 확인 가능  

- **통계 시각화**  
  관리자 통계 페이지(`/admin/stats`)에서  
  Chart.js를 이용해 날짜별 메시지량을 시각화  

---

## 🚀 실행 가이드  

1️⃣ **클론하기**
