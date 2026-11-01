# FinSight AI

## 🎯 Project Objective
FinSight AI is a Financial Intelligence and Business Decision Support System designed for a university exhibition. It provides financial analytics, sales intelligence, predictive forecasting, risk analysis, AI-powered business insights, and business decision simulation to support business decision making.

## 🛠️ Technology Stack
*   **Language:** Python
*   **Framework:** Streamlit
*   **Data Handling:** Pandas, NumPy, SQLAlchemy
*   **Visualization:** Plotly
*   **ML/AI:** Scikit-learn, Gemini API (via python-dotenv)
*   **Testing:** Pytest

## 📂 Directory Structure
The project uses a modular, scalable structure:
- `app.py`: Main Streamlit entry point.
- `pages/`: Individual Streamlit pages for specific intelligence modules (e.g., `sales_intelligence.py`, `financial_intelligence.py`).
- `src/`: Core logic modules (e.g., `data_cleaning.py`, `forecasting.py`, `insight_engine.py`).
- `data/`: Storage for raw and processed datasets.
- `database/`: Database interaction logic (`database.py`).
- `tests/`: Unit and integration tests.
- `assets/`: Static files (CSS, images).

## 🚀 Setup Instructions
1.  Clone the repository and navigate to the `FinSight-AI/` directory.
2.  Create and activate a virtual environment: `python -m venv .venv` then `.\.venv\Scripts\Activate.ps1`.
3.  Install dependencies: `pip install -r requirements.txt`.
4.  Create a `.env` file in the root directory and set your API key: `GEMINI_API_KEY="your_key_here"`.
5.  Run the application: `streamlit run app.py`.

## 🧑‍💻 Author
Khushwant Singh

*Note: This scaffolding is complete. The full application implementation will follow.*