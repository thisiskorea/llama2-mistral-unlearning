# llama2-mistral-unlearning

unlearning 방법론에 대한 실험
fine-tuning으로 언러닝하는 방법과 그와 비슷한 성능을 낼 수 있다고 생각되는 방식들로 구성하여 실험

![image](https://github.com/user-attachments/assets/7b506e23-eec3-4e2a-bfc3-b526c2fdf9c5)

1. fine tuning model
2. RAG model
3. hard prompt model

각각 방법마다 mistral과 llama2 모델을 사용하여 진행

huggingface의 TOFU dataset을 사용하여 진행

gpt4 model을 사용하여 평가를 진행함
