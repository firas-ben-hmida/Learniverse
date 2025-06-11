# 📚 Learniverse

**Learniverse** is a modern and secure e-learning platform that enhances online education with rich student-teacher interaction, strong security systems, and cross-platform accessibility. The platform includes a full-featured **Java desktop app**, a responsive **web-based admin panel**, and a **mobile app** developed using FlutterFlow.


---

## 🚀 Features

### 🔐 Authentication & Security
- Secure login/signup with password hashing
- **Two-Factor Authentication (2FA)**
- **OAuth integration** (Google & GitHub)
- Session tracking (device, IP, location)
- Remote session termination
- Password recovery via email verification
- Account lockout after multiple failed login attempts

### 🛠️ Admin Tools
- Admin dashboard to ban users based on complaints
- Complaint management system

### 🤖 Smart Complaint Module  
- Implementation of a **complaint resolution module** to assist users in resolving issues through an integrated **AI-powered chatbot**.  
- Offers powerful tools for administrators including **search, sorting, pagination, filtering, notifications**, and **statistical analysis** to efficiently manage complaints.  
- Developed **two AI models** using **Python (Anaconda)** and **Jupyter Notebook**:  
  - A **response suggestion model** to automatically propose replies based on complaint content  
  - A **prohibited language detection model** to flag and handle inappropriate or unacceptable words in submissions  
- Both models are integrated into the platform using a **Flask REST API**, allowing real-time interaction between the application and the AI services.

### 📚 Content & Engagement
- 📌 **Courses**: Users can browse and enroll in structured online courses  
- 🏆 **Competitions**: Periodic challenges to encourage learning through gamification  
- 💬 **Forums**: Discussion spaces for collaborative learning and help  
- 🎯 **Offers**: Display of educational offers and relevant opportunities  
- 📝 **Complaints**: Users can submit and track complaints, ensuring platform accountability 
---

## 🧠 Tech Stack

| Component         | Technology                                  |
|------------------|----------------------------------------------|
| 🖥️ Desktop App    | Java, JavaFX, XML, Java Classes              |
| 🌐 Web Platform   | Symfony (PHP), HTML, CSS, JavaScript         |
| 📱 Mobile App     | FlutterFlow (Flutter-based no-code builder) |
| 🗄️ Database       | MySQL                                        |

---

## 🧩 Project Structure

### 🔹 Desktop App
- Built with **JavaFX**
- Provides learning features, authentication,competitions and forums for users
![image](https://github.com/user-attachments/assets/77fa97a9-160b-4c10-a361-4f6ab4c9b94c)
![image](https://github.com/user-attachments/assets/4133d32e-6671-497f-963c-87e3ec3271b5)
![image](https://github.com/user-attachments/assets/603ce990-9e1a-4c83-b70b-ccfc0b928b63)
![image](https://github.com/user-attachments/assets/e71a422e-c0ca-41ab-b1cd-2e72e87db511)
![image](https://github.com/user-attachments/assets/f4fcf6e7-96ee-4dfb-9479-93b5e4d77334)
![image](https://github.com/user-attachments/assets/3f9420a6-ea71-4da6-8020-35948c1302b3)
![image](https://github.com/user-attachments/assets/c31cbf9d-e3a2-4906-8259-5b64f0e584b3)
![image](https://github.com/user-attachments/assets/f5233070-dd63-453e-95c6-4ecabb43f863)
![image](https://github.com/user-attachments/assets/971e9bc2-1d47-4ca3-8422-930d282375a6)
![image](https://github.com/user-attachments/assets/5b7aad06-45c5-4563-8555-6b737c4bca50)
![image](https://github.com/user-attachments/assets/deacff83-a14a-4059-a9a9-5ef826c8b042)
![image](https://github.com/user-attachments/assets/9d98b31e-5c14-4234-810a-511168b60805)
![image](https://github.com/user-attachments/assets/3108e44e-c963-4633-b3e1-e8cecd8a0a90)
![image](https://github.com/user-attachments/assets/dd3e9396-fed6-43f9-9b91-624bd2ffd44b)
![image](https://github.com/user-attachments/assets/6506dd67-11d7-4caa-b4cf-e5ed8db7ab19)

### 🔹 Web Platform
- Symfony-based backend with modern frontend stack
- Used mainly by administrators to manage users, complaints, and sessions
![image](https://github.com/user-attachments/assets/b2d4c44f-cfe5-4164-a3a9-d1960156c44a)
![image](https://github.com/user-attachments/assets/fbfde903-1443-4b29-bf4e-019914bff77c)
![image](https://github.com/user-attachments/assets/58bbf491-3ff8-4aa2-9d01-dd0d0e846870)
![image](https://github.com/user-attachments/assets/1932d921-323f-4f68-90d7-7f7e52517044)
![image](https://github.com/user-attachments/assets/59bd0a16-2751-4992-8b6c-26f90790a13f)
![image](https://github.com/user-attachments/assets/6b6e4b0d-2902-47b6-9c8c-d674d5017b15)
![image](https://github.com/user-attachments/assets/7891c522-c24a-4901-9043-af18a820c3ae)
![image](https://github.com/user-attachments/assets/ff51dd9b-a3a8-456e-808f-c81194385a3a)


### 🔹 Mobile App
- Built with **FlutterFlow**
![image](https://github.com/user-attachments/assets/128512b3-8e6b-41f0-b773-239df6be7099)
![image](https://github.com/user-attachments/assets/f3ba2df3-4d74-4a15-844a-8e7b89ece1bd)
![image](https://github.com/user-attachments/assets/ebf12a3e-f554-491c-a295-31080e327c08)
![image](https://github.com/user-attachments/assets/a70e7695-a815-4a50-9cf9-6ad4d29b1b7c)
![image](https://github.com/user-attachments/assets/32e09b71-be8f-457c-855d-ce98fd6651aa)
![image](https://github.com/user-attachments/assets/7e920fc6-1893-4a84-89e2-1091eec7f15b)
![image](https://github.com/user-attachments/assets/873b84b9-4c2e-4e0a-a97e-a27f6cd1ff04)
![image](https://github.com/user-attachments/assets/4d8bb19d-0191-4eae-afa1-4aa4ced3ebcb)
![image](https://github.com/user-attachments/assets/27a0183e-2349-418f-b484-fac4c38e9e9e)
![image](https://github.com/user-attachments/assets/3b8d9c9a-7c20-45de-b56f-78e602b249cb)
![image](https://github.com/user-attachments/assets/de4359d0-0c59-4494-905d-6813d92da669)

---

## 📺 Demo

▶️ Watch the Learniverse demo video:  
👉 [View Demo](https://youtu.be/wXJ1rjzaVbQ)

---

## 📌 Project Status

✅ Core functionality completed  
🚧 Additional features and UI refinements in progress  
🧭 Planned features: notifications, real-time chat, course recommendations

---

## 🤝 Contributing

Interested in contributing? Fork the repo, open an issue, or submit a pull request. All contributions are welcome!

---
## 👤 Author

**Firas Ben Hmida**  
[GitHub Profile](https://github.com/firas-ben-hmida)

---



