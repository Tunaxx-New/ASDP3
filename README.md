# 🧠 AI-Based Scientific Format Analysis Tool

This project is a scientific software solution that uses artificial intelligence (AI) to classify format for papers for research and improvement purposes. It follows best practices in reproducibility, version control, CI/CD, and containerized deployment, making it suitable for scientific and academic environments.

---

## 🚀 Project Features

- ✅ Deep learning-based image classification
- ✅ Interactive prototyping
- ✅ Reproducible environments using **Docker**
- ✅ CI/CD with **GitHub Actions**
- ✅ Large file support via **Git LFS**


---

## 📦 Installation

### Using pip

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### Or using conda

```bash
conda env create -f environment.yml
conda activate ai-project
```

---

## 🧪 Running the Project

npm run dev

## 🧪 Testing and Linting

```bash
pytest tests/
flake8 src/
```

---

## 🐳 Run with Docker

```bash
docker build -t ai-scientific-tool .
docker run -it --rm ai-scientific-tool
```

---

## 🔁 CI/CD Pipeline

The project uses **GitHub Actions** for:
- Linting (`flake8`)
- Running tests (`pytest`)
- Docker build validation

All workflows are defined in `.github/workflows/`.



---

## 📂 Large File Support

Use **Git LFS** for managing datasets and model weights:




---

## 🙌 Contributors

- Arystan Zhulumbetov
- Alibek Aimenov
- Alen Tassymov
- Nikita Mordvintsev

## 🌐 References

- PyTorch: https://pytorch.org  
- MLflow: https://mlflow.org  
- GitHub Actions: https://docs.github.com/en/actions  
- Docker: https://docker.com  
