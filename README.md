

### 📄 `README.md`

```markdown
# 📖 PDF to Audio Converter (Python)

This is a Python script that converts a **PDF file into speech**, allowing users to listen to the contents of any PDF document using text-to-speech technology.

---

## 🚀 Features

- Opens a file dialog to select a PDF file.
- Reads the entire PDF using `PyPDF2`.
- Converts the text to speech using `pyttsx3`.
- Works offline and doesn't require internet access.

---

## 🛠 Requirements

Make sure the following Python packages are installed:

- `pyttsx3`
- `PyPDF2`
- `tkinter` (usually comes pre-installed with Python)

### 📦 Install dependencies:

```bash
pip install pyttsx3 PyPDF2
```

---

## 📂 How to Use

1. Clone or download this repository.
2. Run the Python script:

```bash
python main.py
```

3. A file selection dialog will appear. Choose a PDF file.
4. The script will begin reading the PDF aloud.

---

## 📝 Notes

- Only works with **text-based PDFs**. Scanned images or handwritten text will not be read.
- Ensure your device has audio output enabled (speakers/headphones).
- You can modify the code to read specific pages or export the audio to a file.

---

## 📌 Example

- Launches a file dialog to pick a PDF.
- Extracts text from each page.
- Reads the text aloud using a built-in voice.
