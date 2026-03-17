# Menu Venture MVP

## 🇺🇸 English
An AI-powered MVP built with LangGraph that analyzes Naver DataLab search trends to support menu-based startup decisions.

### Features
- Naver DataLab integration
- Trend analysis
- AI-based decision support

---

## 🇰🇷 한국어
LangGraph 기반 AI 에이전트를 활용하여 네이버 데이터랩 검색 트렌드를 분석하고, 메뉴 기반 창업 의사결정을 지원하는 MVP 프로젝트입니다.

### 주요 기능
- 네이버 데이터랩 연동
- 검색 트렌드 분석
- AI 기반 창업 판단 지원

### 가상 환경 구축
- 나는 conda와 vscode 환경에서 진행함. 버전 맞아야 작동 수월하니 requirements.txt대로 설치할 것. 아래 명령어를 터미널에 작성
- conda create --name langchain_agent(이름 마음대로) python=3.11
- conda activate langchain_agent 
- mkdir conda_dzq(이름 마음대로)
- cd conda_dzq
- pip install -r requirements.txt

### API_key는 .env 파일에 정의하기
- OPEN_API_KEY
- TAVILY_API_KEY
- NAVER TREND API홈페이지에서 CLIENT_ID, CLIENT_SECRET키 발급받아서 .env 파일에 입력. NAVER TREND API 2가지 있어서, https://api.ncloud-docs.com/docs/ai-naver-searchtrend 이 홈페이지 참고

### 설치할 파일
- https://ollama.com/ 홈페이지에서 Ollama 없으면 다운받고, bge-m3 model 다운받기(word embedding 위함)
