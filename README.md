<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Buffet Thịt Nướng Đức</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', Arial;
    background: #111;
    color: #fff;
}

/* HEADER */
header {
    background: linear-gradient(90deg, #b71c1c, #000);
    text-align: center;
    padding: 25px;
}

header img {
    width: 200px;
    animation: zoom 2s infinite alternate;
}

@keyframes zoom {
    from { transform: scale(1); }
    to { transform: scale(1.05); }
}

header h1 {
    color: #ffcc80;
    margin: 10px 0 5px;
}

header p {
    color: #ffd180;
    font-style: italic;
}

/* BANNER */
.banner {
    background-image: url("https://images.unsplash.com/photo-1553163147-622ab57be1c7");
    background-size: cover;
    background-position: center;
    height: 320px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.banner h2 {
    background: rgba(0,0,0,0.6);
    padding: 20px 30px;
    border-radius: 12px;
    color: #ffeb3b;
    font-size: 30px;
}

/* SECTION */
section {
    padding: 50px 20px;
    text-align: center;
}

section h2 {
    color: #ff7043;
    margin-bottom: 20px;
}

/* MENU */
.menu {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

.menu-item {
    background: #222;
    border-radius: 15px;
    width: 260px;
    padding: 25px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.menu-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 20px #ff5722;
}

.menu-item h3 {
    color: #ffab91;
}

/* BUTTON */
button {
    background: linear-gradient(45deg, #ff5722, #ff9800);
    border: none;
    padding: 15px 30px;
    font-size: 18px;
    color: white;
    border-radius: 30px;
    cursor: pointer;
}

button:hover {
    opacity: 0.85;
}

/* FOOTER */
footer {
    background: black;
    padding: 15px;
    text-align: center;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <img src="logo-duc.png" alt="Buffet Đức">
    <h1>BUFFET THỊT NƯỚNG ĐỨC</h1>
    <p>Phong cách Hàn Quốc – Hương vị Việt Nam</p>
</header>

<div class="banner">
    <h2>🔥 Ăn là ghiền – Nướng là mê 🔥</h2>
</div>

<section>
    <h2>Giới thiệu</h2>
    <p>
        Buffet thịt nướng đậm chất Hàn Quốc kết hợp hương vị Việt Nam,
        thịt tươi – sốt độc quyền – không giới hạn.
    </p>
</section>

<section>
    <h2>Menu nổi bật</h2>
    <div class="menu">
        <div class="menu-item">
            <h3>🥩 Ba chỉ bò Mỹ</h3>
            <p>Ướp sốt cay ngọt đặc trưng</p>
        </div>
        <div class="menu-item">
            <h3>🍖 Sườn heo nướng</h3>
            <p>Mềm – thơm – đậm vị</p>
        </div>
        <div class="menu-item">
            <h3>🦐 Hải sản nướng</h3>
            <p>Tôm – mực – sò tươi sống</p>
        </div>
    </div>
</section>

<section>
    <h2>Đặt bàn ngay</h2>
    <p>Hotline: 090x xxx xxx</p>
    <button onclick="alert('Chức năng đặt bàn sẽ được mở sớm 😊')">
        ĐẶT BÀN NGAY
    </button>
</section>

<footer>
    © 2025 Buffet Thịt Nướng Đức | Chủ quán: Nguyễn Duy Đức
</footer>

</body>
</html>
