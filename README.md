# QAz
موقع لمتجر تطبيقات
<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر APK بسيط</title>
    <style>
        body {
            margin: 0;
            font-family: sans-serif;
            background: #f5f5f5;
            color: #222;
        }
        header {
            background: #ffffff;
            padding: 15px;
            text-align: center;
            font-size: 22px;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .container {
            width: 90%;
            margin: 20px auto;
        }
        .app-card {
            background: #fff;
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 12px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: center;
            gap: 15px;
        }
        .app-card img {
            width: 70px;
            height: 70px;
            border-radius: 10px;
        }
        .app-info h3 {
            margin: 0;
            font-size: 20px;
        }
        .app-info p {
            margin: 5px 0 0 0;
            color: #555;
            font-size: 14px;
        }
        .download-btn {
            margin-left: auto;
            background: #007bff;
            color: #fff;
            padding: 10px 15px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>متجر تحميل تطبيقات APK</header><div class="container">

    <!-- مثال تطبيق جاهز -->
    <div class="app-card">
        <img src="https://via.placeholder.com/70" alt="app">
        <div class="app-info">
            <h3>اسم التطبيق</h3>
            <p>وصف مختصر للتطبيق يوضح وظيفته.</p>
        </div>
        <a class="download-btn" href="apk/app1.apk">تحميل</a>
    </div>

</div>

</body>
</html>
