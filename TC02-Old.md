# Invalid Test Case : Google Authentication
* ### Preconditions:
  1. สมัครใช้งาน gmail แล้ว
  2. เปิดการใช้งาน 2-step verification
  3. ติดตั้ง Google Authenticator บน Smart Phone
  4. ทำการเชื่อมต่อ Google Authenticator App กับ gmail
  
  
* ### Action :
  1. Login โดยใช้ username&password ที่ไม่ถูกต้อง 
  2. Login โดยใช้ username&password ที่ถูกต้อง และจำนวน verify code ไม่เท่ากับ 6 ตัว
  2. Login โดยใช้ username&password ที่ถูกต้อง และ verify code ไม่ถูกต้อง


* ### Input :
  - username & password
  - verify code


* ### Expected Result :
  - แจ้งเตือน เรื่อง username หรือ password ไม่ถูกต้อง
  - แจ้งเตือนการใส่จำนวน verify code ที่ไม่ถูกต้อง
  - แจ้งเตือน verify code ไม่ถูกต้อง


* ### Post Conditions : -
