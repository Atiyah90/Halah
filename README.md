<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صحتك أولاً - دعم السلوك الصحي لطلاب الجامعات</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background: #5cb85c;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: #fff;
            display: flex;
            justify-content: space-around;
            padding: 0.5rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }
        .section {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .section img {
            max-width: 100%;
            height: auto;
            margin-top: 1rem;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>صحتك أولاً</h1>
        <p>دعم السلوك الصحي لطلاب الجامعات في العراق</p>
    </header>
    <nav>
        <a href="#about">من نحن</a>
        <a href="#resources">الموارد</a>
        <a href="#tracker">متابعة السلوك</a>
        <a href="#contact">تواصل معنا</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>من نحن</h2>
            <p>"صحتك أولاً" هو موقع مخصص لدعم الطلاب الجامعيين في العراق لتحسين صحتهم الجسدية والنفسية من خلال متابعة السلوكيات الصحية وتقديم الموارد التعليمية والمشورة المتخصصة.</p>
            <img src="https://via.placeholder.com/600x300?text=%D8%A7%D9%84%D8%AD%D9%81%D8%A7%D8%B8+%D8%B9%D9%84%D9%89+%D8%A7%D9%84%D8%B5%D8%AD%D8%A9" alt="صورة توضح أهمية الصحة">
        </section>

        <section id="resources" class="section">
            <h2>الموارد</h2>
            <p>نقدم مجموعة متنوعة من المقالات والفيديوهات التي تغطي مواضيع مثل التغذية السليمة، أهمية النوم الكافي، استراتيجيات التمارين الرياضية، والتعامل مع التوتر.</p>
            <ul>
                <li><a href="#">10 نصائح للتغذية السليمة</a></li>
                <li><a href="#">أفضل التمارين للطلاب</a></li>
                <li><a href="#">كيفية إدارة وقتك للحصول على نوم كافٍ</a></li>
            </ul>
            <img src="https://via.placeholder.com/600x300?text=%D8%A7%D9%84%D8%AA%D8%BA%D8%B0%D9%8A%D8%A9+%D8%A7%D9%84%D8%B3%D9%84%D9%8A%D9%85%D8%A9" alt="صورة توضح التغذية السليمة">
        </section>

        <section id="tracker" class="section">
            <h2>متابعة السلوك الصحي</h2>
            <p>يمكنك تتبع عاداتك اليومية هنا:</p>
            <form>
                <label for="exercise">عدد دقائق التمارين اليوم:</label><br>
                <input type="number" id="exercise" name="exercise" placeholder="مثال: 30" required><br><br>

                <label for="sleep">عدد ساعات النوم:</label><br>
                <input type="number" id="sleep" name="sleep" placeholder="مثال: 7" required><br><br>

                <label for="meals">عدد الوجبات الصحية:</label><br>
                <input type="number" id="meals" name="meals" placeholder="مثال: 3" required><br><br>

                <button type="submit">إرسال البيانات</button>
            </form>
            <img src="https://via.placeholder.com/600x300?text=%D8%A7%D9%84%D9%86%D9%88%D9%85+%D8%A7%D9%84%D9%83%D8%A7%D9%81%D9%8A" alt="صورة توضح أهمية النوم الكافي">
        </section>

        <section id="contact" class="section">
            <h2>تواصل معنا</h2>
            <p>إذا كان لديك أي استفسارات أو ترغب في الحصول على استشارة صحية، لا تتردد في التواصل معنا:</p>
            <form>
                <label for="name">الاسم:</label><br>
                <input type="text" id="name" name="name" placeholder="اسمك الكامل" required><br><br>

                <label for="email">البريد الإلكتروني:</label><br>
                <input type="email" id="email" name="email" placeholder="example@example.com" required><br><br>

                <label for="message">الرسالة:</label><br>
                <textarea id="message" name="message" rows="5" placeholder="اكتب رسالتك هنا..." required></textarea><br><br>

                <button type="submit">إرسال</button>
            </form>
            <img src="https://via.placeholder.com/600x300?text=%D8%A7%D9%84%D8%AA%D9%85%D8%A7%D8%B1%D9%8A%D9%86+%D8%A7%D9%84%D8%B1%D9%8A%D8%A7%D8%B6%D9%8A%D8%A9" alt="صورة توضح أهمية التمارين الرياضية">
        </section>
    </div>
    <footer>
        <p>&copy; 2024 صحتك أولاً. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
