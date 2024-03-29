คำแนะนำการพัฒนาซอฟต์แวร์ TMT
  1.Version ต่างๆ ของ Software จะอยู่ใน Branch ที่แยกการทำงานออกมาอย่างชัดเจน (เช่น 1.0.0 , 1.1.0 ,1.2.0
   ซึ่งทั้งหมดที่กล่าวมานี้จะอยู่ใน Branch ที่อยู่แยกกันอย่างชัดเจน)
  2.ถ้าต้องการเอกสารเกี่ยวกับ Change Request ทั้งหมด ทุกๆ Change Request จะถูกเก็บอยู่ในโฟลเดอร์ที่ชื่อ CR
  โดยมีรายละเอียดกำกับ เช่น (CR 1.0.0)
  3.รูปแบบของชื่อไฟล์คือ "${ชื่อเอกสาร} ${รุ่น}"

ตัวอย่างกรณีพัฒนา
    Documentation (เอกสาร): การสร้างและบริหารจัดการเอกสารที่เกี่ยวข้องกับโค้ดและโปรเจ็คทั้งหมด รวมถึงคู่มือการใช้งาน คู่มือนักพัฒนา หรือ API documentation.
    Version Control (การควบคุมเวอร์ชัน): การใช้ระบบควบคุมเวอร์ชันเพื่อทำการเก็บเอกสารและโค้ดในรูปแบบที่สามารถติดตามและเปรียบเทียบรุ่นกันได้.  
    Code Comments (คำอธิบายในโค้ด): การใส่คำอธิบายในโค้ดเพื่อช่วยในการทำความเข้าใจโค้ดและการทำงานของระบบ.  
    Issue Tracking (การติดตามปัญหา): ใช้ระบบติดตามปัญหา (issue tracking) เพื่อจัดการและเก็บข้อมูลเกี่ยวกับปัญหาที่พบ.  
    Test Cases (กรณีทดสอบ): เอกสารที่ระบุกรณีการทดสอบ (test cases) เพื่อการทดสอบโค้ดและตรวจสอบความถูกต้อง.  
    Architecture Documentation (เอกสารอุปกรณ์): การบริหารจัดการเอกสารที่เป็นไปตามการออกแบบและโครงสร้างของระบบ.
    API Documentation (เอกสาร API): การเก็บเอกสารเกี่ยวกับ Application Programming Interface (API) ที่ถูกพัฒนา.  
    Deployment Documentation (เอกสารการให้บริการ): เอกสารที่อธิบายกระบวนการการนำไปใช้งาน (deployment) รวมถึงการปรับปรุงและการประสานงาน.  
    Security Documentation (เอกสารด้านความปลอดภัย): เอกสารที่แสดงถึงมาตรฐานและวิธีการปรับปรุงความปลอดภัยของโค้ดและระบบ.  
    Coding Standards (มาตรฐานการเขียนโค้ด): การเก็บเอกสารที่กำหนดมาตรฐานในการเขียนโค้ด เพื่อให้ทุกคนในทีมทำงานได้ตามมาตรฐานที่เหมือนกัน.

บทบาทสมมติ
    เซ็ตอัพ: ห้องประชุมในบริษัท
    เมื่อทุกคนเข้ามาในห้องประชุม
    ตัวละคร:
        Project Manager (PM)
        Developer (Dev)
        Quality Assurance (QA)
    PM: เริ่มต้นด้วยการนำเสนอโครงการที่จะใช้ GitHub เพื่อทำ Track Trace Audit Report โดยอธิบายวัตถุประสงค์และการใช้งานของรายงาน
    PM: "สวัสดีทุกคนครับ/ค่ะ วันนี้เราจะมาพูดถึงการใช้ GitHub เพื่อทำ Track Trace Audit Report ที่จะช่วยให้เราติดตามและบันทึกการเปลี่ยนแปลงในโปรเจกต์ของเราได้อย่างมีประสิทธิภาพ"
    Dev: สงสัยเกี่ยวกับขั้นตอนการใช้งาน GitHub ในการทำรายงาน
    PM: อธิบายขั้นตอนการใช้ GitHub โดยสรุปในไฟล์ Collaboration Guidelines.md ที่อธิบายเกี่ยวกับโครงสร้างโปรเจกต์และการจัดเก็บเอกสารต่าง ๆ
    QA: สงสัยเกี่ยวกับการตรวจสอบคุณภาพของเอกสารที่เกี่ยวข้อง
    PM: อธิบายเกี่ยวกับการตรวจสอบคุณภาพของเอกสาร และการวางแผนเกี่ยวกับการทดสอบและตรวจสอบข้อมูล
    สรุป (Conclusion):
        อธิบายขั้นตอนการใช้งาน GitHub ในการทำ Track Trace Audit Report ในไฟล์ README.md
        กำหนดรายละเอียดเกี่ยวกับการตรวจสอบคุณภาพและการทดสอบข้อมูล
    สิ้นสุด (End):
        PM: ขอบคุณทุกคนที่เข้าร่วมการประชุมวันนี้ หากมีข้อสงสัยเพิ่มเติมหรือคำถามกรุณาแจ้งให้ทราบ
        Dev: ขอบคุณครับ/ค่ะ
        QA: ขอบคุณมากค่ะ/ครับ
    สิ้นสุด (End)
