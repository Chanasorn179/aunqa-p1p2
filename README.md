# aunqa-p1p2

AUN-QA Quality Evidence & Learning Outcome Mapping System (P1: Evidence/SAR/CQI, P2: PLO–CLO Mapping & Coverage) — Team Syntax Error 3

**การออกแบบและพัฒนาระบบบริหารจัดการหลักฐานการประกันคุณภาพและผังเชื่อมโยงผลลัพธ์การเรียนรู้ตามเกณฑ์มาตรฐาน AUN-QA**

หลักสูตรวิศวกรรมซอฟต์แวร์ มหาวิทยาลัยเทคโนโลยีราชมงคลล้านนา · ENGSE211 / ENGSE212 / ENGSE601

## ภาพรวม

เว็บแอปแบบรวมศูนย์สำหรับงานประกันคุณภาพระดับหลักสูตรตามเกณฑ์ AUN-QA ฉบับ 4.0 แบ่งเป็น 2 โมดูล

| โมดูล | หน้าที่ |
|---|---|
| **P1** หลักฐานคุณภาพ, SAR และ CQI | จัดเก็บและค้นหาหลักฐาน, ตรวจทานและอนุมัติ (Draft → Submitted → Reviewed → Approved / Revision), Evidence Gap, ติดตาม CQI Action |
| **P2** PLO–CLO Mapping และ Coverage | รุ่นหลักสูตร, PLO / Sub-PLO / CLO, ผัง Mapping พร้อมระดับ I/R/M, วิเคราะห์ Coverage และ Mapping Gap |

ทั้งสองโมดูลใช้บริการส่วนกลางร่วมกัน ได้แก่ บัญชีผู้ใช้และ RBAC (5 บทบาท), audit log, แดชบอร์ด และการส่งออกรายงาน CSV/PDF

## เทคโนโลยี

- Frontend: React + Tailwind CSS
- Backend: Node.js + Express (REST API)
- Database: PostgreSQL
- สถาปัตยกรรม: Modular Monolith (P1, P2, Shared Services)

## ทีม

| ชื่อ | ความรับผิดชอบ |
|---|---|
| ธาวัน ทิพคุณ (หัวหน้าโครงงาน) | ความต้องการ, Backend และฐานข้อมูลส่วนกลาง, ประสาน P1–P2 |
| เบญจศรายุทธ น้อยอุบล | P1 หลักฐานคุณภาพ, Workflow ตรวจทาน, Evidence Gap และ CQI |
| ชนสรณ์ บุตรถา | P2 PLO–CLO Mapping, I/R/M, Coverage และ Mapping Gap |

อาจารย์ที่ปรึกษา: ธนิต เกตุแก้ว

## เอกสาร

เอกสารของโครงงานอยู่ในโฟลเดอร์ `docs/`
