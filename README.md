<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Nguyễn Thị Huyền - Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #eef5ff, #d9e8ff);
            color: #333;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            display: grid;
            grid-template-columns: 300px 1fr;
            gap: 25px;
        }

        /* LEFT PANEL */
        .left {
            background: linear-gradient(180deg, #0a3d62, #3498db);
            color: white;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .left img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            margin-bottom: 15px;
            object-fit: cover;
        }

        .left h1 {
            font-size: 22px;
            margin-bottom: 10px;
        }

        .left p {
            font-size: 14px;
            margin: 6px 0;
        }

        /* RIGHT PANEL */
        .right {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .card {
            background: white;
            padding: 22px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.05);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        h2 {
            color: #0a3d62;
            margin-bottom: 15px;
            border-left: 5px solid #3498db;
            padding-left: 10px;
        }

        /* SKILL BAR */
        .skill {
            margin-bottom: 12px;
        }

        .skill span {
            font-size: 14px;
        }

        .bar {
            height: 8px;
            background: #ddd;
            border-radius: 10px;
            margin-top: 5px;
            overflow: hidden;
        }

        .bar div {
            height: 100%;
            background: #3498db;
        }

        /* TIMELINE */
        .timeline {
            border-left: 3px solid #3498db;
            padding-left: 15px;
        }

        .timeline-item {
            margin-bottom: 15px;
        }

        .timeline-item h4 {
            color: #0a3d62;
        }

        /* RESPONSIVE */
        @media(max-width: 900px) {
            .container {
                grid-template-columns: 1fr;
            }
        }

    </style>
</head>

<body>

<div class="container">

    <!-- LEFT -->
    <div class="left">
        <img src="huyen.jpg" alt="Huyền">
        <h1>Nguyễn Thị Huyền</h1>
        <p>📞 0965478835</p>
        <p>✉ nguyenhuyen06112005cbg@gmail.com</p>
        <p>📍 Đống Đa, Hà Nội</p>
    </div>

    <!-- RIGHT -->
    <div class="right">

        <div class="card">
            <h2>Giới thiệu</h2>
            <p>
                Tôi có tinh thần trách nhiệm cao, khả năng học hỏi nhanh và làm việc nhóm tốt,
                mong muốn tìm kiếm cơ hội thực tập để phát triển bản thân và đóng góp cho doanh nghiệp.
            </p>
        </div>

        <div class="card">
            <h2>Học vấn</h2>
            <p><strong>Đại học Ngoại Thương (2023 - 2027)</strong></p>
            <p>Ngôn ngữ Trung Quốc</p>
            <p>Chuyên ngành Tiếng Trung Thương Mại</p>
        </div>

        <div class="card">
            <h2>Kỹ năng</h2>

            <div class="skill">
                <span>Tin học văn phòng</span>
                <div class="bar"><div style="width:90%"></div></div>
            </div>

            <div class="skill">
                <span>Làm việc nhóm</span>
                <div class="bar"><div style="width:85%"></div></div>
            </div>

            <div class="skill">
                <span>Giao tiếp</span>
                <div class="bar"><div style="width:88%"></div></div>
            </div>

            <div class="skill">
                <span>Research</span>
                <div class="bar"><div style="width:80%"></div></div>
            </div>

        </div>

        <div class="card">
            <h2>Kinh nghiệm</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <h4>2023 - Nay</h4>
                    <p><strong>Trung tâm gia sư Sư phạm</strong></p>
                    <p>Gia sư Toán, Văn, Anh cấp THCS, THPT</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Hoạt động</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <h4>10/2023 - 7/2024</h4>
                    <p><strong>CLB REC FTU</strong></p>
                    <p>Tìm kiếm tài trợ, viết email marketing, đàm phán đối tác</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Chứng chỉ</h2>
            <ul>
                <li>MOS (2024)</li>
                <li>HSK 4 (2025)</li>
            </ul>
        </div>

    </div>

</div>

</body>
</html>
