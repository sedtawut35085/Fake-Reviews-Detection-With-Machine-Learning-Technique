คู่มือและวิธีการ
- เตรียม jupyter notebook โดย download anaconda มาเพื่อใช้ jupyter notebook
- ลง python version 3.9
- ทำการลง library ต่างๆให้เรียบร้อย
- ใช้คำสั่ง pip3 install scikt-learn numpy seaborn pandas csv string nltk matplotlib

วีธีการ
- สามารถรันแต่ละเซลล์ตามขึ้นตอนไล่ลงจากขึ้นลงมาจนสิ้นสุดได้เลยจะประกอบไปด้วยการ นำ dataset มาใช้งาน การทำ data preprocessing feature extraction การ train ตัว model ทั้ง 4 model รวมถึงการประเมินผล
- โดยต้องทำการใส่ path ที่ตามกับ dataset ทั้งสองคือ yelp_academic_dataset_business.json และ yelp_academic_dataset_review.json ตามไฟล์ที่แนบไปให้
- สามารถเปลี่ยนการทอลองได้โดยกำหนดตรงหัวข้อ Data preprocessing and feature extraction โดย bigram ต้องตั้งเป็น ngram_range=(2,2) และ trigram ตั้งเป็น ngram_range=(3,3)
- สามารถโชว์ positive_comments และ negative_comments ในหัวข้อ Show positive_comments and negative_comments เป็นการแสดงคำที่อยู่ใน positive_comments และ negative_comments


