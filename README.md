# ai-resume-shortlisting-system
A Java-based resume parser using Apache PDFBox &amp; POI for text extraction, with keyword matching, dashboard visualization, and DB storage for efficient hiring.
# AI-Based Resume Shortlisting System

A Java + Spring Boot application for automating the process of resume shortlisting based on keyword matching.  
The system extracts text from PDF/DOCX resumes, compares them against job-specific keywords with weights, and visualizes the top-matched candidates in an admin dashboard.

---

## ✨ Features

- **Resume Parsing**: Extracts text from PDF and DOCX files using Apache PDFBox & Apache POI.
- **Keyword Matching**: Supports weighted keyword scoring and fuzzy matching.
- **Admin Dashboard**: HTML/CSS/JavaScript + Chart.js for visualizing candidate match scores.
- **Database Integration**: Stores candidates, resumes, job roles, and match scores in MySQL.
- **REST API**: Spring Boot-based endpoints for uploading resumes, creating jobs, and retrieving results.
- **File Storage**: Saves uploaded resumes to disk for reference.

---

## 🛠 Tech Stack

**Backend**
- Java 17
- Spring Boot (Web, JPA)
- MySQL
- Apache PDFBox
- Apache POI

**Frontend**
- HTML5, CSS3, JavaScript
- Chart.js

---

## 📂 Project Structure

