🌍ImpactHub<br>
🚀 Bridging NGOs & Students Through Technology

Impact Hub is a platform that connects NGOs facing real-world social challenges with students capable of building technology-driven solutions.

Many NGOs still rely on traditional paperwork and outdated systems. Impact Hub provides a digital bridge where NGOs can post their problems, and students can contribute innovative tech-based solutions. If a student's solution is successfully implemented, the NGO can issue a blockchain-verified certificate as recognition.

🏆 Hackathon Project<br>
📍 Built during our first hackathon<br>
🗓 7th Feb – 9th Feb 2026<br>
🏛 Anna Auditorium, VIT Vellore (Main Campus)<br>
👥 Team of 3 members- Lohith, Aravind and Madhav <br>

This project was developed based on our idea, with fully AI-assisted code generation to accelerate development.

💡 Problem Statement<br>
•	NGOs still rely heavily on paperwork.<br>
•	Lack of digital transformation in solving social problems.<br>
•	Students struggle to find real-world projects to strengthen their resumes.<br>
•	No transparent recognition system for impactful student contributions.<br>

🎯 Solution<br>
Impact Hub enables:<br>
✅ NGOs to post social challenges<br>
✅ Students to propose technical solutions<br>
✅ Transparent collaboration between NGOs and students<br>
✅ Blockchain-based certificate issuance upon successful implementation<br>

🛠 Tech Stack

Frontend<br>
•	HTML<br>
•	CSS<br>
•	JavaScript<br>

Backend<br>
•	Flask<br>
•	SQL Database<br>

Blockchain<br>
•	Smart contract-based certificate validation

✨ Core Features (Current Version)<br>
•	NGO & Student Registration/Login<br>
•	Role-based Dashboard Redirection<br>
•	Problem Posting System (NGO)<br>
•	Solution Submission (Student)<br>
•	Solution can be viewed by NGO<br>
•	Blockchain-based Certificate Concept<br>
•	Full Stack Authentication System

📂 Project Status<br>
⚠ The project is not fully completed.<br>
We have to worki on the following areas :<br>
•  Improving UI/UX<br>
•  Enhancing database structure<br>
•  Implementing full blockchain integration<br>
•  Adding new features to enhance user interface<br>
•  Deployment<br>

⚙ How to Run Locally<br>
Follow the steps below to run the ImpactHub project on your system.

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Madhav1303/ImpactHub.git
cd ImpactHub
```

---

## 2️⃣ Backend Setup (Flask)

### Step 1: Go to Backend Folder

```bash<br>
cd BACKEND
```

---

### Step 2: Create Virtual Environment (Recommended)

#### ▶ On Windows
```bash
python -m venv venv
venv\Scripts\activate
```


### Step 3: Install Required Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not present, install manually:

```bash
pip install flask flask-cors
```

(Add other dependencies if required.)

---

### Step 4: Run the Backend Server

```bash
python main.py
```

After running this, you should see something like:

```
Running on http://127.0.0.1:5000/
```

Your backend API is now running locally.

---

## 3️⃣ Frontend Setup

Open a new terminal (keep backend running).

Go back to project root:

```bash
cd ..
```

Then go to frontend folder (if exists):

```bash
cd FRONTEND
```

---

### Option 1 (Recommended): Use VS Code Live Server

1. Open the FRONTEND folder in VS Code.
2. Right click on `index.html`
3. Click **Open with Live Server**

---

### Option 2: Open Directly in Browser

Simply double click:

```
index.html
```

---

## 4️⃣ Verify Everything Works

- Backend running at:
  ```
  http://127.0.0.1:5000/
  ```

- Frontend should load in browser.
- Make sure API URLs in JS files match:
  ```
  http://127.0.0.1:5000/
  ```

---

## ⚠ Important Notes

- Keep backend terminal running while using frontend.
- If you get CORS error, ensure Flask-CORS is installed.
- If using database/blockchain features, configure them before running.
- Make sure Python is installed and added to PATH.

---

🎉 That's it! ImpactHub should now run locally on your system.

🌐 Deployment<br>
🚧 Not deployed yet.<br>
Deployment planned after feature stabilization.<br>

👨‍💻 Team<br>
This project was built by a team of three passionate developers during our first hackathon experience.<br>

📜 License<br>
This project is developed for educational and hackathon purposes.<br>

⭐ Why Impact Hub?<br>
Impact Hub is not just a project — it is a step toward digital transformation in the social sector, empowering students while enabling NGOs to modernize their workflows.<br>
