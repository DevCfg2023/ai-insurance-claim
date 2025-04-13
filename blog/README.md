# 🚀 ai-insurance-claim - Smart Insurance Claim Processor

> 🤖 A multimodal AI system to automate insurance claim assessments using **gemini-2.0-flash**, **OpenCV**, and **SQLite**.

---

## 🧠 What It Does

This project processes real-world insurance claims using advanced AI tools. It can handle:

- 📸 **Images** of damage
- 🎥 **Videos** showing walkthroughs (via frame extraction)
- 🎤 **Voice notes**, transcribed automatically
- 📝 **Text**
  
Outputs include:

- ✅ Damage type and severity
- 💰 Estimated cost
- 📬 Suggested next steps
- 🗃️ Claim summary saved to database

---
## ✅ Benefits of the Smart Insurance Claim Processor
🧠 1. Intelligent Automation
Reduces manual work by automatically analyzing multimedia inputs (images, videos, audio).

Uses advanced AI (gemini-2.0-flash) for deep understanding and summarization.

⚡ 2. Faster Claim Processing
Cuts down turnaround time from days to minutes by instantly processing claims.

Automatically flags simple vs. complex cases, routing them appropriately.

👨‍💼 3. Enhanced Customer Experience
Sends personalized updates to users within minutes.

Reduces frustration by clearly communicating findings and next steps.

🕵️‍♂️ 4. Built-in Fraud Detection
Compares input against historical data to flag anomalies or suspicious claims.

Detects inconsistencies across images, audio, and descriptions.

📊 5. Rich, Multimodal Insights
Combines data from voice, video, images, and text for accurate decision-making.

Frames from video and transcribed audio are summarized to provide a full picture.

🧠 6. Agent-Based Flexibility
Human-in-the-loop option for edge cases.

Can scale up with LangChain or CrewAI for intelligent task routing and execution.

💾 7. Easily Extendable
Add a web UI (Gradio / Streamlit) for uploads.

Plug in cloud databases or external APIs.

Integrate with CRM or customer support platforms.

💸 8. Cost-Saving for Insurers
Less dependency on manual adjusters.

Reduces claim fraud, misreporting, and processing overhead.

---

## 🌟 Key Features

- 🔍 gemini-2.0-flash for **multimodal understanding**
- 🎞️ OpenCV for **frame sampling from videos**
- 🗂️ SQLite for **persistent claim tracking**

---

## 🎯 Use Case

"A customer uploads a video walkthrough of storm damage, a few photos of their roof, and a voice note explaining what happened. The system processes the inputs, summarizes the situation, estimates costs, and prepares a ready-to-send response."
Input Gathering

"Accepts user-uploaded images of damage, voice messages, videos, and text descriptions."

---

| Tool       |Purpose |
|------------|---------|
| 🧠 gemini-2.0-flash  | `Multimodal analysis (text + image + video)` |
| 📸 PIL / OpenCV	  | `Handle and extract frames` |
| 🗃️ SQLite  | `Store claims, statuses, and context` |

---

🚀 QuickStart
git clone https://github.com/DevCfg2023/ai-insurance-claim.git

---

▶️ Run
jupyter notebook insurance-claim.ipynb

---
## 🖼️ Example Input & Flow

| Input Type | Example |
|------------|---------|
| 🖼️ Image   | `images/roof_damage.jpg` |
| 🎥 Video   | `videos/claim_video.mp4` |
| 🎤 Audio   | `audio/damage_note.wav` |
| 📝 Text    | "The storm knocked over the power lines and damaged the garage roof." |

➡️ **Output**:
{
  "summary": "Severe roof and garage damage due to storm. Estimated repair cost: ₹45,000.",
  "status": "Pending human review",
  "recommended_action": "Send adjuster on-site within 48 hours."
}


## 📬 Contact
   - navurinv@gmail.com

## 📄 License

