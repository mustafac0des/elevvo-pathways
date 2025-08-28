NLP Projects Portfolio 🧠
This repository is a collection of hands-on projects in Natural Language Processing, demonstrating a range of tasks from fundamental text classification to advanced transformer-based models. Each project highlights a specific NLP technique and its application, with a focus on real-world metrics and actionable results.

1. Sentiment Analysis 🎬
   
Objective: Classify movie reviews as positive or negative.
Methodology: Preprocessed, tokenized, and vectorized a dataset of movie reviews.

Key Achievements:
Achieved 89% accuracy using a Logistic Regression model.
An alternative Naive Bayes model provided 86% accuracy.
Visualized the most frequent words in positive and negative reviews to gain deeper insights.

2. News Classification 📰
   
Objective: Perform multiclass classification to categorize news articles.
Methodology: Cleaned and preprocessed the dataset, followed by vectorization.

Key Achievements:
Attained 89% accuracy with a Logistic Regression model.
Significantly improved performance with a neural network, achieving 97% accuracy with a low loss of 0.0998 after 10 epochs.
Plotted the most frequent words for each news category to understand topic distribution.

3. Fake News Detection 💯
   
Objective: Distinguish between true and fake news articles.
Methodology: Preprocessed and feature-engineered the datasets before training.

Key Achievements:
Developed a Logistic Regression model that achieved a high accuracy of 96%.
Generated visualizations of the most frequent words in true and fake news to identify distinguishing features.

4. Named Entity Recognition (NER) 🏷️
   
Objective: Extract named entities from a news articles dataset.
Methodology: Implemented both rule-based and model-based entity recognition.

Key Achievements:
The rule-based system achieved an F1-Score of 0.54.
Pre-trained models were tested, yielding F1-Scores of 0.46 and 0.50.
Visualized the extracted entities to showcase the model's output.

5. Topic Modeling 📖
   
Objective: Discover dominant topics within a news articles dataset.
Methodology: Tokenized the preprocessed dataset and applied two popular models.

Key Achievements:
Successfully extracted topics using LDA and NMF models.
Achieved strong Silhouette scores of 0.76 (LDA) and 0.67 (NMF), indicating well-defined topic clusters.
Visualized topic-word distributions using word clouds.

6. Question Answering ✅
   
Objective: Build a QA system using transformers on the SQuAD dataset.
Methodology: Fine-tuned a pre-trained DistilBERT model.

Key Achievements:
The fine-tuned model achieved perfect 100% Exact Match and F1-Scores, with a training loss of 0.65.
For comparison, a non-fine-tuned model also yielded 100% Exact Match and F1-Scores, demonstrating the model's robust pre-trained capabilities.

7. Text Summarization 📝
   
Objective: Generate concise summaries of news articles.
Methodology: Utilized a pre-trained Pegasus transformer model.

Key Achievements:
Evaluated model performance using ROUGE scores: R1: 45%, R2: 25%, RL: 35%, and RLsum: 35%.
Explored and implemented both extractive and abstractive summarization techniques.
Fine-tuned the pre-trained model for optimal performance.

8. Resume Screening 🎯
   
Objective: Automatically screen resumes against a given job description.
Methodology: Employed similarity scoring between preprocessed resumes and job descriptions.

Key Achievements:
Developed a complete resume screening application.
The application uses Sentence Transformers to find the best-fit resumes.
The tool supports multiple file formats and can process resumes in both batches and individually.
