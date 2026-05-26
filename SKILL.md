---
name: community-digital-km
description: "Research writing skill for Digital Knowledge Management and Community Sustainability. Use this skill whenever the user wants to: write a research proposal, develop a conceptual framework, conduct literature review, design methodology, or measure social impact (SROI/SDG) related to: community digital media adoption, sustainable communities, knowledge management in communities, community capacity building, digital technology for social impact, community leaders and digital transformation, sustainable economy at community level. Triggers: วิจัยชุมชน, การจัดการความรู้ดิจิทัล, ชุมชนยั่งยืน, ขอทุนวิจัย, เขียน proposal, SROI ชุมชน, SDG ชุมชน, สื่อดิจิทัลชุมชน, ผู้นำชุมชน, community research, digital KM, sustainable community, research proposal, social impact, community capacity, CAMT research."
metadata:
  version: "1.0.0"
  last_updated: "2026-05-26"
  status: active
  domain: "Community Development × Digital Technology × Sustainability"
  language: "Thai + English (bilingual)"
  target_users: "นักวิจัย CAMT มช., นักศึกษาปริญญาโท/เอก, นักวิจัยด้านชุมชนและดิจิทัล"
  data_access_level: raw
  task_type: open-ended
  related_skills:
    - deep-research
    - academic-paper
    - thesis-writer
---

# Community Digital Knowledge Management Research Skill
## ทักษะการวิจัย: การจัดการความรู้ดิจิทัลเพื่อความยั่งยืนของชุมชน

เครื่องมือช่วยเขียนวิจัยในหัวข้อ **"การนำเทคโนโลยีดิจิทัลมาใช้ในการจัดการความรู้ชุมชนเพื่อความยั่งยืน"** ครอบคลุมตั้งแต่การตั้งคำถามวิจัย → การทบทวนวรรณกรรม → การออกแบบกรอบแนวคิด → การเขียน Proposal ขอทุน

---

## Quick Start

**เริ่มจาก keyword ที่มี:**
```
ฉันมี keywords เกี่ยวกับชุมชน สื่อดิจิทัล และความยั่งยืน ช่วยสร้าง RQ และ proposal ให้หน่อย
```

**ต้องการ framework:**
```
ช่วยออกแบบ conceptual framework สำหรับงานวิจัยเรื่องการจัดการความรู้ดิจิทัลในชุมชน
```

**เขียน proposal ขอทุน:**
```
เขียน research proposal ขอทุนวิจัย เรื่อง digital KM + ชุมชนยั่งยืน
```

**วัด social impact:**
```
วิธีวัด SROI และเชื่อมกับ SDGs สำหรับโครงการดิจิทัลในชุมชน
```

---

## Trigger Conditions

### ภาษาไทย
วิจัยชุมชน, การจัดการความรู้, ดิจิทัลชุมชน, ชุมชนยั่งยืน, สื่อดิจิทัลชุมชน, ผู้นำชุมชน, เขียน proposal, ขอทุนวิจัย, กรอบแนวคิด, วัด impact ชุมชน, SROI, SDG ชุมชน, ความเข้มแข็งชุมชน, sustainable economy, social impact

### English
community research, digital knowledge management, community sustainability, digital media adoption, community capacity, social impact measurement, SROI, SDG localization, community leaders, sustainable community, digital transformation community, research proposal writing, conceptual framework community

### CAMT/มช. Context
CAMT research, วิจัย CAMT มช., งานวิจัยเพื่อขอทุน, วิทยานิพนธ์ CAMT, mixed methods community

---

## Mode Selection Guide

| สถานการณ์ | Mode | เหมาะกับ |
|---|---|---|
| มี keywords แต่ยังไม่มี RQ | `socratic` | ต้องการ guidance ก่อน |
| มี RQ แล้ว ต้องการ proposal เต็ม | `proposal` | งานขอทุน |
| ต้องการสร้าง framework ใหม่ | `framework` | สร้าง conceptual model |
| ต้องการทบทวนวรรณกรรม | `lit-review` | เตรียมบทที่ 2 |
| ต้องการวัด SROI + SDG | `impact` | วัดผลกระทบ |
| สรุปเร็ว ภาพรวมงานวิจัย | `quick` | ใช้เวลา < 30 นาที |

**ไม่แน่ใจ?** เริ่มด้วย `socratic` เสมอ — จะช่วยชี้แนะจนได้ RQ ที่ชัดเจน

---

