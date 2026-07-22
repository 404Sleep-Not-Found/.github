<div align="center">

<img src="https://raw.githubusercontent.com/404Sleep-Not-Found/.github/main/profile/logo.png" alt="404 SLEEP NOT FOUND logo" width="160" />

# 404 SLEEP NOT FOUND

***We build while the world sleeps.***
**พวกเราลงมือสร้าง ขณะที่โลกกำลังหลับ**

[🌐 404sleepnotfound.com](https://404sleepnotfound.com) · [📧 nongnine260@gmail.com](mailto:nongnine260@gmail.com)

</div>

---

## 🚀 Our Projects · ผลงานของเรา

> Every project here is a prototype built from scratch by the team — from idea to deployed product. We build to learn, compete, and prove what we can ship.

ทุกโปรเจกต์ที่นี่คือต้นแบบที่ทีมสร้างเองทั้งหมด — ตั้งแต่ไอเดียจนถึง deploy จริง เราสร้างเพื่อเรียนรู้ ลงแข่งขัน และพิสูจน์ว่าเราทำอะไรได้บ้าง

---

### 🛡️ Breach72 — PDPA Incident Response Command Center

<!-- ![Breach72](https://img.shields.io/badge/status-live-success) -->
[![Live Demo](https://img.shields.io/badge/demo-pdpa.404sleepnotfound.com-22d3ee?style=flat-square)](https://pdpa.404sleepnotfound.com)
[![Stack](https://img.shields.io/badge/stack-Next.js_16_•_React_19_•_CF_Workers_•_D1_•_Drizzle_•_Tailwind_4-6366f1?style=flat-square)](#)

**PDPA Hackathon Track 4: Incident Response & Breach** — ระบบรับมือเหตุละเมิดข้อมูลส่วนบุคคลภายในกรอบ 72 ชั่วโมง สำหรับ DPO, Incident Commander และ Security Team

| ความสามารถ | รายละเอียด |
|---|---|
| ⏱️ **Command Center** | นาฬิกา 72 ชั่วโมงนับจากเวลาที่องค์กรทราบเหตุ |
| 📋 **Decision Tree** | ประเมิน Severity × Likelihood + checklist PDPA 8 ข้อ + จุดตัดสินใจของ Controller |
| 📖 **Playbook & Runbook** | แบ่งเฟส 0–4, 4–24, 24–48, 48–72 ชั่วโมง และหลัง 72 ชั่วโมง |
| 📨 **Communication Templates** | ร่างรายงานสำหรับหน่วยงานกำกับ เจ้าของข้อมูล Controller/Processor และผู้บริหาร |
| 🔒 **Guardrail** | ห้าม export เมื่อข้อมูลไม่ครบหรือยังไม่มีคำตัดสินใจจากผู้มีอำนาจ |
| 📜 **Audit Trail** | บันทึกทุกการกระทำ — เปิดเหตุ, ประเมิน, อนุมัติ, override, export |

---

### 💬💸 ChatUp — แชท + กระเป๋าเงินดิจิทัล

<!-- ![ChatUp](https://img.shields.io/badge/status-building-yellow) -->
[![Goal](https://img.shields.io/badge/goal-chatup.404sleepnotfound.com-f59e0b?style=flat-square)](#)
[![Stack](https://img.shields.io/badge/stack-React_19_•_CF_Workers_•_D1_•_KV_•_R2_•_Durable_Objects_•_PWA-8b5cf6?style=flat-square)](#)

**WeChat เวอร์ชันไทย** — แอปแชท + กระเป๋าเงินดิจิทัลเพื่อ Financial Inclusion กลุ่มเป้าหมายคือคนที่ไม่มีบัญชีธนาคาร

| ความสามารถ | รายละเอียด |
|---|---|
| 💬 **แชท** | ข้อความส่วนตัว, กลุ่ม, แชร์รูป, ส่งไฟล์ — UI ใหญ่ รองรับเสียงอ่าน |
| 💰 **กระเป๋าเงิน** | โอนเงินในแชท, สแกน QR จ่าย, อั่งเปา, จ่ายบิล — ครบในแอปเดียว |
| 🌏 **5 ภาษา** | ไทย (หลัก) + EN, เมียนมา, ลาว, เขมร |
| 🔐 **สมัครง่าย** | ใช้แค่เบอร์มือถือ — ไม่ต้องมีบัญชีธนาคาร |
| 🏗️ **Monorepo** | pnpm workspaces: `apps/web` (PWA), `apps/api` (Worker), `packages/shared` |

---

### 💰 DocMoney — จัดการเงินส่วนตัวแบบไทยๆ

<!-- ![DocMoney](https://img.shields.io/badge/status-prototype-informational) -->
[![Stack](https://img.shields.io/badge/stack-PHP_8_•_MySQL_•_Google_OAuth_•_Vanilla_JS_•_PhpSpreadsheet-096353?style=flat-square)](#)

**Personal Finance Tracker** — เว็บแอปจัดการรายรับ-รายจ่ายส่วนตัว ออกแบบให้สวย ใช้ง่าย สบายตา เน้นผู้ใช้ชาวไทย

| ความสามารถ | รายละเอียด |
|---|---|
| 🔐 **Google OAuth** | ล็อกอินด้วยบัญชี Google — ไม่ต้องจำรหัสผ่าน |
| 📊 **Dashboard** | สรุปยอดรายรับ-รายจ่าย แยกตามหมวดหมู่ รายเดือน |
| 🏷️ **หมวดหมู่กำหนดเอง** | สร้างหมวดหมู่รายรับ/รายจ่ายตามต้องการ |
| 🧾 **อัปโหลดสลิป** | แนบรูปหลักฐานในแต่ละรายการ |
| 📄 **Export Excel** | ส่งออกรายการเป็นไฟล์ .xlsx |
| 🧮 **โมดูลภาษี** | คำนวณภาษีคร่าวๆ จากรายรับ-รายจ่าย |
| 📱 **Responsive** | รองรับทุกหน้าจอ — UI โทน Teal Premium ฟอนต์ Kanit |

---

### 🎨 Portfolio — Team Showcase

[![Live](https://img.shields.io/badge/live-404sleepnotfound.com-22d3ee?style=flat-square)](https://404sleepnotfound.com)
[![Stack](https://img.shields.io/badge/stack-Vite_•_React_18_•_Tailwind_•_Framer_Motion-06b6d4?style=flat-square)](#)

เว็บโชว์พอร์ตของทีม — แยกแท็บสมาชิกแต่ละคน มี animation เลื่อน/นับสกอร์, ผลงาน, certificate แบบ verify ได้, deploy บน Cloudflare Pages

👉 **[ดูเว็บพอร์ต](https://404sleepnotfound.com)** — profile สมาชิกทุกคน พร้อมภาษา ผลงาน และใบเซอร์

---

## 👥 Members · สมาชิก (8 คน)

<!-- MEMBERS-DATA {"extra":[{"login":"thanachotsienop-hub","name":"Thanachot Sienop","role":"Junior Customer Journey Manager"},{"login":"thanathorncheen-glitch","name":"Thanathorn Cheente","role":"Full Stack Developer"},{"login":"frit-01","name":"Jirayos Tippason","role":"Project Manager"},{"login":"rahatburanabenya-sudo","name":"Rahart Buranabenya","role":"Full Stack Developer"}]} -->
<!-- MEMBERS:START -->
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/NexwestLedgerCoreCompanyLimited">
        <img src="https://github.com/NexwestLedgerCoreCompanyLimited.png?size=100" width="80" alt="" /><br />
        <sub><b>Natthawut Ngamoiu</b></sub>
      </a><br />
      <sub>Junior Full-stack Developer / Network & System Engineer</sub>
    </td>
    <td align="center">
      <a href="https://github.com/bbk865327-byte">
        <img src="https://github.com/bbk865327-byte.png?size=100" width="80" alt="" /><br />
        <sub><b>Thodsaphon Ratchamangsa</b></sub>
      </a><br />
      <sub>Full-stack Developer</sub>
    </td>
    <td align="center">
      <a href="https://github.com/V1stor1a">
        <img src="https://github.com/V1stor1a.png?size=100" width="80" alt="" /><br />
        <sub><b>Thananan Jansoongnern</b></sub>
      </a><br />
      <sub>Junior AI/ML Engineer</sub>
    </td>
    <td align="center">
      <a href="https://github.com/rahatburanabenya-sudo">
        <img src="https://github.com/rahatburanabenya-sudo.png?size=100" width="80" alt="" /><br />
        <sub><b>Rahart Buranabenya</b></sub>
      </a><br />
      <sub>Full Stack Developer</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/thanathorncheen-glitch">
        <img src="https://github.com/thanathorncheen-glitch.png?size=100" width="80" alt="" /><br />
        <sub><b>Thanathorn Cheente</b></sub>
      </a><br />
      <sub>Full Stack Developer</sub>
    </td>
    <td align="center">
      <a href="https://github.com/thanachotsienop-hub">
        <img src="https://github.com/thanachotsienop-hub.png?size=100" width="80" alt="" /><br />
        <sub><b>Thanachot Sienop</b></sub>
      </a><br />
      <sub>Junior Customer Journey Manager</sub>
    </td>
    <td align="center">
      <a href="https://github.com/frit-01">
        <img src="https://github.com/frit-01.png?size=100" width="80" alt="" /><br />
        <sub><b>Jirayos Tippason</b></sub>
      </a><br />
      <sub>Project Manager</sub>
    </td>
    <td align="center">
      <a href="https://github.com/SunnyVV99">
        <img src="https://github.com/SunnyVV99.png?size=100" width="80" alt="" /><br />
        <sub><b>Siththipon Chaiporn</b></sub>
      </a><br />
      <sub>Team Member</sub>
    </td>
  </tr>
</table>
<!-- MEMBERS:END -->

---

## 🛠️ Tech We Use · สแต็กที่เราใช้

| Layer | Tools |
|---|---|
| **Frontend** | React 18/19 · TypeScript · Next.js 16 · Vite · Tailwind CSS · shadcn/ui · Framer Motion · PWA |
| **Backend** | Cloudflare Workers · itty-router · Hono · Durable Objects · WebSocket |
| **Data** | Cloudflare D1 (SQLite) · KV · R2 · Drizzle ORM |
| **Languages** | TypeScript · JavaScript · Python · Go · SQL · C · Rust · Bash |
| **DevOps** | GitHub Actions · Wrangler · pnpm monorepo · ESLint · Prettier · Vitest |

---

<div align="center">
  <sub>404 SLEEP NOT FOUND · Thailand 🇹🇭 · <a href="https://404sleepnotfound.com">404sleepnotfound.com</a></sub>
</div>
