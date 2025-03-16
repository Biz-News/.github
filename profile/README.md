# Biz-News 📰

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
<img width="1582" alt="스크린샷 2025-03-17 오전 2 31 09" src="https://github.com/user-attachments/assets/0b0078a4-b68f-487a-85ff-e42579070901" />

## 시연 영상


https://github.com/user-attachments/assets/1859e5db-1237-4917-9a4d-6063584264e0




## Service Architecutre
![image](https://github.com/user-attachments/assets/7f14b623-52a4-480f-b1c2-ae27440787b6)

## FrontEnd
### 사용 기술
- Next.js 15 (App Router)
- TypeScript
- Material-UI (MUI)
- Tailwind CSS
- Framer Motion
- Chart.js
### 주요 기능
- Al, Backend 서버와 Ap 통신
- 데이터 시각화
- 반응형 디자인
- SSR, 컴포넌트 단위 스트리밍 (점진적 렌더링)
- 애니메이션

## BackEnd
### 사용 기술
- SpringBoot
- MySQL (RDB)
### 주요 기능
- 공공데이터 API 호출 및 DB 저장
- 프런트와 API 통신

## AI
### 사용 기술
- Python
- FastAPl
- ChatGPT 4o
- LangChain
- BeautifulSoup4 (bs4)
- Neo4j (GraphDB)
### 주요 기능
- 데이터 수집 및 저장
- LangChain + Neoaj를 활용한 Graph RAG 기반 뉴스 요약/추천
### 기술적 특징
- 각 노드 (기업, 키워드, 뉴스 등) 간의 연관성 분석을 극대화 하기 위해 Graph RAG 구현
- Neo4j를 활용하여 (기업 - 키워드 - 뉴스) 관계 저장
- 각 노드간의 Knowledge Graph를 구축해서 고도화된 연관성 검색 가능
- 연관 뉴스 요약 및 추천
- Neo4j + LangChain + ChatGPT 4o를 활용
- 관련성 추출에 최적화된 Cypher Query 작성 및 뉴스 요약과 투자 의견까지 LLM 사용
### 개선 방향
- Graph RAG를 사용했다는 차별점을 극대화할 예정
- PageRank 등 Graph 기반 DB를 활용한 심층 검색 알고리즘 도입
~ 뉴스에 키워드 언급 횟수 등 다양한 연결성을 발견하여 더 많은 인사이트 도출

## Cloud
### 사용 기술
- AWS(EC2,RDS)
- Github Actions
- Docker
- Nginx
### 주요 기능
- EC2 + Docker 기반 서비스 안정적인 운영
- CI/CD 자동화 구축으로 빠른 배포 가능
- Nginx Reverse Proxy로 효율적인 트래픽 관리
