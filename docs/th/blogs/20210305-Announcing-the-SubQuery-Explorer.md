# ประกาศ SubQuery Explorer

นับตั้งแต่ประกาศ SubQuery ไปทั่วโลกเมื่อเดือนที่แล้ว การตอบสนองและข้อเสนอแนะที่เราได้รับจากชุมชน Polkadot นั้นเป็นไปในเชิงบวกอย่างท่วมท้น เราได้รับ follower หลายพันคนบนช่องของเรา และมีการติดตั้งมากกว่า 1,353 ครั้งจาก NPM การรับข้อความสนับสนุนทั้งหมดและเห็นการมีส่วนร่วมจากชุมชนถือเป็นกำลังใจ **ได้เวลาพวกเราตอบแทนบ้างแล้ว!**

เราได้ทำงานล่วงเวลาในช่วงเดือนที่ผ่านมาเพื่อเผยแพร่ขั้นตอนหลักถัดไปของแผนงานสำหรับ SubQuery วันนี้เราจะประกาศเปิดตัว [SubQuery Explorer](https://explorer.subquery.network/)

![](https://miro.medium.com/max/1400/0*2bDaF3HPgNkpm8Kt)

[SubQuery Explorer](https://explorer.subquery.network/) เป็นบริการโฮสต์ออนไลน์ที่ให้การเข้าถึงโครงการ SubQuery ที่เผยแพร่โดยผู้ร่วมให้ข้อมูลทั่วโลกและจัดการโดยทีม SubQuery เป็นการต่อยอดภารกิจของเราในการสนับสนุนนักพัฒนา Polkadot โดยการให้บริการโครงสร้างพื้นฐานโดยทำให้การเข้าถึงข้อมูลเครือข่าย Polkadot ง่ายยิ่งขึ้น

วันนี้ ใครๆ ก็ query และดึงข้อมูลเครือข่าย Polkadot ได้ในเวลาเพียงไม่กี่นาทีโดยไม่มีค่าใช้จ่าย

SubQuery explorer ทำให้การเริ่มต้นใช้งานทำได้ง่าย เราได้สร้างโครงการ SubQuery ไว้ล่วงหน้าสำหรับกรณีการใช้งานสองกรณี (ข้อมูลเพิ่มเติมอยู่ด้านล่าง) และได้จัดทำดัชนีแต่ละเครือข่าย เรากำลังโฮสต์โหนด SubQuery เหล่านี้ทางออนไลน์และอนุญาตให้ทุกคน query ได้ฟรี โหนดที่มีการจัดการเหล่านี้จะได้รับการตรวจสอบและเรียกใช้โดยทีม SubQuery ที่เลเวลของประสิทธิภาพที่จะอนุญาตให้แอปที่ใช้งานจริงใช้และพึ่งพาได้

![](https://miro.medium.com/max/1400/0*3hmnk6sNoO5pdOWc)

นอกจากนี้ คุณจะทราบด้วยว่า SubQuery Explorer มี playground สำหรับการค้นหาข้อมูลที่มีพร้อมตัวอย่างการ query คุณสามารถเล่นกับ SubQuery Graph แต่ละรายการโดยใช้ explorer นี้โดยไม่ต้องติดตั้งอะไรในโค้ด นอกจากนี้ เราได้ทำการปรับปรุงเล็กๆ น้อยๆ ในเอกสารของเรา เพื่อสนับสนุนนักพัฒนาในการเดินทางไปยังการสืบค้นที่ดีขึ้นและวิเคราะห์ข้อมูลของโลก Polkadot ได้ดียิ่งขึ้น

![](https://miro.medium.com/max/1400/0*V1Mjpi1-gAT6M8-q)

## **ยอดรวมการ stake ของ SubQuery Project (**[GitHub Code ของโปรเจ็ค](https://github.com/subquery/subql-examples/tree/main/sum-reward))

คุณสามารถค้นหารายได้จากการ stake ทั้งหมดที่มอบให้กับบัญชีใด ๆ ก็ตามได้อย่างรวดเร็วตั้งแต่เริ่มต้นโดยการ query ที่อยู่บัญชีของพวกเขา โปรเจ็ค SubQuery นี้จัดทำดัชนีและบันทึกบัญชีที่เข้าร่วมในการ stake บนบล็อกเชน การจัดทำดัชนีอย่างต่อเนื่องจะค้นหารางวัลการ stake ที่ได้รับและขีดค่าสำหรับบัญชีนี้ และรวบรวมผลรวมไปยังฐานข้อมูล

## **เกณฑ์ Validator ของโปรเจ็ค SubQuery (**[GitHub Code ของโปรเจ็ค](https://github.com/subquery/subql-examples/tree/main/validator-threshold))

คุณสามารถดูจำนวน stake ขั้นต่ำที่จำเป็นสำหรับ validator ที่จะเลือกได้อย่างรวดเร็ว โปรเจ็กต์นี้เป็นตัวอย่างที่ยอดเยี่ยมของการนำสถานะการ query ไปใช้ในฟังก์ชันการทำแผนที่ อันดับแรกจะค้นหาช่วงระยะการ stake ที่ใช้งานอยู่ผ่านสถานะการ query และบันทึก validator ของจำนวนการ stake เซสชันนี้โดยแต่ละคน จากนั้นจะคำนวณจำนวนการ stake ขั้นต่ำและจำนวนเงินที่ stake ทั้งหมดในช่วงระยะนี้ สุดท้าย บันทึกจำนวนผู้เสนอชื่อสูงสุดที่สามารถรับรางวัลได้

SubQuery Explorer นี้เป็นเพียงแผนชุดแรกของเราในการสร้างศูนย์กลางชุมชนสำหรับข้อมูล Polkadot เราจะทำตามคุณสมบัติต่อไปนี้:

-   เรากำลังมุ่งเน้นไปที่เครื่องมือของชุมชน ดังนั้นคุณสามารถคาดหวังเอกสารสำหรับนักพัฒนาในเชิงลึกมากขึ้น บทช่วยสอนที่ง่ายต่อการติดตาม และโครงการตัวอย่างที่เน้นกรณีการใช้งานที่ยอดเยี่ยมจริงๆ สำหรับข้อมูลที่ SubQuery แสดง
-   โครงการ SubQuery เพิ่มเติมจะค่อยๆ ออนไลน์ตามความคิดเห็นของชุมชน เราชอบแนวคิดบางอย่างเกี่ยวกับสิ่งที่คุณอยากเห็นในอนาคต — เข้าถึงช่องทางโซเชียลของเรา (ดูด้านล่าง)
-   เรากำลังจะสร้างแพลตฟอร์ม partner เพื่อให้ชุมชนของเราสามารถสร้างและอัปโหลดโครงการ SubQuery ของตนเองได้ และเราจะจัดการและโฮสต์ให้คุณฟรี

เริ่มการ query ข้อมูลใน [SubQuery Explorer](https://explorer.subquery.network/) อันใหม่

สร้างโปรเจ็ค SubQuery ของคุณเองโดยทำตาม [เอกสาร SubQuery](https://doc.subquery.network/) ของเรา

เยี่ยมชม [เว็บไซต์](https://subquery.network/)ของเรา

**พูดคุยกับเราได้ที่:**

-   [hello@subquery.network](mailto:hello@subquery.network)
-   [Discord](https://discord.com/invite/78zg8aBSMG)
-   [Telegram](https://t.me/subquerynetwork)
-   [Twitter](https://twitter.com/subquerynetwork)
-   [Matrix](https://matrix.to/#/#subquery:matrix.org)
-   [LinkedIn](https://www.linkedin.com/company/subquery)

![](https://miro.medium.com/max/1400/0*tzhwpKRunR7AqFhr)