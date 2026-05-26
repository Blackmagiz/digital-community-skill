# คู่มือ SROI + SDG สำหรับโครงการดิจิทัลในชุมชน

## ส่วนที่ 1: SROI Quick Reference

### สูตร SROI
```
SROI = Present Value of Social Outcomes / Total Investment

ตัวอย่าง:
- ลงทุน: 500,000 บาท
- Social value สร้างได้: 1,750,000 บาท
- SROI = 1,750,000 / 500,000 = 3.5 : 1
```

### Financial Proxies สำหรับ Digital Community Projects

| Outcome | Financial Proxy | แหล่งข้อมูล |
|---|---|---|
| รายได้เพิ่มจากขายออนไลน์ | รายได้จริงที่เพิ่มขึ้น | บันทึกขาย |
| ประหยัดเวลาในการหาข้อมูล | ค่าแรงขั้นต่ำ × ชั่วโมงที่ประหยัด | กรมแรงงาน |
| เพิ่ม Human Capital | ค่าอบรมที่ไม่ต้องจ่าย | ราคาตลาด |
| ลดต้นทุนการสื่อสาร | ค่าโทรศัพท์/ค่าเดินทางที่ลดลง | ข้อมูลจริง |
| Social cohesion เพิ่ม | Proxy: ลดต้นทุนการแก้ปัญหาชุมชน | วรรณกรรม |

### การปรับลดด้วย 4 ปัจจัย

**Deadweight (%)**: สิ่งที่จะเกิดขึ้นอยู่แล้วโดยไม่มีโครงการ
- ตัวอย่าง: ถ้า 20% ของชุมชนจะขายออนไลน์อยู่แล้ว → Deadweight = 20%

**Attribution (%)**: ส่วนที่โครงการนี้รับผิดชอบ
- ตัวอย่าง: ถ้ามีโครงการอื่นร่วมด้วย → Attribution อาจเป็น 60-70%

**Displacement (%)**: ผลกระทบลบต่อกลุ่มอื่น
- ตัวอย่าง: ชุมชนนี้ขายได้มากขึ้น แต่ชุมชนข้างเคียงขายได้น้อยลง

**Drop-off (% ต่อปี)**: ผลที่ลดลงในปีถัดไป
- ตัวอย่าง: ทักษะดิจิทัลลดลง 10%/ปี ถ้าไม่มีการ upskill

### Template Impact Map

| Stakeholder | Input | Activity | Output | Outcome | Financial Proxy | Deadweight | Attribution | Net Value |
|---|---|---|---|---|---|---|---|---|
| สมาชิกชุมชน | เวลาเข้าร่วม | อบรม digital | จำนวนคนผ่าน | ทักษะดิจิทัลเพิ่ม | ค่าอบรมที่ไม่ต้องจ่าย | 10% | 80% | XX บาท |
| ผู้ประกอบการชุมชน | เงินลงทุนเวลา | ใช้ platform | ยอดขายออนไลน์ | รายได้เพิ่ม | รายได้จริง | 15% | 75% | XX บาท |

---

## ส่วนที่ 2: SDG Localization Guide

### SDG targets ที่เกี่ยวข้องโดยตรง

**SDG 1: No Poverty**
- Target 1.4: By 2030, ensure that all men and women have equal rights to economic resources, as well as access to basic services, **new technology** and financial services
- Indicator: รายได้ครัวเรือนที่เพิ่มขึ้นจากการใช้ digital platform

**SDG 4: Quality Education**  
- Target 4.4: By 2030, substantially increase the number of youth and adults who have relevant skills, including **technical and vocational skills**, for employment
- Indicator: จำนวนคนที่ผ่านการอบรมทักษะดิจิทัล

**SDG 8: Decent Work and Economic Growth**
- Target 8.3: Promote development-oriented policies that support productive activities, decent job creation, entrepreneurship, **creativity and innovation**
- Indicator: จำนวนธุรกิจชุมชนใหม่, รายได้จาก digital commerce

**SDG 9: Industry, Innovation and Infrastructure**
- Target 9.c: Significantly increase access to **information and communications technology** and strive to provide universal and affordable access to the Internet
- Indicator: % ของชุมชนที่เข้าถึง digital tools

**SDG 11: Sustainable Cities and Communities**
- Target 11.3: Enhance inclusive and sustainable urbanization and capacity for participatory, integrated and sustainable human settlement planning
- Indicator: Community Resilience Index, Community Capitals score

**SDG 17: Partnerships for the Goals**
- Target 17.8: Fully operationalize the **technology bank** and science, technology and innovation capacity-building mechanism
- Indicator: จำนวน partnerships ที่เกิดขึ้น

### SDG Mapping Template

```markdown
## SDG Alignment Report

### Primary SDGs
| SDG | Target | Contribution | Evidence |
|---|---|---|---|
| SDG 11 | 11.3 | Direct | Community Capitals score เพิ่มขึ้น |
| SDG 8 | 8.3 | Direct | รายได้ชุมชนเพิ่ม X% |

### Secondary SDGs  
| SDG | Target | Contribution | Evidence |
|---|---|---|---|
| SDG 4 | 4.4 | Indirect | จำนวนคนมีทักษะดิจิทัลเพิ่ม |
| SDG 1 | 1.4 | Indirect | การเข้าถึง digital services |
```

---

## ส่วนที่ 3: ข้อจำกัดและคำแนะนำ

### ข้อจำกัดของ SROI ในบริบทชุมชนไทย
1. **Data availability**: ชุมชนอาจไม่มีข้อมูลย้อนหลัง baseline → ต้องเก็บข้อมูล baseline ก่อน
2. **Monetization ยาก**: social capital, cultural value ประเมินเป็นตัวเงินยาก → ใช้ proxy อย่างระมัดระวัง
3. **Attribution ซับซ้อน**: ชุมชนมักมีหลายโครงการพร้อมกัน → ใช้ contribution analysis แทน attribution

### แนะนำ: ใช้ SROI เป็น "range" ไม่ใช่ตัวเลขเดียว
```
Conservative estimate: SROI = X.X : 1
Base case estimate:    SROI = Y.Y : 1
Optimistic estimate:   SROI = Z.Z : 1
```

### Alternative: Social Impact Assessment (SIA)
ถ้า SROI ยากเกินไป ใช้ SIA แทน:
- ระบุ stakeholders
- ระบุ changes (positive/negative)
- ประเมิน magnitude + likelihood
- แสดง mitigation strategies
