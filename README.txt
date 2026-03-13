
## Cohere Chat Bot

---

### ⚠️ Note

Don’t forget to **get your API key from Cohere** before running the bot.

---

### Features

* Read and analyze documents (PDF, DOCX, TXT)
* Search for keywords in your documents
* Summarize content
* Export results to CSV or PDF

---

### Installation

#### 1. Clone the repository

#### 2. Install required Python packages

```bash
pip install -r requirements.txt
```

#### Optional: Use a virtual environment (recommended)

```bash
# Create a virtual environment
python -m venv myenv

# Activate the environment
# macOS/Linux
source myenv/bin/activate
# Windows
myenv\Scripts\activate

# Install dependencies inside the virtual environment
pip install -r requirements.txt
```

---

### 3. Prepare your documents

* Place all files you want the bot to read in the `data/` folder
* Supported file formats: **PDF, DOCX, TXT**

---

### 4. Run the Chat Bot

```bash
python main.py
```
