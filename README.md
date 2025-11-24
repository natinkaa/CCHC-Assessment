## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:

1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.

## Setup & Run Guide

This guide explains how to install and locally run this Dash application.

---

### 1. Install Python 3.11

This project is configured to run with Python 3.11.

```bash
sudo apt install -y python3.11 python3.11-venv python3.11-dev
```

Verify installation:

```bash
python3.11 --version
```

Expected output:

```
Python 3.11.x
```

---

### 2. Create and Activate Virtual Environment

From the project root directory:

```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

You should now see `(.venv)` in your terminal prompt.

---

### 3. Install Application Dependencies

This project uses a dependency setup via `pyproject.toml`.

Install everything with:

```bash
pip install .
```

This will install:

- Dash
- NumPy 1.23.5
- pandas 1.5.3
- pandas-stubs 1.5.3.230203
- All required supporting packages

---

### 4. Running the App

Start the Dash server:

```bash
python main.py
```

The application runs on port 10030.

---

### 5. Accessing the App

This runs entirely on your local machine.

Open your browser and go to:

```
http://localhost:10030
```
