# YiPun
YiPun by Uncle Engineer v.0.0.1- โปรแกรมฝึกภาษาญี่ปุ่น

ลุงแจกโปรแกรมฝึกภาษาญี่ปุ่นฟรี!

YiPun โปรแกรมสำหรับใช้ฝึกภาษาญี่ปุ่น คำศัพท์ต่างๆในภาษาญี่ปุ่นต้องใช้พลังในการจดจำเป็นอย่างมาก การจดบันทึกลงสมุดก็ดี แต่หากมีซอฟแวร์มาช่วยให้เราสามารถเก็บคำศัพท์ที่เคยท่องมาทบทวนได้จะดียิ่งกว่า ใช้การท่องจำคำศัพท์โดยนำ flashcard เข้ามาช่วย โปรแกรมจะ random คำศัพท์แล้วให้เราพิมพ์ความหมายของคำศัพท์นั้นหรือประโยคให้ถูกต้อง เพื่อเก็บคะแนน (ฟังชั่นบันทึกประวัติคะแนนยังไม่เขียนเพิ่ม รอ v.0.0.2) หากคำศัพท์ไหนที่เราจำไม่ได้สามารถกดฟังเสียงได้ ซึ่งจะช่วยให้นึกความหมายออก คันจิบางตัวเราอาจจะจำไม่ได้แต่หากได้ยินเสียงคำศัพท์ เราอาจจะจำได้ทันที ใช้วิธีสร้างกระบวนจดจำคำศัพท์โดยใช้เสียงมาช่วย อนาคตลุงจะเพิ่มรูปภาพของคำศัพท์ด้วย ซึ่งจะทำให้เรายิ่งจำได้มากขึ้นอีก เห็นทั้งตัวอักษร เห็นทั้งภาพ เห็นทั้งเสียง ซึ่งเป็นจุดเริ่มต้นที่จะทำให้เราจำคำศัพท์ได้ดีขึ้น หวังว่าโปรแกรมของลุงจะอำนวยความสะดวกในการเรียนรู้ภาษาญี่ปุ่นได้มากยิ่งขึ้นจร้าาาา

「ความสามารถหลักๆ คือ」

- แปลจากญี่ปุ่นเป็นไทย ไทยเป็นญี่ปุ่น หรืออังกฤษ
- บันทึกคำศัพท์โดยแปลอัตโนมัติหรือแบบกรอกความหมายเอง
- สามารถฟังเสียงพูดได้ เสียงพูดของ google translate
- มีตารางคำศัพท์ที่เคยบันทึกไว้ ลบ แก้ไขความหมายได้
- มีเกม Flashcard ให้เล่นเพื่อทดสอบความจำ
- ภาษาแปลด้วย Google Translate ( ความหมายที่เป็นประโยคบางคำอาจจะเข้าใจได้ยาก ลองเปลี่ยนเป็นภาษาอังกฤษ อาจจะแปลได้ดีกว่า)
- แสดงจำนวนคำศัพท์ที่บันทึกได้
-----------------------------------------
「เทคนิคเพิ่มเติม」
- แท็บ Flashcard - กด F1 เพื่อ random คำศัพท์, F2 โชว์ความหมายที่ซ่อนอยู่ , F3 เพื่ออ่านออกเสียง พิมพ์ในช่องตรวจความหมายเพื่อเก็บคะแนน

- แท็บ All vocab - ดับเบิลคลิกเพื่อฟังเสียง คลิกขวากด delete vocab หรือเลือกศัพท์แล้วกดปุ่ม delete เพื่อลบคำศัพท์ได้ กด Change Meaning สำหรับเปลี่ยนความหมาย (หากเปลี่ยนคำศัพท์ญี่ปุ่น โปรแกรมจะบันทึกเป็นคำศัพท์ใหม่)

- แท็บ Translate - เลือก Japanese - พิมพ์คำศัพท์ภาษาไทย กด enter จากนั้นคำศัพท์ญี่ปุ่นจะขึ้นมา หากต้องการเข้าไปดูความหมายเพิ่มเติมในเว็บไซต์ https://jisho.org/ กด F4 เพื่อฟังเสียงได้ สามารถกด F5 เพื่อลิ้งค์คำศัพท์ไปยังเว็บไซต์
-----------------------------------------
ปล. โปรแกรมยังไม่สมบูรณ์ อยากให้เพิ่มฟังชั่นไหนพิเศษคอมเมนท์ไว้ได้จร้าาาา จะเขียนเพิ่มให้ ลุงเขียนแบบรีบๆ โค้ดอาจไม่สมบูรณ์ ใครเขียนโปรแกรมเป็นก็ลองโหลดโค้ดด้านล่าง เพิ่มฟังชั่นที่ต้องการได้เลย

ดาวน์โหลด Source Code: https://github.com/UncleEngineer/YiPun

ดาวน์โหลดไฟล์ exe: https://github.com/UncleEngineer/YiPun/blob/master/YiPun%20v.0.0.1.zip (วิธีติดตั้งให้ unzip แล้วดับเบิลคลิกไฟล์ YiPun.exe)

ปล2. สำหรับคนเขียน Python เป็น โปรแกรมนี้ลุงเขียนขึ้นมาด้วย Python โดยใช้ไลบรารี่ชื่อ tkinter ที่แถมมากับ Python ตอนติดตั้งครั้งแรก ตัวฐานข้อมูลใช้แค่ csv ก็เพียงพอ รันโปรแกรมขึ้นมาจะมีไฟล์ vocab.csv อยู่ในโฟลเดอร์โปรแกรม สามารถคลิกขวาแล้ว Edit เพื่อดูคำศัพท์หรือเพิ่มศัพท์แบบ Manual ได้ การฟังเสียง ใช้ไลบรารี่ gtts (Google Text to Speech) 
