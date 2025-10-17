<!doctype html>

<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>بورتفوليوا — اسمك</title>
  <meta name="description" content="بورتفوليوا شخصي وCV — اسمك">
  <link href="https://fonts.googleapis.com/css2?family=Almarai:wght@300;400;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa6b2; --accent:#06b6d4; --glass: rgba(255,255,255,0.04);
    }
    *{box-sizing:border-box}
    body{font-family:'Almarai',sans-serif;margin:0;background:linear-gradient(180deg,var(--bg),#071428);color:#e6eef6;line-height:1.5}
    .container{max-width:1000px;margin:28px auto;padding:20px}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:14px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-size:32px;color:var(--muted)}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin:6px 0 0}.grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:22px}
main{background:rgba(255,255,255,0.02);padding:18px;border-radius:12px}
aside{background:rgba(255,255,255,0.02);padding:18px;border-radius:12px}

section{margin-bottom:16px}
.skills .skill{margin-bottom:10px}
.bar{background:rgba(255,255,255,0.06);height:10px;border-radius:20px;overflow:hidden}
.bar > i{display:block;height:100%;background:linear-gradient(90deg,var(--accent),#7c3aed)}

.projects{display:flex;flex-direction:column;gap:10px}
.project{background:var(--card);padding:10px;border-radius:10px}
.meta{color:var(--muted);font-size:13px}

.cv-btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#7c3aed);color:#041022;text-decoration:none;font-weight:700}

footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}

/* responsive */
@media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:90px;height:90px}}

  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">اس</div>
      <div>
        <h1>اسمك الكامل — <span class="meta">المسمّى الوظيفي</span></h1>
        <p class="lead">جملة تعريفية قصيرة عنك — مطور واجهات، مصمم، باحث... احطها هنا.</p>
        <div style="margin-top:10px">
          <a class="cv-btn" href="cv.pdf" download>تحميل السيرة الذاتية (PDF)</a>
        </div>
      </div>
    </header><div class="grid">
  <main>
    <section id="about">
      <h2>من أنا</h2>
      <p>فقرة قصيرة تشرح خبرتك، ما تبحث عنه، المهارات الأساسية، ولِمَ عليك التواصل معك. اذكر مشاريع بارزة أو رابط لينكدإن/جيتهاب.</p>
    </section>

    <section id="projects">
      <h2>مشاريع</h2>
      <div class="projects">
        <div class="project">
          <strong>اسم المشروع 1</strong>
          <div class="meta">وصف موجز — تقنيات: HTML, CSS, JS</div>
          <div style="margin-top:8px"><a href="#" style="color:var(--accent)">رابط المشروع</a></div>
        </div>
        <div class="project">
          <strong>اسم المشروع 2</strong>
          <div class="meta">وصف موجز — تقنيات: React, Node</div>
          <div style="margin-top:8px"><a href="#" style="color:var(--accent)">رابط المشروع</a></div>
        </div>
      </div>
    </section>

    <section id="experience">
      <h2>الخبرة العملية</h2>
      <div>
        <strong>الشركة/المؤسسة — المسمى الوظيفي</strong>
        <div class="meta">من — إلى (مثال: جانفي 2023 — الآن)</div>
        <p>نقاط موجزة لـ

achievements والمهام: استخدم نقاط قصيرة.</p> </div> </section>

<section id="education">
      <h2>التعليم</h2>
      <div>
        <strong>اسم المؤسسة — الشهادة</strong>
        <div class="meta">سنة التخرج</div>
        <p>مواد/مشاريع مهمة إن وجدت.</p>
      </div>
    </section>

  </main>

  <aside>
    <section class="skills">
      <h3>المهارات</h3>
      <div class="skill">
        <div style="display:flex;justify-content:space-between"><span>HTML/CSS</span><span class="meta">95%</span></div>
        <div class="bar"><i style="width:95%"></i></div>
      </div>
      <div class="skill">
        <div style="display:flex;justify-content:space-between"><span>JavaScript</span><span class="meta">85%</span></div>
        <div class="bar"><i style="width:85%"></i></div>
      </div>
      <div class="skill">
        <div style="display:flex;justify-content:space-between"><span>Design / Figma</span><span class="meta">70%</span></div>
        <div class="bar"><i style="width:70%"></i></div>
      </div>
    </section>

    <section>
      <h3>معلومات الاتصال</h3>
      <div class="meta">المدينة — الدولة</div>
      <div class="meta">البريد: your@mail.com</div>
      <div class="meta">الهاتف: +213 5X XX XX XX</div>
      <div style="margin-top:8px"><a href="#contact" style="color:var(--accent)">أرسل رسالة</a></div>
    </section>

    <section style="margin-top:14px">
      <h3>روابط</h3>
      <div class="meta"><a href="#" style="color:var(--accent)">LinkedIn</a></div>
      <div class="meta"><a href="#" style="color:var(--accent)">GitHub</a></div>
      <div class="meta"><a href="#" style="color:var(--accent)">Behance/Dribbble</a></div>
    </section>
  </aside>
</div>

<section id="contact" style="margin-top:18px;background:rgba(255,255,255,0.02);padding:16px;border-radius:12px">
  <h2>تواصل معي</h2>
  <form action="https://formspree.io/f/your-id" method="POST">
    <div style="display:flex;gap:8px;flex-wrap:wrap">
      <input name="name" placeholder="الإسم" style="flex:1;padding:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit">
      <input name="email" placeholder="البريد" style="flex:1;padding:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit">
    </div>
    <textarea name="message" placeholder="رسالتك" style="width:100%;margin-top:8px;padding:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit;height:100px"></textarea>
    <div style="margin-top:8px"><button type="submit" style="padding:10px 14px;border-radius:8px;border:none;background:var(--accent);color:#041022;font-weight:700">إرسال</button></div>
  </form>
</section>

<footer>مصنوع بواسطة — اسمك • تحديث: 2025</footer>

  </div>
</body>
</html># portfolio
