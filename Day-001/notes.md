**Key Concepts**: AI, Machine Learning, Deep Learning, LLMs,and GenAI
**Artificial Intelligence (AI)**:A theory and development framework for computers to perform tasks mimicking humanintelligence. More a theory than direct implementation.
**Machine Learning (ML)**:Practical approach for computers to learn from data, without explicit programming, to achieve AI.
**Deep Learning**:Subset of machine learning inspired by the neural architecture of the human brain (uses artificialneural networks); handles complex pattern recognition.
**Large Language Models (LLM)**:AI models (such as ChatGPT) that process massive text datasets to generate or process text-basedoutputs; inputs can increasingly include images, audio, and video, but outputs are typically text.• Generative AI (GenAI):Advanced models capable of accepting various input types and generating multiple kinds ofoutputs (e.g., text, images, audio, video).
**Discriminative vs. Generative Models**
**Discriminative Models**:(ML and Deep Learning) Trained to classify or predict specific target outcomes; operate withlabeled data (target column present).
**Generative Models**:(LLMs, GenAI) Trained on large, unstructured data to generate new content; not limited topredicting labels/classifications.
**Supervised and Unsupervised Learning**
**Supervised Learning**:- Requires a 'target column' (labelled outcome).- Data is split into features (independent variables) and target (dependent variable).- Examples: Predicting house prices (regression), predicting loan default (classification).- Model evaluation is possible because true answers are available for comparison.
**Unsupervised Learning**:- No target column; goal is to find patterns/groupings (like customer segmentation).- No direct way to validate output; lacks an explicit measure of accuracy.Data Splitting and Model Validation
**Data Splitting**:Raw data is typically divided into training data (70-80%) and testing data (20-30%). Randomsampling is preferred for representativeness.
**Process**:- Split data into training and testing sets.- Further split each set into features (X) and target (Y).- Train model on training data (X_train, Y_train), test on unseen test data (X_test), and comparepredictions to Y_test.- Accuracy is relevant only for supervised learning.
**Classification vs. Regression in Supervised Learning**
**Classification**:Target variable is categorical (binary or multi-class). Example: Loan outcome (paid/not paid),animal type.
**Regression**: Target is continuous numerical value. Example: Price prediction, profit, stock prices.Prerequisites and Tools for Learning
**Required programming & libraries**: Python, NumPy, Pandas, Matplotlib, Seaborn, sklearn,statsmodels, etc.• Recommended editors: Colab, Jupyter, VS Code, Spyder, PyCharm.• Basic statistics and probability are foundational: descriptive and inferential statistics, hypothesistesting, Bayes theorem.
