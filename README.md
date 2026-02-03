
[INDEX02.html](https://github.com/user-attachments/files/25029354/INDEX02.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قسم التسويق والشراكات الاحترافي</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --main-gradient: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
            --text-main: #1f2937;
            --bg-light: #f3f4f6;
            --shadow: 0 10px 15px rgba(0,0,0,0.1);
        }

        body { 
            font-family: 'Cairo', sans-serif; 
            background-color: var(--bg-light); 
            padding: 40px 20px; 
            direction: rtl; 
            margin: 0;
        }

        .container { max-width: 1100px; margin: auto; }
        
        .section-title { text-align: center; margin-bottom: 50px; }
        .section-title h1 { color: var(--text-main); font-size: 2.2rem; }
        .section-title h1 span { color: #3b82f6; border-bottom: 3px solid #fbbf24; }

        .grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); 
            gap: 30px; 
        }
        
        .card { 
            background: white; 
            border-radius: 24px; 
            overflow: hidden; 
            box-shadow: var(--shadow); 
            display: flex; 
            flex-direction: column; 
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid rgba(0,0,0,0.05);
        }
        .card:hover { transform: translateY(-8px); box-shadow: 0 15px 30px rgba(0,0,0,0.15); }
        
        .card-icon { background: var(--main-gradient); padding: 35px; text-align: center; font-size: 45px; }
        .card-content { padding: 30px; text-align: center; flex-grow: 1; display: flex; flex-direction: column; }
        
        .card-content h3 { margin: 0 0 15px 0; color: var(--text-main); font-size: 1.4rem; }
        .card-content p { color: #6b7280; font-size: 0.95rem; margin-bottom: 25px; flex-grow: 1; line-height: 1.7; }

        .btn-group { display: flex; flex-direction: column; gap: 12px; }
        .btn-row { display: flex; gap: 10px; justify-content: center; }

        .base-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 12px 20px;
            border-radius: 12px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            font-size: 0.9rem;
            transition: 0.3s;
            border: none;
            cursor: pointer;
        }

        .fb-btn { background-color: #1877f2; flex: 1; }
        .ig-btn { background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%,#d6249f 60%,#285AEB 90%); flex: 1; }

        .email-btn { background-color: #34495e; }
        .whatsapp-btn { background-color: #25d366; }

        .schedule-btn { background-color: #1e3a8a; }
        .register-btn { background-color: #f59e0b; color: #1e293b; }

        .base-btn:hover { opacity: 0.9; transform: scale(1.03); }
    </style>
</head>
<body>

<div class="container">
    <div class="section-title">
        <h1><span></span> التسويق والشراكات</h1>
    </div>

    <div class="grid">
        <div class="card">
            <div class="card-icon">📱</div>
            <div class="card-content">
                <h3>التواجد الرقمي</h3>
                <p>بناء مجتمع تفاعلي عبر منصاتنا لمشاركة أحدث الأخبار والوصول لجمهورنا المستهدف.</p>
                <div class="btn-row">
                    <a href="https://facebook.com/YOUR_PAGE" target="_blank" class="base-btn fb-btn">فيسبوك</a>
                    <a href="https://instagram.com/YOUR_ACCOUNT" target="_blank" class="base-btn ig-btn">إنستغرام</a>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-icon">🤝</div>
            <div class="card-content">
                <h3>التعاون المؤسسي</h3>
                <p>عقد اتفاقيات استراتيجية مع المدارس والأندية المحلية لتبادل الخبرات وتوسيع قاعدة المستفيدين.</p>
                <div class="btn-group">
                    <a href="mailto:office@yourdomain.com" class="base-btn email-btn">📧 مراسلة رسمية</a>
                    <a href="https://wa.me/212600000000" target="_blank" class="base-btn whatsapp-btn">💬 واتساب الشراكات</a>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-icon">🏆</div>
            <div class="card-content">
                <h3>الفعاليات الرياضية</h3>
                <p>تنظيم دوريات محلية احترافية تهدف إلى اكتشاف المواهب وتعزيز الروح الرياضية في المجتمع.</p>
                <div class="btn-group">
                    <a href="#" class="base-btn schedule-btn">📅 جدول الدوريات</a>
                    <a href="register.html" target="_blank" class="base-btn register-btn">📝 سجل فريقك الآن</a>
                </div>
            </div>
        </div>
    </div>
</div>

</body>
</html>
