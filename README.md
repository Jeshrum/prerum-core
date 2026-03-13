# Prerum Core - Trade Execution Infrastructure

Prerum Core is the foundational infrastructure for automated trade execution. it provides a robust system to convert trading signals into risk-controlled trades on MetaTrader 4 (MT4) and MetaTrader 5 (MT5) platforms.

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)

## 🌟 Features

- **Signal Parsing Engine**: Advanced logic to parse complex trading signals from various sources.
- **Risk Management**: Integrated risk controls to ensure safe trade execution.
- **Multi-Platform Support**: Native hooks for both MT4 and MT5 execution environments.
- **Developer Helper**: Unified CLI (`dev.py`) for managing local development services.
- **Modern Dashboard**: Real-time monitoring and control panel for active trade streams.

## 🚀 Tech Stack

- **Backend**: Python, FastAPI, SQLAlchemy
- **Frontend**: React, Vite, Tailwind CSS
- **Execution**: MetaTrader Integration
- **Database**: SQLite (Local)

## 📂 Project Structure

```text
/
├── backend/          # Signal parsing and risk engine
├── frontend/         # Control dashboard
├── src/              # Shared source components
├── scripts/          # Utility and diagnostic scripts
└── dev.py            # Development orchestration script
```

## 🛠️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/prerum-core.git
   ```

2. **Backend Setup**:
   ```bash
   pip install -r backend/requirements.txt
   cd backend
   uvicorn app.main:app --reload
   ```

3. **Frontend Setup**:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
