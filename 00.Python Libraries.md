
# 🐍 Python Libraries Cheat Sheet (Beginner to Advanced)

---

## 🔧 Core & Built-in Libraries

| Library     | Purpose                         | Example              |
|-------------|----------------------------------|----------------------|
| `os`        | OS-level operations              | `os.listdir()`       |
| `sys`       | System-specific parameters       | `sys.argv`           |
| `math`      | Basic math functions             | `math.sqrt(16)`      |
| `datetime`  | Date and time handling           | `datetime.now()`     |
| `json`      | JSON parsing                     | `json.loads()`       |
| `re`        | Regular expressions              | `re.findall()`       |
| `collections` | Specialized containers         | `Counter(), deque()` |
| `itertools` | Efficient looping                | `chain(), groupby()` |
| `functools` | Function tools                   | `lru_cache(), reduce()` |

---

## 📊 Data Science & Analysis

| Library     | Purpose                 | Example           |
|-------------|--------------------------|-------------------|
| `pandas`    | Data manipulation        | `pd.DataFrame()`  |
| `numpy`     | Numerical computing      | `np.array()`      |
| `matplotlib`| Plotting and visualization | `plt.plot()`   |
| `seaborn`   | Statistical plots        | `sns.histplot()`  |
| `scikit-learn` | Machine learning      | `model.fit()`     |
| `statsmodels` | Statistical modeling   | `sm.OLS()`        |

---

## 🌐 Web Development

| Library     | Purpose                      | Example              |
|-------------|-------------------------------|----------------------|
| `Flask`     | Lightweight web framework     | `@app.route('/')`    |
| `Django`    | Full-featured web framework   | `django-admin startproject` |
| `FastAPI`   | High-performance APIs         | `@app.get("/")`      |

---

## 🤖 Machine Learning & AI

| Library     | Purpose                       | Example               |
|-------------|-------------------------------|-----------------------|
| `TensorFlow`| Deep learning                 | `tf.keras.Model()`    |
| `PyTorch`   | Neural networks               | `torch.nn.Module()`   |
| `Keras`     | High-level API for TensorFlow | `Sequential()`        |
| `XGBoost`   | Gradient boosting             | `xgb.train()`         |
| `LightGBM`  | Fast boosting                 | `lgb.train()`         |

---

## 🧪 Testing & Automation

| Library      | Purpose            | Example              |
|--------------|--------------------|----------------------|
| `unittest`   | Built-in testing   | `assertEqual()`      |
| `pytest`     | Advanced testing   | `def test_func()`    |
| `selenium`   | Browser automation | `webdriver.Chrome()` |
| `requests`   | HTTP requests      | `requests.get()`     |
| `beautifulsoup4` | HTML parsing   | `soup.find()`        |

---

## 📄 PDF & Excel Handling

| Library      | Purpose                | Example               |
|--------------|-------------------------|-----------------------|
| `reportlab`  | Create PDFs             | `canvas.drawString()` |
| `weasyprint` | HTML to PDF             | `HTML().write_pdf()`  |
| `PyPDF2`     | Read/edit PDFs          | `PdfReader()`         |
| `openpyxl`   | Excel file handling     | `Workbook()`          |
| `fpdf`       | Simple PDF generation   | `pdf.cell()`          |

---

## 🖥️ GUI Development

| Library   | Purpose                   | Example             |
|-----------|----------------------------|---------------------|
| `Tkinter` | Built-in GUI toolkit       | `tk.Label()`        |
| `PyQt`    | Advanced GUI framework     | `QWidget()`         |
| `Kivy`    | Multitouch/mobile apps     | `Label(text='Hello')` |

---

## 🗃️ Database & File Handling

| Library   | Purpose               | Example              |
|-----------|------------------------|----------------------|
| `sqlite3` | Lightweight database   | `conn.execute()`     |
| `shutil`  | File operations        | `shutil.copy()`      |
| `glob`    | File pattern matching  | `glob.glob()`        |
