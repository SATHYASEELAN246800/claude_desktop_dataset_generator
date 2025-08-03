
```
# 🧠 Smart Dataset Generator & ML Classifier (End-to-End MCP Project)

A full-stack project that combines AI-assisted data generation (Claude), machine learning model training (Python), and GUI-based interaction (Colab + Gradio) for smart outcome prediction and analytics. Built using the MCP (Machine Learning + Content Pipeline) methodology.

---

## 🔗 Live Project Links

- 🤖 Claude Desktop Artifact: [View Claude Output](https://claude.ai/public/artifacts/0289f87f-d9f4-4f06-9d5a-8b704e9ba01c)
- 🧪 Google Colab GUI Notebook: [Open in Colab](https://colab.research.google.com/drive/1SamHX1MZscWHJRWyb6P30j3dlUiqAQKV#scrollTo=g3gDlZ-97m0t)

---

## 🧾 Prompt Used in Claude Desktop

```

Generate a smart dataset of 100 rows with:

* Name, Role, MediaType, Job Domain, Gender, Age, Income, Region, Duration, Status, Date, Outcome

Then:

1. Analyze: unique counts, trends, missing values
2. Train ML model (Decision Tree / Logistic Regression)
3. Show accuracy + confusion matrix
4. Export as SmartDataset.xlsx
5. Save to D:\claude desktop

```

---

## 📂 Folder Structure

```

D:/
└── claude desktop/
├── SmartDataset.xlsx
├── ML\_Model\_Output.txt
├── GUI\_Classifier.ipynb
├── confusion\_matrix.png (optional)
└── README.md

````

---

## 🛠️ Technologies Used

| Tool/Tech           | Purpose                                      |
|---------------------|----------------------------------------------|
| **Claude Desktop AI** | Data generation + ML automation via prompts |
| **Python 3.10+**     | Programming language                         |
| **pandas**           | Data handling                                |
| **scikit-learn**     | ML model building                            |
| **matplotlib / seaborn** | Data visualization (if added)             |
| **Google Colab**     | Online Python notebook platform              |
| **Gradio**           | GUI for model training (in Colab)            |
| **Excel**            | Output format for datasets                   |
| **LabelEncoder / StandardScaler** | Preprocessing tools in sklearn  |

---

## 📊 Sample Dataset Output (Excel)

| Name        | Role       | MediaType | Domain       | Region     | Outcome |
|-------------|------------|-----------|--------------|------------|---------|
| Arul Kumar  | Farmer     | Image     | Agriculture  | Madurai    | Success |
| Lavanya R   | Developer  | Video     | Tech         | Chennai    | Pending |
| Sanjay B    | Laundry    | Audio     | Home Service | Trichy     | Failure |

---


---

## 💻 GUI via Google Colab

The project includes a **Gradio-based GUI** in Google Colab that allows users to:

* Upload or generate new data
* Select model type (Logistic, Tree)
* Click-to-train and visualize results
* Export predictions

📎 Launch here: [Google Colab Notebook](https://colab.research.google.com/drive/1SamHX1MZscWHJRWyb6P30j3dlUiqAQKV#scrollTo=g3gDlZ-97m0t)

---

## 🚀 How to Use

1. Open **Claude Desktop**
2. Paste the provided prompt
3. Download the generated Excel dataset
4. Move to `D:\claude desktop`
5. Run the provided Python code or Colab GUI
6. View predictions, accuracy, and reports

---

## 📈 Future Enhancements

* Add support for real image/audio files
* Extend to multi-label outcome predictions
* Connect to real-time sensors or APIs
* Export analytics to PDF or dashboards
* Dockerize for deployment

---

## 📝 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 👤 Credits

* **Project Lead:** Sathya Seelan
* **ML Assistant:** Claude AI
* **GUI Developer:** Gradio + Google Colab

```
