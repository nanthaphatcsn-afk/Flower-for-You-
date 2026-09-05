# 🌸 Don't Give Up Seed Co.

ร้านขายเมล็ดพันธุ์ดอกไม้ที่ไม่มีเมล็ดจริง ๆ ขาย — มีแต่ดอกไม้กับคำพูดดี ๆ ให้คนที่กำลังเหนื่อย

A tiny seed shop that doesn't sell seeds. Every packet opens into a flower, a few sweet words
in Thai and English, and a stamp that says **อย่ายอมแพ้นะ · Don't give up**.

**Live:** https://nanthaphatcsn-afk.github.io/Flower-for-You-/

## ส่งดอกไม้ให้ใครสักคน / Send someone a flower

ทุกซองมีลิงก์ของตัวเอง เปิดซองที่ชอบ กด **Copy this packet's link** แล้วส่งไปให้เขา
พอเขากดลิงก์ ดอกไม้ซองนั้นจะเด้งขึ้นมาทันที

Each packet has its own link. Open one, hit **Copy this packet's link**, and send it —
the link opens straight to that flower's popup.

```
https://nanthaphatcsn-afk.github.io/Flower-for-You-/#/stubborn-lotus
https://nanthaphatcsn-afk.github.io/Flower-for-You-/#/late-night-jasmine
https://nanthaphatcsn-afk.github.io/Flower-for-You-/#/second-chance-sunflower
```

## 12 varieties

| Lot | Variety | ชื่อไทย |
|----|----|----|
| 01 | Sunrise Marigold | ดาวเรืองอรุณ |
| 02 | Quiet Cosmos | คอสมอสเงียบ ๆ |
| 03 | Slow-Bloom Peony | โบตั๋นค่อย ๆ บาน |
| 04 | Rainy Day Hydrangea | ไฮเดรนเยียวันฝน |
| 05 | Little Courage Daisy | เดซี่ใจกล้า |
| 06 | Late-Night Jasmine | มะลิดึก |
| 07 | Second-Chance Sunflower | ทานตะวันครั้งที่สอง |
| 08 | Stubborn Lotus | บัวใจแข็ง |
| 09 | Tiny-Wins Forget-Me-Not | อย่าลืมฉันดวงจิ๋ว |
| 10 | Homesick Bougainvillea | เฟื่องฟ้าคิดถึงบ้าน |
| 11 | Grow-Anyway Dandelion | แดนดิไลออนดื้อ ๆ |
| 12 | Someday Cherry Blossom | ซากุระสักวัน |

## แก้ข้อความเอง / Editing the messages

ทุกอย่างอยู่ในไฟล์เดียว — `index.html` ไม่ต้องติดตั้งอะไรทั้งนั้น
เลื่อนไปที่ตัวแปร `VARIETIES` แล้วแก้ได้เลย:

Everything is one file, `index.html`, with no build step. Find `VARIETIES` and edit:

- `th` / `en` — the sweet words
- `sow` / `water` / `blooms` — the growing notes
- `petals`, `rings`, `width`, `petal`, `petal2`, `center`, `pollen` — the flower drawing

เปิดดูในเครื่องได้ด้วยการดับเบิลคลิก `index.html` / Just double-click `index.html` to preview.

---

Flowers are drawn as parametric SVG — no images, no libraries, no tracking.
