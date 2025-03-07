# 🗃️ Use Case Generator

## 📌 Project Description

**Use Case Generator** is a Django-based web application designed to assist software engineering teams in generating **comprehensive and structured use case diagrams and descriptions** for their projects.

This tool helps project managers and developers by automating the creation of **standard use cases** based on minimal inputs.

### Key Features
- **User Authentication** (Login/Signup)
- **Storage of Generated Use Cases per User**
- **Clean and User-Friendly Interface**
- **Integration with Ivis Labs API for High-Quality Use Case Generation**

---

## 🛠️ Prerequisites

Ensure you have the following installed on your system:
- Python **3.8+**
- **pip** (Python package manager)
- **virtualenv** (for creating virtual environments)

---

## 🚀 Setup and Running the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/use-case-generator.git
cd use-case-generator
```

---

### Step 2: Initialize a Virtual Environment

#### On macOS/Linux
```bash
python -m venv venv
source venv/bin/activate
```

#### On Windows
```bash
python -m venv venv
venv\Scripts\activate
```

---

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Step 4: Set Up Environment Variables

Create a `.env` file in the **root directory** and add your **Ivis Labs API Key** in the following format:

```
IVIS_LABS_API_KEY=YOUR_API_KEY
```

---

### Step 5: Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### Step 6: Run the Development Server

```bash
python manage.py runserver
```

---

### Step 7: Access the Application

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 👥 Contributors

| Name | USN |
|---|---|
| Muskan Thakur | 4NI22CS127 |
| Naga Keerti Krith Thimmapuram | 4NI22CS129 |
| Nagashree S | 4NI22CS130 |
| Nagashreya S G | 4NI22CS131 |
| Nagaveni T R | 4NI23CS417 |



