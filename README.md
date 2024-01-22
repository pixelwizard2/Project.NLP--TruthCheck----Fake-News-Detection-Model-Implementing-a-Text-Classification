# Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification
_가짜 뉴스(헤드라인) 판별을 위한  텍스트 분류 모델 구현(LSTM)_
<p align="right">
  <a href="https://blog.naver.com/pixelwizard/223301468800">
    <img src="https://img.shields.io/badge/한국어%20번역본-03C75A?style=flat-square&logo=Naver&logoColor=white" alt="네이버 블로그">
  </a> </p>  
  
![3 화면 캡처 2024-01-22 152546](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/4ffcc76d-4fd1-4234-b096-b8a6efe55928)

## 1. Project Overview and Background (프로젝트 개요 및 배경)

-**Problem Recognition:** In the digital age, the spread of fake news causes social chaos and misinformation. Identifying fake news is becoming increasingly important.
-**Project Objective:** To develop a natural language processing (NLP) model based on LSTM (Long Short-Term Memory) neural networks to effectively classify fake and real news.

**※ Development Period: October 24, 2023, Total 5 hours**


## 2. Team Composition and Role Distribution (팀 구성 및 역할 분담 )

- **Team Leader :** Responsible for data preprocessing and project management.
- **Team Member 1 :** In charge of designing, implementing, and optimizing the LSTM model.
- **Team Member 2 :** Responsible for model performance evaluation, result interpretation, and visualization.


## 3. Technologies and Tools Used (사용 기술 및 도구)

- **Programming Language:** Python
- **Libraries and Frameworks:** TensorFlow, Keras, Pandas, Re, NumPy, Matplotlib, Seaborn, Scikit-Learn, NLTK
- **Machine Learning Techniques:** LSTM, Embedding, Dropout


## 4. Project Features and Challenges (프로젝트 특징 및 도전 과제)

- Emphasis on the importance of collaboration 
- Challenge of addressing the issues of overfitting and underfitting in the model

![3 화면 캡처 2024-01-22 152546](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/4ffcc76d-4fd1-4234-b096-b8a6efe55928)

## 5. Project Development Process (프로젝트 개발 과정)

**(1) Data Preprocessing and Exploratory Data Analysis (EDA)**

**Data Source:** Utilizing "Fake and Real News" Dataset from Kaggle.

![4 데이터셋](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/b5bf1617-d646-476f-b52f-ce5da20f5fdc)

**Preprocessing:** Text cleaning, tokenization, stopwords removal, label encoding, etc.  
**EDA:** Analyzing text length of news headlines, distribution of fake and real news, keyword analysis, etc.

![5](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/c5e59dda-0988-48aa-bb9b-051dd508e6e8)


**(2) Model Design and Implementation**

- **LSTM Architecture:** Composed of word embedding, recurrent layer (LSTM), dropout, and densely connected layers.
- **Hyperparameter Tuning:** Adjusting batch size, number of epochs, learning rate, etc., for model performance optimization.

![6](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/199d4227-72d4-46cc-966e-5cc7fd759b67)
![7](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/5d23652c-a807-41b9-97cb-3940abdb0e99)
![8](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/ff43a2d6-b815-40ed-a544-79d4cc9aa434)


- **Visualization:** Diagrammatic visualization of each layer (Embedding, LSTM, Dense) from a 3D perspective, clearly indicating the output shape and number of parameters of each layer.



**(3) Performance Evaluation and Optimization**

- **Evaluation Metrics:** Accuracy, precision, recall, F1 score, etc.
- **Cross-validation:** Assessing the model's generalization ability and establishing strategies to prevent overfitting.

![9](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/0837ba1c-e36e-40a5-b268-d65bbe3f1f01)


**(4) Result Analysis and Visualization**

- **Result Interpretation:** Analyzing the classification results and error patterns of the model.
- **Visualization:** Representing performance metrics and learning curves graphically.

![10](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/49307ebe-d542-4e35-9a90-d899ba943d66)

## 6. Reflections and Areas for Improvement (느낀 점 및 아쉬운 점)

- **Reflections:** Gained a deep understanding of the LSTM model and data science, and realized the importance of teamwork in solving complex real-world problems.
- **Areas for Improvement:** Lack of diverse data sources and experimental approaches during the project duration, and limited application of advanced NLP techniques.



## 7. Future Directions and Improvements (보완사항 및 미래 방향)

Plan to utilize a wider range of datasets and explore and apply the latest NLP techniques to enhance the model's performance through additional experiments.
Future Direction: Comparing performance with other NLP models, improving accuracy and versatility through more sophisticated feature engineering, and exploring applicability in actual journalistic environments.

![1 화면 캡처 2023-12-26 115739](https://github.com/pixelwizard2/Project.NLP--TruthCheck----Fake-News-Detection-Model-Implementing-a-Text-Classification/assets/138272416/db00524b-2cb1-4c4c-a2b6-0d8d18a4102d)
