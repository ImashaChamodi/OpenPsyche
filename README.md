# 🧠 Open Psych – Mental Health Support Platform

**[Demo Video ▶️](https://youtu.be/rCa9TPuvQMY)**

Open Psych is a web-based mental health support application that connects individuals with licensed medical professionals for secure, real-time communication. Designed to offer a safe and confidential space, the platform helps users, particularly the younger generation, receive timely and judgment-free assistance for mental health concerns such as depression, anxiety, and stress.

---

## 🌟 Key Features

- ✅ **User Authentication**  
  Secure login for both patients and doctors.

- 📝 **Registration and Login**  
  Easy-to-use forms for user onboarding and secure access.

- 💬 **Real-Time Chat**  
  Patients can chat directly with doctors using secure WebSocket communication.

- 📂 **Message History**  
  Previous sessions are stored and can be reviewed by both patients and doctors.

- 👨‍⚕️ **Doctor Profiles**  
  Display qualifications and experience to help patients choose the right doctor.

- ✔️ **Data Validation**  
  Ensures user-entered data (form inputs, messages, etc.) is complete and well-structured.

- 🗃️ **Database Integration**  
  MongoDB used for storing chats, users, and medical professional records.

---

## 🏗 Architecture

The system uses a **client-server** model with **real-time communication** capabilities.

### 🧩 Technologies Used

- **Frontend**: Angular, HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (via Mongoose)  
- **Real-time Communication**: Socket.IO

### 🔄 Process Flow

1. The Angular client sends HTTP or WebSocket requests to the Node.js backend.
2. The backend handles logic, queries MongoDB, and returns data or messages.
3. Real-time chat is managed using **Socket.IO**, enabling instant communication.
4. MongoDB ensures secure and efficient storage of all user and message data.

---

## 📚 Project Goals

- Provide accessible and anonymous mental health support.
- Break stigma by offering confidential online therapy sessions.
- Allow young users to connect with professionals quickly and privately.
- Leverage modern tech (Angular + Node + Socket.IO) for a seamless experience.

---

## 🚀 Getting Started

### Clone the repository:

```bash
git clone https://github.com/ImashaChamodi/OpenPsyche.git
cd OpenPsyche
