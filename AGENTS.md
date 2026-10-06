# AGENTS.md

- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`（例如：`conda run -n iem_python python ...`）。

Greenfield code-storage repo. Only `README.md`, `LICENSE`, and a Python `.gitignore` exist. Single `Initial commit`, no source code yet.

- No build, test, lint, typecheck, or CI config exists. Do not assume any toolchain; check what gets added before running commands.
- Root `.gitignore` is the Python template (venv, `__pycache__`, `.env`, etc.). Keep it; extend only when a new stack needs it.
- `README.md` is a one-line stub (`储存程式碼的`). Update it when a real project layout lands.
- No `AGENTS.md` predecessors, workspace config, or `opencode.json` to reconcile.  
