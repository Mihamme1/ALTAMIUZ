<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALTAMIUZ - حيث التميز بلا حدود</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<!-- Header Section -->
<header class="text-center py-5 bg-dark text-white">
    <h1 class="display-4">ALTAMIUZ</h1>
    <p class="lead">حيث التميز بلا حدود</p>
    <p class="mt-3">مع التميز، لا حدود للإبداع</p>
</header>

<!-- About Us Section -->
<section class="py-5 bg-light">
    <div class="container">
        <h2 class="text-center mb-4">نبذة عنا</h2>
        <p class="text-center">نعمل على تقديم حلول دعائية وإعلانية مميزة تلبي احتياجات عملائنا وتحقق أهدافهم.</p>
    </div>
</section>

<!-- Services Section -->
<section class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">خدماتنا</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">تصميم الهوية البصرية</h5>
                        <p class="card-text">شعار، كروت الزيارة، بطاقات العمل، إلخ.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">الحملات الإعلانية</h5>
                        <p class="card-text">تصميم وإدارة حملات إعلانية على الإنترنت والوسائل التقليدية.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">إدارة وسائل التواصل الاجتماعي</h5>
                        <p class="card-text">إدارة الحسابات وزيادة التفاعل.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section class="py-5 bg-dark text-white">
    <div class="container">
        <h2 class="text-center mb-4">تواصل معنا</h2>
        <p class="text-center">للأسئلة والاستفسارات:</p>
        <ul class="list-unstyled text-center">
            <li><strong>هاتف:</strong> +249120286928 / +249992350850</li>
            <li><strong>بريد إلكتروني:</strong> alwathqmohammed@gmail.com</li>
            <li><strong>الموقع:</strong> أم روابة، السودان</li>
        </ul>
    </div>
</section>

<!-- Footer -->
<footer class="bg-black text-white text-center py-3">
    <p>&copy; 2023 ALTAMIUZ. جميع الحقوق محفوظة.</p>
</footer>

<script src="js/script.js"></script>
</body>
</html>/* General Styles */
body {
    font-family: Arial, sans-serif;
    color: #333;
}

header {
    background-color: #000 !important;
    color: #fff;
}

.bg-dark {
    background-color: #333 !important;
}

.text-gold {
    color: gold;
}

/* Cards Styling */
.card {
    border: none;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
}

/* Footer */
footer {
    background-color: #000;
    color: #fff;
}<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALTAMIUZ - تواصل معنا</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<!-- Header -->
<header class="text-center py-5 bg-dark text-white">
    <h1 class="display-4">ALTAMIUZ</h1>
    <p class="lead">تواصل معنا</p>
</header>

<!-- Contact Form -->
<section class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">نموذج الاتصال</h2>
        <form action="submit_form.php" method="POST">
            <div class="mb-3">
                <label for="name" class="form-label">الاسم:</label>
                <input type="text" class="form-control" id="name" name="name" required>
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">البريد الإلكتروني:</label>
                <input type="email" class="form-control" id="email" name="email" required>
            </div>
            <div class="mb-3">
                <label for="phone" class="form-label">رقم الهاتف:</label>
                <input type="tel" class="form-control" id="phone" name="phone">
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">الرسالة:</label>
                <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">إرسال</button>
        </form>
    </div>
</section>

<!-- Footer -->
<footer class="bg-black text-white text-center py-3">
    <p>&copy; 2023 ALTAMIUZ. جميع الحقوق محفوظة.</p>
</footer>

</body>
</html>
