<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Nguyễn Thị Huyền Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: linear-gradient(135deg, #cfd9df, #e2ebf0);
}

/* HEADER */
header {
    background: linear-gradient(135deg, #a1c4fd, #fbc2eb);
    padding: 40px;
    border-bottom-left-radius: 30px;
    border-bottom-right-radius: 30px;
}

.header-container {
    display: flex;
    align-items: center;
    gap: 30px;
    flex-wrap: wrap;
}

.avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid white;
}

.info h1 {
    font-size: 34px;
}

.info p {
    margin-top: 5px;
    color: #333;
}

/* CARD */
.card {
    background: white;
    max-width: 900px;
    margin: 30px auto;
    padding: 25px;
    border-radius: 20px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.card h2 {
    margin-bottom: 15px;
}

/* LIST */
ul {
    padding-left: 20px;
}

/* SKILL TAG */
.tags span {
    display: inline-block;
    background: #e0ecff;
    padding: 8px 15px;
    border-radius: 20px;
    margin: 5px;
    font-size: 14px;
}

/* CONTACT */
.contact a {
    display: block;
    margin-top: 5px;
    color: #0077cc;
    text-decoration: none;
}
</style>
</head>

<body>

<header>
    <div class="header-container">
        <!-- ẢNH CỦA BẠN -->
        <img src="Huyền.jpg" class="avatar">

        <div class="info">
            <h1>Nguyễn Thị Huyền</h1>
            <p>Business Chinese • Foreign Trade University</p>
            <p>📍 Hà Nội | 📧 k62.2311720018@ftu.edu.vn</p>
            <p><i>今天的努力，是为了明天更好的自己</i></p>
        </div>
    </div>
</header>

<div class="card">
    <h2>Giới thiệu</h2>
    <p>
        Mình là sinh viên Đại học Ngoại thương, chuyên ngành Tiếng Trung thương mại.
        Mình có khả năng học nhanh, làm việc nhóm ổn và khá cẩn thận trong công việc.
        Hiện tại mình đang tìm cơ hội thực tập để học hỏi thêm kinh nghiệm thực tế.
    </p>
</div>

<div class="card">
    <h2>Học vấn</h2>
    <p><b>Đại học Ngoại thương</b> (10/2023 – nay)</p>
    <p>Chuyên ngành: Tiếng Trung Thương mại</p>
    <p>Định hướng phát triển trong lĩnh vực kinh doanh quốc tế</p>
</div>

<div class="card">
    <h2>Kinh nghiệm</h2>

    <p><b>Gia sư Toán THPT</b> (11/2022 – nay)</p>
    <ul>
        <li>Giúp học sinh nâng điểm Toán từ 5 → 9</li>
        <li>Rèn kỹ năng giảng dạy và quản lý thời gian</li>
    </ul>
</div>

<div class="card">
    <h2>Hoạt động & Kỹ năng</h2>
    <p>Vòng chung kết “Cuộc thi viết chữ Hán đẹp” 2023 – FTU</p>

    <div class="tags">
        <span>Tiếng Trung tốt</span>
        <span>Tiếng Anh khá</span>
        <span>Word</span>
        <span>Excel</span>
        <span>PowerPoint</span>
        <span>Làm việc nhóm</span>
        <span>Quản lý thời gian</span>
    </div>
</div>

<div class="card">
    <h2>Liên hệ</h2>
    <div class="contact">
      <p>📧 <a href="mailto:k62.2311720018@ftu.edu.vn">
k62.2311720018@ftu.edu.vn
</a></p>
</div>

</body>
</html>
