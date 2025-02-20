

# Django HTOP App 🚀

A simple Django application that serves an `/htop` endpoint, displaying system details like:

- **Your Full Name**
- **System Username**
- **Server Time (IST)**
- **`top` command output (system processes)**

---

## 🔧 Setup Instructions

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/django-htop.git
cd django-htop
```

### **2️⃣ Create a Virtual Environment & Install Dependencies**
```sh
python -m venv venv   # Create a virtual environment
source venv/bin/activate  # Activate it (use venv\Scripts\activate on Windows)
pip install -r requirements.txt  # Install dependencies
```

### **3️⃣ Run Database Migrations**
```sh
python manage.py migrate
```

### **4️⃣ Start the Server**
```sh
python manage.py runserver 0.0.0.0:8000
```
> Make sure to **expose port 8000** in GitHub Codespaces.

---

## 🌐 Access the `/htop` Endpoint
Open the following URL in your browser:
```
https://refactored-sniffle-7v74pqw4v6v6frjvj-8000.app.github.dev/htop/
```
If using GitHub Codespaces, access the public URL it provides.

