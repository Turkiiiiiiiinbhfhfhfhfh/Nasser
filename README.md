# Nasser
Tourism company
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الباقات السياحية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .package {
            background-color: #ffffff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .package h2 {
            color: #4CAF50;
            font-size: 24px;
            margin-bottom: 15px;
        }

        .package p {
            font-size: 18px;
            line-height: 1.6;
        }

        .price {
            font-size: 22px;
            font-weight: bold;
            color: #f39c12;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
        }

        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>الباقات السياحية</h1>
</header>

<div class="container">
    <!-- باقة برونزية -->
    <div class="package">
        <h2>الباقة البرونزية</h2>
        <p class="price">600 ريال</p>
        <p>الرحلة إلى محافظة الوجه تشمل:</p>
        <ul>
            <li>إقامة لمدة يومين</li>
            <li>زيارة الأماكن السياحية المشهورة</li>
            <li>تذكرة العودة</li>
            <li>سيارة لنقلك من المطار</li>
        </ul>
        <a href="#" class="button">احجز الآن</a>
    </div>

    <!-- باقة فضية -->
    <div class="package">
        <h2>الباقة الفضية</h2>
        <p class="price">850 ريال</p>
        <p>الرحلة تشمل:</p>
        <ul>
            <li>إقامة لمدة 4 أيام في الفندق</li>
            <li>رحلات سياحية مجانية</li>
            <li>تذكرة العودة</li>
            <li>سيارة لنقلك من المطار</li>
        </ul>
        <a href="#" class="button">احجز الآن</a>
    </div>

    <!-- باقة ذهبية -->
    <div class="package">
        <h2>الباقة الذهبية</h2>
        <p class="price">1100 ريال</p>
        <p>الرحلة تشمل:</p>
        <ul>
            <li>رحلات سياحية شاملة</li>
            <li>تذكرة العودة</li>
            <li>سيارة لنقلك من المطار</li>
            <li>إقامة في الفندق لمدة أسبوع</li>
            <li>وجبات مفتوحة في الفندق</li>
        </ul>
        <a href="#" class="button">احجز الآن</a>
    </div>
</div>

</body>
</html>