## Agent Team (6 Agents)

| # | Agent | บทบาท | Phase |
|---|---|---|---|
| 1 | `research_question_agent` | สร้าง RQ ด้วย FINER framework, sub-questions, scope | Phase 0 |
| 2 | `literature_agent` | ค้นหาและสังเคราะห์วรรณกรรม, identify research gap | Phase 1 |
| 3 | `framework_designer_agent` | ออกแบบ conceptual framework + ทฤษฎีฐาน | Phase 2 |
| 4 | `methodology_agent` | ออกแบบ mixed methods, instruments, data collection | Phase 3 |
| 5 | `sroi_sdg_agent` | วัด social impact ด้วย SROI + map กับ SDGs | Phase 4 |
| 6 | `proposal_writer_agent` | เขียน proposal ฉบับสมบูรณ์พร้อม budget rationale | Phase 5 |

---

## Orchestration Workflow

```
Phase 0: SCOPING     → [research_question_agent]    → RQ Brief + Sub-questions
Phase 1: RESEARCH    → [literature_agent]           → Literature Matrix + Research Gap
Phase 2: FRAMEWORK   → [framework_designer_agent]   → Conceptual Framework + Theory Map
Phase 3: METHODOLOGY → [methodology_agent]          → Research Design + Instruments
Phase 4: IMPACT      → [sroi_sdg_agent]             → SROI Model + SDG Mapping
Phase 5: WRITING     → [proposal_writer_agent]      → Full Proposal Draft
```

**User checkpoint** ✋ หลัง Phase 0 และ Phase 2 — ต้องได้รับการยืนยันก่อนดำเนินต่อ

---

## Mode Details

### `socratic` mode
เมื่อ user มี keywords แต่ยังไม่แน่ใจ RQ → ใช้คำถาม FINER นำทาง  
อ่าน: `agents/research_question_agent.md` → Socratic Mode section

### `proposal` mode (full pipeline)
รัน Phase 0 → 5 ครบทุก phase  
output: proposal ฉบับสมบูรณ์ (TH + EN abstract, budget outline)  
อ่าน template: `templates/proposal_template.md`

### `framework` mode
เน้น Phase 2: ออกแบบ conceptual framework + เชื่อมทฤษฎี  
อ่าน: `references/theories.md` สำหรับทฤษฎีที่รองรับ

### `lit-review` mode
เน้น Phase 1: สังเคราะห์วรรณกรรม + สร้าง literature matrix  
output: annotated bibliography + research gap analysis

### `impact` mode
เน้น Phase 4: SROI calculation model + SDG localization mapping  
อ่าน: `references/sroi_sdg_guide.md`

### `quick` mode
ภาพรวมงานวิจัย: RQ + framework skeleton + methodology outline ใน 1 รอบ  
ไม่มี user checkpoint ระหว่างทาง

---

## Key Theories (Summary)
อ่านรายละเอียดทั้งหมดใน `references/theories.md`

| ทฤษฎี | ใช้ใน Phase |
|---|---|
| Knowledge Management (Nonaka & Takeuchi SECI) | Framework, Methodology |
| Community Capitals Framework (Flora & Flora) | RQ, Framework |
| Technology Acceptance Model — TAM | Framework, Methodology |
| Sustainability Theory / Triple Bottom Line | Framework, Impact |
| SDG Localization Framework | Impact |
| SROI Framework (Social Value UK) | Impact |
| Diffusion of Innovations (Rogers) | Framework |
| Community of Practice (Wenger) | Framework |

---

## Research Gap Statement
*(ใช้ใน proposal writing)*

> งานวิจัยที่ผ่านมาศึกษา digital adoption และ knowledge management แยกจากกัน ยังขาดงานที่บูรณาการ **Digital Technology × Knowledge Management × Community Sustainability** ในบริบทชุมชนท้องถิ่นไทย พร้อมเสนอ replicable framework และวัดผลด้วย SROI/SDGs

---

## Quality Standards

- **RQ** ต้องผ่าน FINER average ≥ 3.5/5
- **Framework** ต้องมีทฤษฎีรองรับ ≥ 2 ทฤษฎี
- **Proposal** ต้องมี: วัตถุประสงค์, methodology, timeline, expected outcomes, SDG alignment
- **ทุกส่วน** ต้องสามารถ justify ได้ด้วย literature
- **ภาษา**: ไทยเป็นหลัก + English สำหรับ abstract และ keywords
