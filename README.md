# E-commerce Review Classification

This project is a machine learning application designed to classify e-commerce product reviews into three categories: **Positive**, **Neutral**, or **Negative**. Using natural language processing (NLP) techniques and an artificial neural network (ANN), the system analyzes review texts and predicts their sentiment.

---

## 🌟 Features

✅ Cleans and preprocesses raw review text (removing special characters, lowercasing, etc.)
✅ Uses **TF-IDF vectorization** to convert text into numerical features
✅ Implements an **ANN model** built with Keras and TensorFlow
✅ Classifies reviews into three categories: Positive, Neutral, Negative
✅ Provides evaluation metrics like **accuracy**, **confusion matrix**, and **classification report**
✅ Allows **real-time prediction** on new user-provided review text

---

## 🛠 Technologies Used

* **Python 3**
* **Pandas, NumPy** for data handling
* **Matplotlib, Seaborn** for data visualization
* **Scikit-learn** for preprocessing and evaluation
* **TensorFlow, Keras** for building and training the neural network

---

## 💻 Project Structure

* `dataset2.csv` → Raw dataset of e-commerce reviews
* `notebook.ipynb` → Main Jupyter Notebook with all preprocessing, model building, training, and evaluation steps

---

## 📊 Example Results

* **Accuracy**: Achieved \~91% accuracy on the test set.
* **Confusion Matrix**: Visualizes the performance of the classifier across all three classes.
* **Sample Predictions**:

  * *“I loved this product, highly recommend!”* → Positive
  * *“It’s okay, not great but not bad either.”* → Neutral
  * *“Terrible quality, very disappointed.”* → Negative

---

## ⚙️ How to Use

1️⃣ Clone this repository or download the `.ipynb` file.
2️⃣ Make sure you have the required Python packages installed.
3️⃣ Run the Jupyter Notebook, which:

* Loads and cleans the data
* Splits it into training and test sets
* Trains the ANN model
* Evaluates the model’s performance
* Allows you to enter your own review and see the predicted sentiment

---

## 🚀 Future Improvements

✨ Improve model performance by experimenting with different architectures (e.g., LSTM, BERT).
✨ Add a web or desktop interface for easier user interaction.
✨ Include more diverse datasets to improve generalization.

---

## 📫 Contact

If you want to collaborate or discuss improvements, feel free to reach me through GitHub or at **[dilekkeskin@example.com](mailto:dilekkeskin@gmail.com)** (replace with your real contact if you want).

---

If you like this project, please ⭐ **star the repository** and follow me for more machine learning and NLP projects!
