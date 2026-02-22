# 📝 FastAPI Note Management System with AWS RDS & Railway

A professional Full-Stack CRUD application built with **FastAPI**, using **Amazon AWS RDS (PostgreSQL)** for cloud storage and **Railway** for seamless deployment.

🔗 **Live Demo:** [https://rdsdemo-production.up.railway.app/](https://rdsdemo-production.up.railway.app/)

## 🚀 Features

- **Cloud Infrastructure:** Fully integrated with **Amazon RDS (PostgreSQL)**.
- **Full-Stack Functionality:** Includes a responsive Frontend to interact with the API.
- **Automated Metadata:** Notes automatically include **Author** ("Baris") and **Server-side Timestamps**.
- **CRUD Operations:** Create, Read, Update, and Delete notes in real-time.
- **ORM & Validation:** Structured with SQLAlchemy and Pydantic for data integrity.
- **Interactive API Docs:** Built-in Swagger UI and Redoc.

## 🛠️ Tech Stack

- **Backend:** FastAPI (Python 3.9+)
- **Database:** PostgreSQL (AWS RDS)
- **Frontend:** HTML5, CSS3, JavaScript (Fetch API)
- **Deployment:** Railway
- **ORM:** SQLAlchemy

## 📋 API Endpoints

| Method   | Endpoint      | Description                      |
| :------- | :------------ | :------------------------------- |
| `GET`    | `/`           | Serves the Frontend (index.html) |
| `GET`    | `/notes`      | Fetch all notes from AWS RDS     |
| `POST`   | `/notes`      | Create a new note                |
| `PUT`    | `/notes/{id}` | Update an existing note by ID    |
| `DELETE` | `/notes/{id}` | Delete a note from cloud storage |

## ⚙️ Setup & Installation

1. **Clone the repository:**

```bash
git clone [https://github.com/BozgunBer-2506/RDS_demo.git](https://github.com/BozgunBer-2506/RDS_demo.git)
cd RDS_demo

```

2. **Create a Virtual Environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```

3. **Install Dependencies:**

```bash
pip install -r requirements.txt

```

4. **Environment Variables:**
   Create a `.env` file and add your AWS RDS connection string:

```env
DATABASE_URL=postgresql://user:password@host:port/dbname

```

5. **Run Locally:**

```bash
uvicorn main:app --reload

```

## 🌐 Deployment (Railway)

This project is configured for **Railway**. To deploy your own:

1. Connect your GitHub repository to Railway.
2. Add the `DATABASE_URL` to the **Variables** tab in Railway.
3. Railway will automatically detect the `requirements.txt` and start the server.

---

Developed by **The_Bozgun** as a Cloud Database Demo. Feb 2026
