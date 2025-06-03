
# 📄 PDF Summarizer Using HuggingFace Transformers (Colab-Compatible)

This project allows you to upload any PDF document, extract its content, split it into manageable chunks, and generate a concise summary using a transformer-based model (`facebook/bart-large-cnn`) from Hugging Face.

---

## 🚀 Features

- 📤 Upload any PDF file from your local machine.
- 📖 Extracts and summarizes up to the first 10 pages.
- ✂️ Automatically splits large text into optimal chunks.
- 🧠 Generates high-quality summaries using a pretrained BART model.
- 🧾 Easily extendable to save summaries or integrate other models.

---

## 🔧 Dependencies

Run this in Google Colab. Required Python packages:

```bash
pip install transformers pymupdf
```

---

## ▶️ How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Run the code cell to install dependencies and upload your PDF.
3. Wait for the summary to be printed after automatic extraction and processing.

---

## 📁 Files

- `RFP_summarization.ipynb` – Main Colab notebook that runs the end-to-end summarization.
- `README.md` – Project overview and usage instructions.

---

## 🧠 Model Details

- **Model:** `facebook/bart-large-cnn`
- **Task:** Summarization
- **Max Length per Chunk:** 1000 characters
- **Summary Length:** Between 50–150 tokens per chunk

---

## 🛠️ Future Enhancements

- Add support for saving summaries as `.txt` or `.docx`.
- Enable user-defined page limits or summarization lengths.
- Support longer PDFs with sliding window or batch processing.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
