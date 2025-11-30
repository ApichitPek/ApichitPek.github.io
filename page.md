#page 
  + [A contiguous, fixed-length block of virtual addresses. It is copied from memory to disk and back during paging
    operations. Windows 2000 uses 4 KB blocks to map physical and virtual memory addresses. SQL Server allocates
    database space in 8K pages.]

| User |meaning |
| :--- | :--- |
| **GPT** | บล็อกของที่อยู่เสมือน (virtual addresses) ที่มีความยาวคงที่และอยู่ติดกัน เพจจะถูกคัดลอกจากหน่วยความจำไปยังดิสก์และกลับมาในระหว่างกระบวนการเพจจิง (paging) Windows 2000 ใช้บล็อกขนาด 4 KB เพื่อแมปที่อยู่หน่วยความจำจริงและเสมือน SQL Server จัดสรรพื้นที่ฐานข้อมูลเป็นเพจขนาด 8 KB|
| **Gimini** | บล็อกของที่อยู่หน่วยความจำเสมือน (virtual addresses) ที่มีขนาดคงที่และเรียงต่อเนื่องกัน โดยเพจจะถูกคัดลอกจากหน่วยความจำหลักไปยังดิสก์ และคัดลอกกลับมาในระหว่างกระบวนการสลับหน้าหน่วยความจำ (paging operations) ตัวอย่างขนาดของเพจในระบบต่างๆ: Windows 2000: ใช้บล็อกขนาด 4 KB ในการจับคู่ (map) ระหว่างที่อยู่หน่วยความจำจริง (physical) และหน่วยความจำเสมือน SQL Server: จัดสรรพื้นที่ในฐานข้อมูลโดยแบ่งเป็นเพจขนาด 8 KB |
| **Myself** | เป็นหน้าที่แยกส่วนไว้เรียงกัน เพื่อให้ทำงานง่ายขึ้น|
