# SMS-Spam-Classifier
<h1>SMS Spam Classifier</h1>

<p>This project is a machine learning model that classifies SMS messages as <b>Spam</b> or <b>Ham (Not Spam)</b> using natural language processing (NLP).</p>

<h2>Tools & Libraries</h2>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>NLTK (for text preprocessing)</li>
  <li>Scikit-learn (for ML models)</li>
  <li>Matplotlib, Seaborn (for EDA & visualization)</li>
</ul>

<h2>Project Workflow</h2>
<ol>
  <li><b>Data Preprocessing</b><br>
      Cleaned the text (lowercasing, removing punctuation, stopwords, stemming).  
      Transformed text into numerical form using TF-IDF vectorization.
  </li>
  <li><b>Exploratory Data Analysis (EDA)</b><br>
      Checked word frequencies, spam vs ham distribution, and visualized with bar plots and word clouds.
  </li>
  <li><b>Model Training</b><br>
      Tried multiple models: Naive Bayes, Logistic Regression, SVM, Random Forest, and KNN.  
      Compared their accuracy and precision scores.
  </li>
  <li><b>Results</b><br>
      The best model was Multinomial Naive Bayes, achieving around 98% accuracy and 100% precision on spam messages.
  </li>
</ol>

<h2>How to Run</h2>
<pre>
# clone repo and install requirements
pip install -r requirements.txt

# run the script
python smsspamclassifier.py
</pre>

<h2>Key Takeaway</h2>
<p>This project shows how simple NLP techniques with the right preprocessing and model choice can give highly reliable results for spam detection.</p>
