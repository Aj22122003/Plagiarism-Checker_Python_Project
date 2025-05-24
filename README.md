# 📄 CodeClause_Plagiarism_Checker

This is an AI-based Python project that detects **plagiarism** between multiple `.txt` files using **TF-IDF Vectorization** and **Cosine Similarity**. It outputs similarity scores between all combinations of input files to help identify textual overlaps and copied content.

---

## 🚀 Features

- Scans all `.txt` files in the current directory
- Uses **TF-IDF** to vectorize file contents
- Calculates **cosine similarity** between every pair of documents
- Displays pairs of files with their corresponding plagiarism scores

---

## 🧠 Technologies Used

- Python
- `scikit-learn` for TF-IDF and cosine similarity
- Jupyter Notebook (for development)

---

## 🛠 How It Works

1. **Read Files**: All `.txt` files in the directory are read.
2. **Vectorization**: The content of the files is transformed into vectors using `TfidfVectorizer()`.
3. **Similarity Calculation**: Cosine similarity is calculated between each pair of vectors.
4. **Output**: A set of file pairs with similarity scores is printed.

---

## 📂 Sample Output

Example of output format:
('lorem 2.txt', 'lorem 3.txt', 0.100829...)
('lorem 2.txt', 'simpletext.txt', 0.044...)
('lorem 2.txt', 'lorem.txt', 0.218...)

cpp
Copy
Edit

Each tuple represents:
(File A, File B, Similarity Score)

yaml
Copy
Edit

---

## 📦 Dependencies

Install required libraries using:

```bash
pip install scikit-learn
▶️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/mihirbramhane/CodeClause_Plagiarism_Checker.git
Navigate to the directory:

bash
Copy
Edit
cd CodeClause_Plagiarism_Checker
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook CodeClause_Plagiarism Checker.ipynb
Add your .txt files to the directory.

Execute all cells to get plagiarism similarity scores.

## 📌 Notes
Ensure all text files are encoded in UTF-8.

The results depend on the lexical similarity of the content.

This is a basic similarity checker, not a full plagiarism detector (i.e., it doesn't catch paraphrased content).

##🧑‍💻 Author
Ajinkya Kutarmare


Let me know if you want this saved as a downloadable `README.md` file.
