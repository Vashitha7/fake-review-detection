*Fake Review Detection*

This project uses a Machine Learning model to detect whether a review is *fake or genuine*, based on the review text.

 🔍 What It Does

- Takes a review as input
- Uses *TF-IDF* to convert the review into numbers
- Predicts whether the review is:
  - ✅ *Genuine (Real)*— if label is `1`
  - ❌ *Fake* — if label is `0`

Technologies Used

- Python
- Pandas
- Scikit-learn (Naive Bayes)
- Google Colab / VS Code
- TF-IDF Vectorizer

Files Included

- `fake_review_detection.ipynb` – Main notebook with code
- `requirements.txt` – Python libraries (optional)
- `project_ppt.pdf` – (If available) Project presentation

 Example Input
Enter a review: "This product is a scam!"
→ 🔴 This review is predicted to be FAKE

Enter a review: "Loved the product and fast delivery!"
→ 🟢 This review is predicted to be GENUINE

📌 Note
This is a beginner-friendly AI project. Accuracy can be improved with more real-world data and advanced models like Logistic Regression or BERT.

Author
Vashitha M – 3rd Year CST Student, SNS College of Engineering
