# Breast-Cancer-Logistic-Regression

Lab: การสร้างโมเดลจำแนกมะเร็งเต้านมด้วย Logistic Regression

โปรเจกต์นี้เป็นการจำลองการสร้างโมเดล Machine Learning เพื่อจำแนกประเภทของมะเร็งเต้านมด้วย Logistic Regression และทำการปรับจูน Hyperparameter ด้วย GridSearchCV

Topics: `python`, `machine-learning`, `data-analysis`, `logistic-regression`, `breast-cancer-classification`, `hyperparameter-tuning`

## Folder Structure
- `data/`: ไฟล์ข้อมูลต้นฉบับ 
- `notebooks/`: ไฟล์การทดลอง Jupyter Notebook (`Logistic_Regression_Breast_Cancer.ipynb`)
- `src/`: ไฟล์โค้ดโปรแกรมหลัก 
- `outputs/`: รูประหว่างการวิเคราะห์ข้อมูล โฟลเดอร์ที่จัดเตรียมไว้เผื่อเก็บโมเดลหรือผลลัพธ์

## Dataset Source
ชุดข้อมูล: Breast Cancer Wisconsin (Diagnostic) Dataset จาก Scikit-learn (`sklearn.datasets.load_breast_cancer`)

## Installation (วิธีการติดตั้ง)
1. Clone repository นี้:
   ```bash
   git clone [url-ของ-repository]
   cd breast-cancer-logistic-regression
   ```
2. สร้าง Virtual Environment (ถ้าต้องการ) และติดตั้ง Library ที่จำเป็น:
   ```bash
   pip install -r requirements.txt
   ```
*Note เพิ่มเติม: หากต้องการนำโมเดลไปพัฒนาต่อเพื่อประมวลผลบน GPU (เช่น Deep Learning) อาจต้องติดตั้ง CUDA เพิ่มเติม*

## Usage (วิธีใช้งาน)
เปิด Jupyter Notebook ที่อยู่ในโฟลเดอร์ `notebooks/` เพื่อรันการทดลองทีละขั้นตอน:
```bash
jupyter notebook notebooks/Logistic_Regression_Breast_Cancer.ipynb
```
