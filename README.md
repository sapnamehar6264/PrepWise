# PrepWise – AI Mock Interview Platform

PrepWise is an AI-powered mock interview web application built to help users practice job interviews in a realistic and structured environment. The platform simulates interview sessions, records responses, and provides detailed AI-generated feedback to help users improve their communication, technical skills, and confidence.

This project is designed with a strong focus on **clean UI/UX**, **smooth interview flow**, and **practical AI integration**.

---

## 🚧 Project Status

This project is currently under active development. 
The core interview flow, authentication, and AI integration are functional. 
Multi-turn conversational refinement and response chaining improvements are in progress.

## 🚀 Features

- 🔐 **Authentication** – Secure sign up and login using Firebase
- 🎤 **AI Mock Interviews** – Role-based AI interview sessions with interactive question flow
- 🧠 **Smart Question Generation** – AI-generated interview questions based on selected role and skills
- 📊 **AI Feedback & Scoring** – Detailed feedback with category-wise scoring
- 📋 **Interview Dashboard** – View, manage, and track all interview attempts
- 🔁 **Retake Interviews** – Practice interviews multiple times for improvement
- 📱 **Responsive Design** – Works smoothly on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, TypeScript  
- **Styling:** Tailwind CSS  
- **Authentication & Database:** Firebase  
- **AI Services:** Vapi AI, Google Gemini  
- **UI Components:** shadcn/ui  
- **Validation:** Zod  

---

## 🧩 Project Structure

app/
├─ auth/
├─ interview/
├─ api/
├─ dashboard/
lib/
├─ actions/
├─ utils.ts
constants/
public/

---

## ⚙️ Setup & Installation

### Prerequisites
Make sure you have:
- Node.js (v18 or later recommended)
- npm or yarn
- Git

### Clone the Repository
```bash
git clone https://github.com/sapnamehar6264/PrepWise.git
cd PrepWise
```
### Install Dependencies
```bash
npm install
```

### Environment Variables
```
Create a .env.local file in the root directory:
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

### Run the Project
```bash
npm run dev
```
## ⚠️ Current Limitations

- Ongoing improvements in multi-turn AI conversation handling
- Voice workflow optimization in progress
- Performance tuning for low-latency response delivery

## 📈 Future Enhancements
- Real-time voice emotion analysis
- Resume-based interview personalization
- Interview performance analytics dashboard
- Multi-language interview support
- Company-specific interview simulations

## 👩‍💻 Author

**Sapna Mehar** - IT Student | Frontend Developer | UI/UX Designer

GitHub: https://github.com/sapnamehar6264


