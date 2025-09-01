# Campus_Flow-Exam-Seat-Planner-
**Collaborative Project by:**  
- Ayush Khaire (BT22CSD028)  
- Ashutosh Sahoo (BT22CSD062)  
- Kishor Zatale (BT22CSD010)  
- Vasu Parashar (BT22CSD021)


**Institute:** Indian Institute of Information Technology , Nagpur

  
## Overview
Campus Flow is a **product-based solution** designed to automate **exam seat allocation** in educational institutions.  
The system enhances efficiency and accuracy by assigning seats to students based on predefined criteria, optimizing classroom space, and minimizing manual intervention.

---

## Core Features
1. **Exam Management**
   - Create exams with metadata
   - Import student lists from Excel
   - Support multiple courses per exam
   - Automatic sorting by roll number

2. **Classroom Management**
   - Define layouts with rows and columns
   - Mark unavailable seats
   - Group classrooms by building/floor
   - Calculate classroom capacity

3. **Seating Plan Generation**
   - Advanced anti-cheating algorithm
   - Optimized student distribution
   - Real-time preview
   - Support multiple courses in a single exam

4. **Export & Publishing**
   - Export to Excel with color-coding
   - Professional formatting for printing
   - Track plan status (draft, finalized, published)
   - Master sheet with summary

---

## Technical Architecture
**Frontend:**  
- React with TypeScript  
- TailwindCSS for responsive design  
- Lucide React for icons  
- React Router, React Toastify, React Dropzone  

**Backend:**  
- Node.js with Express.js  
- MongoDB with Mongoose  
- XLSX.js for Excel operations  
- Multer for file uploads  

---

## Algorithm
- **Greedy Column-Alternating Approach** with forward checking and optimized course pairing  
- Alternates courses in adjacent columns to prevent cheating  
- Key optimizations: course pairing, forward checking, dynamic course rotation  

**Seat Allocation Steps:**  
1. Sort courses by size  
2. Calculate optimal course pairings  
3. Fill classrooms column by column  
4. Apply checkerboard pattern  
5. Adjust dynamically for remaining students  

---

## User Workflow
1. **Exam Setup:** Create exam, import student data  
2. **Seating Plan Generation:** Select classrooms, generate optimized plan  
3. **Plan Review:** Preview seating, manually adjust if needed  
4. **Finalization & Export:** Update status, export to Excel, print/share  

---

## Results
- The system efficiently generates seating plans that **prevent cheating** while **maximizing classroom utilization**, with structured storage in MongoDB and Excel export with color-coded visualization.
---



## Dataset
- Student roll numbers and names grouped by course. The full dataset cannot be made public as it contains institute data. A **sample dataset** has been uploaded for demonstration purposes.

---

## Future Enhancements
- Support accessibility requirements  
- Time-based constraints for multiple exam sessions  
- AI integration with OR-Tools CP-SAT solver  
- Machine learning for pattern detection in cheating  
- Predictive analytics for exam planning  
- Mobile app for students to find seats  
- Integrated attendance tracking and real-time updates

⚠️ Note: The "Automated Lecture Summarization" part of the project is not uploaded yet. It will be added soon.
