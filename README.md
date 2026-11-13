# ปัญหาทางกฎหมายเกี่ยวกับการขอออกหมายจับและการจับกุมผู้ถูกกล่าวหาในชั้นไต่สวนของคณะกรรมการป้องกันและปราบปรามการทุจริตแห่งชาติ

สารนิพนธ์ น.ม. กลุ่มวิชากฎหมายอาญาและกระบวนการยุติธรรมทางอาญา คณะนิติศาสตร์ มหาวิทยาลัยศรีปทุม (เล่มที่ 2 แยกจาก `nacc-flagrant-arrest-thesis`)

**Title:** Legal Problems Concerning the Application for Arrest Warrants and the Arrest of Alleged Offenders during the Inquiry Stage of the National Anti-Corruption Commission

## โครงสร้าง repo

| path | เนื้อหา |
|---|---|
| `HANDOVER.md` | สรุปบริบทงานวิจัย สถานะ และงานค้าง (ใช้เริ่ม chat ใหม่) |
| `CLAUDE.md` | กฎการทำงานและสถานะการตรวจล่าสุด |
| `docs/index.html` | หน้าเว็บฉบับร่างแบบเรียบ (สร้างจาก `draft/original.html`) ใช้ copy ลง Word; ป้าย (รอตรวจสอบ) = แหล่งที่ยังไม่ยืนยัน |
| `draft/original.html` | ไฟล์ร่างต้นฉบับ (แหล่งความจริงของเนื้อหา) |
| `draft/src/` | ต้นฉบับแต่ละบท `chN.txt` (ใช้กับ `tools/build2.py`) |
| `tools/` | `make_page.py` แปลงร่างเป็นหน้าเว็บ, `build2.py` สร้างบทจาก `draft/src/`, `pending.json` รายการที่ติดป้ายรอตรวจสอบ |
| `sources/` | ทะเบียนแหล่งตัวบทและข้อความตัดตอน (ดู `sources/INDEX.md`) คัดลอกจากเล่มแรก |
| `research-notes/` | บันทึกศึกษาตัวบท คู่มือ SPU และร่างประเด็นหัวข้อ |

## สร้างหน้าเว็บใหม่

```
python3 -I tools/make_page.py draft/original.html docs/index.html
```

เมื่อตรวจแหล่งใดเสร็จ ให้ลบรายการนั้นออกจาก `tools/pending.json` แล้วสร้างใหม่
