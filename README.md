<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH | kimgiakhanh.com - Vật Liệu Xây Dựng & Nội Thất Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH (kimgiakhanh.com) - Chuyên phân phối Sơn, Thiết bị vệ sinh, Gạch men, Ngói lợp, Bồn nước, Bình nóng lạnh, Keo dán gạch chính hãng tại 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng. Hotline: 0905.119.918">
  <meta name="keywords" content="Kim Gia Khánh, kimgiakhanh.com, vật liệu xây dựng Đà Nẵng, thiết bị vệ sinh Đà Nẵng, sơn Jotun Đà Nẵng, gạch men Đồng Tâm, 631 Ngô Quyền">

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://kimgiakhanh.com/">
  <meta property="og:title" content="CÔNG TY TNHH MTV KIM GIA KHÁNH - Vật Liệu Xây Dựng & Nội Thất Chính Hãng">
  <meta property="og:description" content="Địa chỉ: 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng - Hotline/Zalo: 0905.119.918. Phân phối Sơn, Thiết bị vệ sinh, Gạch men, Ngói lợp, Bồn nước, Bình nóng lạnh.">
  <meta property="og:image" content="https://placehold.co/1200x630/0b3b75/f59e0b?text=KIM+GIA+KHANH+-+kimgiakhanh.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://placehold.co/1200x630/0b3b75/f59e0b?text=KIM+GIA+KHANH+-+kimgiakhanh.com">

  <!-- Favicon đồng bộ màu logo -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230b3b75'/%3E%3Cpath d='M14 46V18h7v11l10-11h9L28 31l13 15h-9l-9-11-2 2v9h-7z' fill='%23ffffff'/%3E%3Cpath d='M32 12l18 10v6L32 18 14 28v-6l18-10z' fill='%23f59e0b'/%3E%3C/svg%3E">

  <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              dark: '#082a56',
              primary: '#0b3b75',   /* Màu xanh chủ đạo theo logo */
              light: '#165299',
              soft: '#eef4fb',
              gold: '#d97706',      /* Màu vàng kim theo logo */
              goldLight: '#f59e0b',
              sale: '#d90429'       /* Màu đỏ giảm giá chuẩn Flatsome */
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Reset chống tràn viền & chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: #f6f8fb;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
    .container-95 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ tự ngắt dòng trong tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-start;
      gap: 2px;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    .desktop-nav-item {
      position: relative;
    }
    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      padding: 9px 10px;
      font-size: 12px;
      font-weight: 700;
      color: #ffffff;
      text-transform: uppercase;
      white-space: nowrap; /* Bắt buộc không xuống dòng trong tên danh mục */
      letter-spacing: 0.01em;
      transition: background-color 0.2s ease, color 0.2s ease;
      border-radius: 4px;
    }
    @media (min-width: 1280px) {
      .desktop-nav-link {
        font-size: 12.5px;
        padding: 10px 12px;
      }
    }
    .desktop-nav-link:hover, .desktop-nav-item:hover > .desktop-nav-link {
      background-color: rgba(255, 255, 255, 0.14);
      color: #fbbf24;
    }

    /* Dropdown Submenu chuẩn Flatsome */
    .flatsome-dropdown {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #ffffff;
      border-top: 3px solid #f59e0b;
      box-shadow: 0 10px 25px rgba(11, 59, 117, 0.16);
      border-radius: 0 0 6px 6px;
      z-index: 60;
      padding: 6px 0;
    }
    .desktop-nav-item:hover .flatsome-dropdown {
      display: block;
    }
    .flatsome-dropdown a {
      display: block;
      padding: 8px 14px;
      font-size: 12.5px;
      font-weight: 500;
      color: #1e293b;
      white-space: nowrap;
      border-bottom: 1px solid #f1f5f9;
      transition: all 0.15s ease;
    }
    .flatsome-dropdown a:last-child {
      border-bottom: none;
    }
    .flatsome-dropdown a:hover {
      background-color: #eef4fb;
      color: #0b3b75;
      padding-left: 18px;
      font-weight: 600;
    }

    /* Banner Slider kích thước bằng nhau tuyệt đối, chữ cách xa viền ảnh */
    .banner-wrapper {
      position: relative;
      width: 100%;
      height: 290px;
      overflow: hidden;
      border-radius: 8px;
      background: #082a56;
    }
    @media (min-width: 640px) {
      .banner-wrapper {
        height: 330px;
      }
    }
    @media (min-width: 1024px) {
      .banner-wrapper {
        height: 380px;
      }
    }
    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.6s ease-in-out, visibility 0.6s ease-in-out;
      display: flex;
      align-items: center;
      justify-content: space-between;
      /* Chữ và hình cách xa viền ảnh banner trên cả điện thoại và máy tính */
      padding: 22px 26px;
    }
    @media (min-width: 640px) {
      .banner-slide {
        padding: 32px 48px;
      }
    }
    @media (min-width: 1024px) {
      .banner-slide {
        padding: 44px 72px;
      }
    }
    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Thẻ sản phẩm Flatsome: Tên đầy đủ không bị cắt/thiếu chữ, badge % giảm giá góc trên bên trái */
    .product-card {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 6px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      height: 100%;
      position: relative;
      transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease;
    }
    .product-card:hover {
      box-shadow: 0 8px 20px rgba(11, 59, 117, 0.11);
      border-color: #93c5fd;
      transform: translateY(-2px);
    }
    /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d90429;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 38px;
      height: 38px;
      border-radius: 9999px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 4, 41, 0.35);
      line-height: 1;
      pointer-events: none;
    }
    @media (min-width: 768px) {
      .flatsome-sale-badge {
        width: 40px;
        height: 40px;
        font-size: 11.5px;
      }
    }

    /* Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt dấu ... hoặc tràn ra ngoài */
    .product-title {
      font-size: 12.5px;
      font-weight: 600;
      color: #1e293b;
      line-height: 1.4;
      word-break: break-word;
      overflow-wrap: anywhere;
      white-space: normal;
      margin-bottom: 6px;
    }
    @media (min-width: 768px) {
      .product-title {
        font-size: 13.5px;
      }
    }
    .product-card:hover .product-title {
      color: #0b3b75;
    }

    /* Thanh tiêu đề danh mục trang chủ kiểu Flatsome gọn đẹp */
    .flatsome-sec-head {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
      background: #ffffff;
      border-bottom: 2px solid #0b3b75;
      border-radius: 6px 6px 0 0;
      padding: 8px 12px;
      margin-bottom: 12px;
    }
    .flatsome-sec-title {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: #0b3b75;
      color: #ffffff;
      font-size: 13px;
      font-weight: 700;
      text-transform: uppercase;
      padding: 6px 12px;
      border-radius: 4px;
      white-space: nowrap;
    }
    .flatsome-subcat-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 6px;
    }
    .flatsome-subcat-pill {
      font-size: 11.5px;
      font-weight: 600;
      color: #334155;
      background: #f1f5f9;
      padding: 4px 9px;
      border-radius: 4px;
      white-space: nowrap;
      transition: all 0.15s ease;
      cursor: pointer;
    }
    .flatsome-subcat-pill:hover {
      background: #0b3b75;
      color: #ffffff;
    }

    /* Nút liên hệ nổi bật Zalo, Facebook, Hotline có hiệu ứng sóng lan tỏa */
    @keyframes pulseRing {
      0% { transform: scale(0.95); opacity: 0.8; }
      70% { transform: scale(1.35); opacity: 0; }
      100% { transform: scale(1.35); opacity: 0; }
    }
    .floating-contact-wrap {
      position: fixed;
      bottom: 16px;
      left: 12px;
      z-index: 90;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .floating-btn {
      position: relative;
      display: flex;
      align-items: center;
      gap: 8px;
      height: 42px;
      padding: 0 12px 0 6px;
      border-radius: 9999px;
      color: #ffffff;
      font-size: 12px;
      font-weight: 700;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.22);
      transition: transform 0.2s ease;
      text-decoration: none;
    }
    .floating-btn:hover {
      transform: translateY(-2px) scale(1.03);
    }
    .floating-btn-icon {
      position: relative;
      width: 32px;
      height: 32px;
      border-radius: 9999px;
      background: rgba(255, 255, 255, 0.2);
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }
    .floating-btn-icon::after {
      content: '';
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      border: 2px solid rgba(255, 255, 255, 0.75);
      animation: pulseRing 1.8s infinite;
    }

    /* Ẩn thanh cuộn ngang cho danh mục điện thoại nhưng vẫn vuốt mượt */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body>

  <!-- =====================================================================
       [UX BUILDER BLOCK 1]: TOP BAR (ĐỊA CHỈ & LIÊN KẾT NHANH)
       ===================================================================== -->
  <div class="bg-brand-dark text-white text-[11.5px] py-1.5 border-b border-white/10">
    <div class="container-95 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 overflow-hidden">
        <span class="inline-flex items-center gap-1 font-medium text-amber-300">
          <svg class="w-3.5 h-3.5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>631 Ngô Quyền, Phường An Hải, TP Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-block text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1 text-slate-200">
          <svg class="w-3.5 h-3.5 shrink-0 text-amber-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
          <span>Website: <strong class="text-white">kimgiakhanh.com</strong> - MST: 0401415530</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-slate-200 font-medium">
        <a href="#danh-muc-trang-chu" class="hover:text-amber-300 transition">Sản phẩm</a>
        <a href="#form-bao-gia" class="hover:text-amber-300 transition">Báo giá sỉ & lẻ</a>
        <a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức</a>
        <a href="#lien-he-map" class="hover:text-amber-300 transition">Bản đồ & Fanpage</a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       [UX BUILDER BLOCK 2]: HEADER CHÍNH (LOGO NHỎ GỌN, TÌM KIẾM, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
       ===================================================================== -->
  <header class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
    <div class="container-95 py-2.5 flex items-center justify-between gap-2 sm:gap-4">
      
      <!-- Nút mở Danh mục trên Điện thoại -->
      <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center p-2 rounded-md bg-brand-soft text-brand-primary hover:bg-brand-primary hover:text-white transition shrink-0">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 6h16M4 12h16M4 18h16"/></svg>
      </button>

      <!-- Logo Công Ty TNHH MTV Kim Gia Khánh: Thiết kế chuyên nghiệp, chỉnh gọn nhỏ lại -->
      <a href="#" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
        <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-gradient-to-br from-brand-primary to-brand-dark flex items-center justify-center shadow-sm border border-amber-400/50 shrink-0">
          <!-- Biểu tượng Logo SVG Kim Gia Khánh -->
          <svg class="w-6 h-6 sm:w-7 sm:h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M32 6L56 20V27L32 13L8 27V20L32 6Z" fill="#F59E0B"/>
            <path d="M14 26H22V52H14V26Z" fill="#FFFFFF"/>
            <path d="M23 38L36 25H46L31 39L47 52H36L23 40V38Z" fill="#FFFFFF"/>
            <circle cx="48" cy="28" r="4" fill="#F59E0B"/>
          </svg>
        </div>
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-brand-primary group-hover:text-brand-light transition">
            KIM GIA KHÁNH
          </div>
          <div class="text-[10px] sm:text-[11px] font-semibold text-amber-600 uppercase tracking-wider">
            kimgiakhanh.com
          </div>
        </div>
      </a>

      <!-- Ô tìm kiếm sản phẩm chuẩn Flatsome -->
      <div class="flex-1 max-w-xl mx-1 sm:mx-3">
        <div class="relative flex items-center w-full">
          <input
            id="searchInput"
            type="text"
            placeholder="Tìm sơn Jotun, bồn cầu, gạch men, bình nóng lạnh..."
            class="w-full pl-3 pr-9 py-1.5 sm:py-2 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-md focus:outline-none focus:border-brand-primary focus:bg-white transition"
          >
          <button id="searchBtn" type="button" aria-label="Tìm kiếm" class="absolute right-1 top-1/2 -translate-y-1/2 px-2 py-1 text-brand-primary hover:text-amber-600">
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
          </button>
        </div>
      </div>

      <!-- Nút Yêu cầu Báo Giá nhanh (Không để nút Gọi ngay trên Header để tránh tràn viền) -->
      <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 px-2.5 sm:px-3.5 py-1.5 sm:py-2 rounded-md bg-brand-soft text-brand-primary hover:bg-brand-primary hover:text-white font-semibold text-xs transition shrink-0 border border-brand-primary/20">
        <svg class="w-4 h-4 text-amber-600 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
        <span class="hidden sm:inline">Nhận báo giá</span>
      </a>
    </div>

    <!-- ===================================================================
         THANH MENU DANH MỤC TRÊN MÁY TÍNH:
         - Viết liền trên 1 hàng chữ nhỏ gọn (hoặc tự xuống hàng 2 nguyên cụm)
         - Không bao giờ xuống dòng bên trong tên danh mục (white-space: nowrap)
         =================================================================== -->
    <nav class="hidden lg:block bg-brand-primary border-t border-brand-light/40">
      <div class="container-95">
        <ul class="desktop-nav-list">
          <li class="desktop-nav-item">
            <a href="#" onclick="filterCategory('ALL'); return false;" class="desktop-nav-link bg-amber-500 !text-slate-950 hover:bg-amber-400">
              <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 20 20"><path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"/></svg>
              <span>TRANG CHỦ</span>
            </a>
          </li>

          <!-- 1. SƠN -->
          <li class="desktop-nav-item">
            <a href="#sec-son" class="desktop-nav-link">
              <span>SƠN</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-son" onclick="filterSubCategory('sec-son', 'Jotun')">Sơn Jotun (Ngoại thất, Nội thất, Sơn lót, Bột trét)</a>
              <a href="#sec-son" onclick="filterSubCategory('sec-son', 'Dulux-Maxilite')">Sơn Dulux - Maxilite</a>
              <a href="#sec-son" onclick="filterSubCategory('sec-son', 'Tito')">Sơn Tito (Chống kiềm, Chống thấm màu, Sơn nhũ)</a>
              <a href="#sec-son" onclick="filterSubCategory('sec-son', 'Chống thấm')">Chống thấm (Sika, Bestmix, Mapei)</a>
            </div>
          </li>

          <!-- 2. THIẾT BỊ VỆ SINH -->
          <li class="desktop-nav-item">
            <a href="#sec-tbvs" class="desktop-nav-link">
              <span>THIẾT BỊ VỆ SINH</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-tbvs">Bồn cầu liền khối</a>
              <a href="#sec-tbvs">Sen vòi & Sen cây nóng lạnh</a>
              <a href="#sec-tbvs">Chậu rửa Lavabo</a>
              <a href="#sec-tbvs">Gương phòng tắm</a>
              <a href="#sec-tbvs">Phụ kiện nhà tắm</a>
            </div>
          </li>

          <!-- 3. GẠCH MEN -->
          <li class="desktop-nav-item">
            <a href="#sec-gach" class="desktop-nav-link">
              <span>GẠCH MEN</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-gach">Gạch Đồng Tâm (80x80, 60x60, 40x80, 30x60)</a>
              <a href="#sec-gach">Gạch Kimgres</a>
              <a href="#sec-gach">Gạch Porcelain Kháng Khuẩn</a>
            </div>
          </li>

          <!-- 4. NGÓI LỢP -->
          <li class="desktop-nav-item">
            <a href="#sec-ngoi" class="desktop-nav-link">
              <span>NGÓI LỢP</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-ngoi">Ngói màu DIC</a>
              <a href="#sec-ngoi">Ngói Đất Việt</a>
            </div>
          </li>

          <!-- 5. BỒN NƯỚC -->
          <li class="desktop-nav-item">
            <a href="#sec-bonnuoc" class="desktop-nav-link">
              <span>BỒN NƯỚC</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-bonnuoc">Bồn nước Tân Á</a>
              <a href="#sec-bonnuoc">Bồn nước Sơn Hà</a>
              <a href="#sec-bonnuoc">Bồn nước Letton</a>
            </div>
          </li>

          <!-- 6. BÌNH NÓNG LẠNH -->
          <li class="desktop-nav-item">
            <a href="#sec-binhnonglanh" class="desktop-nav-link">
              <span>BÌNH NÓNG LẠNH</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-binhnonglanh">Máy nước nóng Ariston</a>
              <a href="#sec-binhnonglanh">Máy nước nóng Ferroli</a>
            </div>
          </li>

          <!-- 7. DÁN GẠCH, CHÀ RON -->
          <li class="desktop-nav-item">
            <a href="#sec-keo" class="desktop-nav-link">
              <span>DÁN GẠCH, CHÀ RON</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="flatsome-dropdown">
              <a href="#sec-keo">Keo cá sấu (Crocodile)</a>
              <a href="#sec-keo">Keo Sika</a>
              <a href="#sec-keo">Bestmix & Đồng Tâm</a>
            </div>
          </li>

          <!-- 8. ĐỐI TÁC -->
          <li class="desktop-nav-item">
            <a href="#doi-tac" class="desktop-nav-link"><span>ĐỐI TÁC</span></a>
          </li>

          <!-- 9. TIN TỨC -->
          <li class="desktop-nav-item">
            <a href="#tin-tuc" class="desktop-nav-link"><span>BÀI VIẾT</span></a>
          </li>

          <!-- 10. LIÊN HỆ -->
          <li class="desktop-nav-item">
            <a href="#lien-he-map" class="desktop-nav-link"><span>LIÊN HỆ</span></a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Thanh cuộn nhanh danh mục trên Điện thoại (gọn đẹp, không xuống dòng chữ) -->
    <div class="lg:hidden bg-brand-primary px-2 py-1.5 overflow-x-auto no-scrollbar border-t border-white/10">
      <div class="flex items-center gap-1.5">
        <a href="#danh-muc-trang-chu" class="px-2.5 py-1 rounded bg-amber-500 text-slate-950 font-bold text-[11px] whitespace-nowrap">TRANG CHỦ</a>
        <a href="#sec-son" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">SƠN</a>
        <a href="#sec-tbvs" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">THIẾT BỊ VỆ SINH</a>
        <a href="#sec-gach" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">GẠCH MEN</a>
        <a href="#sec-ngoi" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">NGÓI LỢP</a>
        <a href="#sec-bonnuoc" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">BỒN NƯỚC</a>
        <a href="#sec-binhnonglanh" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">BÌNH NÓNG LẠNH</a>
        <a href="#sec-keo" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">DÁN GẠCH, CHÀ RON</a>
        <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">BÁO GIÁ</a>
        <a href="#lien-he-map" class="px-2.5 py-1 rounded bg-white/10 text-white font-semibold text-[11px] whitespace-nowrap">LIÊN HỆ</a>
      </div>
    </div>
  </header>

  <!-- MENU DRAWER CHO ĐIỆN THOẠI (CHUẨN FLATSOME OFF-CANVAS) -->
  <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
    <div id="mobileDrawerBackdrop" class="absolute inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
    <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col z-10 overflow-y-auto">
      <div class="p-3.5 bg-brand-primary text-white flex items-center justify-between">
        <div class="font-bold text-sm tracking-wide">DANH MỤC KIM GIA KHÁNH</div>
        <button id="closeMobileDrawer" type="button" class="p-1 rounded hover:bg-white/10">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
        <a href="#sec-son" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>1. SƠN (Jotun, Dulux, Tito, Sika)</span>
          <span>›</span>
        </a>
        <a href="#sec-tbvs" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>2. THIẾT BỊ VỆ SINH (Bồn cầu, Sen vòi)</span>
          <span>›</span>
        </a>
        <a href="#sec-gach" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>3. GẠCH MEN (Đồng Tâm, Kimgres)</span>
          <span>›</span>
        </a>
        <a href="#sec-ngoi" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>4. NGÓI LỢP (DIC, Ngói Đất Việt)</span>
          <span>›</span>
        </a>
        <a href="#sec-bonnuoc" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>5. BỒN NƯỚC (Tân Á, Sơn Hà, Letton)</span>
          <span>›</span>
        </a>
        <a href="#sec-binhnonglanh" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>6. BÌNH NÓNG LẠNH (Ariston, Ferroli)</span>
          <span>›</span>
        </a>
        <a href="#sec-keo" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>7. DÁN GẠCH, CHÀ RON (Cá Sấu, Sika)</span>
          <span>›</span>
        </a>
        <a href="#doi-tac" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>8. ĐỐI TÁC THƯƠNG HIỆU</span>
          <span>›</span>
        </a>
        <a href="#form-bao-gia" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>9. YÊU CẦU BÁO GIÁ</span>
          <span>›</span>
        </a>
        <a href="#tin-tuc" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>10. BÀI VIẾT & KINH NGHIỆM</span>
          <span>›</span>
        </a>
        <a href="#lien-he-map" class="mobile-nav-item flex items-center justify-between px-4 py-3 hover:bg-brand-soft hover:text-brand-primary">
          <span>11. BẢN ĐỒ & FANPAGE</span>
          <span>›</span>
        </a>
      </div>
      <div class="mt-auto p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
        <div class="font-bold text-brand-primary">CÔNG TY TNHH MTV KIM GIA KHÁNH</div>
        <div>Đ/c: 631 Ngô Quyền, P. An Hải, TP Đà Nẵng</div>
        <div>Hotline/Zalo: <strong class="text-red-600">0905.119.918</strong></div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       [UX BUILDER BLOCK 3]: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       - Chữ và hình ảnh nằm gọn bên trong, cách xa viền banner
       - Không bị thiếu chữ trên cả điện thoại và máy tính
       - Không gắn các nhãn dán rối mắt
       ===================================================================== -->
  <section class="py-3 sm:py-4">
    <div class="container-95">
      <div class="banner-wrapper shadow-md" id="heroSlider">
        
        <!-- SLIDE 1 -->
        <div class="banner-slide active bg-gradient-to-r from-[#072549] via-[#0b3b75] to-[#134e94]">
          <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3 z-10">
            <div class="text-amber-400 text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-wider">
              CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH - KIMIAKHANH.COM
            </div>
            <h1 class="text-base sm:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
              TỔNG KHO VẬT LIỆU XÂY DỰNG &amp; TRANG TRÍ NỘI THẤT ĐÀ NẴNG
            </h1>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed max-w-xl">
              Chuyên phân phối chính hãng: Sơn Jotun, Dulux, Thiết bị vệ sinh Inax &amp; Viglacera, Gạch men Đồng Tâm, Ngói lợp, Bồn nước, Bình nóng lạnh Ariston &amp; Keo dán gạch.
            </p>
            <div class="pt-1 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs text-amber-200 font-medium">
              <span>📍 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng</span>
              <span class="hidden sm:inline">•</span>
              <span>📞 Hotline/Zalo: 0905.119.918</span>
            </div>
            <div class="pt-1.5 flex flex-wrap gap-2">
              <a href="#sec-son" class="px-3.5 py-1.5 sm:px-4 sm:py-2 rounded bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs transition">
                Xem danh mục sản phẩm
              </a>
              <a href="#form-bao-gia" class="px-3.5 py-1.5 sm:px-4 sm:py-2 rounded bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                Nhận báo giá công trình
              </a>
            </div>
          </div>

          <!-- Khối ảnh sản phẩm thực tế bên trong Banner 1 -->
          <div class="hidden md:grid grid-cols-2 gap-2.5 w-4/12 max-w-[320px] shrink-0 z-10">
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w500';"
                   alt="Sản phẩm Kim Gia Khánh 1" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP=w500';"
                   alt="Sản phẩm Kim Gia Khánh 2" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr=w500';"
                   alt="Sản phẩm Kim Gia Khánh 3" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1X31hmhpLVVORV-tmMSZYzBO-qtpyusry&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1X31hmhpLVVORV-tmMSZYzBO-qtpyusry=w500';"
                   alt="Sản phẩm Kim Gia Khánh 4" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
          </div>
        </div>

        <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
        <div class="banner-slide bg-gradient-to-r from-[#09305e] via-[#0e4483] to-[#082a56]">
          <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3 z-10">
            <div class="text-amber-400 text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-wider">
              NHÀ PHÂN PHỐI UY TÍN TẠI ĐÀ NẴNG &amp; MIỀN TRUNG
            </div>
            <h2 class="text-base sm:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
              GIẢI PHÁP ĐỒNG BỘ CHO MỌI CÔNG TRÌNH DÂN DỤNG &amp; DỰ ÁN
            </h2>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed max-w-xl">
              Cung cấp trọn gói Thiết bị vệ sinh phòng tắm, Gạch Porcelain kháng khuẩn, Sơn nước nội ngoại thất, Bồn nước Inox &amp; Bình nóng lạnh chiết khấu cao, giao hàng tận nơi.
            </p>
            <div class="pt-1 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs text-amber-200 font-medium">
              <span>📍 Showroom &amp; Kho: 631 Ngô Quyền, P. An Hải, TP Đà Nẵng</span>
              <span class="hidden sm:inline">•</span>
              <span>🌐 kimgiakhanh.com</span>
            </div>
            <div class="pt-1.5 flex flex-wrap gap-2">
              <a href="#sec-tbvs" class="px-3.5 py-1.5 sm:px-4 sm:py-2 rounded bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs transition">
                Khám phá sản phẩm
              </a>
              <a href="#lien-he-map" class="px-3.5 py-1.5 sm:px-4 sm:py-2 rounded bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                Xem bản đồ chỉ đường
              </a>
            </div>
          </div>

          <!-- Khối ảnh sản phẩm thực tế bên trong Banner 2 -->
          <div class="hidden md:grid grid-cols-2 gap-2.5 w-4/12 max-w-[320px] shrink-0 z-10">
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w500';"
                   alt="Sản phẩm Kim Gia Khánh 5" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg=w500';"
                   alt="Sản phẩm Kim Gia Khánh 6" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4=w500';"
                   alt="Sản phẩm Kim Gia Khánh 7" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
            <div class="bg-white p-1.5 rounded-lg shadow">
              <img src="https://drive.google.com/thumbnail?id=1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54=w500';"
                   alt="Sản phẩm Kim Gia Khánh 8" class="w-full h-24 lg:h-28 object-contain rounded">
            </div>
          </div>
        </div>

        <!-- Nút chuyển Banner Trái / Phải & Chấm tròn -->
        <button id="prevBannerBtn" type="button" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
          ‹
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
          ›
        </button>
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition" aria-label="Banner 1"></button>
          <button type="button" onclick="goToSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/40 transition" aria-label="Banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 4]: DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, RÕ RÀNG)
       ===================================================================== -->
  <section id="danh-muc-trang-chu" class="py-2 sm:py-3">
    <div class="container-95">
      <div class="bg-white rounded-md border border-slate-200 p-3 sm:p-4">
        <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
          <h2 class="text-xs sm:text-sm font-extrabold uppercase text-brand-primary tracking-wide">
            DANH MỤC SẢN PHẨM CHÍNH HÃNG
          </h2>
          <span class="text-[11px] text-slate-500">Chọn nhanh danh mục</span>
        </div>

        <!-- Chia 2 cột trên điện thoại, 7 cột trên máy tính, chữ danh mục nhỏ gọn không xuống dòng từ -->
        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-7 gap-2 sm:gap-2.5">
          <a href="#sec-son" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w200';"
                 alt="Sơn" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">SƠN NƯỚC</div>
              <div class="text-[10px] text-slate-500 truncate">Jotun, Dulux, Tito</div>
            </div>
          </a>

          <a href="#sec-tbvs" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w200';"
                 alt="Thiết bị vệ sinh" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">THIẾT BỊ VỆ SINH</div>
              <div class="text-[10px] text-slate-500 truncate">Bồn cầu, Sen vòi</div>
            </div>
          </a>

          <a href="#sec-gach" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r=w200';"
                 alt="Gạch men" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">GẠCH MEN</div>
              <div class="text-[10px] text-slate-500 truncate">Đồng Tâm, Kimgres</div>
            </div>
          </a>

          <a href="#sec-ngoi" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c=w200';"
                 alt="Ngói lợp" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">NGÓI LỢP</div>
              <div class="text-[10px] text-slate-500 truncate">DIC, Đất Việt</div>
            </div>
          </a>

          <a href="#sec-bonnuoc" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-=w200';"
                 alt="Bồn nước" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">BỒN NƯỚC</div>
              <div class="text-[10px] text-slate-500 truncate">Tân Á, Sơn Hà</div>
            </div>
          </a>

          <a href="#sec-binhnonglanh" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition">
            <img src="https://drive.google.com/thumbnail?id=19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP=w200';"
                 alt="Bình nóng lạnh" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">BÌNH NÓNG LẠNH</div>
              <div class="text-[10px] text-slate-500 truncate">Ariston, Ferroli</div>
            </div>
          </a>

          <a href="#sec-keo" class="group flex items-center gap-2.5 p-2 rounded border border-slate-200 hover:border-brand-primary hover:bg-brand-soft transition col-span-2 sm:col-span-1">
            <img src="https://drive.google.com/thumbnail?id=15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_&sz=w200"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_=w200';"
                 alt="Dán gạch, chà ron" class="w-10 h-10 object-contain rounded bg-slate-50 shrink-0">
            <div class="min-w-0">
              <div class="text-[11.5px] font-bold text-slate-800 group-hover:text-brand-primary whitespace-nowrap">DÁN GẠCH, CHÀ RON</div>
              <div class="text-[10px] text-slate-500 truncate">Keo cá sấu, Sika</div>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 5]: DANH SÁCH SẢN PHẨM THEO DANH MỤC MẪU NOITHATNGONGUYEN.COM
       - Sử dụng trực tiếp 19 file ảnh thực tế từ Google Drive
       - Chia 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính
       - Có giá gốc, giá giảm và % giảm giá góc trên bên trái chuẩn Flatsome
       - Tên sản phẩm hiển thị đầy đủ không bị cắt chữ hay tràn ra ngoài
       ===================================================================== -->
  <main class="space-y-5 py-2">
    <div id="catalogContainer" class="container-95 space-y-6">
      <!-- Nội dung các danh mục sản phẩm được render tự động từ dữ liệu chuẩn bên dưới -->
    </div>
  </main>

  <!-- =====================================================================
       [UX BUILDER BLOCK 6]: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section id="form-bao-gia" class="py-5">
    <div class="container-95">
      <div class="bg-white rounded-md border border-slate-200 shadow-xs overflow-hidden">
        <div class="grid grid-cols-1 lg:grid-cols-12">
          
          <!-- Thông tin cam kết bên trái -->
          <div class="lg:col-span-5 bg-gradient-to-br from-brand-primary to-brand-dark text-white p-5 sm:p-7 flex flex-col justify-between">
            <div class="space-y-3">
              <div class="text-amber-400 text-xs font-bold uppercase tracking-wider">
                HỖ TRỢ DỰ ÁN &amp; NHÀ DÂN ĐÀ NẴNG
              </div>
              <h2 class="text-lg sm:text-xl font-extrabold leading-snug">
                ĐĂNG KÝ NHẬN BÁO GIÁ VẬT LIỆU XÂY DỰNG &amp; NỘI THẤT CHIẾT KHẤU CAO
              </h2>
              <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                Quý khách hàng, nhà thầu, kiến trúc sư cần báo giá sỉ &amp; lẻ các mặt hàng Sơn, Thiết bị vệ sinh, Gạch men, Ngói lợp, Bồn nước, Bình nóng lạnh, Keo dán gạch vui lòng điền thông tin bên cạnh.
              </p>
              <ul class="space-y-2 text-xs text-slate-100 pt-2">
                <li class="flex items-center gap-2">
                  <span class="w-4 h-4 rounded-full bg-amber-500 text-slate-950 font-bold flex items-center justify-center text-[10px]">✓</span>
                  <span>Hàng chính hãng 100% từ nhà máy có đầy đủ CO/CQ, hóa đơn VAT</span>
                </li>
                <li class="flex items-center gap-2">
                  <span class="w-4 h-4 rounded-full bg-amber-500 text-slate-950 font-bold flex items-center justify-center text-[10px]">✓</span>
                  <span>Chiết khấu trực tiếp theo số lượng đơn hàng &amp; hạng mục công trình</span>
                </li>
                <li class="flex items-center gap-2">
                  <span class="w-4 h-4 rounded-full bg-amber-500 text-slate-950 font-bold flex items-center justify-center text-[10px]">✓</span>
                  <span>Giao hàng nhanh tận chân công trình tại Đà Nẵng &amp; khu vực lân cận</span>
                </li>
              </ul>
            </div>

            <div class="mt-6 pt-4 border-t border-white/15 text-xs space-y-1">
              <div class="font-bold text-amber-300">CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH</div>
              <div>Địa chỉ: 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng</div>
              <div>Hotline/Zalo tư vấn: <a href="tel:0905119918" class="font-bold text-white underline">0905.119.918</a></div>
            </div>
          </div>

          <!-- Form nhập thông tin bên phải -->
          <div class="lg:col-span-7 p-5 sm:p-7">
            <h3 class="text-sm sm:text-base font-bold text-brand-primary uppercase mb-4">
              FORM YÊU CẦU TƯ VẤN &amp; BÁO GIÁ NHANH
            </h3>
            <form id="quoteForm" class="space-y-3.5" onsubmit="handleQuoteSubmit(event)">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905119918" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục sản phẩm cần báo giá *</label>
                  <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary bg-white">
                    <option value="Trọn gói VLXD & Nội thất">Trọn gói VLXD &amp; Nội thất công trình</option>
                    <option value="Sơn (Jotun, Dulux, Tito, Chống thấm)">Sơn (Jotun, Dulux, Tito, Chống thấm)</option>
                    <option value="Thiết bị vệ sinh (Bồn cầu, Sen vòi, Lavabo)">Thiết bị vệ sinh (Bồn cầu, Sen vòi, Lavabo)</option>
                    <option value="Gạch men (Đồng Tâm, Kimgres)">Gạch men (Đồng Tâm, Kimgres)</option>
                    <option value="Ngói lợp (DIC, Ngói Đất Việt)">Ngói lợp (DIC, Ngói Đất Việt)</option>
                    <option value="Bồn nước (Tân Á, Sơn Hà, Letton)">Bồn nước (Tân Á, Sơn Hà, Letton)</option>
                    <option value="Bình nóng lạnh (Ariston, Ferroli)">Bình nóng lạnh (Ariston, Ferroli)</option>
                    <option value="Keo dán gạch, chà ron (Cá Sấu, Sika, Bestmix)">Keo dán gạch, chà ron (Cá Sấu, Sika, Bestmix)</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ giao hàng / Công trình</label>
                  <input id="qAddress" type="text" placeholder="Quận/Phường tại Đà Nẵng hoặc tỉnh lân cận" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary">
                </div>
              </div>

              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Nội dung chi tiết / Mã sản phẩm &amp; số lượng</label>
                <textarea id="qNote" rows="3" placeholder="Nhập tên sản phẩm, mã hàng hoặc khối lượng cần báo giá..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-primary"></textarea>
              </div>

              <div class="flex flex-wrap items-center gap-3 pt-1">
                <button type="submit" class="px-5 py-2.5 rounded bg-brand-primary hover:bg-brand-light text-white font-bold text-xs sm:text-sm transition cursor-pointer">
                  GỬI YÊU CẦU BÁO GIÁ
                </button>
                <a href="https://zalo.me/0905119918" target="_blank" rel="noopener" class="px-4 py-2.5 rounded bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs sm:text-sm transition">
                  Nhắn Zalo: 0905.119.918
                </a>
              </div>

              <div id="quoteSuccessBox" class="hidden p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 7]: DANH MỤC CÁC ĐỐI TÁC (THƯƠNG HIỆU PHÂN PHỐI)
       ===================================================================== -->
  <section id="doi-tac" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-md border border-slate-200 p-4">
        <div class="flatsome-sec-head !mb-3">
          <div class="flatsome-sec-title">ĐỐI TÁC &amp; THƯƠNG HIỆU PHÂN PHỐI</div>
          <span class="text-xs text-slate-500">Cam kết chính hãng 100% tại Kim Gia Khánh</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-6 gap-2.5">
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#003876] tracking-wider">JOTUN</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Sơn Nội &amp; Ngoại Thất</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#1d4ed8] tracking-wider">DULUX - MAXILITE</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Sơn Trang Trí Cao Cấp</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#0284c7] tracking-wider">INAX</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh Nhật Bản</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#0f766e] tracking-wider">VIGLACERA</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Sen Vòi &amp; Sứ Vệ Sinh</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#b91c1c] tracking-wider">ĐỒNG TÂM</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Gạch Men &amp; Porcelain</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#7c2d12] tracking-wider">KIMGRES</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Gạch Ốp Lát Cao Cấp</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#dc2626] tracking-wider">ARISTON</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Bình Nước Nóng Ý</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#ea580c] tracking-wider">FERROLI</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Máy Nước Nóng Trực Tiếp</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#0369a1] tracking-wider">TÂN Á - SƠN HÀ</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Bồn Nước Inox &amp; Nhựa</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#d97706] tracking-wider">SIKA - BESTMIX</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Hóa Chất Chống Thấm</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#15803d] tracking-wider">CROCODILE</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Keo Dán Gạch &amp; Chà Ron</div>
          </div>
          <div class="p-3 rounded border border-slate-200 bg-slate-50/60 flex flex-col items-center justify-center text-center hover:border-brand-primary transition">
            <div class="text-sm font-black text-[#991b1b] tracking-wider">DIC - ĐẤT VIỆT</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Ngói Lợp Công Nghệ Mới</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 8]: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)
       ===================================================================== -->
  <section id="tin-tuc" class="py-3">
    <div class="container-95">
      <div class="bg-white rounded-md border border-slate-200 p-4">
        <div class="flatsome-sec-head !mb-3">
          <div class="flatsome-sec-title">DANH MỤC BÀI VIẾT &amp; KINH NGHIỆM XÂY DỰNG</div>
          <a href="#form-bao-gia" class="text-xs font-semibold text-brand-primary hover:underline">Tư vấn kỹ thuật ›</a>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
          <!-- Bài viết 1 -->
          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col hover:shadow-md transition">
            <div class="h-40 bg-slate-100 p-2 flex items-center justify-center">
              <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w500';"
                   alt="Kinh nghiệm chọn sơn Jotun" class="max-h-full object-contain">
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-amber-600 font-semibold mb-1">Tư vấn Sơn nước • Đà Nẵng</div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Kinh nghiệm chọn sơn ngoại thất Jotun bền màu trước khí hậu nắng gió miền Trung
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Hướng dẫn quy trình thi công sơn lót chống kiềm và 2 lớp phủ Jotashield giúp bảo vệ tường nhà lên đến 8-10 năm.
                </p>
              </div>
              <button type="button" onclick="openArticleModal(0)" class="mt-3 text-left text-xs font-bold text-brand-primary hover:text-amber-600">
                Đọc chi tiết ›
              </button>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col hover:shadow-md transition">
            <div class="h-40 bg-slate-100 p-2 flex items-center justify-center">
              <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w500';"
                   alt="Chọn thiết bị vệ sinh" class="max-h-full object-contain">
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-amber-600 font-semibold mb-1">Thiết bị vệ sinh • Phòng tắm</div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Cách chọn trọn bộ bồn cầu liền khối và sen cây nóng lạnh tiết kiệm nước
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  So sánh các dòng bồn cầu liền khối men tuyết kháng khuẩn và sen cây Inax, Viglacera phù hợp diện tích phòng tắm.
                </p>
              </div>
              <button type="button" onclick="openArticleModal(1)" class="mt-3 text-left text-xs font-bold text-brand-primary hover:text-amber-600">
                Đọc chi tiết ›
              </button>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col hover:shadow-md transition">
            <div class="h-40 bg-slate-100 p-2 flex items-center justify-center">
              <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r=w500';"
                   alt="Phối màu gạch men Đồng Tâm" class="max-h-full object-contain">
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-amber-600 font-semibold mb-1">Gạch ốp lát • Kiến trúc</div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Xu hướng chọn gạch Porcelain 80x80 và keo dán gạch chống bong tróc nền nhà
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Vì sao gạch khổ lớn Porcelain kết hợp keo dán gạch Crocodile &amp; Sika đang thay thế hoàn toàn hồ dầu truyền thống?
                </p>
              </div>
              <button type="button" onclick="openArticleModal(2)" class="mt-3 text-left text-xs font-bold text-brand-primary hover:text-amber-600">
                Đọc chi tiết ›
              </button>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col hover:shadow-md transition">
            <div class="h-40 bg-slate-100 p-2 flex items-center justify-center">
              <img src="https://drive.google.com/thumbnail?id=1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-&sz=w500"
                   onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-=w500';"
                   alt="Lắp đặt bồn nước và bình nóng lạnh" class="max-h-full object-contain">
            </div>
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] text-amber-600 font-semibold mb-1">Giải pháp Nước &amp; Nhiệt</div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Hướng dẫn chọn dung tích bồn nước Tân Á, Sơn Hà và bình nóng lạnh theo số người
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Tư vấn chọn bồn inox hay bồn nhựa nguyên sinh và máy nước nóng gián tiếp Ariston, Ferroli an toàn điện tuyệt đối.
                </p>
              </div>
              <button type="button" onclick="openArticleModal(3)" class="mt-3 text-left text-xs font-bold text-brand-primary hover:text-amber-600">
                Đọc chi tiết ›
              </button>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 9]: ĐƯA ẢNH/BẢN ĐỒ GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ
       - Địa chỉ: 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng
       - SĐT: 0905.119.918
       ===================================================================== -->
  <section id="lien-he-map" class="py-4">
    <div class="container-95">
      <div class="bg-white rounded-md border border-slate-200 p-4">
        <div class="flatsome-sec-head !mb-4">
          <div class="flatsome-sec-title">BẢN ĐỒ GOOGLE MAPS &amp; FANPAGE TRANG CHỦ</div>
          <span class="text-xs text-slate-600 font-medium">631 Ngô Quyền, Phường An Hải, TP Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
          
          <!-- CỘT TRÁI (7/12): BẢN ĐỒ GOOGLE MAPS TRỰC TIẾP NGOÀI TRANG CHỦ -->
          <div class="lg:col-span-7 flex flex-col border border-slate-200 rounded-md overflow-hidden bg-slate-50">
            <div class="p-3 bg-brand-soft border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
              <div>
                <div class="text-xs sm:text-sm font-bold text-brand-primary">
                  📍 VỊ TRÍ SHOWROOM &amp; KHO KIM GIA KHÁNH TRÊN GOOGLE MAPS
                </div>
                <div class="text-[11.5px] text-slate-600">
                  Địa chỉ: 631 Ngô Quyền, Phường An Hải, Thành phố Đà Nẵng • ĐT: 0905.119.918
                </div>
              </div>
              <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJZ0bL1SUYQjEREDlTTC35Smo" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-brand-primary hover:bg-brand-light text-white font-bold text-xs shrink-0 transition">
                Mở Google Maps lớn ↗
              </a>
            </div>
            <!-- Khung bản đồ Google Maps trực quan ngoài trang chủ -->
            <div class="relative w-full h-64 sm:h-72 bg-slate-200">
              <iframe
                title="Bản đồ 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng"
                src="https://www.google.com/maps?q=631+Ng%C3%B4+Quy%E1%BB%81n,+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <!-- CỘT PHẢI (5/12): FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
          <div class="lg:col-span-5 flex flex-col border border-slate-200 rounded-md overflow-hidden bg-white">
            <div class="p-3 bg-[#1877f2]/10 border-b border-slate-200 flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-6 h-6 rounded-full bg-[#1877f2] text-white flex items-center justify-center font-bold text-xs">f</span>
                <span class="text-xs sm:text-sm font-bold text-slate-800">FANPAGE FACEBOOK CHÍNH THỨC</span>
              </div>
              <span class="text-[11px] text-[#1877f2] font-semibold">kimgiakhanh.com</span>
            </div>

            <!-- Giao diện Fanpage Card chuẩn Flatsome ngoài trang chủ -->
            <div class="p-4 flex-1 flex flex-col justify-between bg-gradient-to-b from-slate-50 to-white">
              <div>
                <!-- Ảnh bìa Fanpage -->
                <div class="relative rounded-md overflow-hidden bg-gradient-to-r from-brand-dark via-brand-primary to-brand-light p-4 text-white shadow-xs">
                  <div class="flex items-center gap-3">
                    <div class="w-12 h-12 rounded-lg bg-white p-1 flex items-center justify-center shadow shrink-0">
                      <svg class="w-9 h-9" viewBox="0 0 64 64" fill="none">
                        <rect width="64" height="64" rx="10" fill="#0b3b75"/>
                        <path d="M32 10L52 22V28L32 16L12 28V22L32 10Z" fill="#F59E0B"/>
                        <path d="M18 27H25V50H18V27Z" fill="#FFFFFF"/>
                        <path d="M26 38L37 27H46L33 39L47 50H37L26 40V38Z" fill="#FFFFFF"/>
                      </svg>
                    </div>
                    <div class="min-w-0">
                      <div class="font-extrabold text-sm sm:text-base truncate">
                        Công Ty TNHH MTV Kim Gia Khánh
                      </div>
                      <div class="text-[11px] text-amber-300 font-medium">
                        Vật Liệu Xây Dựng &amp; Nội Thất Đà Nẵng • 4.9 ★
                      </div>
                    </div>
                  </div>
                  <div class="mt-3 flex flex-wrap gap-2">
                    <a href="https://facebook.com" target="_blank" rel="noopener" class="px-3 py-1 rounded bg-[#1877f2] hover:bg-blue-600 text-white font-bold text-xs inline-flex items-center gap-1">
                      <span>👍 Theo dõi Trang</span>
                    </a>
                    <a href="https://zalo.me/0905119918" target="_blank" rel="noopener" class="px-3 py-1 rounded bg-white text-slate-900 hover:bg-slate-100 font-bold text-xs inline-flex items-center gap-1">
                      <span>💬 Nhắn tin tư vấn</span>
                    </a>
                  </div>
                </div>

                <!-- Bài đăng nổi bật trên Fanpage -->
                <div class="mt-3 p-3 rounded border border-slate-200 bg-white space-y-2 text-xs text-slate-700">
                  <div class="flex items-center justify-between text-[11px] text-slate-500">
                    <span class="font-semibold text-brand-primary">📌 Tin mới trên Fanpage</span>
                    <span>Cập nhật hôm nay</span>
                  </div>
                  <p class="leading-relaxed">
                    Kho <strong>Kim Gia Khánh (631 Ngô Quyền, P. An Hải, TP Đà Nẵng)</strong> vừa về đầy đủ các mẫu Bồn cầu liền khối, Sen cây nóng lạnh, Gạch Porcelain 80x80, Sơn Jotun &amp; Bình nóng lạnh Ariston phục vụ công trình.
                  </p>
                  <div class="text-[11px] font-semibold text-red-600">
                    📞 Hotline/Zalo báo giá nhanh: 0905.119.918
                  </div>
                </div>
              </div>

              <div class="mt-3 pt-2 border-t border-slate-200 flex items-center justify-between text-[11px] text-slate-500">
                <span>🌐 Website: kimgiakhanh.com</span>
                <a href="tel:0905119918" class="font-bold text-brand-primary hover:underline">Gọi: 0905.119.918</a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       [UX BUILDER BLOCK 10]: FOOTER CHÂN TRANG CHUẨN MẪU NOITHATNGONGUYEN.COM
       ===================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-8 pb-6 mt-4 border-t-4 border-amber-500">
    <div class="container-95">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
        
        <!-- Thông tin công ty (5 cột) -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded-lg bg-brand-primary border border-amber-400 flex items-center justify-center shrink-0">
              <svg class="w-6 h-6" viewBox="0 0 64 64" fill="none">
                <path d="M32 6L56 20V27L32 13L8 27V20L32 6Z" fill="#F59E0B"/>
                <path d="M14 26H22V52H14V26Z" fill="#FFFFFF"/>
                <path d="M23 38L36 25H46L31 39L47 52H36L23 40V38Z" fill="#FFFFFF"/>
              </svg>
            </div>
            <div>
              <div class="text-sm font-extrabold text-white uppercase">
                CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH
              </div>
              <div class="text-[11px] text-amber-400 font-semibold">
                Website: kimgiakhanh.com • MST: 0401415530
              </div>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed">
            Chuyên phân phối sỉ và lẻ Sơn nước nội ngoại thất, Chất chống thấm, Thiết bị vệ sinh, Gạch men, Ngói lợp, Bồn nước, Bình nóng lạnh, Keo dán gạch và Vật tư thiết bị xây dựng chính hãng tại TP Đà Nẵng.
          </p>
          <ul class="text-xs space-y-1.5 text-slate-200 pt-1">
            <li>📍 <strong>Địa chỉ:</strong> 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng</li>
            <li>📞 <strong>Điện thoại / Zalo:</strong> <a href="tel:0905119918" class="text-amber-300 font-bold hover:underline">0905.119.918</a></li>
            <li>👤 <strong>Đại diện pháp luật:</strong> Trương Văn Thuyền</li>
            <li>🌐 <strong>Website:</strong> <a href="https://kimgiakhanh.com" class="text-amber-300 hover:underline">https://kimgiakhanh.com</a></li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm (4 cột) -->
        <div class="lg:col-span-4 space-y-2">
          <div class="text-xs font-extrabold uppercase text-amber-400 tracking-wider">
            DANH MỤC SẢN PHẨM
          </div>
          <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
            <a href="#sec-son" class="hover:text-white">› Sơn Jotun &amp; Dulux</a>
            <a href="#sec-son" class="hover:text-white">› Chống thấm Sika</a>
            <a href="#sec-tbvs" class="hover:text-white">› Bồn cầu liền khối</a>
            <a href="#sec-tbvs" class="hover:text-white">› Sen cây nóng lạnh</a>
            <a href="#sec-gach" class="hover:text-white">› Gạch men Đồng Tâm</a>
            <a href="#sec-gach" class="hover:text-white">› Gạch Kimgres</a>
            <a href="#sec-ngoi" class="hover:text-white">› Ngói lợp DIC &amp; Đất Việt</a>
            <a href="#sec-bonnuoc" class="hover:text-white">› Bồn nước Tân Á, Sơn Hà</a>
            <a href="#sec-binhnonglanh" class="hover:text-white">› Bình nóng lạnh Ariston</a>
            <a href="#sec-keo" class="hover:text-white">› Keo dán gạch, chà ron</a>
          </div>
        </div>

        <!-- Liên kết & Hỗ trợ khách hàng (3 cột) -->
        <div class="lg:col-span-3 space-y-2">
          <div class="text-xs font-extrabold uppercase text-amber-400 tracking-wider">
            LIÊN KẾT &amp; HỖ TRỢ
          </div>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li><a href="#" class="hover:text-white">› Trang chủ kimgiakhanh.com</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white">› Yêu cầu báo giá công trình</a></li>
            <li><a href="#doi-tac" class="hover:text-white">› Đối tác thương hiệu</a></li>
            <li><a href="#tin-tuc" class="hover:text-white">› Kinh nghiệm lựa chọn VLXD</a></li>
            <li><a href="#lien-he-map" class="hover:text-white">› Bản đồ đường đi (631 Ngô Quyền)</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>Copyright 2026 © <strong>CÔNG TY TNHH MỘT THÀNH VIÊN KIM GIA KHÁNH</strong> (kimgiakhanh.com). All rights reserved.</div>
        <div>Địa chỉ: 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng • SĐT: 0905.119.918</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE
       (Tương thích hoàn hảo trên cả máy tính và điện thoại)
       ===================================================================== -->
  <div class="floating-contact-wrap" aria-label="Liên hệ nhanh">
    <!-- Nút Zalo -->
    <a href="https://zalo.me/0905119918" target="_blank" rel="noopener" class="floating-btn bg-[#0068ff] hover:bg-[#0056d6]">
      <span class="floating-btn-icon font-extrabold text-[11px]">Zalo</span>
      <span>Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a href="#lien-he-map" class="floating-btn bg-[#1877f2] hover:bg-[#1464cc]">
      <span class="floating-btn-icon">
        <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M13.397 20.997v-8.196h2.765l.411-3.209h-3.176V7.548c0-.926.258-1.56 1.587-1.56h1.684V3.127A22.336 22.336 0 0 0 14.201 3c-2.444 0-4.122 1.492-4.122 4.231v2.355H7.332v3.209h2.753v8.202h3.312z"/></svg>
      </span>
      <span>Facebook</span>
    </a>

    <!-- Nút Hotline -->
    <a href="tel:0905119918" class="floating-btn bg-[#d90429] hover:bg-[#b80322]">
      <span class="floating-btn-icon">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      </span>
      <span>0905.119.918</span>
    </a>
  </div>

  <!-- MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH -->
  <div id="productModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-slate-900/65 backdrop-blur-xs">
    <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="p-3.5 bg-brand-primary text-white flex items-center justify-between">
        <h3 id="modalTitle" class="text-xs sm:text-sm font-bold pr-2">Chi tiết sản phẩm</h3>
        <button type="button" onclick="closeProductModal()" class="p-1 rounded hover:bg-white/15">✕</button>
      </div>
      <div class="p-4 space-y-3">
        <div class="flex flex-col sm:flex-row gap-4 items-center">
          <div class="w-40 h-40 bg-slate-50 border border-slate-200 rounded p-2 flex items-center justify-center shrink-0">
            <img id="modalImg" src="" alt="" class="max-w-full max-h-full object-contain">
          </div>
          <div class="space-y-1.5 text-xs w-full">
            <div id="modalCat" class="text-amber-600 font-bold uppercase text-[11px]"></div>
            <div id="modalName" class="text-sm font-extrabold text-slate-800"></div>
            <div class="flex items-center gap-2 pt-1">
              <span id="modalOldPrice" class="line-through text-slate-400 text-xs"></span>
              <span id="modalPrice" class="text-base font-extrabold text-red-600"></span>
              <span id="modalDiscount" class="px-1.5 py-0.5 rounded bg-red-600 text-white font-bold text-[10px]"></span>
            </div>
            <p class="text-slate-600 pt-1 leading-relaxed">
              Phân phối chính hãng bởi <strong>CÔNG TY TNHH MTV KIM GIA KHÁNH</strong> tại 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng.
            </p>
          </div>
        </div>
        <div class="pt-3 border-t border-slate-200 flex flex-wrap justify-end gap-2">
          <a href="tel:0905119918" class="px-3.5 py-2 rounded bg-red-600 hover:bg-red-700 text-white font-bold text-xs">
            📞 Gọi báo giá: 0905.119.918
          </a>
          <a href="https://zalo.me/0905119918" target="_blank" rel="noopener" class="px-3.5 py-2 rounded bg-brand-primary hover:bg-brand-light text-white font-bold text-xs">
            💬 Nhắn Zalo đặt hàng
          </a>
          <button type="button" onclick="closeProductModal()" class="px-3 py-2 rounded bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-xs">
            Đóng
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- MODAL ĐỌC BÀI VIẾT -->
  <div id="articleModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-slate-900/65 backdrop-blur-xs">
    <div class="bg-white rounded-lg max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="p-3.5 bg-brand-primary text-white flex items-center justify-between">
        <h3 id="artModalTitle" class="text-xs sm:text-sm font-bold pr-2">Kinh nghiệm xây dựng</h3>
        <button type="button" onclick="closeArticleModal()" class="p-1 rounded hover:bg-white/15">✕</button>
      </div>
      <div class="p-4 space-y-3 text-xs sm:text-sm text-slate-700 leading-relaxed">
        <div id="artModalBody"></div>
        <div class="p-3 rounded bg-brand-soft text-xs text-brand-primary font-medium">
          Cần tư vấn kỹ thuật &amp; báo giá chi tiết tại Đà Nẵng, quý khách vui lòng liên hệ <strong>CÔNG TY TNHH MTV KIM GIA KHÁNH</strong> - 631 Ngô Quyền, Phường An Hải, TP Đà Nẵng - Hotline/Zalo: <strong>0905.119.918</strong>.
        </div>
        <div class="text-right">
          <button type="button" onclick="closeArticleModal()" class="px-4 py-1.5 rounded bg-brand-primary text-white font-bold text-xs">Đóng</button>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT: DỮ LIỆU 19 ẢNH SẢN PHẨM THỰC TẾ GOOGLE DRIVE & TƯƠNG TÁC
       ===================================================================== -->
  <script>
    // Danh sách 19 ID file ảnh thực tế từ Google Drive do khách hàng cung cấp
    const DRIVE_IDS = [
      "1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY", // #1
      "11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP", // #2
      "1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr", // #3
      "1X31hmhpLVVORV-tmMSZYzBO-qtpyusry", // #4
      "171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O", // #5
      "1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg", // #6
      "1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4", // #7
      "1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54", // #8
      "19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r", // #9
      "1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h", // #10
      "1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN", // #11
      "1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c", // #12
      "1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP", // #13
      "1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-", // #14
      "17YrxXteZmzhvVRYgfaklNGC2hKjN09N8", // #15
      "19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP", // #16
      "1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf", // #17
      "15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_", // #18
      "1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh"  // #19
    ];

    // Cấu trúc danh mục sản phẩm chuẩn website mẫu noithatngonguyen.com
    // Gắn toàn bộ 19 ảnh thực tế từ Google Drive vào đúng danh mục và tên sản phẩm
    const CATALOG_SECTIONS = [
      {
        id: "sec-son",
        title: "SƠN",
        subcats: ["Jotun", "Dulux-Maxilite", "Tito", "Chống thấm"],
        products: [
          {
            driveId: DRIVE_IDS[0],
            name: "Essence Sơn Trắng Trần Chuyên Dụng Jotun Chính Hãng",
            subcat: "Jotun",
            oldPrice: "1.150.000₫",
            price: "940.000₫",
            discount: "-18%"
          },
          {
            driveId: DRIVE_IDS[1],
            name: "Sơn Ngoại Thất Jotun Tough Shield Max Bền Màu",
            subcat: "Jotun",
            oldPrice: "1.680.000₫",
            price: "1.390.000₫",
            discount: "-17%"
          },
          {
            driveId: DRIVE_IDS[2],
            name: "Sơn Jotun Jotashield Sạch Vượt Trội Cao Cấp",
            subcat: "Jotun",
            oldPrice: "2.350.000₫",
            price: "1.950.000₫",
            discount: "-17%"
          },
          {
            driveId: DRIVE_IDS[3],
            name: "Sơn Nội Thất Dulux - Maxilite Che Phủ Hiệu Quả",
            subcat: "Dulux-Maxilite",
            oldPrice: "1.290.000₫",
            price: "1.050.000₫",
            discount: "-19%"
          }
        ]
      },
      {
        id: "sec-tbvs",
        title: "THIẾT BỊ VỆ SINH",
        subcats: ["Bồn cầu", "Sen vòi", "Lavabo", "Gương", "Phụ kiện nhà tắm"],
        products: [
          {
            driveId: DRIVE_IDS[4],
            name: "Bồn Cầu Liền Khối DK-C6551-W Men Tuyết Kháng Khuẩn",
            subcat: "Bồn cầu",
            oldPrice: "4.500.000₫",
            price: "3.600.000₫",
            discount: "-20%"
          },
          {
            driveId: DRIVE_IDS[5],
            name: "Sen Tắm Âm Tường Inax BFV-81SEHW Nóng Lạnh",
            subcat: "Sen vòi",
            oldPrice: "5.200.000₫",
            price: "4.250.000₫",
            discount: "-18%"
          },
          {
            driveId: DRIVE_IDS[6],
            name: "Sen Cây Viglacera Nóng Lạnh VG596 Đồng Mạ Crom",
            subcat: "Sen vòi",
            oldPrice: "3.950.000₫",
            price: "3.150.000₫",
            discount: "-20%"
          },
          {
            driveId: DRIVE_IDS[7],
            name: "Bộ Tủ Chậu Lavabo & Gương Phòng Tắm Cao Cấp",
            subcat: "Lavabo",
            oldPrice: "3.400.000₫",
            price: "2.850.000₫",
            discount: "-16%"
          }
        ]
      },
      {
        id: "sec-gach",
        title: "GẠCH MEN",
        subcats: ["Đồng Tâm", "Gạch 80 x 80", "Gạch 60 x 60", "Gạch 30 x 60", "Kimgres"],
        products: [
          {
            driveId: DRIVE_IDS[8],
            name: "Gạch Porcelain Kháng Khuẩn 8080FANSIPAN007-FP Đồng Tâm",
            subcat: "Đồng Tâm",
            oldPrice: "420.000₫/m²",
            price: "345.000₫/m²",
            discount: "-18%"
          },
          {
            driveId: DRIVE_IDS[9],
            name: "Gạch Porcelain 2 Da 8080PLATINUM003 Bóng Kiếng",
            subcat: "Đồng Tâm",
            oldPrice: "395.000₫/m²",
            price: "325.000₫/m²",
            discount: "-18%"
          },
          {
            driveId: DRIVE_IDS[10],
            name: "Gạch Porcelain Kháng Khuẩn 8080DONGVAN010-FP-H+ Cao Cấp",
            subcat: "Kimgres",
            oldPrice: "410.000₫/m²",
            price: "340.000₫/m²",
            discount: "-17%"
          },
          {
            driveId: DRIVE_IDS[0],
            name: "Gạch Ốp Lát Đồng Tâm 60x60 Vân Đá Tự Nhiên",
            subcat: "Đồng Tâm",
            oldPrice: "295.000₫/m²",
            price: "245.000₫/m²",
            discount: "-17%"
          }
        ]
      },
      {
        id: "sec-ngoi",
        title: "NGÓI LỢP",
        subcats: ["DIC", "Ngói Đất Việt"],
        products: [
          {
            driveId: DRIVE_IDS[11],
            name: "Ngói Màu DIC Đỏ Tươi DT10S Chống Rêu Mốc",
            subcat: "DIC",
            oldPrice: "38.000₫/viên",
            price: "31.500₫/viên",
            discount: "-17%"
          },
          {
            driveId: DRIVE_IDS[12],
            name: "Ngói Đất Việt Đỏ Đậm DD09S Lợp Mái Biệt Thự",
            subcat: "Ngói Đất Việt",
            oldPrice: "36.000₫/viên",
            price: "29.900₫/viên",
            discount: "-17%"
          }
        ]
      },
      {
        id: "sec-bonnuoc",
        title: "BỒN NƯỚC",
        subcats: ["Letton", "Sơn Hà", "Tân Á"],
        products: [
          {
            driveId: DRIVE_IDS[13],
            name: "Bồn Nước Inox Tân Á Đứng 1000 Lít TA8D1000 (F940)",
            subcat: "Tân Á",
            oldPrice: "4.350.000₫",
            price: "3.590.000₫",
            discount: "-17%"
          },
          {
            driveId: DRIVE_IDS[14],
            name: "Bồn Nhựa Vân Đá Sơn Hà Ngang 1000 Lít Bền Đẹp",
            subcat: "Sơn Hà",
            oldPrice: "3.150.000₫",
            price: "2.620.000₫",
            discount: "-17%"
          }
        ]
      },
      {
        id: "sec-binhnonglanh",
        title: "BÌNH NÓNG LẠNH",
        subcats: ["Ariston", "Ferroli"],
        products: [
          {
            driveId: DRIVE_IDS[15],
            name: "Máy Nước Nóng Ariston AN2 30 RS 2.5 FE 30 Lít 2.5KW",
            subcat: "Ariston",
            oldPrice: "4.190.000₫",
            price: "3.390.000₫",
            discount: "-19%"
          },
          {
            driveId: DRIVE_IDS[16],
            name: "Máy Nước Nóng Ferroli QQ Evo 15L ME 15 Lít 2.5KW",
            subcat: "Ferroli",
            oldPrice: "2.890.000₫",
            price: "2.350.000₫",
            discount: "-19%"
          }
        ]
      },
      {
        id: "sec-keo",
        title: "KEO DÁN GẠCH, CHÀ RON",
        subcats: ["Bestmix", "Đồng Tâm", "Keo cá sấu", "Sika"],
        products: [
          {
            driveId: DRIVE_IDS[17],
            name: "Keo Dán Gạch Gecko Floor Chuyên Lát Nền Bao 25Kg",
            subcat: "Đồng Tâm",
            oldPrice: "285.000₫/bao",
            price: "235.000₫/bao",
            discount: "-18%"
          },
          {
            driveId: DRIVE_IDS[18],
            name: "Keo Chà Ron Crocodile Silver (Keo Cá Sấu Thái Lan) & Sika Tilebond GP",
            subcat: "Keo cá sấu",
            oldPrice: "145.000₫",
            price: "118.000₫",
            discount: "-19%"
          }
        ]
      }
    ];

    // Hàm tạo URL ảnh thực tế từ Google Drive có cơ chế tự động chuyển đổi dự phòng
    function getDriveThumbUrl(fileId) {
      return `https://drive.google.com/thumbnail?id=${fileId}&sz=w700`;
    }
    function getDriveFallbackUrl(fileId) {
      return `https://lh3.googleusercontent.com/d/${fileId}=w700`;
    }

    // Render toàn bộ danh mục và sản phẩm ra trang chủ
    function renderCatalog(searchKeyword = "") {
      const container = document.getElementById("catalogContainer");
      const kw = searchKeyword.trim().toLowerCase();
      let html = "";

      CATALOG_SECTIONS.forEach((sec) => {
        const filteredProducts = sec.products.filter((p) => {
          if (!kw) return true;
          return (
            p.name.toLowerCase().includes(kw) ||
            p.subcat.toLowerCase().includes(kw) ||
            sec.title.toLowerCase().includes(kw)
          );
        });

        if (filteredProducts.length === 0) return;

        const subcatPills = sec.subcats
          .map(
            (sc) =>
              `<button type="button" onclick="filterSubCategory('${sec.id}', '${sc}')" class="flatsome-subcat-pill">${sc}</button>`
          )
          .join("");

        const productCards = filteredProducts
          .map((prod) => {
            const thumbUrl = getDriveThumbUrl(prod.driveId);
            const fallbackUrl = getDriveFallbackUrl(prod.driveId);
            const safeName = prod.name.replace(/'/g, "\\'");
            return `
              <div class="product-card">
                <!-- Badge % giảm giá góc trên bên trái chuẩn Flatsome -->
                <div class="flatsome-sale-badge">${prod.discount}</div>

                <!-- Ảnh sản phẩm thực tế từ Google Drive -->
                <div onclick="openProductModal('${safeName}', '${sec.title} - ${prod.subcat}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}', '${thumbUrl}')"
                     class="cursor-pointer bg-white p-2.5 sm:p-3 h-40 sm:h-48 flex items-center justify-center border-b border-slate-100">
                  <img
                    src="${thumbUrl}"
                    onerror="if(!this.dataset.tried){this.dataset.tried='1';this.src='${fallbackUrl}';}else{this.src='https://placehold.co/400x400/eef4fb/0b3b75?text=KIM+GIA+KHANH';}"
                    alt="${prod.name}"
                    loading="lazy"
                    class="max-h-full max-w-full object-contain transition-transform duration-300 hover:scale-105"
                  >
                </div>

                <!-- Thông tin sản phẩm: Tên đầy đủ không bị cắt hay tràn chữ -->
                <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between bg-white">
                  <div>
                    <div class="text-[10.5px] font-semibold text-amber-600 uppercase mb-1">
                      ${prod.subcat}
                    </div>
                    <h3 onclick="openProductModal('${safeName}', '${sec.title} - ${prod.subcat}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}', '${thumbUrl}')"
                        class="product-title cursor-pointer">
                      ${prod.name}
                    </h3>
                  </div>

                  <div class="pt-1.5 border-t border-slate-100 mt-1">
                    <div class="flex flex-wrap items-baseline gap-1.5">
                      <span class="text-[11px] text-slate-400 line-through">${prod.oldPrice}</span>
                      <span class="text-xs sm:text-sm font-extrabold text-brand-sale">${prod.price}</span>
                    </div>
                    <div class="mt-2 flex items-center gap-1.5">
                      <button type="button"
                        onclick="openProductModal('${safeName}', '${sec.title} - ${prod.subcat}', '${prod.oldPrice}', '${prod.price}', '${prod.discount}', '${thumbUrl}')"
                        class="w-full py-1.5 px-2 rounded bg-brand-soft hover:bg-brand-primary text-brand-primary hover:text-white font-bold text-[11px] transition cursor-pointer">
                        Đặt hàng / Báo giá
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            `;
          })
          .join("");

        // Chia 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính
        html += `
          <section id="${sec.id}" class="ux-category-section">
            <div class="flatsome-sec-head">
              <div class="flatsome-sec-title">${sec.title}</div>
              <div class="flatsome-subcat-list">
                <button type="button" onclick="filterSubCategory('${sec.id}', 'ALL')" class="flatsome-subcat-pill !bg-brand-soft !text-brand-primary">Tất cả</button>
                ${subcatPills}
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-primary hover:text-amber-600 ml-1 whitespace-nowrap">Xem thêm ›</a>
              </div>
            </div>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-3.5">
              ${productCards}
            </div>
          </section>
        `;
      });

      if (!html) {
        html = `
          <div class="bg-white p-6 rounded border border-slate-200 text-center space-y-2">
            <div class="text-sm font-bold text-slate-700">Không tìm thấy sản phẩm khớp với từ khóa "${searchKeyword}"</div>
            <button type="button" onclick="resetSearch()" class="px-4 py-1.5 rounded bg-brand-primary text-white text-xs font-bold">Hiển thị tất cả sản phẩm</button>
          </div>
        `;
      }

      container.innerHTML = html;
    }

    function filterCategory(cat) {
      document.getElementById("searchInput").value = "";
      renderCatalog("");
    }

    function filterSubCategory(sectionId, subcat) {
      const secEl = document.getElementById(sectionId);
      if (secEl) {
        secEl.scrollIntoView({ behavior: "smooth", block: "start" });
      }
    }

    function resetSearch() {
      const input = document.getElementById("searchInput");
      input.value = "";
      renderCatalog("");
    }

    // Tự động trượt 2 Banner
    let currentSlide = 0;
    const slides = document.querySelectorAll(".banner-slide");
    const dots = document.querySelectorAll(".banner-dot");

    function showSlide(index) {
      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((sl, idx) => {
        if (idx === currentSlide) {
          sl.classList.add("active");
        } else {
          sl.classList.remove("active");
        }
      });
      dots.forEach((dot, idx) => {
        dot.className =
          idx === currentSlide
            ? "banner-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition"
            : "banner-dot w-2.5 h-2.5 rounded-full bg-white/40 transition";
      });
    }

    function goToSlide(index) {
      showSlide(index);
    }

    document.getElementById("prevBannerBtn").addEventListener("click", () => {
      showSlide(currentSlide - 1);
    });
    document.getElementById("nextBannerBtn").addEventListener("click", () => {
      showSlide(currentSlide + 1);
    });

    setInterval(() => {
      showSlide(currentSlide + 1);
    }, 5500);

    // Xử lý đóng/mở menu trên điện thoại
    const mobileDrawer = document.getElementById("mobileDrawer");
    document.getElementById("mobileMenuBtn").addEventListener("click", () => {
      mobileDrawer.classList.remove("hidden");
    });
    document.getElementById("closeMobileDrawer").addEventListener("click", () => {
      mobileDrawer.classList.add("hidden");
    });
    document.getElementById("mobileDrawerBackdrop").addEventListener("click", () => {
      mobileDrawer.classList.add("hidden");
    });
    document.querySelectorAll(".mobile-nav-item").forEach((item) => {
      item.addEventListener("click", () => {
        mobileDrawer.classList.add("hidden");
      });
    });

    // Tìm kiếm sản phẩm trực tiếp
    document.getElementById("searchInput").addEventListener("input", (e) => {
      renderCatalog(e.target.value);
    });
    document.getElementById("searchBtn").addEventListener("click", () => {
      renderCatalog(document.getElementById("searchInput").value);
    });

    // Modal Chi tiết sản phẩm
    function openProductModal(name, cat, oldPrice, price, discount, imgUrl) {
      document.getElementById("modalTitle").textContent = name;
      document.getElementById("modalName").textContent = name;
      document.getElementById("modalCat").textContent = cat;
      document.getElementById("modalOldPrice").textContent = oldPrice;
      document.getElementById("modalPrice").textContent = price;
      document.getElementById("modalDiscount").textContent = discount;
      document.getElementById("modalImg").src = imgUrl;
      const modal = document.getElementById("productModal");
      modal.classList.remove("hidden");
      modal.classList.add("flex");
    }

    function closeProductModal() {
      const modal = document.getElementById("productModal");
      modal.classList.add("hidden");
      modal.classList.remove("flex");
    }

    // Modal Đọc bài viết trang chủ
    const ARTICLES = [
      {
        title: "Kinh nghiệm chọn sơn ngoại thất Jotun bền màu trước khí hậu nắng gió miền Trung",
        body: "Tại khu vực Đà Nẵng và miền Trung, tường ngoại thất thường xuyên chịu tác động của tia UV cường độ cao và mưa bão. Để lớp sơn bền màu từ 8-10 năm, gia chủ nên sử dụng hệ thống sơn đồng bộ gồm: 2 lớp bột trét chống nứt, 1 lớp sơn lót chống kiềm Jotun Ultra Primer hoặc Majestic Primer, và 2 lớp sơn phủ ngoại thất Jotun Jotashield hoặc Tough Shield Max."
      },
      {
        title: "Cách chọn trọn bộ bồn cầu liền khối và sen cây nóng lạnh tiết kiệm nước",
        body: "Bồn cầu liền khối với thiết kế không khe hở giúp việc vệ sinh cực kỳ nhanh chóng, kết hợp chế độ xả xoáy Siphon mạnh mẽ tiết kiệm nước. Khi chọn sen cây tắm nóng lạnh Inax hoặc Viglacera, quý khách nên kiểm tra áp lực nước từ bồn chứa để lựa chọn bát sen tăng áp phù hợp."
      },
      {
        title: "Xu hướng chọn gạch Porcelain 80x80 và keo dán gạch chống bong tróc nền nhà",
        body: "Gạch xương đá Porcelain 80x80 của Đồng Tâm và Kimgres có độ hút nước cực thấp (<0.5%). Do kết cấu đặc chắc, việc lát gạch khổ lớn bằng keo dán gạch chuyên dụng (Gecko Floor, Sika Tilebond GP, Keo Cá Sấu) và keo chà ron chống thấm giúp nền nhà bám dính vĩnh viễn, không bị phồng rộp."
      },
      {
        title: "Hướng dẫn chọn dung tích bồn nước Tân Á, Sơn Hà và bình nóng lạnh theo số người",
        body: "Với gia đình từ 3-5 thành viên, bồn nước dung tích 1000L - 1500L (Inox Tân Á hoặc Bồn nhựa Sơn Hà) kết hợp bình nóng lạnh gián tiếp 15L - 30L của Ariston hoặc Ferroli có tích hợp cầu giao chống giật ELCB là giải pháp an toàn và tiết kiệm điện năng nhất."
      }
    ];

    function openArticleModal(idx) {
      const art = ARTICLES[idx];
      if (!art) return;
      document.getElementById("artModalTitle").textContent = art.title;
      document.getElementById("artModalBody").textContent = art.body;
      const modal = document.getElementById("articleModal");
      modal.classList.remove("hidden");
      modal.classList.add("flex");
    }

    function closeArticleModal() {
      const modal = document.getElementById("articleModal");
      modal.classList.add("hidden");
      modal.classList.remove("flex");
    }

    // Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById("qName").value.trim();
      const phone = document.getElementById("qPhone").value.trim();
      const cat = document.getElementById("qCategory").value;
      const addr = document.getElementById("qAddress").value.trim();
      const box = document.getElementById("quoteSuccessBox");

      box.classList.remove("hidden");
      box.innerHTML = `Cảm ơn quý khách <strong>${name}</strong> (${phone})! Yêu cầu báo giá danh mục <strong>${cat}</strong> ${addr ? "tại " + addr : ""} đã được ghi nhận. Bộ phận kinh doanh <strong>CÔNG TY TNHH MTV KIM GIA KHÁNH (0905.119.918)</strong> sẽ liên hệ lại ngay!`;
      document.getElementById("quoteForm").reset();
    }

    // Khởi chạy render sản phẩm khi tải trang
    window.onload = function () {
      renderCatalog("");
    };
  </script>
</body>
</html>
