# 🏆 AI & Web Projects Portfolio

This repository contains three projects showcasing AI, Web Development, and Python-based applications:

1. **Automatic Traffic Law Violation Detection System**  
2. **Event Management System**  
3. **AI Quotation Generator**

---

**#1. Automatic Traffic Law Violation Detection System**
An AI-powered system that detects traffic violations from images or videos using **YOLOv8**. The system identifies violations such as missing helmets, red light violations, and over-speeding vehicles. Built with Python and Streamlit.
### Features
- Upload images (`JPG`, `PNG`) or videos (`MP4`, `MPEG4`) for traffic violation detection.
- Real-time detection using **YOLOv8**.
- Annotated output images showing detected objects and violations.
- Interactive Streamlit web interface.
- Customizable violation rules.
### Technologies Used
- Python 3.13  
- Streamlit  
- OpenCV  
- Ultralytics YOLOv8  
- Pandas  
### How to Run
```bash
git clone <repo-link>
cd Automatic-Traffic-Law-Violation-System
pip install -r requirements.txt
streamlit run app.py
```


**#2.  Event Management System**
## 📝 Overview
The Event Management System** is a web-based application designed to help event organizers manage events efficiently. It provides a clean and interactive dashboard for creating, editing, and managing events, as well as sending invitations to participants via CSV upload.
---
## ⚡ Features
- **Multi-role login system**:
  - **Admin**: Full control over all events and users.
  - **Organizer**: Can create and manage events they organize.
  - **Attendee**: Can view events they are invited to.
  - **Guest**: Can browse public events without login.  
- **Event creation & editing**: Create new events with details like name, date, time, location, and description.  
- **Invitation sending**: Upload CSV files of participants and send invitations via email.  
- **Dashboard interface**: View all events, track invitations, and manage event details.  
- **Responsive design**: Works on both desktop and mobile devices.
---
## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, JavaScript  
- **Other Tools**:  
  - CSV file handling for sending invitations  
  - File upload functionality for images or PDFs  
---
## 🚀 How to Use

1. Open the `index.html` file in a web browser.  
2. Login as **Admin**, **Organizer**, **Attendee**, or **Guest**.  
3. **Admin**: Manage all events and users.  
4. **Organizer**: Create new events and manage your events.  
5. **Attendee**: View events you are invited to.  
6. **Guest**: Browse public events.  
7. Upload participant emails via CSV and attach invitation PDFs or images.  
8. Send invitations and manage your events from the dashboard.


---


#3.  AI Quotation Generator

A **Python & Streamlit** application to generate professional quotations automatically with PDF output.
---
## Features
- Input **Company Information**: Name, email, phone  
- Input **Client Information**: Name, company, email  
- Add multiple **Quotation Items**:
  - Description, Quantity, MRP, Discount %, GST %  
- Automatic calculation of:
  - Subtotal, TDS deduction, Shipping, Grand Total  
- Generate **PDF quotation** with terms & conditions  
- Copyable **shareable link** for the quotation  
---
## Technologies Used
- Python 3.13  
- Streamlit  
- FPDF2  
- Pandas  
- Pyperclip  
---
## Installation & Setup
1. Clone the repository:
```bash
git clone <your-repo-link>
cd AI-Quotation-Generator
pip install -r requirements.txt
streamlit run app.py
```
## 📁 Project Structure

http://localhost:8501
