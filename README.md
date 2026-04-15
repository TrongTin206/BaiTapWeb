<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Java OOP Project</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: #0f172a;
            color: white;
        }

        .header {
            text-align: center;
            padding: 40px;
            background: linear-gradient(90deg, #ff4d4d, #4d79ff);
        }

        .header h1 {
            margin: 0;
            font-size: 40px;
        }

        .container {
            padding: 30px;
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 0 10px rgba(255,255,255,0.1);
        }

        .card h2 {
            color: #38bdf8;
        }

        .footer {
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            background: #111827;
        }

        button {
            padding: 10px 15px;
            border: none;
            background: #22c55e;
            color: white;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #16a34a;
        }
    </style>
</head>

<body>

    <div class="header">
        <h1>☕ Java OOP Project</h1>
        <p>Thiết kế web đơn giản bằng HTML + CSS</p>
    </div>

    <div class="container">

        <div class="card">
            <h2>📋 Class & Object</h2>
            <p>Hiểu cách tạo class và object trong Java.</p>
        </div>

        <div class="card">
            <h2>🔐 Encapsulation</h2>
            <p>Đóng gói dữ liệu bằng private + getter/setter.</p>
        </div>

        <div class="card">
            <h2>⚙️ Constructor</h2>
            <p>Hàm khởi tạo giúp tạo object nhanh hơn.</p>
        </div>

        <div class="card">
            <h2>🚀 Thực hành</h2>
            <p>Áp dụng OOP vào bài tập thực tế.</p>
            <button onclick="alert('Xin chào Java OOP!')">Bấm thử</button>
        </div>

    </div>

    <div class="footer">
        © 2026 Java OOP Project | Designed by Student
    </div>

</body>
</html>
