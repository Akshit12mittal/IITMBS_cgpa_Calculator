# 📊 IITM BS CGPA Calculator  
### An **anonymous web app** to calculate **GPA & CGPA** for IIT Madras BS in Data Science & Applications learners.  
### No login, No data collection — just select your grades, and get your CGPA instantly.  
#### Link to Calculator: [IITM BS CGPA Calculator](https://akshit12mittal.github.io/IITMBS_cgpa_Calculator/)
##### Developed by: [Akshit Mittal](https://www.linkedin.com/in/akshit12mittal/)
---
## 🚀 Features  
- 🎯 Choose your current level → Foundation / Diploma / BSc Degree  
- 📚 Auto-loads all courses up to that level (including previous levels)  
- 📝 Select grade for each course (or keep **N/A** for not attempted yet)  
- 📈 Calculates:  
  - GPA per section (Foundation, Diploma Programming, Diploma Data Science, BSc)  
  - Special CGPA for **Diploma Projects**  
  - ✅ Final **Overall Aggregate CGPA**  
  - Total credits considered  
- 🔒 100% Anonymous → no login, no email, no tracking  
---
## 🧮 Grading Rules  
The calculator follows **absolute grading** (IITM official rules):  
| Grade | Points |
|-------|---------|
| S     | 10 |
| A     | 9 |
| B     | 8 |
| C     | 7 |
| D     | 6 |
| E     | 4 |
| U, WA, WQ | 0 |
| I, I_BOTH, I_OP | Excluded (no GPA until cleared) |
| NA    | Not attempted (ignored) |

📌 Pass criteria → **40/100 marks** minimum in each course.  

## 📐 CGPA Formula  
CGPA is calculated as a **weighted average of grade points**:  

$$\text{CGPA} = \frac{\sum ( \text{Credits of Course} \times \text{Grade Point of Course} )}{\sum (\text{Credits of All Attempted Courses})}$$

---
### Example:  
- Course 1: 4 credits, Grade = A (9 points) → $4 \times 9 = 36$  
- Course 2: 3 credits, Grade = B (8 points) → $3 \times 8 = 24$  
- Course 3: 2 credits, Grade = S (10 points) → $2 \times 10 = 20$  

$$\text{CGPA} = \frac{36 + 24 + 20}{4 + 3 + 2} = \frac{80}{9} = 8.89$$

---
📌 **Notes:**  
- Courses marked as **NA** are ignored.  
- **I (Incomplete)** courses are excluded until cleared.  
- **U, WA, WQ** count as **0 points** (failures reduce CGPA).  
---
Made with ❤️ for students  
Maintained by Akshit Mittal
