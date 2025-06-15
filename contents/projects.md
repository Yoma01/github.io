Fine-Tuning Multimodal Foundation Models for Dementia Diagnosis ([Research paper)](https://github.com/Yoma01/Research-Contributions/blob/main/Fine-Tuning%20Multimodal%20Foundation%20Models%20for%20Dementia%20Diagnosis.pdf)
University of Southern California – AI & Healthcare Research 

Developed a resource-efficient pipeline for dementia diagnosis by fine-tuning the multimodal foundation model LLaVA-7B on MRI data. This project addressed challenges in medical AI deployment such as limited data availability and compute constraints by leveraging parameter efficient fine-tuning techniques (LoRA, bfloat16, NF4 quantization, paged optimizers) and running all experiments on a single A100 GPU via Google Colab.

Achieved classification accuracy comparable to state-of-the-art CNNs (e.g., EfficientNet) while requiring significantly less training data. Demonstrated robustness across two neuroimaging datasets (OASIS, ADNI) and explored the generalizability between them. Results showed strong within-dataset performance (up to 98.65% accuracy) and highlighted the need for more diverse, representative training data to improve cross-dataset generalization.

This work contributes to the growing field of accessible, real-world AI applications in healthcare, emphasizing low-resource, high accuracy deployment strategies using foundation models.
