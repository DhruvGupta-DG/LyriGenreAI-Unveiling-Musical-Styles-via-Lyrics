# LyriGenreAI-Unveiling-Musical-Styles-via-Lyrics

This project involves the analysis and classification of song lyrics into two genres: progressive rock and pop. The project follows a structured approach and can be summarized as follows:

Importing Libraries and Data: The project begins by importing essential libraries such as NumPy, Pandas, Matplotlib, and Seaborn for data manipulation and visualization. The dataset containing song lyrics and their associated genres is imported from an Excel file.

Data Preprocessing: Several preprocessing steps are applied to clean and prepare the lyrics data. These steps include removing numbers, punctuations, converting text to lowercase, removing special characters, eliminating stopwords, and performing lemmatization to group similar words together.

Vectorization: The text data is transformed into numerical format using CountVectorizer and TF-IDF (Term Frequency-Inverse Document Frequency) to prepare it for machine learning models.

Exploratory Data Analysis (EDA): EDA is conducted to gain insights into the lyrics data. Histograms are used to visualize the distribution of characters and words in the lyrics. N-grams (sequences of adjacent words) are analyzed to identify common patterns and repetitions in the text. Word clouds are generated to visualize the most frequent words in the lyrics.

Sentiment Analysis: Sentiment analysis is performed using the TextBlob library to determine the polarity (positive or negative sentiment) of the lyrics. The sentiment scores are visualized in histograms for both genres and the overall dataset.

Feature Creation & Selection: Features are created from the vectorized lyrics data, and redundant features are eliminated to prepare the data for modeling.

Train-Test Split: The dataset is split into training and testing sets to train and evaluate machine learning models.

Modeling: Three different classification models are implemented:
Naive Bayes
Decision Trees
Random Forest

Model Evaluation: The models are evaluated using metrics such as confusion matrices, classification reports, and accuracy scores. Random Forest Classifier achieved the highest accuracy score of approximately 0.90.

Conclusion: The project concludes by summarizing the entire process and highlighting the key findings. It emphasizes that Random Forest Classifier performed well in classifying song lyrics into their respective genres.

Overall, this project demonstrates a comprehensive workflow for preprocessing and analyzing text data, building machine learning models, and evaluating their performance. It can be extended and adapted for similar text classification tasks in various domains.
