# NLP Disaster Tweets Classification

Проект посвящён бинарной классификации твитов на тему реальных катастроф. Выполнен полный NLP-пайплайн: предобработка данных (обработка пропусков, объединение текстовых полей), исследовательский анализ, векторизация текста (Bag-of-Words, TF-IDF, Hashing), разработка кастомного токенизатора (очистка, стоп-слова, стемминг), обучение и сравнение моделей. В качестве базовой модели использована Logistic Regression, качество оценивалось по f1-score. Проведён сравнительный анализ разных способов представления текста и их влияния на результат.

## Технологии
- pandas, numpy  
- scikit-learn (CountVectorizer, TfidfVectorizer, HashingVectorizer, LogisticRegression)  
- nltk (tokenization, stopwords, stemming)  
- matplotlib, seaborn  
