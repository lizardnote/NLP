# Rag Finetuing

## RAG 프로젝트 진행 단계

- `1차 dataset`: dataset 각 100개씩 샘플 생성
- `1차 모델`: HuggingFace Trainer 모델 확보 (meta-llama/Llama-2-7b-chat-hf)
- `2차 모델`: HuggingFace SFTTrainer + DataCollator 모델 확보
- `3차 목표`: trl 코드로 SFT 학습
  - packing, DataCollatorForCompletionOnly 적용 (assistant 턴만 학습)
  - +PEFT (메모리 초과 시)
  - +Quantization (메모리 초과 시)
- `4차 목표`: trl 코드로 DPO 학습
- `5차 목표`: inference 코드 개발
    
## 🚀 사용 기술
- Python
- Runpod / RTX4090
- Colab / Jupyter Notebook
- HuggingFace Transformers

