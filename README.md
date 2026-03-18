🧠 Arabic Sentiment Analysis using AraBERT

---

📌 Project Description | وصف المشروع

This project aims to perform Arabic Sentiment Analysis using a deep learning model called AraBERT.
The goal is to classify Arabic text into positive or negative sentiments.

يهدف هذا المشروع إلى تحليل المشاعر للنصوص العربية باستخدام نموذج تعلم عميق يسمى AraBERT،
حيث يتم تصنيف النص إلى إيجابي أو سلبي.

---

🎯 Objectives | أهداف المشروع

- Apply Deep Learning on Arabic text

- Build a sentiment classification model

- Evaluate model performance

- Test the model on new unseen data

- تطبيق التعلم العميق على النصوص العربية

- بناء نموذج لتصنيف المشاعر

- تقييم أداء النموذج

- اختبار النموذج على بيانات جديدة

---

📊 Dataset | البيانات

- Source: Hugging Face Arabic datasets
- Contains labeled Arabic comments
- Labels:
  - 1 → Positive
  - 0 → Negative

تم استخدام بيانات عربية تحتوي على تعليقات مصنفة مسبقًا إلى إيجابي وسلبي.

---

⚙️ Data Preprocessing | المعالجة المسبقة

- Text cleaning (removing noise if needed)
- Tokenization using AraBERT tokenizer
- Padding & truncation
- Max length = 128

تم تجهيز البيانات وتحويل النصوص إلى صيغة يفهمها النموذج باستخدام Tokenizer.

---

🤖 Model | النموذج

- Model Name: "aubmindlab/bert-base-arabertv02"
- Based on Transformer architecture
- Designed specifically for Arabic language

نموذج AraBERT هو نموذج مبني على تقنية Transformer ومخصص للغة العربية.

---

🏋️ Training Process | عملية التدريب

- Split data: 80% training / 20% testing
- Used Hugging Face Trainer
- Epochs: 2–3
- Batch size: small (for CPU)

تم تدريب النموذج باستخدام مكتبة Transformers وتقسيم البيانات للتدريب والاختبار.

---

📈 Evaluation | التقييم

- Metric used: Accuracy
- Achieved accuracy: ~94%

تم استخدام مقياس الدقة لتقييم النموذج وحقق أداء ممتاز.

---

🧪 Testing | الاختبار

The model was tested on custom Arabic sentences:

تم اختبار النموذج على جمل عربية جديدة:

Example:

text = "الخدمة ممتازة جدا"

---

💻 Technologies Used | الأدوات المستخدمة

- Python
- Transformers (Hugging Face)
- PyTorch
- Datasets
- Pandas
- NumPy
- Scikit-learn

---

📦 Project Structure | هيكل المشروع

arabert-sentiment/
│
├── arabert.ipynb
├── labeled_comments.csv
├── requirements.txt
└── README.md

---

⚠️ Important Note | ملاحظة مهمة

The trained model is not included due to its large size.
You can train the model again using the notebook.

النموذج المدرب غير مرفوع بسبب حجمه الكبير ويمكن إعادة تدريبه بسهولة.

---

▶️ How to Run | طريقة التشغيل

1. Open the notebook in Google Colab
2. Install required libraries
3. Run all cells

---

🚀 Future Improvements | تطوير المشروع

- Build a web application
- Add more classes (neutral sentiment)
- Improve dataset size
- Deploy the model

---

👤 Author | المطور

Abduhskim Khald
