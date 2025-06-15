**Fine-Tuning Multimodal Foundation Models for Dementia Diagnosis ([Research paper)](https://github.com/Yoma01/Research-Contributions/blob/main/Fine-Tuning%20Multimodal%20Foundation%20Models%20for%20Dementia%20Diagnosis.pdf)<br />
University of Southern California – AI & Healthcare Research**

Developed a resource-efficient pipeline for dementia diagnosis by fine-tuning the multimodal foundation model LLaVA-7B on MRI data. This project addressed challenges in medical AI deployment such as limited data availability and compute constraints by leveraging parameter efficient fine-tuning techniques (LoRA, bfloat16, NF4 quantization, paged optimizers) and running all experiments on a single A100 GPU via Google Colab.

Achieved classification accuracy comparable to state-of-the-art CNNs (e.g., EfficientNet) while requiring significantly less training data. Demonstrated robustness across two neuroimaging datasets (OASIS, ADNI) and explored the generalizability between them. Results showed strong within-dataset performance (up to 98.65% accuracy) and highlighted the need for more diverse, representative training data to improve cross-dataset generalization.

This work contributes to the growing field of accessible, real-world AI applications in healthcare, emphasizing low-resource, high accuracy deployment strategies using foundation models.


**Neural Network Implementation for Structured Prediction on Real-World Data**<br />

Engineered a fully custom multi-layer perceptron (MLP) from scratch without using any machine learning libraries to classify housing listings by bedroom count using structured data from the New York real estate market (4,800+ samples, 16 features). The project emphasized algorithmic rigor, efficient computation, and architectural design within strict resource and runtime constraints.

**Manual Neural Network Design:** Implemented a feedforward architecture with configurable depth, activation functions (ReLU, sigmoid), and backpropagation using only NumPy, including matrix-based gradient computation and weight updates.

**Efficient Training Pipeline:** Vectorized all forward and backward passes to meet runtime limits (<5 min end-to-end) in a constrained environment, using techniques such as mini-batch gradient descent and early stopping.

**Feature Engineering:** Performed domain-aware preprocessing including one-hot encoding for high-cardinality categorical variables and normalization for numeric attributes; handled text fields with customized embeddings and reduced dimensionality.

**Hyperparameter Optimization:** Conducted structured tuning across learning rates, batch sizes, layer widths, and initialization schemes; recorded validation accuracy across 5 train-test splits to empirically guide model selection.

**Performance Benchmarking:** Consistently achieved >90% of baseline model accuracy across randomized evaluations, demonstrating robustness and generalizability of the custom-built network.


