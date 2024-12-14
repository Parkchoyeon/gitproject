# 팀 소개
### 📌 팀 구성  <br/>
[팀원]</strong> 허상호 박초연 황호준 장정호 
<br/><br/>


# 프로젝트
## 🏨 운전자 보험 약관 질의응답 챗봇🏨 [(Notion 링크)](https://)

### 📌 프로젝트 소개 
운전자 보험 약관을 보다 쉽게 이해하고 활용할 수 있도록 설계된 질의응답 시스템입니다. 이 프로젝트는 내외부 문서를 효율적으로 처리하고,
사용자가 원하는 정보를 신속하게 제공하는 데 초점을 맞추고 있습니다. RAG(Retrieval-Augmented Generation) 방식을 활용하여, LangChain과 Chroma 데이터베이스를 기반으로 전문 문서의 신뢰도 높은 답변을 생성합니다.
<br/><br/>


### 📌 서비스 목표
복잡한 보험 약관의 정보를 일반 사용자나 상담원이 쉽게 조회할 수 있도록 돕는 것이 목표입니다.
기존 LLM 모델이 제공하는 일반적인 답변을 보완하기 위해 RAG 기술을 도입하여 실질적이고 구체적인 답변을 생성합니다.
<br/><br/>


### 📌 개발 기간
2024.12.18 ~ 2024.12.19 (2일)
<br/><br/>


### 🔨 기술 스택
<div align=left><h3>🕹️ Frontend</div>
<div align=left>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">
</div>

<div align=left><h3>🕹️ Backend</div>
<div aling=left>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
  <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white">
  <img src="https://img.shields.io/badge/sqlite-003B57?style=for-the-badge&logo=Sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/virtualbox-183A61?style=for-the-badge&logo=Virtualbox&logoColor=white">
</div>

<div align=left><h3>🕹️ AI Core</div>
<div align=left>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=OpenAI&logoColor=white">
</div>

<div align=left><h3>🕹️ Dev Tool </div>
<div align="left">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
  <img src="https://img.shields.io/badge/Visual Studio Code-008CFF?style=for-the-badge&logo=Visual Studio Code&logoColor=white">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
</div>

<div align=left><h3>🕹️ etc </div>
<div align="left">
  <img src="https://img.shields.io/badge/selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white">
  <img src="https://github.com/user-attachments/assets/d56c2af3-c1fe-4a3e-92f2-524faa577e00" height=28 width=50>
  <img src="https://github.com/user-attachments/assets/ff6a1794-2fcc-4a1a-96a7-2302433de56d" height=28>
</div>
<br/><br/>


### 📋 요구사항 명세서

### 1. 프로젝트 범위
- **포함되는 범위**:
   - 자동차 설명서에 있는 내용을 검색하여 사용자 질문에 답변 제공
   - **예시**: 배터리 방전 시 문 여는 방법 검색
- **제외되는 범위**:
   - 각 자동차 모델별 비교, 가격, 자세한 제원 (자동차의 트림별로 다를 수 있기 때문)

### 2. 기능 요구사항 
## 💻 DB 테이블 - ERD 및 DDL
<img src="https://github.com/user-attachments/assets/eb7c8b6b-2181-44ae-9314-94db1cc08b70" />
<img src="https://github.com/user-attachments/assets/5b26d713-22e9-4ac0-b73e-5be80b3a7a65" />

## 📚 수행결과
<img src="https://github.com/user-attachments/assets/e4102cd8-6f27-4544-b24f-380f8c9015e1" />
<img src="https://github.com/user-attachments/assets/1d766509-3c03-4f2a-97d1-191a93d38d5c" />
<img src="https://github.com/user-attachments/assets/d500834a-4c59-4377-8421-d5e5440494d4" />

### 📚 개선사항 및 확장 가능성 
#### 서비스 측면 및 기술 측면 

**1. 데이터 품질 개선**
- 정기적인 업데이트: 데이터베이스를 주기적으로 업데이트하여 최신 정보를 반영할 수 있습니다.

**2. 사용자 맞춤형 서비스**
- 피드백 서비스: 사용자의 피드백을 통해 추천 알고리즘 개선 / 사용자가 추천된 차량에 대한 만족도를 평가할 수 있습니다. 수 

**3. 사용자 인터페이스(UI)및 경험 개선(UX)**
- 모바일 최적화: 다양한 기기에서 원활하게 사용할 수 있도록 모바일 최적화를 진행할 수 있습니다.

**4. 보안 및 개인정보 보호**
- 데이터 암호화: 사용자 데이터를 안전하게 보호하기 위해 암호화 기술을 적용할 수 있습니다.
- 개인정보 보호 방침 수립: 사용자 데이터의 수집 및 사용에 대한 명확한 정책을 마련하고

**5. 통합 기능 개발**
- 대화형 챗봇 기능:
- 다양한 필터 옵션 추가:
- 비교 기능:
- 이미지 생성 기능:

**6. 고객 지원 서비스**
- FAQ 및 도움말 제공:
1. **특허 가능성**
- Mobility Director"의 기술적 혁신성과 고유한 데이터 처리 방식, 특히 사용자 질문에 기반한 맞춤형 정보 제공 
<br/><br/>


### 📚 System Architecture
![Architecture](./images/architecture.png)


### 📚 RAG 구조도 
<img width="916" alt="image" src="https://github.com/user-attachments/assets/91afda06-9a13-44e3-97eb-3ecf2fd27a68"><br/>
<img width="916" alt="image2" src="https://github.com/user-attachments/assets/01b1ee70-9f9a-4bbf-96a4-64da07d7b79b">
<br/><br/>


### 📚 수행결과
<img width="916" alt="image" src="https://github.com/user-attachments/assets/512a5fa2-525b-41ac-904a-43077c2a9ac2"><br/>
<img width="916" alt="image" src="https://github.com/user-attachments/assets/bdc6ac9c-ecfc-49be-9895-4d814b29322b"><br/>
<img width="916" alt="image" src="https://github.com/user-attachments/assets/aa8e9c8a-0123-4766-9c6a-2d714e4068cf">
<br/><br/>

### 📚 한줄 회고
* **진정현 :** 넣고싶은 기능이 많았지만 시간이 조금 부족하다고 느껴서 시간관리가 조금 필요할 것같다.
* **사재민 :** 구현해둔 기능을 활용하지 못해 아쉬웠지만 부족함을 느끼고 자극을 받았다. 부족했던 시간에도 최선을 다 해준 팀원들에게 감사함을 느낀다
* **서종호 :** 다들 같이 프로젝트를 진행하며 많이 성장한것같다. 다음 프로젝트는 좀 더 나은 방향으로 노력하며 완성도 있게 해야함을 느낀다 그래도 좋은 팀원들가 같이해서 정말 좋았다.  
* **장정원 :** 장고가 낯설어 생각보다 시간이 많이 걸려 시간적 제약이 아쉬웠지만 모두 열심히 협력해서 발표까지 마칠수 있어서 감사하다. 기회가 된다면 프로젝트를 이어나가서 기능을 더 추가해 발전된 챗봇을 만들고 싶다.

### 🖇️자료 출처
* [RAG 구조도 이미지](https://)
* [사용 데이터 (KB 손해보험 운전자보험 약관)](https://)

### 발표 노션 주소
**https://burnt-paneer-0f6.notion.site/SKN02-4rd-4Team-1006c152949280849b8fc158b7002c46?pvs=4**
