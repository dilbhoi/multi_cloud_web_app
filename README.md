# 🌐 Task 3 – Multi-Cloud Web Application

## 📌 Objective
To build and deploy a simple multi-cloud architecture with:
- **Frontend hosted on AWS S3**
- **Backend API hosted on Google Cloud Run**

This task demonstrates cloud interoperability by connecting services deployed on different cloud platforms.

---

## 🧱 Project Architecture


- The frontend contains a static HTML file hosted using AWS S3 Static Website Hosting.
- The backend is a simple HTTP API deployed as a Docker container on Google Cloud Run.
- The frontend calls the backend API using `fetch()` and displays the response.

---

## 🔗 Live Links

- **Frontend (S3 Website):**  
  [http://dil-multicloud-frontend.s3-website.eu-north-1.amazonaws.com](http://dil-multicloud-frontend.s3-website.eu-north-1.amazonaws.com)

- **Backend (Cloud Run API):**  
  [https://multicloud-api-670260642439.europe-north2.run.app](https://multicloud-api-670260642439.europe-north2.run.app)

---

## 🛠️ Technologies Used

- **HTML + JS** for frontend UI
- **AWS S3** for static website hosting
- **Google Cloud Run** to deploy a containerized backend API
- **JavaScript Fetch API** to connect frontend with backend

---

## 📸 Screenshots

> Add the following screenshots:
- Deployed S3 bucket with static hosting URL
- Cloud Run dashboard showing deployed container
- Working web app with response output

---

## ✍️ How to Run

1. Clone or download this repository.
2. Open `index.html` in browser (or deploy to S3).
3. Click the "Call Backend" button.
4. You’ll see a response from the backend API.

---

## 🙌 Author

**Dil Bhoi**  
Intern @ Cloud Computing  
DY Patil International University, Pune

---

