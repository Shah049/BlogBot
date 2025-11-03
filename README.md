# 🧠 AI Article & Blog Generation System  
### *(Gradio + Groq Llama 3.3 70B + Wikipedia Context + DOCX Export)*

An intelligent article and blog generation system powered by **Groq’s Llama 3.3 (70B)** model.  
This app allows users to generate full-length, high-quality articles or blog posts, optionally enriched with real-time contextual data from **Wikipedia**, and export the results directly to a `.docx` file — all through an interactive **Gradio** interface.

---

## 🚀 Features

✅ **Powered by Groq’s Llama 3.3 (70B)**  
Uses Groq’s ultra-fast **chat completions endpoint** for high-quality and low-latency text generation.

✅ **Optional Wikipedia Enrichment**  
Enhance your article context with verified public information from Wikipedia before generation.

✅ **DOCX Export**  
Easily download your generated article in professional format using **`python-docx`**.

✅ **Session History (Last 5 Articles)**  
Keeps a short memory of the last 5 generated articles for quick re-access or editing.

✅ **No .env Required**  
Simply set your `GROQ_API_KEY` directly in the code, or configure it using **Hugging Face Secrets** when deploying.

---

## 🧩 Tech Stack

| Component | Description |
|------------|-------------|
| **Model** | Groq Llama 3.3 70B (via `chat.completions` endpoint) |
| **Frontend** | Gradio Interface |
| **Backend** | Python + Requests |
| **Contextual Data** | Wikipedia (via `requests` + BeautifulSoup) |
| **Export** | python-docx |
| **Hosting (optional)** | Hugging Face Spaces |

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://huggingface.co/spaces/<your-username>/<your-space-name>
cd <your-space-name>
