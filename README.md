# Bangla and English Question Answering Using Fine-Tuned LLaMA Model

This repository demonstrates fine-tuning and deploying the **Meta-LLaMA model** for question-answering tasks in both **Bangla** and **English**. It integrates datasets from multiple languages to provide a robust multilingual QA system.

## **Features**
- **Fine-tuned Meta-LLaMA model** with multilingual capabilities.
- Supports both **Bangla** and **English** question-answering tasks.
- Efficient memory usage using **4-bit quantization** and **LoRA-based training**.
- Lightweight and scalable training setup with **deployment-ready inference**.

## **Dataset**

### **English Dataset**:
Utilizes the **Alpaca Dataset**, containing diverse instruction-based question-answer pairs for English language tasks.

### **Bangla Dataset**:
Incorporates a curated **Bangla QA Dataset** containing question-answer pairs to enhance the model’s multilingual capabilities.

## **Model Training**

The model is fine-tuned using a combination of **English** and **Bangla** datasets. **LoRA** and **4-bit quantization** are applied to optimize the training process for hardware efficiency and scalability. This approach ensures high performance while reducing memory consumption.

## **Inference**

After fine-tuning, the model supports inference in both **Bangla** and **English**. It can accurately understand and generate answers to questions based on the multilingual training.

## **Deployment**

The fine-tuned model is ready for integration into applications or services. It supports efficient inference, making it suitable for real-time systems.

## **Key Highlights**
- Combines **multilingual datasets** for improved model performance.
- **Memory-efficient** training and inference techniques.
- Scalable approach leveraging **LoRA** and **quantization**.

## **Contributions**

Contributions to this project are welcome! Feel free to open issues or submit pull requests for new features, bug fixes, or improvements.

## **License**

This project is open-sourced under the **MIT License**.
