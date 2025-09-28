<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>আমার ডিজিটাল এজেন্সি - পেশাদার ওয়েবসাইট ডিজাইন</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
        body { line-height: 1.6; color: #333; scroll-behavior: smooth; }
        .navbar { background: #2c3e50; padding: 1rem 0; position: fixed; width: 100%; top: 0; z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        .nav-container { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 0 2rem; }
        .logo { color: white; font-size: 1.8rem; font-weight: bold; text-decoration: none; }
        .nav-links a { color: white; text-decoration: none; margin-left: 2rem; transition: color 0.3s; font-weight: 500; }
        .nav-links a:hover { color: #3498db; }
        .hero { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 180px 0 100px; text-align: center; }
        .hero h1 { font-size: 3rem; margin-bottom: 1rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        .hero p { font-size: 1.2rem; max-width: 600px; margin: 0 auto 2rem; opacity: 0.9; }
        .btn { background: #e74c3c; color: white; border: none; padding: 15px 30px; border-radius: 5px; font-size: 1.1rem; cursor: pointer; transition: all 0.3s; font-weight: bold; }
        .btn:hover { background: #c0392b; transform: translateY(-2px); box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 2rem; }
        .services { padding: 80px 0; background: #f8f9fa; }
        .section-title { text-align: center; margin-bottom: 3rem; }
        .section-title h2 { font-size: 2.5rem; color: #2c3e50; margin-bottom: 1rem; }
        .section-title p { color: #666; font-size: 1.1rem; max-width: 600px; margin: 0 auto; }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .service-card { background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); text-align: center; transition: all 0.3s; border: 1px solid #eee; }
        .service-card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.15); }
        .service-card h3 { color: #2c3e50; margin-bottom: 1rem; font-size: 1.4rem; }
        .service-card p { color: #666; line-height: 1.6; }
        .contact { padding: 80px 0; background: white; }
        .contact-form { max-width: 600px; margin: 0 auto; background: #f8f9fa; padding: 2rem; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .form-group { margin-bottom: 1.5rem; }
        .form-group label { display: block; margin-bottom: 0.5rem; color: #333; font-weight: 500; }
        .form-group input, .form-group textarea { width: 100%; padding: 12px; border: 1px solid #ddd; border-radius: 5px; font-size: 1rem; transition: border-color 0.3s; }
        .form-group input:focus, .form-group textarea:focus { outline: none; border-color: #3498db; box-shadow: 0 0 5px rgba(52, 152, 219, 0.3); }
        .form-group textarea { height: 120px; resize: vertical; }
        footer { background: #2c3e50; color: white; padding: 2rem 0; text-align: center; }
        .footer-content { max-width: 1200px; margin: 0 auto; padding: 0 2rem; }
        .social-links { margin: 1rem 0; }
        .social-links a { color: white; text-decoration: none; margin: 0 10px; font-size: 1.2rem; }
        @media (max-width: 768px) {
            .nav-container { flex-direction: column; text-align: center; }
            .nav-links { margin-top: 1rem; }
            .nav-links a { margin: 0 0.5rem; font-size: 0.9rem; }
            .hero h1 { font-size: 2rem; }
            .hero p { font-size: 1rem; padding: 0 1rem; }
            .services-grid { grid-template-columns: 1fr; }
        }
        @media (max-width: 480px) {
            .nav-links a { margin: 0 0.3rem; font-size: 0.8rem; }
            .hero { padding: 150px 0 80px; }
            .hero h1 { font-size: 1.8rem; }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <a href="#home" class="logo">Skill Zone Agency</a>
            <div class="nav-links">
                <a href="#home">হোম</a>
                <a href="#services">সেবাসমূহ</a>
                <a href="#contact">যোগাযোগ</a>
            </div>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="container">
            <h1>পেশাদার ডিজিটাল মার্কেটিং সমাধান</h1>
            <p>আপনার ব্যবসাকে ডিজিটাল জগতে নিয়ে যান আমাদের এক্সপার্ট টিমের সাথে</p>
            <button class="btn" onclick="scrollToContact()">বিনামূল্য কনসাল্টেশন নিন</button>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <div class="section-title">
                <h2>আমাদের সেবাসমূহ</h2>
                <p>আমরা comprehensive ডিজিটাল মার্কেটিং সলিউশন অফার করি</p>
            </div>
            <div class="services-grid">
                <div class="service-card"><h3>ওয়েবসাইট ডিজাইন</h3><p>আধুনিক এবং রেস্পন্সিভ ওয়েবসাইট ডিজাইন</p></div>
                <div class="service-card"><h3>এসইও সার্ভিস</h3><p>গুগলে প্রথম পেজে আনার গ্যারান্টি</p></div>
                <div class="service-card"><h3>সোশ্যাল মিডিয়া মার্কেটিং</h3><p>ফেসবুক, ইনস্টাগ্রাম মার্কেটিং</p></div>
                <div class="service-card"><h3>কন্টেন্ট মার্কেটিং</h3><p>মানসম্পন্ন কন্টেন্ট তৈরি</p></div>
                <div class="service-card"><h3>ই-কমার্স সলিউশন</h3><p>অনলাইন স্টোর তৈরি</p></div>
                <div class="service-card"><h3>ব্র্যান্ডিং</h3><p>পেশাদার ব্র্যান্ড আইডেন্টিটি</p></div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <div class="section-title">
                <h2>যোগাযোগ করুন</h2>
                <p>আমাদের সাথে কাজ করতে চাইলে নিচের ফর্মটি পূরণ করুন</p>
            </div>
            <div class="contact-form">
                <form id="contactForm">
                    <div class="form-group"><label for="name">আপনার নাম</label><input type="text" id="name" name="name" required placeholder="আপনার পুরো নাম"></div>
                    <div class="form-group"><label for="email">ইমেইল ঠিকানা</label><input type="email" id="email" name="email" required placeholder="আপনার ইমেইল"></div>
                    <div class="form-group"><label for="phone">ফোন নম্বর</label><input type="tel" id="phone" name="phone" placeholder="আপনার ফোন নম্বর"></div>
                    <div class="form-group"><label for="message">আপনার মেসেজ</label><textarea id="message" name="message" required placeholder="আপনার প্রয়োজনীয়তা লিখুন..."></textarea></div>
                    <button type="submit" class="btn" style="width: 100%;">মেসেজ পাঠান</button>
                </form>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <h3>Skill Zone Agency</h3>
            <p>ডিজিটাল জগতে আপনার ব্যবসার সেরা পার্টনার</p>
            <div class="social-links">
                <a href="#">📘 Facebook</a>
                <a href="#">📷 Instagram</a>
                <a href="#">💼 LinkedIn</a>
                <a href="#">📞 WhatsApp</a>
            </div>
            <p>ইমেইল: contact@skillzone.com | ফোন: ০১৭XX-XXXXXX</p>
            <p>ঠিকানা: আপনার ব্যবসার ঠিকানা, শহর, বাংলাদেশ</p>
            <p>&copy; ২০২৪ Skill Zone Agency। সকল অধিকার সংরক্ষিত।</p>
        </div>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) { target.scrollIntoView({ behavior: 'smooth', block: 'start' }); }
            });
        });
        function scrollToContact() { document.getElementById('contact').scrollIntoView({ behavior: 'smooth' }); }
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const formData = new FormData(this);
            const name = formData.get('name');
            const email = formData.get('email');
            alert(`ধন্যবাদ ${name}! আপনার মেসেজটি আমরা পেয়েছি। শীঘ্রই আমরা ${email} এ যোগাযোগ করব।`);
            this.reset();
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 100) {
                navbar.style.background = 'rgba(44, 62, 80, 0.95)';
                navbar.style.backdropFilter = 'blur(10px)';
            } else {
                navbar.style.background = '#2c3e50';
                navbar.style.backdropFilter = 'none';
            }
        });
    </script>
</body>
</html>
