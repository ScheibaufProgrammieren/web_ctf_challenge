# web_ctf_challenge
This is a custom web Capture-The-Flag (CTF) challenge built using **Python Flask**. Your mission is simple:

> 🚩 **Bypass login, gain admin access, and delete user `joe@fsec.local` to capture the flag!**

---

## 🎯 Objective

Players must:
- Find a hidden registration page
- Bypass normal login restrictions
- Escalate privileges to become **admin**
- Navigate to another user's profile
- Delete the target user to reveal the flag

---

## 🛠 Requirements

- Python 3.7+
- Flask

---

## 🚀 How to Run (Step-by-Step)

> 💡 No database required — everything is stored in memory.

### 
1. Clone or Download the zip file and extract it
2. open the terminal and go to the file location
3. Create a Virtual Environment (optional but recommended)
'''python -m venv venv'''
4.Activate it:
On Windows:
'''venv\Scripts\activate'''
On Mac/Linux:
'''source venv/bin/activate'''
5. Install Flask
'''pip install flask'''
6. Run the Application
'''python app.py'''
You’ll see something like:
 '''* Running on http://127.0.0.1:5000'''
7. Open It in Your Browser
Go to:
👉 http://localhost:5000

Then follow the challenge — starting at /welcome.
///////////////
🧠 Hints
Not all pages are linked... some are hidden

Check URLs like /registeration

Some profile pages change your session

Only admins can delete users

Deleting the right user wins the game
