# Personal MLOps & Data Science Template

My personal starter template for machine learning and data science projects—designed to easily go from notebook exploration to API deployment and Streamlit UI testing.

---

> ⚠️ **Setup Reminder (`.gitignore`)**
> Open your `.gitignore` and **uncomment the `#`** in the data section (e.g., `# data/raw/*` $\rightarrow$ `data/raw/*`) before adding any files so raw or large datasets aren't accidentally pushed to GitHub.

---

## 🚀 Quick Start

### 1. Environment Setup

```bash
# Clone this template for a new project
git clone <your-new-repo-url>
cd <your-new-repo-name>

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt