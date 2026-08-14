#  DC-Resource Intelligence (1st Place Winner - GISTDA Hackathon)

*🇹🇭 [คลิกที่นี่เพื่ออ่านเวอร์ชันภาษาไทย (Click here for Thai version)](#เวอร์ชันภาษาไทย-thai-version)*

**DC-Resource Intelligence** is an Environmental Early Warning System designed specifically for large-scale Data Centers. This project was awarded **1st Place** at the GISTDA Space Innovation Hackathon.

##  Live Demo
**[Launch Streamlit Dashboard](https://dc-resource-bcq6nwzamzt47jtz5xwyvy.streamlit.app)**

##  The Problem
Data Centers require massive amounts of energy and water for cooling (24/7). Existing monitoring systems are highly **Reactive** (only alerting when internal temperatures have already spiked), leading to server overloads, costly downtimes, and contract penalties.

##  The Solution (Proactive Prevention)
Instead of monitoring the "inside" of the building, our system monitors the "outside" using satellite data.
- **Global Data Source:** Connects directly to Google Earth Engine APIs for reliable, global-scale data.
- **Spatial Risk Map:** Calculates environmental risks using ECI/ESS Scores to filter and display critically hot areas in red.
- **Deep Dive & Action:** Analyzes Land Surface Temperature (LST) and Normalized Difference Water Index (NDWI) at the facility level, providing **Actionable Insights** (e.g., "Adjust cooling fan cycles 48 hours in advance").

##  High-Performance Hybrid Architecture
- **Data Core:** Google Earth Engine (Historical Data 2020-2025).
- **Backend Processing:** Python (Streamlit & Pandas) processes spatial risk data.
- **Frontend Rendering:** HTML5, JS, & SVG render graphs and maps directly on the client side for zero-latency interactions.

##  Repository Contents
- `dc_resource_nexus.py`: The main Streamlit Python application containing the dashboard logic, UI components, and data processing.
- `DC-Resource-Intelligence-Pitch-Deck.pdf`: The official presentation slides used during the hackathon pitch (originally created by Team "Moo Prieo").

---
---

# เวอร์ชันภาษาไทย (Thai Version)

**DC-Resource Intelligence** คือ "ระบบแจ้งเตือนภัยล่วงหน้าทางสิ่งแวดล้อมสำหรับศูนย์ข้อมูล (Data Center)" ซึ่งโปรเจกต์นี้ได้รับรางวัล **ชนะเลิศอันดับ 1 (1st Place)** จากงานแข่งขัน GISTDA Space Innovation Hackathon (ผลงานจากทีมหมูเปรี้ยว)

##  ลิงก์เข้าใช้งาน
**[เปิดใช้งาน Dashboard (Streamlit)](https://dc-resource-bcq6nwzamzt47jtz5xwyvy.streamlit.app)**

##  ปัญหา (The Problem)
เซิร์ฟเวอร์ใน Data Center ต้องใช้พลังงานและทรัพยากรน้ำมหาศาลในการระบายความร้อนตลอด 24 ชั่วโมง ท่ามกลางภาวะโลกร้อนที่ผันผวน ระบบเดิมมักจะเป็นแบบ **ตั้งรับ (Reactive)** คือเซนเซอร์ภายในจะแจ้งเตือนก็ต่อเมื่ออุณหภูมิพุ่งสูงเกินเกณฑ์ไปแล้ว ส่งผลให้ระบบหล่อเย็นทำงานหนักเกินกำลัง เกิด Downtime และความเสียหายทางธุรกิจระดับหลักล้านบาท

##  ทางออก (The Solution)
เปลี่ยนกระบวนการทำงานจากแค่การมอนิเตอร์ "ภายในอาคาร" เป็นการประเมินสภาพแวดล้อม "รอบอาคาร" จากมุมมองดาวเทียม (Proactive Prevention)
- นำข้อมูลดิบย้อนหลัง 6 ปี จากดาวเทียมมาประมวลผล เป็นดัชนีชี้เป้าความเสี่ยงที่แม่นยำสูง
- ให้ค่าความเสี่ยงเชิงพื้นที่ (ECI / ESS Score) แสดงผลพื้นที่ที่มีความเสี่ยงวิกฤตความร้อนด้วยสีแดง
- เจาะลึกข้อมูลรายศูนย์ (LST & NDWI) พร้อมระบบ Actionable Insights แนะนำมาตรการหน้างานแบบเรียลไทม์ (เช่น ปรับเพิ่มรอบพัดลมระบายอากาศล่วงหน้า 48 ชม.)

##  เทคโนโลยีที่ใช้
- **Data Core:** ดึงข้อมูลจาก Google Earth Engine (2020-2025)
- **Backend:** ใช้ Python (Streamlit & Pandas) ประมวลผลข้อมูลความเสี่ยงเชิงพื้นที่
- **Frontend:** ใช้ HTML5, JS & SVG วาดกราฟและแผนที่บนฝั่ง Client โดยตรง ทำให้หน้าเว็บตอบสนองเร็วระดับมิลลิวินาที 

##  ไฟล์ในโปรเจกต์
- `dc_resource_nexus.py`: โค้ดหลักของระบบ Streamlit Dashboard
- `DC-Resource-Intelligence-Pitch-Deck.pdf`: สไลด์นำเสนอผลงาน (Pitch Deck) ที่ใช้ในวันแข่งจริง
