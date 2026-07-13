# Executive Gantt Chart Generator

A VBA macro that builds a polished, executive‑grade Gantt chart for project initiation tasks.  
Designed for clarity, alignment, and presentation quality — ideal for management reporting.

---

## 📊 Features
- Clean spacing and alignment (including Project Sponsor offset)
- High‑contrast color palette for readability
- External predecessor labels
- Professional typography (Segoe UI / Calibri)
- Error handling and success confirmation

---

## 🧠 How It Works
The macro reads task data from a worksheet named **GanttData** and automatically generates a stacked‑bar Gantt chart showing:
- Task names and durations  
- Predecessor relationships  
- Sequential week numbering  

---

## ⚙️ Usage
1. Open Excel and enable the **Developer** tab.  
2. Insert a new module and paste the VBA code from [`CreateGanttChart_CEOView.vba`](./CreateGanttChart_CEOView.vba).  
3. Prepare your worksheet with columns:
   - **A:** Task Name  
   - **B:** Start Week  
   - **C:** Duration  
   - **D:** Predecessor(s)  
4. Run the macro to generate the chart.

---

## 🧩 Example Output
The chart displays tasks in reverse order, with external labels showing predecessor links and a clean axis layout for executive readability.

---

## 🧑‍💼 Author
**Matthew Woytych**  
Master of Science in Accountancy – CSU Sacramento  
Staff Accountant | Project Management | Data Analysis  

---

## 🌐 GitHub Pages
View the project landing page:  
👉 [https://mwoytych.github.io/Gantt‑Chart](https://mwoytych.github.io/Gantt-Chart)
