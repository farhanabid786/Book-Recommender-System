
# 📚 Book Recommender System

An intelligent book recommendation system leveraging large language models (LLMs) and Python. This project transforms book descriptions into vector embeddings for precise content-based matching and provides features like text classification, sentiment analysis, and an interactive web application using Gradio.

## 🚀 Features

- **Text Data Cleaning:** Preprocess book descriptions for better model performance.
- **Semantic Vector Search:** Build a vector database for efficient similarity search to match user queries with book descriptions.
- **Zero-Shot Text Classification:** Classify books as "Fiction" or "Non-Fiction" using LLMs without labeled data.
- **Sentiment Analysis:** Extract emotions from text to enable sorting books by tone (suspenseful, joyful, sad, etc.).
- **Interactive Web Application:** Gradio-based interface allowing users to input queries and receive recommendations in real-time.

## 🧱 Project Structure

- `data-exploration.ipynb`: Data cleaning and exploration steps.
- `vector-search.ipynb`: Semantic search implementation and vector database creation.
- `text-classification.ipynb`: Zero-shot classification of book types.
- `sentiment-analysis.ipynb`: Sentiment analysis using LLMs.
- `gradio-dashboard.py`: Gradio web app for end-user interaction.

## ⚙️ Technologies Used

- Python 3.12.7
- NVIDIA API for LLM inference
- Langchain and langchain-community
- Transformers
- Gradio
- pandas, matplotlib, seaborn
- python-dotenv

## 📋 Installation

1. Clone the repository:
    ```bash
    [git clone https://github.com/yourusername/book-recommender-system.git
    cd book-recommender-system]

    (https://github.com/farhanabid786/Book-Recommender-System.git)
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory with your NVIDIA API Key:
    ```env
    NVIDIA_API_KEY=your_nvidia_api_key_here
    ```

## 📊 Dataset

The dataset can be downloaded from Kaggle. Instructions and the dataset link are provided in the repo.

## 🚀 Usage

Run the Gradio web application:
```bash
python gradio-dashboard.py
```

Upload your book dataset, ask natural language queries, and get recommendations instantly.

## 💡 Notes

- The system is optimized for semantic similarity queries.
- Zero-shot classification and sentiment analysis improve recommendation quality.
- NVIDIA API Key is required for LLM inference.

## 📄 License

MIT License

---

Made with ❤️ using Python and LLMs.
