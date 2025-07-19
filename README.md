# NLP
# 📚 RAG 실습 모음 (Retrieval-Augmented Generation with Vector DB)

이 디렉토리는 RAG(Retrieval-Augmented Generation) 기반의 챗봇과 검색 시스템 구현을 위한 실습 노트북들을 모아놓은 공간입니다.

RAG는 사전학습된 언어 모델(LLM)과 외부 지식 저장소(예: 벡터 DB)를 결합하여, **보다 정확하고 맥락 있는 응답을 생성**할 수 있도록 설계된 프레임워크입니다.

---

## 📌 실습 흐름 요약

1. **데이터 전처리 및 임베딩 생성**  
   → 텍스트 데이터를 처리하고, 임베딩 모델을 사용해 벡터화

2. **벡터 데이터베이스 구축 (FAISS 등)**  
   → 검색 기반 시스템의 핵심이 되는 벡터 저장소 구성

3. **RAG 파이프라인 구성**  
   → 벡터 DB에서 관련 문서를 검색하고, LLM으로 응답 생성

4. **도메인 기반 챗봇 제작 (예: 금융 도메인)**  
   → 특정 분야에 맞춘 응답 생성과 응용

---

## 📂 파일 설명

| 파일명 | 설명 |
|--------|------|
| `01_Embedding_and_DB.ipynb` | 텍스트 전처리 및 Sentence-BERT 기반 임베딩 생성, FAISS 인덱스 구축 |
| `02_RAG_pipeline.ipynb` | 사용자 질의에 대해 유사 문서를 검색하고, LLM 응답을 생성하는 RAG 구성 실습 |
| `03_RAG_finance_chatbot.ipynb` | 금융 도메인 지식을 기반으로 하는 RAG 챗봇 구현 예시 |

---

## 🛠 사용 기술 및 도구

- **Python, Colab**
- **Hugging Face Transformers**
- **FAISS**: 벡터 기반 검색
- **OpenAI / ChatGPT API** (선택)
- **LangChain** (선택)
- **Pandas, NumPy, Matplotlib** (데이터 처리 및 시각화)

---

## 💡 학습 포인트

- 텍스트 임베딩 기법 이해
- 벡터 DB의 활용과 검색 흐름 파악
- LLM과 검색결과의 결합 구조(RAG 구조) 구현
- 도메인 맞춤형 챗봇 개발 방법론

---

## 📬 Contact

실습 노트북에 대한 질문이나 제안이 있다면 [GitHub Issues](https://github.com/lizardnote/Text-Analytics/issues)를 통해 남겨주세요!
