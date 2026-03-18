<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Nguyễn Thị Huyền - Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: #f4f8fb;
            color: #333;
        }

        /* HEADER */
        header {
            background: linear-gradient(135deg, #0a3d62, #3498db);
            color: white;
            padding: 30px 20px;
            display: flex;
            align-items: center;
        }

        header img {
            width: 95px;
            height: 95px;
            border-radius: 50%;
            margin-right: 20px;
            border: 3px solid white;
            object-fit: cover;
        }

        header .info h1 {
            margin: 0;
            font-size: 28px;
        }

        header .info p {
            margin: 5px 0;
            font-size: 14px;
        }

        /* CONTAINER */
        .container {
            max-width: 1000px;
            margin: 25px auto;
            padding: 0 20px;
        }

        /* SECTION */
        section {
            background: white;
            padding: 22px;
            margin-bottom: 20px;
            border-radius: 12px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.05);
        }

        h2 {
            color: #0a3d62;
            border-left: 5px solid #3498db;
            padding-left: 10px;
            margin-bottom: 15px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        /* GRID */
        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        /* FOOTER */
        footer {
            text-align: center;
            padding: 18px;
            background: #0a3d62;
            color: white;
            margin-top: 30px;
        }

        /* RESPONSIVE */
        @media(max-width: 768px) {
            .grid {
                grid-template-columns: 1fr;
            }

            header {
                flex-direction: column;
                text-align: center;
            }

            header img {
                margin-bottom: 10px;
            }
        }
    </style>
</head>

<body>

<header>
    <img src="huyen.jpg" alt="Huyền">
    <div class="info">
        <h1>Nguyễn Thị Huyền</h1>
        <p>📞 0965478835</p>
        <p>✉ nguyenhuyen06112005cbg@gmail.com</p>
        <p>📍 Đống Đa, Hà Nội</p>
    </div>
</header>

<div class="container">

    <!-- GIỚI THIỆU -->
    <section>
        <h2>Giới thiệu</h2>
        <p>
            Tôi có tinh thần trách nhiệm cao, khả năng học hỏi nhanh và làm việc nhóm tốt,
            mong muốn tìm kiếm cơ hội thực tập để phát triển bản thân và đóng góp cho doanh nghiệp.
        </p>
    </section>

    <!-- GRID 1 -->
    <div class="grid">

        <section>
            <h2>Học vấn</h2>
            <p><strong>Đại học Ngoại Thương (2023 - 2027)</strong></p>
            <p>Ngôn ngữ Trung Quốc</p>
            <p>Chuyên ngành Tiếng Trung Thương Mại</p>
        </section>

        <section>
            <h2>Kỹ năng</h2>
            <ul>
                <li>Tin học văn phòng</li>
                <li>Làm việc nhóm, tổ chức sự kiện</li>
                <li>Kỹ năng giao tiếp, xử lý tình huống</li>
                <li>Research & xử lý thông tin</li>
            </ul>
        </section>

    </div>

    <!-- KINH NGHIỆM -->
    <section>
        <h2>Kinh nghiệm làm việc</h2>
        <p><strong>Trung tâm gia sư Sư phạm (2023 - Nay)</strong></p>
        <ul>
            <li>Gia sư Toán, Văn, Anh cấp THCS, THPT</li>
        </ul>
    </section>

    <!-- GRID 2 -->
    <div class="grid">

        <section>
            <h2>Chứng chỉ</h2>
            <ul>
                <li>MOS (2024)</li>
                <li>HSK 4 (2025)</li>
            </ul>
        </section>

        <section>
            <h2>Hoạt động</h2>
            <p><strong>CLB REC FTU (10/2023 - 7/2024)</strong></p>
            <ul>
                <li>Tìm kiếm tài trợ cho sự kiện</li>
                <li>Viết email marketing, hồ sơ tài trợ</li>
                <li>Đàm phán với đối tác</li>
            </ul>
        </section>

    </div>

</div>

<footer>
    © 2026 Nguyễn Thị Huyền | Portfolio
</footer>

</body>
</html>
