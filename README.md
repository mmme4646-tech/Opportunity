# Opportunity
My own website 
<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعي الشخصي</title>
    <style>
        body {
            margin: 0;
            font-family: 'Tahoma', sans-serif;
            background: linear-gradient(to bottom, #f0f0f0, #d0e7ff);
            color: #333;
        }
        header {
            text-align: center;
            padding: 60px 20px;
            animation: fadeIn 1.5s ease-in-out;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2em;
            color: #555;
        }
        .section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            width: 150px;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
        }
        .card img {
            width: 40px;
            margin-bottom: 10px;
        }
        .articles ul {
            list-style: none;
            padding: 0;
        }
        .articles li {
            background: white;
            margin-bottom: 10px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .contact p {
            text-align: center;
            margin: 5px 0;
        }
        @keyframes fadeIn {
            from {opacity: 0; transform: translateY(-20px);}
            to {opacity: 1; transform: translateY(0);}
        }
        @media (max-width: 600px) {
            .links {
                flex-direction: column;
                align-items: center;
            }
            .card {
                width: 80%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحباً بك في موقعي الشخصي</h1>
        <p>اكتشف روابطي ومقالاتي</p>
    </header><section class="section">
    <h2>روابطي</h2>
    <div class="links">
        <div class="card">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="تويتر">
            <a href="#">تويتر</a>
        </div>
        <div class="card">
            <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="لينكدإن">
            <a href="#">لينكد إن</a>
        </div>
        <div class="card">
            <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="جيت هاب">
            <a href="#">جيت هاب</a>
        </div>
    </div>
</section>

<section class="section articles">
    <h2>مقالاتي</h2>
    <ul>
        <li>
            <span>عنوان المقال الأول</span>
            <span>2025-08-12</span>
        </li>
        <li>
            <span>عنوان المقال الثاني</span>
            <span>2025-08-10</span>
        </li>
    </ul>
</section>

<section class="section contact">
    <h2>التواصل</h2>
    <p>البريد الإلكتروني: example@email.com</p>
    <p>رقم الهاتف: 0123456789</p>
</section>

</body>
</html>
