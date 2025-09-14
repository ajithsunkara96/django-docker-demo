# Django Docker Demo 🚀

This project demonstrates how to **containerize a Django application** using Docker for deployment in cloud or DevOps environments.

---

## 📌 Features

* Django-based web application
* Dockerfile for containerized deployment
* Runs on **Python 3** with `requirements.txt` dependencies
* Exposes the app on **port 8000**

---

## 🛠️ Tech Stack

* **Framework:** Django
* **Containerization:** Docker
* **Language:** Python 3
* **OS Base Image:** Ubuntu

---

## ⚙️ Setup Instructions

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/ajithsunkara96/django-docker-demo.git](https://github.com/ajithsunkara96/django-docker-demo.git)
    cd django-docker-demo
    ```

2.  **Build the Docker Image**
    ```bash
    docker build -t django-docker-demo .
    ```

3.  **Run the Container**
    ```bash
    docker run -p 8000:8000 django-docker-demo
    ```

---

### 🔍 Verification

Once running, open your browser and go to:
👉 `http://localhost:8000`

---

### 📚 Learning Outcome

This repo demonstrates how to:

* Containerize a Django app
* Use Docker for consistent deployment
* Prepare applications for cloud-native or DevOps environments

---

✍️ **Author:** Venkata Ajith Sunkara
