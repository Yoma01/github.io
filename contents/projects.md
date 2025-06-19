#### Fine-Tuning Multimodal Foundation Models for Dementia Diagnosis ([Research paper)](https://github.com/Yoma01/Research-Contributions/blob/main/Dementia_prediction_reserach/Fine-Tuning%20Multimodal%20Foundation%20Models%20for%20Dementia%20Diagnosis.pdf)
Developed a resource-efficient pipeline for dementia diagnosis by fine-tuning the multimodal foundation model LLaVA-7B on MRI data. This project addressed challenges in medical AI deployment such as limited data availability and compute constraints by leveraging parameter-efficient fine-tuning techniques (LoRA, bfloat16, NF4 quantization, paged optimizers) and running all experiments on a single A100 GPU via Google Colab.

The model achieved classification accuracy comparable to state-of-the-art CNNs (e.g., EfficientNet) while requiring significantly less training data. It demonstrated robustness across two neuroimaging datasets (OASIS, ADNI) and explored their generalizability. Results showed strong within-dataset performance (up to 98.65% accuracy) and highlighted the need for more diverse, representative training data to improve cross-dataset generalization.

This work contributes to the growing field of accessible, real-world AI applications in healthcare, emphasizing low-resource, high-accuracy deployment strategies using foundation models.

**Research Poster**

<p align="center">
  <img src="/static/assets/img/Poster%20566.png" alt="dementia_prediction_poster" width="500"/>
</p>

#### Neural Network Implementation for Structured Prediction on Real-World Data [(Code Repo)](https://github.com/Yoma01/Housing-Price-Prediction-Neural-Network-) 

Engineered a fully custom multi-layer perceptron (MLP) from scratch without using any machine learning libraries to classify housing listings by bedroom count using structured data from the New York real estate market (4,800+ samples, 16 features). The project emphasized algorithmic rigor, efficient computation, and architectural design within strict resource and runtime constraints.

- **Manual Neural Network Design:** Implemented a feedforward architecture with configurable depth, activation functions (ReLU, sigmoid), and backpropagation using only NumPy, including matrix-based gradient computation and weight updates.

- **Efficient Training Pipeline:** Vectorized all forward and backward passes to meet runtime limits (<5 min end-to-end) in a constrained environment, using techniques such as mini-batch gradient descent and early stopping.

- **Feature Engineering:** Performed domain-aware preprocessing including one-hot encoding for high-cardinality categorical variables and normalization for numeric attributes; handled text fields with customized embeddings and reduced dimensionality.

- **Hyperparameter Optimization:** Conducted structured tuning across learning rates, batch sizes, layer widths, and initialization schemes; recorded validation accuracy across 5 train-test splits to empirically guide model selection.

- **Performance Benchmarking:** Consistently achieved >90% of baseline model accuracy across randomized evaluations, demonstrating robustness and generalizability of the custom-built network.

#### Duo-Othello Game Playing Agent – Adversarial Search & Strategic Evaluation [(Code Repo)](https://github.com/Yoma01/othello_AI_agent) 

Designed and implemented a time-bounded, competitive AI agent for Duo-Othello, a variant of Reversi game. The agent was built to autonomously select optimal moves in real-time adversarial settings against both random and minimax-based opponents under strict performance and format constraints.

- **Minimax with Adaptive Depth:** Implemented a minimax search algorithm with dynamic depth adjustment based on remaining time, ensuring real-time responsiveness and strategic foresight under time-critical conditions.

- **Strategic Evaluation Heuristics:** Designed and integrated domain-specific heuristics including stability, mobility, corner capturing, and disk differential to guide the evaluation of non-terminal game states and maximize long-term advantage.

- **Time Management Strategy:** Integrated CPU time tracking and budgeting across multiple turns, optimizing move quality while avoiding timeouts. Designed fallback strategies for fast approximation under low time (<0.05s)

- **Move Validation and Legal Action Generation:** Efficiently generated all valid moves according to extended flipping rules across all directions, enabling fast pruning and accurate simulations.

The agent consistently outperformed both random and minimax-based baseline opponents across 20 evaluation games, demonstrating strong performance regardless of play order. This project showcases proficiency in adversarial AI, heuristic-driven decision-making, and real-time strategy under tight constraints skills directly applicable to game AI, autonomous agents, and general-purpose planning systems.

#### Artsy API Artist Discovery Platform 

**[Demo of Artsy Android App Functionality](https://youtu.be/ykjJmsXR2ys)** <br />
**[Access the app on GCP](https://test-317810304200.us-west1.run.app/)**

Developed an artist discovery system that allows users to search, explore, and favorite visual artists using live Artsy API data. The platform supports dynamic search with real-time results, detailed artist profiles with artwork and category carousels, and user authentication for favoriting functionality. It has a persistent login system, interactive artwork dialogs,  snackbars for user feedback, and support for dark mode.

The application is accessible both as a web application (built using Angular and Node.js) and a native Android app (built using Kotlin and Jetpack Compose), offering seamless experiences across devices. Users can register, log in, manage sessions, and maintain synchronized favorites across platforms, backed by a cloud-hosted MongoDB database.

<p align="center">
  <a href="https://youtu.be/ykjJmsXR2ys" target="_blank">
   <img src="static/assets/img/thumbnail.png" alt="Artsy API" width="500" height="400" border="0" />
  </a>
</p>

**Skills Used:** TypeScript, HTML, CSS, Angular, JavaScript, Node.js, Python, Flask, Kotlin, Jetpack Compose, RESTful APIs, MongoDB Atlas, Google Cloud Platform


#### Other projects:

#### Movie Recommendation Systems with LLM and Cosine Similarity ([Code Repo](https://github.com/Yoma01/Movie-Recommendation-Systems-with-LLM-and-Cosine-Similarity-)):
Designed two movie recommendation systems using the Netflix Kaggle dataset:
- **LLM-based:** Used LLaMA-2 embeddings to capture semantic similarity between movies.
- **Content-based:** Applied cosine similarity on bag-of-words vectors derived from movie descriptions, genres, and tags

#### WORLDWIDE COVID-19 VACCINE TRACKER - Tableau visualization [(Project Link)](https://public.tableau.com/app/profile/yoma.akoni/viz/covid-19globalvaccinetracker_16829564134810/covidvaccinetracker):
The dashboard shows the worldwide performance of vaccination programs making use of a bar chart, map and graphs

