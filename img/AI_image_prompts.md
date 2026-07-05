# Prompt สร้างภาพประกอบเว็บ BAZI by Arng (ให้ตรงโทนเว็บ)

โทนเว็บ: luxury สว่าง — ครีม/งาช้าง, ทองอ่อน, น้ำตาลเอสเพรสโซ่ (ตัวอักษร), แสงนุ่ม

กติกาการปิดข้อมูล (สำคัญ):
- แสดง "เนื้อหาดวง" ได้เต็มที่ — ผังปาจื้อ 4 เสา, ตัวอักษรจีน, ตัวเลข, แผนภาพธาตุ, ตาราง
- ปิดเฉพาะ "ชื่อ-นามสกุล" และ "วันเดือนปีเกิด" (อย่าให้มีช่องข้อมูลส่วนตัวเหล่านี้ในภาพ)
- ตัวอักษรจีน + ตัวเลข: ให้ AI ทำได้เลย (ดูสมจริง)
- ข้อความบรรยาย "ภาษาไทย": ให้เป็นเส้นข้อความจำลองอ่านไม่ออก (เพราะ AI เขียนไทยเพี้ยน)

วางไฟล์ที่ได้ในโฟลเดอร์ img/ ตามชื่อนี้:
- report1.jpg – report4.jpg (แนวตั้ง 3:4)
- report-desk.jpg (แนวนอน 4:3)

---

## STYLE (คำนำหน้า ใช้ร่วมทุก prompt ได้)
```
Luxury minimal editorial style, warm ivory and cream paper, soft gold foil accents,
deep espresso-brown ink, gentle natural daylight, elegant and premium, calm and
expensive feeling. Real-looking Chinese BaZi astrology content is welcome (Chinese
characters and numbers are fine and encouraged). Thai body copy should be shown as
non-legible placeholder lines only. IMPORTANT: do NOT show any personal name or
birth date field anywhere. High detail, clean layout.
```

---

## report1.jpg — หน้าปก + ผังปาจื้อ 4 เสา (3:4 แนวตั้ง)
```
A premium BaZi report page, portrait orientation. Top: an elegant title band with a
small five-element circular emblem in gold (NO name, NO birth date). Below it, a
realistic BaZi "Four Pillars" chart table: four columns labeled Hour / Day / Month /
Year (時 日 月 月 year), each column showing a Chinese Heavenly Stem character on top
and an Earthly Branch character below (e.g. 甲 乙 丙 丁 / 子 丑 寅 卯), with small
element tags. Thin gold dividers, ivory paper texture, deep brown ink, gold accents,
luxury stationery. Chinese characters legible; any Thai text as non-legible lines.
Portrait 3:4.
```

## report2.jpg — หน้าสมดุลธาตุ 5 + สิบเทพ (3:4 แนวตั้ง)
```
An inside BaZi report page. Upper half: a five-element radar/pentagon chart with five
labeled nodes (Wood Fire Earth Metal Water) connected by soft gold lines, one node
glowing warmer, with small percentage numbers. Lower half: a "Ten Gods" style
horizontal bar chart with several bars of different lengths and percentage numbers in
gold/brown. Ivory background, espresso-brown ink, gold accents, editorial infographic,
premium. Numbers and simple labels legible; Thai captions as non-legible lines.
Portrait 3:4.
```

## report3.jpg — หน้ารอบโชค + แนวทางรายเดือน (3:4 แนวตั้ง)
```
An inside BaZi report page. Top: a Luck Pillar (大運) horizontal timeline with age
numbers (e.g. 3 13 23 33 43 53) and small Chinese characters above each segment.
Below: a 12-month table, one row per month, with small gold star ratings (★★★★★) and a
few warning dots, thin dividing lines, an elegant gold header band. Ivory paper, deep
brown ink, warm gold highlights, clean premium data layout. Numbers/stars/Chinese
legible; Thai text as non-legible placeholder lines. Portrait 3:4.
```

## report4.jpg — หน้าเสริมธาตุ (สี/ของมงคล/ทิศ) (3:4 แนวตั้ง)
```
An inside BaZi report page about lifestyle remedies. A neat grid of warm color
swatches (terracotta, amber, ochre, ivory, gold) with tiny hex-like number labels, a
small compass diagram with directions, and a few elegant gold line-art icons (a
gemstone, a perfume bottle, a leaf, a bowl of food). Ivory background, espresso-brown
ink, gold accents, luxury lookbook feel. Icons/swatches clear; Thai captions as
non-legible lines. Portrait 3:4.
```

## report-desk.jpg — รายงานวางคู่โต๊ะทำงาน (4:3 แนวนอน)
```
An elegant flat-lay / desk scene, landscape orientation, top-down and slightly
angled. A printed premium report booklet (ivory cover with subtle gold BaZi motif)
resting on a warm cream desk, next to a slim laptop, a linen notebook, a gold pen,
a small clear quartz crystal, and a cup of coffee. Soft natural window light, warm
shadows, cream–gold–espresso palette, expensive lifestyle photography, shallow depth
of field. Landscape 4:3. No legible text on the pages.
```

---

## หมายเหตุ
- ถ้าใช้ Midjourney เติมท้าย: report pages ใส่ `--ar 3:4` · desk ใส่ `--ar 4:3`
- ถ้าใช้ ChatGPT/DALL·E บอกว่า "portrait 3:4" หรือ "landscape 4:3" ในคำสั่งได้เลย
- อยากได้ 4 หน้ารายงานให้ดู "เป็นเล่มเดียวกัน" ให้บอกโมเดลว่า same design system, same ivory paper and gold accents
- ได้ไฟล์มาแล้ว ถ้าสัดส่วนไม่ตรงเป๊ะ บอกผมปรับ CSS ให้พอดี
