# Fine-Tuning Large Language Models Efficiently: A Case Study

- This project fine-tunes the Llama-2-7b-chat-hf model using parameter-efficient techniques like QLoRA to optimize performance with limited computational resources. I have applied a 4-bit precision quantization to reduce VRAM usage. Real-time training progress is monitored using TensorBoard, demonstrating effective fine-tuning of large language models under resource constraints.
- The dataset used in this project is the guanaco-llama2-1k from Hugging Face. In this project, I have used the “Llama-2-7b-chat-hf" as the base model which is directly loaded from Hugging Face
-	To run the code file you need to install a few packages that are given in the code file. This code file is self-sufficient, running each cell will give you the results.
-	However, please note that this code was written and specifically designed for systems with NVIDIA GPU and driver. Hence, if your system does not have an NVIDIA GPU this will throw a runtime error.
