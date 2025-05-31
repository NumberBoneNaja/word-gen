# LSTM ทำนายคำถัดไป

โปรเจกต์นี้เป็นการพัฒนาโมเดล deep learning โดยใช้โครงข่าย Long Short-Term Memory (LSTM) เพื่อทำนายคำถัดไปในลำดับข้อความ จุดประสงค์เพื่อประเมินว่าโครงสร้าง LSTM สามารถจับความสัมพันธ์เชิงลำดับของข้อมูลภาษาธรรมชาติได้ดีแค่ไหน 
## คุณสมบัติหลัก

- เตรียมข้อมูลข้อความ (Tokenization และ Encoding)
- ฝึกสอนโมเดล LSTM ด้วยข้อมูลลำดับข้อความ
- ทำนายคำถัดไปจากโมเดลที่ฝึกเสร็จแล้ว
- ประเมินผลการทำงานของโมเดลในงานประมวลผลภาษา

## ชุดข้อมูล

สามารถใช้ชุดข้อมูลข้อความใดก็ได้ที่เหมาะกับการทำ Language Modeling เช่น

- [Dataset](https://www.kaggle.com/datasets/ashishpandey2062/next-word-predictor-text-generator-dataset)
- [โค้ดตั้งต้น](https://www.kaggle.com/code/kirollosashraf/next-word-predictor-by-lstm)
