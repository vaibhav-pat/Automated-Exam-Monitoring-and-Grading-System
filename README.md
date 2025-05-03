# Automated Exam Monitoring and Grading System

This project aims to automate the **invigilation** and **grading** processes of online examinations using **Computer Vision** and **Machine Learning** techniques. It enhances exam integrity while minimizing manual efforts involved in supervision and answer evaluation.

---

## Features

1. **Real-time Monitoring**  
   Monitors webcam feed during the exam to detect suspicious behavior.

2. **Face Detection and Tracking**  
   Ensures the continuous presence of the candidate using facial recognition.

3. **Cheating Detection**  
   Detects and flags activities such as:
   - Presence of multiple people
   - Use of mobile phones
   - Frequent or unusual head movements

4. **Automated Grading**  
   - Automatically evaluates Multiple Choice Questions (MCQs)
   - Uses NLP techniques for grading descriptive answers

5. **Result Generation**  
   Generates detailed performance reports including scores, feedback, and flagged incidents.

6. **Logs and Reports**  
   Maintains logs of exam sessions and records of any suspected cheating behavior.

---

## Technologies Used

### Frontend
- HTML/CSS
- JavaScript 

### Backend and Machine Learning
- **Language**: Python  
- **Framework**: Flask / Django 
- **Libraries**:
  - OpenCV
  - TensorFlow / PyTorch
  - scikit-learn

### Database
- SQLite / MySQL / Firebase 

### Tools & Platforms
- Git & GitHub
- Jupyter Notebook
- Visual Studio Code

---

## Project Structure 
```plaintext
.
├── README.md
├── SRS.doc
└── use_cases
    ├── Monitor Exam Session use case.png
    ├── TakeOnlineExam_Usecase.png
    └── evaluate_and_grade_exam_uc.png
