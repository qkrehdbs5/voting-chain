# VotingChain

블록체인 기반 간단한 투표 시스템 API 프로젝트

---

## 1. 프로젝트 개요
- **이름**: VotingChain  
- **목표**: Ganache 로컬 이더리움 네트워크에 스마트컨트랙트를 배포하고,  
  FastAPI로 REST API(투표 생성·참여·조회) 제공.  
- **주요 기능**  
  - 후보자 목록 조회  
  - 지갑 주소 기반 투표  
  - 투표 결과 조회  
  - MySQL에 투표 여부 보조 저장  

---

## 2. 기술 스택
| 역할            | 기술/라이브러리           |
| --------------- | ------------------------- |
| 스마트컨트랙트   | Solidity                  |
| 로컬 블록체인   | Ganache                   |
| 배포 · 테스트   | Brownie                   |
| Python ↔ Ethereum | web3.py                 |
| 웹 API 서버     | FastAPI, Uvicorn          |
| DB              | MySQL, SQLAlchemy (pymysql) |
| 환경변수 관리   | python-dotenv             |
| 테스팅          | pytest                    |

---
<!-- 
## 3. 사전 준비 (Prerequisites)

1. **MacOS Homebrew**  
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" -->