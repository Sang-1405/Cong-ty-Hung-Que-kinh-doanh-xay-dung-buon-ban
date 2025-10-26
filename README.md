<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Công Ty Hưng Quế kinh doanh</title>
  <style>
    :root{
      --primary:#2196f3;
      --accent:#1565c0;
      --brand-red:#d32f2f;
      --bg:#e3f2fd;
      --card:#fff;
      --muted:#5c7fa3;
      --dark:#0d2240;
      --radius:12px;
      --max-width:1200px;
    }
    *{box-sizing:border-box}
    body{font-family:Arial, Helvetica, sans-serif;background:var(--bg);color:var(--dark);line-height:1.5;margin:0}
    a{color:var(--accent)}
    header.site-header{display:flex;align-items:center;justify-content:space-between;padding:10px 16px;background:var(--card);border-bottom:1px solid #cce1ff;position:sticky;top:0;z-index:60}
    .brand{font-weight:700;color:var(--brand-red);font-size:22px;letter-spacing:0.5px;}
    .main-nav{display:flex;gap:10px;align-items:center}
    .nav-link{padding:8px 10px;border-radius:8px;color:var(--dark);text-decoration:none}
    .nav-link:hover,.nav-link.active{background:#e3f2fd;color:var(--accent)}
    .header-contact{font-size:14px;color:var(--muted);display:flex;align-items:center;gap:8px}
    .header-contact a{color:var(--accent);font-weight:600;text-decoration:none}
    .mobile-toggle{display:none;background:transparent;border:0;font-size:20px;padding:6px;cursor:pointer;color:var(--accent)}
    .container{max-width:var(--max-width);margin:0 auto;padding:18px}
    .hero{display:grid;grid-template-columns:1fr 1fr;gap:20px;align-items:center;padding:24px;background:var(--card);border-radius:12px;box-shadow:0 6px 24px rgba(33,150,243,0.09)}
    .hero h1{margin:0 0 12px;font-size:28px;color:var(--primary)}
    .hero p{color:var(--muted)}
    .hero img{width:100%;border-radius:10px;display:block;box-shadow:0 4px 16px rgba(33,150,243,0.08)}
    h2{margin-bottom:12px;color:var(--primary)}
  </style>
</head>
<body>
  <header class="site-header">
    <div class="brand">Công Ty Hưng Quế kinh doanh</div>
    <nav class="main-nav" aria-label="main navigation">
      <a class="nav-link active" href="#home">Trang chủ</a>
      <a class="nav-link" href="#gioi-thieu">Giới thiệu</a>
      <a class="nav-link" href="#dich-vu">Dịch vụ</a>
      <a class="nav-link" href="#san-pham">Sản phẩm</a>
      <a class="nav-link" href="#lien-he">Liên hệ</a>
    </nav>
    <div class="header-contact">
      <span class="small">Điện thoại:</span>
      <a href="tel:0914414368">0914414368</a>
      <span class="sep">|</span>
      <span class="small">Hotline:</span>
      <a href="tel:0944215456">0944215456</a>
    </div>
    <button class="mobile-toggle" aria-label="Mở menu">☰</button>
  </header>

  <main class="container">
    <section id="home" class="hero">
      <div>
        <h1>Giải pháp vật liệu & thiết bị cho mọi công trình</h1>
        <p>Hưng Quế cung cấp vật liệu xây dựng, nội thất, thiết bị điện nước. Đồng hành cùng bạn xây dựng những công trình bền vững.</p>
        <p>
          <a class="btn primary" href="#san-pham">Xem sản phẩm</a>
          <a class="btn" href="#lien-he">Liên hệ ngay</a>
        </p>
      </div>
      <div>
        <img src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg" alt="Showroom Hưng Quế">
      </div>
    </section>

    <section id="gioi-thieu" class="section">
      <h2>Giới thiệu công ty Hưng Quế</h2>
      <p>Hưng Quế là đơn vị phân phối vật liệu xây dựng, nội thất và thiết bị điện nước. Chúng tôi cung cấp giải pháp toàn diện cho nhà thầu, chủ đầu tư và hộ gia đình.</p>
      <img 
        src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg"
        alt="Mặt tiền Công ty Hưng Quế"
        style="width:100%;max-width:700px;display:block;margin:18px auto 8px auto;border-radius:12px;box-shadow:0 4px 18px rgba(33,150,243,0.10)"
      >
      <div class="video-wrapper">
        <iframe
          src="https://www.youtube.com/embed/NqTrCk04Qok"
          title="Giới thiệu Hưng Quế"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
          loading="lazy"></iframe>
      </div>
    </section>
