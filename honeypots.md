# 6530200274 ปาณิสรา วิจารณ์
# [6530200371 มนัสวี ปิยะโสภาสกุล](https://manatsawee-pi/vocabulary)
## Honeypots/Honeynet
- CISSP Glossary https://www.isc2.org/certifications/cissp/cissp-student-glossary
  - Machines that exist on the network, but do not contain sensitive or valuable data,
  and are meant to distract and occupy maliciousor unauthorized intruders,
  as a means ofdelaying their attempts to accessproduction data/assets.
  A number ofmachines of this kind, linked together as anetwork or subnet,
  are referred to as a “honeynet.”
  - ChatGPT
    - เครื่องที่มีอยู่ในเครือข่าย แต่ไม่ได้เก็บข้อมูลที่สำคัญหรือมีค่าและมีจุดประสงค์เพื่อเบี่ยงเบนความสนใจและยึดเวลาผู้บุกรุกที่ไม่ได้รับอนุญาตหรือมุ่งร้าย
    เป็นวิธีการชะลอความพยายามในการเข้าถึงข้อมูลหรือสินทรัพย์ที่สำคัญในระบบการผลิต เครื่องหลายเครื่องที่มีลักษณะเช่นนี้ และเชื่อมต่อกันเป็นเครือข่ายหรือซับเน็ต จะเรียกว่า “honeynet”
  - Gemini
    - เครื่องจักรที่เชื่อมต่อกับเครือข่ายแต่ไม่ได้เก็บข้อมูลที่สำคัญหรือมีค่าและถูกตั้งใจให้เป็นเหยื่อล่อเพื่อดึงดูดผู้บุกรุกที่ไม่ได้รับอนุญาตหรือมีเจตนาไม่ดี
    เพื่อชะลอความพยายามในการเข้าถึงข้อมูล/ทรัพย์สินที่สำคัญ เครื่องจักรประเภทนี้หลายเครื่องที่เชื่อมโยงกันเป็นเครือข่ายหรือซับเน็ตเดียวกัน เรียกว่า "ฮันนี่เน็ต"

- imperva https://www.imperva.com/learn/application-security/honeypot-honeynet/
  - A honeypot is a security mechanism that creates a virtual trap to lure attackers. An intentionally compromised computer system allows attackers to exploit vulnerabilities so you can study them to improve your security policies. You can apply a honeypot to any computing resource from software and networks to file servers and routers.
  Honeypots are a type of deception technology that allows you to understand attacker behavior patterns. Security teams can use honeypots to investigate cybersecurity breaches to collect intel on how cybercriminals operate.
  They also reduce the risk of false positives, when compared to traditional cybersecurity measures, because they are unlikely to attract legitimate activity.
- ChatGPT
  - ฮันนี่พอต (Honeypot) เป็นกลไกด้านความปลอดภัยที่สร้างกับดักเสมือนเพื่อดึงดูดผู้โจมตี ระบบคอมพิวเตอร์ที่ตั้งใจทำให้เกิดช่องโหว่จะอนุญาตให้ผู้โจมตีใช้ประโยชน์จากช่องโหว่นั้น เพื่อให้คุณสามารถศึกษาพฤติกรรมเหล่านั้นและปรับปรุงนโยบายด้านความปลอดภัยของคุณได้ คุณสามารถใช้ฮันนี่พอตกับทรัพยากรการคำนวณใด ๆ ตั้งแต่ซอฟต์แวร์และเครือข่ายไปจนถึงเซิร์ฟเวอร์ไฟล์และเราเตอร์
  ฮันนี่พอตเป็นเทคโนโลยีประเภทการหลอกลวง (Deception Technology) ที่ช่วยให้คุณเข้าใจรูปแบบพฤติกรรมของผู้โจมตี ทีมงานด้านความปลอดภัยสามารถใช้ฮันนี่พอตเพื่อสืบสวนการละเมิดความปลอดภัยทางไซเบอร์และรวบรวมข้อมูลเกี่ยวกับวิธีการที่อาชญากรไซเบอร์ดำเนินการ
  นอกจากนี้ฮันนี่พอตยังช่วยลดความเสี่ยงจากการตรวจจับผิดพลาด (false positives) เมื่อเทียบกับมาตรการด้านความปลอดภัยแบบดั้งเดิม เพราะมันไม่น่าจะดึงดูดกิจกรรมที่ชอบด้วยกฎหมาย ์
- Gemini
  - ฮันนี่พ็อต เป็นกลไกด้านความปลอดภัยที่สร้างกับดักเสมือนจริงเพื่อดึงดูดผู้โจมตี ระบบคอมพิวเตอร์ที่ถูกตั้งใจให้ถูกโจมตีเพื่อให้ผู้โจมตีสามารถใช้ประโยชน์จากช่องโหว่ได้ เพื่อให้คุณสามารถศึกษาและปรับปรุงนโยบายความปลอดภัยของคุณ ฮันนี่พ็อตสามารถนำไปใช้กับทรัพยากรคอมพิวเตอร์ใด ๆ ตั้งแต่ซอฟต์แวร์และเครือข่ายไปจนถึงเซิร์ฟเวอร์ไฟล์และเราเตอร์
  ฮันนี่พ็อตเป็นเทคโนโลยีการหลอกลวงประเภทหนึ่งที่ช่วยให้คุณเข้าใจรูปแบบพฤติกรรมของผู้โจมตี ทีมรักษาความปลอดภัยสามารถใช้ฮันนี่พ็อตเพื่อตรวจสอบการละเมิดความปลอดภัยทางไซเบอร์เพื่อรวบรวมข้อมูลเกี่ยวกับวิธีการดำเนินงานของอาชญากรไซเบอร์ นอกจากนี้ยังลดความเสี่ยงของผลบวกปลอม เมื่อเทียบกับมาตรการรักษาความปลอดภัยทางไซเบอร์แบบดั้งเดิม เนื่องจากไม่น่าจะดึงดูดกิจกรรมที่ถูกต้องตามกฎหมาย
- สรุป ฮันนี่พอต (Honeypot) คือความปลอดภัยที่ที่เอาไว้ดึงดูดผู้ที่ไม่ประสงค์ดีที่จะมาโจมตีระบบคอมพิวเตอร์ ช่วยไม่ให้ข้อมูลในระบบนั้นหลุดรั่วออกไปสู่สารธณชนได้สร้างความปลอดภัยให้กับผู้ใช้งานได้อย่างดี
- ตัวอย่างในชีวิตประจำวัน สามารถใช้ฮันนี่พอตเป็นเครื่องมือในการดักจับและศึกษาพฤติกรรมของผู้โจมตีในเครือข่ายได้ นำฮันนี่พอตมาช่วยลดจำนวนการแจ้งเตือนปลอมได้
