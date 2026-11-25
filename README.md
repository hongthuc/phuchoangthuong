<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG | Cửa Nhôm Xingfa Đà Nẵng</title>
  <meta name="description" content="Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương - Chuyên thiết kế, gia công, thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0905.479.773.">
  <meta name="keywords" content="Phúc Hoàng Thương, phuchoangthuong.com, cửa nhôm xingfa Đà Nẵng, cửa kính cường lực Đà Nẵng, cầu thang kính, phòng tắm kính, kính ốp bếp">

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ liên kết trang web (Zalo, Facebook) -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="Phúc Hoàng Thương - phuchoangthuong.com">
  <meta property="og:url" content="https://phuchoangthuong.com/">
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG | Cửa Nhôm Xingfa Đà Nẵng">
  <meta property="og:description" content="Thi công Cửa nhôm Xingfa, Cửa nhựa lõi thép, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính chuyên nghiệp tại Đà Nẵng. Hotline: 0905.479.773.">
  <meta property="og:image" content="https://phuchoangthuong.com/assets/logo-phuc-hoang-thuong-thumbnail.png">
  <meta property="og:image:alt" content="Logo Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://phuchoangthuong.com/assets/logo-phuc-hoang-thuong-thumbnail.png">

  <!-- Google Font: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    /* Cấu hình hệ màu thương hiệu đồng bộ với Logo Phúc Hoàng Thương (Xanh Navy Hoàng Gia & Vàng Kim) */
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              navy: '#0F4C81',
              dark: '#0A355C',
              deep: '#072745',
              light: '#EAF2FA',
              gold: '#C88A1E',
              goldLight: '#E5A93B',
              goldBg: '#FDF6E7',
              slate: '#F5F7FA',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo Box-Sizing chuẩn và tuyệt đối không tràn viền ngang, không lệch phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    /* Container chuẩn 95% chiều ngang màn hình máy tính theo yêu cầu */
    .pht-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .pht-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Dropdown Menu Flatsome mượt mà cho Desktop */
    .nav-dropdown-parent {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      pointer-events: none;
    }
    .nav-dropdown-parent:hover .nav-dropdown-menu,
    .nav-dropdown-parent:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
      pointer-events: auto;
    }

    /* Banner Slider chuyên nghiệp: Đảm bảo 2 slide luôn có kích thước bằng nhau 100% */
    .banner-track {
      display: grid;
      grid-template-columns: 1fr;
    }
    .banner-slide {
      grid-area: 1 / 1 / 2 / 2;
      transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
    }
    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 10;
    }

    /* Hiệu ứng gợn sóng nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
      70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }
    .hotline-pulse {
      animation: pulseRing 2s infinite;
    }

    /* Hiệu ứng gạch chân tiêu đề Flatsome */
    .flatsome-title-wrap {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      margin-bottom: 1.5rem;
    }
    .flatsome-title-line {
      height: 2px;
      flex: 1;
      max-width: 90px;
      background: linear-gradient(90deg, transparent, #CBD5E1);
    }
    .flatsome-title-line.right {
      background: linear-gradient(90deg, #CBD5E1, transparent);
    }
  </style>
</head>

<body class="bg-white text-slate-800 antialiased selection:bg-brand-navy selection:text-white">

  <!-- ========================================================================= -->
  <!-- 1. TOP BAR THÔNG TIN CÔNG TY (Sạch sẽ, không hiển thị thanh sửa UXBuilder) -->
  <!-- ========================================================================= -->
  <div class="bg-brand-dark text-white text-xs border-b border-brand-navy/60">
    <div class="pht-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1 text-slate-200">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-brand-goldLight shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>110 Đặng Huy Trứ, P. Hòa Khánh, TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-brand-goldLight shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Làm việc: 07:30 - 21:00 (T2 - CN)</span>
        </span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-slate-200">
        <a href="tel:0905479773" class="hover:text-brand-goldLight transition font-medium">Hotline: 0905.479.773</a>
        <span class="text-slate-500">|</span>
        <span class="text-brand-goldLight font-medium">phuchoangthuong.com</span>
      </div>
    </div>
  </div>

  <!-- ========================================================================= -->
  <!-- 2. MAIN HEADER (Logo gọn nhỏ + Menu 1 hàng chuẩn Desktop, KHÔNG nút gọi)   -->
  <!-- ========================================================================= -->
  <header id="main-header" class="sticky top-0 z-40 bg-white/98 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="pht-container">
      <div class="flex items-center justify-between h-16 lg:h-[68px] gap-2">

        <!-- Logo Công Ty Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Phúc Hoàng Thương - Trang chủ">
          <!-- Biểu tượng SVG Logo khung cửa nhôm kính & chữ lồng PHT -->
          <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Phúc Hoàng Thương">
            <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F4C81"/>
            <rect x="6" y="6" width="52" height="52" rx="9" stroke="#C88A1E" stroke-width="2.2"/>
            <!-- Biểu tượng mái kiến trúc và khung cửa nhôm kính -->
            <path d="M14 27L32 14L50 27" stroke="#E5A93B" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
            <rect x="18" y="29" width="12" height="19" rx="1.5" fill="#FFFFFF" fill-opacity="0.95"/>
            <rect x="34" y="29" width="12" height="19" rx="1.5" fill="#E5A93B"/>
            <line x1="24" y1="29" x2="24" y2="48" stroke="#0F4C81" stroke-width="1.5"/>
            <line x1="40" y1="29" x2="40" y2="48" stroke="#0F4C81" stroke-width="1.5"/>
            <line x1="15" y1="50" x2="49" y2="50" stroke="#FFFFFF" stroke-width="2" stroke-linecap="round"/>
          </svg>
          <div class="leading-tight">
            <div class="text-[13px] sm:text-[14px] lg:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition whitespace-nowrap">
              PHÚC HOÀNG THƯƠNG
            </div>
            <div class="text-[9.5px] sm:text-[10px] font-semibold tracking-wider text-brand-gold uppercase whitespace-nowrap">
              Nhôm Kính &amp; Xây Dựng
            </div>
          </div>
        </a>

        <!-- Menu Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng duy nhất, không xuống dòng -->
        <nav class="hidden lg:flex items-center justify-end flex-1 min-w-0" aria-label="Menu chính">
          <ul class="flex items-center justify-end gap-0.5 xl:gap-1.5 flex-nowrap">
            <li>
              <a href="#trang-chu" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Trang chủ
              </a>
            </li>
            <li>
              <a href="#gioi-thieu" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Giới thiệu
              </a>
            </li>

            <!-- Dropdown: Cửa nhôm xingfa -->
            <li class="nav-dropdown-parent">
              <a href="#cua-nhom-xingfa" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                <span>Cửa nhôm xingfa</span>
                <svg class="w-3 h-3 text-slate-400" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-56 z-50">
                <ul class="bg-white rounded-xl shadow-xl border border-slate-100 py-1.5 overflow-hidden">
                  <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('1-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa 1 cánh</a></li>
                  <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('2-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa 2 cánh</a></li>
                  <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('3-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa 3 cánh</a></li>
                  <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('4-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa 4 cánh</a></li>
                  <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('5-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa 5 cánh</a></li>
                </ul>
              </div>
            </li>

            <li>
              <a href="#danh-muc-san-pham" onclick="scrollToSection('danh-muc-san-pham')" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Cửa kính cường lực
              </a>
            </li>

            <!-- Dropdown: Sản phẩm -->
            <li class="nav-dropdown-parent">
              <a href="#danh-muc-san-pham" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                <span>Sản phẩm</span>
                <svg class="w-3 h-3 text-slate-400" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-52 z-50">
                <ul class="bg-white rounded-xl shadow-xl border border-slate-100 py-1.5 overflow-hidden">
                  <li><a href="#cua-nhom-xingfa" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhôm xingfa</a></li>
                  <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa nhựa lõi thép</a></li>
                  <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cửa kính tự động</a></li>
                  <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Cầu thang kính</a></li>
                  <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Kính ốp bếp</a></li>
                  <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-light hover:text-brand-navy font-medium transition">Phòng tắm kính</a></li>
                </ul>
              </div>
            </li>

            <li>
              <a href="#cong-trinh" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Công trình
              </a>
            </li>
            <li>
              <a href="#bao-gia" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Báo giá
              </a>
            </li>
            <li>
              <a href="#tin-tuc" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Tin tức
              </a>
            </li>
            <li>
              <a href="#lien-he" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-navy transition whitespace-nowrap rounded-lg hover:bg-brand-light/70">
                Liên hệ
              </a>
            </li>
          </ul>
        </nav>

        <!-- Nút mở Menu Mobile (Không đặt nút Gọi Ngay ở Header để tránh tràn viền) -->
        <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-xl text-brand-navy bg-brand-light hover:bg-brand-navy hover:text-white transition" aria-label="Mở danh mục trang web" aria-expanded="false">
          <svg id="icon-menu-open" class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
          <svg id="icon-menu-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>

      </div>
    </div>

    <!-- Menu Mobile Drawer (Thu gọn gọn gàng, dễ thao tác chạm trên điện thoại) -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg max-h-[82vh] overflow-y-auto">
      <div class="p-3 space-y-1">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-brand-navy bg-brand-light/60">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Giới thiệu</a>

        <!-- Accordion Mobile: Cửa nhôm xingfa -->
        <div class="rounded-lg border border-slate-100 overflow-hidden">
          <button type="button" onclick="toggleSubmenu('sub-xingfa')" class="w-full flex items-center justify-between px-3.5 py-2.5 text-sm font-semibold text-slate-700 hover:bg-slate-50">
            <span>Cửa nhôm xingfa</span>
            <svg id="arrow-sub-xingfa" class="w-4 h-4 text-slate-500 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </button>
          <div id="sub-xingfa" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 border-t border-slate-100">
            <a href="#cua-nhom-xingfa" onclick="selectProductCategory('1-canh'); closeMobileMenu();" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa 1 cánh</a>
            <a href="#cua-nhom-xingfa" onclick="selectProductCategory('2-canh'); closeMobileMenu();" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa 2 cánh</a>
            <a href="#cua-nhom-xingfa" onclick="selectProductCategory('3-canh'); closeMobileMenu();" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa 3 cánh</a>
            <a href="#cua-nhom-xingfa" onclick="selectProductCategory('4-canh'); closeMobileMenu();" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa 4 cánh</a>
            <a href="#cua-nhom-xingfa" onclick="selectProductCategory('5-canh'); closeMobileMenu();" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa 5 cánh</a>
          </div>
        </div>

        <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Cửa kính cường lực</a>

        <!-- Accordion Mobile: Sản phẩm -->
        <div class="rounded-lg border border-slate-100 overflow-hidden">
          <button type="button" onclick="toggleSubmenu('sub-sanpham')" class="w-full flex items-center justify-between px-3.5 py-2.5 text-sm font-semibold text-slate-700 hover:bg-slate-50">
            <span>Sản phẩm</span>
            <svg id="arrow-sub-sanpham" class="w-4 h-4 text-slate-500 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </button>
          <div id="sub-sanpham" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 border-t border-slate-100">
            <a href="#cua-nhom-xingfa" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhôm xingfa</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa nhựa lõi thép</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cửa kính tự động</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Cầu thang kính</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Kính ốp bếp</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2 text-[13px] text-slate-700 hover:text-brand-navy rounded">Phòng tắm kính</a>
          </div>
        </div>

        <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Công trình</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3.5 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ========================================================================= -->
    <!-- 3. 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Kích thước bằng nhau, chữ cách xa viền) -->
    <!-- ========================================================================= -->
    <section class="py-3 sm:py-5 bg-brand-slate" aria-label="Banner quảng bá">
      <div class="pht-container">
        <div id="hero-slider" class="relative rounded-2xl overflow-hidden shadow-lg bg-brand-dark">
          <!-- Container Grid chồng lớp giúp 2 slide luôn có kích thước cao & rộng bằng nhau 100% -->
          <div class="banner-track">

            <!-- BANNER 1: CỬA NHÔM XINGFA NHẬP KHẨU -->
            <div class="banner-slide active bg-gradient-to-br from-brand-deep via-brand-navy to-[#155E9E]" data-slide="0">
              <!-- Khoảng cách đệm lớn (px-10 sm:px-14 lg:px-20 py-8 sm:py-12) đảm bảo chữ và ảnh luôn cách xa viền, không bao giờ mất chữ -->
              <div class="w-full h-full px-10 sm:px-14 md:px-16 lg:px-20 py-8 sm:py-11 lg:py-14 flex flex-col md:flex-row items-center justify-between gap-6 lg:gap-10">
                <div class="w-full md:w-[54%] text-center md:text-left space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-bold tracking-[0.18em] text-brand-goldLight uppercase">
                    PHÚC HOÀNG THƯƠNG • ĐÀ NẴNG
                  </p>
                  <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-tight break-words">
                    CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG
                  </h1>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl mx-auto md:mx-0">
                    Gia công chuẩn kỹ thuật, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội, độ bền trên 20 năm cho nhà phố, biệt thự và khách sạn tại Đà Nẵng.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center justify-center md:justify-start gap-3">
                    <a href="#form-bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm shadow transition">
                      Nhận Báo Giá Ngay
                    </a>
                    <a href="#cua-nhom-xingfa" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                      Xem Sản Phẩm
                    </a>
                  </div>
                </div>
                <!-- Khung ảnh nằm gọn hoàn toàn bên trong Banner -->
                <div class="w-full md:w-[44%] flex justify-center">
                  <div class="w-full max-w-[380px] md:max-w-none aspect-[16/10] rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-xl bg-brand-deep">
                    <img
                      src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w1000"
                      data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                      alt="Cửa nhôm Xingfa nhập khẩu Phúc Hoàng Thương"
                      class="w-full h-full object-cover"
                      onerror="handleImgError(this, 'Cua+Nhom+Xingfa')"
                    >
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2: THI CÔNG DỰ ÁN KHÁCH SẠN & BIỆT THỰ ĐÀ NẴNG -->
            <div class="banner-slide bg-gradient-to-br from-[#0B2942] via-brand-dark to-brand-navy" data-slide="1">
              <div class="w-full h-full px-10 sm:px-14 md:px-16 lg:px-20 py-8 sm:py-11 lg:py-14 flex flex-col md:flex-row items-center justify-between gap-6 lg:gap-10">
                <div class="w-full md:w-[54%] text-center md:text-left space-y-3 sm:space-y-4">
                  <p class="text-[11px] sm:text-xs font-bold tracking-[0.18em] text-brand-goldLight uppercase">
                    THI CÔNG TRỌN GÓI • UY TÍN HÀNG ĐẦU
                  </p>
                  <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-tight break-words">
                    GIẢI PHÁP NHÔM KÍNH CHO MỌI CÔNG TRÌNH
                  </h2>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl mx-auto md:mx-0">
                    Thi công cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp chuyên nghiệp. Khảo sát tận nơi miễn phí — bảo hành dài hạn tại Đà Nẵng.
                  </p>
                  <div class="pt-1 flex flex-wrap items-center justify-center md:justify-start gap-3">
                    <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm shadow transition">
                      Xem Dự Án Đà Nẵng
                    </a>
                    <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                      Bảng Báo Giá 2026
                    </a>
                  </div>
                </div>
                <!-- Khung ảnh nằm gọn hoàn toàn bên trong Banner -->
                <div class="w-full md:w-[44%] flex justify-center">
                  <div class="w-full max-w-[380px] md:max-w-none aspect-[16/10] rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-xl bg-brand-deep">
                    <img
                      src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                      data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                      alt="Dự án thi công nhôm kính tại Đà Nẵng - Phúc Hoàng Thương"
                      class="w-full h-full object-cover"
                      onerror="handleImgError(this, 'Du+An+Da+Nang')"
                    >
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển trái / phải gọn sát mép (không đè lên chữ nhờ padding an toàn) -->
          <button type="button" onclick="prevSlide()" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition" aria-label="Banner trước">
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
          </button>
          <button type="button" onclick="nextSlide()" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition" aria-label="Banner sau">
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
          </button>

          <!-- Chấm chỉ báo vị trí 2 banner -->
          <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" onclick="goToSlide(0)" class="slider-dot w-6 h-2 rounded-full bg-brand-goldLight transition-all" aria-label="Chọn banner 1"></button>
            <button type="button" onclick="goToSlide(1)" class="slider-dot w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Chọn banner 2"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 4. DANH MỤC SẢN PHẨM NỔI BẬT (Chuẩn web mẫu ngochanwindow, chữ nhỏ gọn)    -->
    <!-- ========================================================================= -->
    <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-white">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            DANH MỤC SẢN PHẨM
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <!-- 6 danh mục chuẩn web mẫu: 2 cột trên mobile, 3 cột tablet, 6 cột desktop -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">

          <a href="#cua-nhom-xingfa" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w800" data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX" alt="Cửa nhôm Xingfa" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Cua+Nhom+Xingfa')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Cửa nhôm Xingfa</h3>
            </div>
          </a>

          <a href="#form-bao-gia" onclick="prefillQuote('Cửa nhựa lõi thép')" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&sz=w800" data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA" alt="Cửa nhựa lõi thép" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Cua+Nhua+Loi+Thep')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Cửa nhựa lõi thép</h3>
            </div>
          </a>

          <a href="#form-bao-gia" onclick="prefillQuote('Cửa kính tự động')" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&sz=w800" data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ" alt="Cửa kính tự động" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Cua+Tu+Dong')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Cửa kính tự động</h3>
            </div>
          </a>

          <a href="#form-bao-gia" onclick="prefillQuote('Cầu thang kính')" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&sz=w800" data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul" alt="Cầu thang kính" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Cau+Thang+Kinh')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Cầu thang kính</h3>
            </div>
          </a>

          <a href="#form-bao-gia" onclick="prefillQuote('Kính ốp bếp')" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w800" data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb" alt="Kính ốp bếp" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Kinh+Op+Bep')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Kính ốp bếp</h3>
            </div>
          </a>

          <a href="#form-bao-gia" onclick="prefillQuote('Phòng tắm kính')" class="group block rounded-xl overflow-hidden bg-white border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w800" data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH" alt="Phòng tắm kính" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Phong+Tam+Kinh')">
            </div>
            <div class="p-2.5 text-center">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy group-hover:text-brand-gold uppercase leading-snug">Phòng tắm kính</h3>
            </div>
          </a>

        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 5. SẢN PHẨM CỬA NHÔM XINGFA (2 cột mobile, có giá & % giảm giá góc trái)  -->
    <!-- ========================================================================= -->
    <section id="cua-nhom-xingfa" class="py-10 sm:py-12 bg-brand-slate border-y border-slate-200/80">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <!-- Bộ lọc nhỏ gọn theo kiểu cửa -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterProducts('all', this)" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition">Tất cả</button>
          <button type="button" onclick="filterProducts('mo-quay', this)" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition">Cửa đi mở quay</button>
          <button type="button" onclick="filterProducts('xep-truot', this)" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition">Cửa đi xếp trượt</button>
          <button type="button" onclick="filterProducts('cua-so', this)" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition">Cửa sổ mở hất</button>
        </div>

        <!-- Grid sản phẩm: Đúng 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
        <div id="products-grid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS để đồng bộ dữ liệu, giá, % giảm giá và modal chi tiết -->
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 6. GIỚI THIỆU CÔNG TY & THÔNG SỐ NĂNG LỰC (Bố cục Flatsome 2 cột + 4 ô)    -->
    <!-- ========================================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-white">
      <div class="pht-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">

          <!-- Cột trái: Giới thiệu Công Ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương -->
          <div class="lg:col-span-7 space-y-4">
            <div class="border-l-4 border-brand-gold pl-4">
              <p class="text-xs font-bold uppercase tracking-wider text-brand-gold">Về chúng tôi</p>
              <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase leading-snug mt-0.5">
                CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG
              </h2>
            </div>

            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
              <strong>Phúc Hoàng Thương (phuchoangthuong.com)</strong> là đơn vị chuyên thiết kế, sản xuất, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực gồm: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ</strong>, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
              Với xưởng sản xuất hiện đại tọa lạc tại <strong>110 Đặng Huy Trứ, Phường Hòa Khánh, TP Đà Nẵng</strong> cùng đội ngũ kỹ sư, thợ lành nghề nhiều năm kinh nghiệm, chúng tôi cam kết mang đến công trình đạt chuẩn kỹ thuật, thẩm mỹ sang trọng, vận hành êm ái và chi phí tối ưu nhất cho mọi khách hàng.
            </p>

            <!-- 4 chỉ số năng lực Flatsome -->
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
              <div class="p-3.5 rounded-xl bg-brand-light/70 border border-brand-navy/10 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">150+</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Dự án hoàn thành</div>
              </div>
              <div class="p-3.5 rounded-xl bg-brand-light/70 border border-brand-navy/10 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">50+</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Kỹ thuật viên</div>
              </div>
              <div class="p-3.5 rounded-xl bg-brand-light/70 border border-brand-navy/10 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">100+</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Mẫu cửa đẹp</div>
              </div>
              <div class="p-3.5 rounded-xl bg-brand-goldBg border border-brand-gold/25 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-brand-gold">100%</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-700 mt-0.5">Khách hài lòng</div>
              </div>
            </div>
          </div>

          <!-- Cột phải: Bảng cam kết dịch vụ chuẩn mẫu ngochanwindow -->
          <div class="lg:col-span-5">
            <div class="rounded-2xl border border-slate-200 bg-brand-slate p-5 sm:p-6 shadow-sm">
              <h3 class="text-base sm:text-lg font-extrabold text-brand-navy uppercase mb-4 pb-2.5 border-b border-slate-200">
                CAM KẾT DỊCH VỤ PHÚC HOÀNG THƯƠNG
              </h3>
              <ul class="divide-y divide-slate-200 text-sm">
                <li class="py-3 flex items-center justify-between gap-3">
                  <span class="font-semibold text-slate-700">Hotline tư vấn 24/7</span>
                  <a href="tel:0905479773" class="font-bold text-brand-navy hover:text-brand-gold">0905.479.773</a>
                </li>
                <li class="py-3 flex items-center justify-between gap-3">
                  <span class="font-semibold text-slate-700">Khảo sát &amp; Lắp đặt</span>
                  <span class="font-semibold text-emerald-700 text-right">Miễn phí tại Đà Nẵng</span>
                </li>
                <li class="py-3 flex items-center justify-between gap-3">
                  <span class="font-semibold text-slate-700">Chính sách ưu đãi</span>
                  <span class="font-semibold text-brand-gold text-right">Giảm đến 15% - 20%</span>
                </li>
                <li class="py-3 flex items-center justify-between gap-3">
                  <span class="font-semibold text-slate-700">Chất lượng vật tư</span>
                  <span class="font-semibold text-slate-800 text-right">Xingfa nhập khẩu 100%</span>
                </li>
                <li class="py-3 flex items-center justify-between gap-3">
                  <span class="font-semibold text-slate-700">Chế độ bảo hành</span>
                  <span class="font-semibold text-slate-800 text-right">Thanh nhôm 5 năm • PK 2 năm</span>
                </li>
              </ul>
              <div class="mt-4">
                <a href="#form-bao-gia" class="block w-full text-center py-2.5 px-4 rounded-xl bg-brand-navy hover:bg-brand-dark text-white font-semibold text-sm transition">
                  Đăng Ký Khảo Sát Miễn Phí
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 7. BẢNG BÁO GIÁ THAM KHẢO (Dễ chỉnh sửa trực tiếp trong UX Builder)        -->
    <!-- ========================================================================= -->
    <section id="bao-gia" class="py-10 sm:py-12 bg-brand-slate border-y border-slate-200/80">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            BẢNG BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-navy text-white">
                  <th class="py-3 px-3 sm:px-5 font-semibold w-12 text-center">STT</th>
                  <th class="py-3 px-3 sm:px-5 font-semibold">Hạng Mục Cửa Nhôm Xingfa / Kính Cường Lực</th>
                  <th class="py-3 px-3 sm:px-5 font-semibold hidden md:table-cell">Quy Cách &amp; Độ Dày</th>
                  <th class="py-3 px-3 sm:px-5 font-semibold text-right whitespace-nowrap">Đơn Giá (VNĐ/m²)</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-200">
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">01</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa đi mở quay 1 cánh nhôm Xingfa hệ 55</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Nhôm dày 2.0mm, kính cường lực 8mm</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-red-600 whitespace-nowrap">1.850.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">02</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa đi mở quay 2 cánh nhôm Xingfa hệ 55</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Nhôm dày 2.0mm, phụ kiện Kinlong chính hãng</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-red-600 whitespace-nowrap">1.890.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">03</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa đi mở quay 3 cánh / 4 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Nhôm dày 2.0mm, gioăng EPDM kín khít</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-red-600 whitespace-nowrap">1.950.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">04</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa đi mở xếp trượt nhôm Xingfa hệ 63</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Nhôm dày 1.8 - 3.0mm, ray trượt êm ái</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-red-600 whitespace-nowrap">2.100.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">05</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa sổ mở hất 2 cánh / mở quay nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Nhôm hệ 55 dày 1.4mm, chống thấm nước</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-red-600 whitespace-nowrap">1.750.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-light/40 transition">
                  <td class="py-3 px-3 sm:px-5 text-center font-medium text-slate-500">06</td>
                  <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa kính cường lực, Phòng tắm kính, Cầu thang kính</td>
                  <td class="py-3 px-3 sm:px-5 text-slate-600 hidden md:table-cell">Kính cường lực 10mm - 12mm, phụ kiện Inox 304</td>
                  <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-navy whitespace-nowrap">Liên hệ báo giá</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="px-4 py-3 bg-brand-light/50 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
            <span>* Đơn giá mang tính tham khảo và sẽ ưu đãi tốt hơn theo khối lượng thực tế công trình.</span>
            <a href="#form-bao-gia" class="font-bold text-brand-navy hover:text-brand-gold underline">Nhận báo giá chi tiết theo bản vẽ &rarr;</a>
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 8. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 dự án thực tế từ Google Drive)       -->
    <!-- ========================================================================= -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-white">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
          <!-- Dự án 1 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1000" data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ" alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Khach+San+Ruby+Light')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                DỰ ÁN KHÁCH SẠN RUBY LIGHT
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Thi công hạng mục cửa nhôm Xingfa &amp; vách kính mặt dựng tại Đà Nẵng.</p>
            </div>
          </article>

          <!-- Dự án 2 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000" data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ" alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'My+Son+Heritage+Resort')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Lắp đặt trọn gói hệ cửa nhôm kính cao cấp và phòng tắm kính cường lực.</p>
            </div>
          </article>

          <!-- Dự án 3 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy&sz=w1000" data-drive-id="1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy" alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Khach+San+Goden+Line')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Cung cấp và lắp đặt hệ cửa nhôm Xingfa cách âm chuẩn khách sạn ven biển.</p>
            </div>
          </article>

          <!-- Dự án 4 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64&sz=w1000" data-drive-id="1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64" alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Khach+San+Jolia')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Thi công cửa kính tự động sảnh chính, lan can kính và cửa sổ mở hất.</p>
            </div>
          </article>

          <!-- Dự án 5 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt&sz=w1000" data-drive-id="1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt" alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Khach+San+Soho')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Hoàn thiện hệ cửa nhôm kính kiến trúc hiện đại tại TP Đà Nẵng.</p>
            </div>
          </article>

          <!-- Dự án 6 -->
          <article class="group rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&sz=w1000" data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc" alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" onerror="handleImgError(this, 'Raon+Da+Nang+Beach+Hotel')">
            </div>
            <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">Thi công đồng bộ cửa nhôm Xingfa chịu gió bão ven biển Mỹ Khê, Đà Nẵng.</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRỰC TIẾP TRANG CHỦ                      -->
    <!-- ========================================================================= -->
    <section id="form-bao-gia" class="py-10 sm:py-14 bg-gradient-to-br from-brand-deep via-brand-navy to-brand-dark text-white">
      <div class="pht-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">

          <!-- Thông tin kêu gọi hành động -->
          <div class="lg:col-span-5 space-y-4">
            <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight">Tư vấn &amp; Dự toán miễn phí</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
              ĐĂNG KÝ NHẬN BÁO GIÁ &amp; KHẢO SÁT TẬN NƠI
            </h2>
            <p class="text-sm text-slate-200 leading-relaxed">
              Quý khách vui lòng để lại thông tin hạng mục cần thi công. Kỹ thuật viên của <strong>Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương</strong> sẽ liên hệ tư vấn mẫu cửa, đo đạc thực tế và gửi bảng báo giá chi tiết trong vòng 15 phút.
            </p>
            <div class="space-y-2.5 pt-2 text-sm text-slate-100">
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-gold/25 text-brand-goldLight flex items-center justify-center shrink-0">✓</span>
                <span>Báo giá minh bạch, trực tiếp từ xưởng sản xuất không qua trung gian</span>
              </div>
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-gold/25 text-brand-goldLight flex items-center justify-center shrink-0">✓</span>
                <span>Cung cấp đầy đủ mẫu góc nhôm Xingfa &amp; phụ kiện kiểm tra tận nơi</span>
              </div>
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-gold/25 text-brand-goldLight flex items-center justify-center shrink-0">✓</span>
                <span>Hotline hỗ trợ nhanh: <a href="tel:0905479773" class="font-bold text-brand-goldLight underline">0905.479.773</a></span>
              </div>
            </div>
          </div>

          <!-- Form yêu cầu & báo giá -->
          <div class="lg:col-span-7">
            <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="q-name" class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Họ và tên *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15">
                </div>
                <div>
                  <label for="q-phone" class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Số điện thoại / Zalo *</label>
                  <input id="q-phone" type="tel" required placeholder="Ví dụ: 0905 479 773" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="q-category" class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Hạng mục cần báo giá</label>
                  <select id="q-category" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15">
                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang kính</option>
                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                    <option value="Thi công trọn gói công trình">Thi công trọn gói công trình</option>
                  </select>
                </div>
                <div>
                  <label for="q-address" class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Địa chỉ công trình</label>
                  <input id="q-address" type="text" placeholder="Quận/Huyện, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15">
                </div>
              </div>

              <div>
                <label for="q-note" class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Yêu cầu chi tiết (kích thước, số bộ cửa...)</label>
                <textarea id="q-note" rows="3" placeholder="Ví dụ: Cần báo giá 1 bộ cửa đi 4 cánh nhôm Xingfa màu xám ghi, 2 cửa sổ mở hất..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15"></textarea>
              </div>

              <button type="submit" class="w-full py-3 px-6 rounded-xl bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-sm uppercase tracking-wide shadow-md transition">
                Gửi Yêu Cầu Báo Giá Miễn Phí
              </button>

              <!-- Thông báo gửi thành công (không dùng alert) -->
              <div id="quote-feedback" class="hidden rounded-xl bg-emerald-50 border border-emerald-200 p-3.5 text-sm text-emerald-800 font-medium"></div>
            </form>
          </div>

        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 10. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Tư vấn nhôm kính)           -->
    <!-- ========================================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <!-- Danh mục bài viết nhỏ gọn -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
          <button type="button" onclick="filterArticles('all', this)" class="art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition">Tất cả bài viết</button>
          <button type="button" onclick="filterArticles('tu-van', this)" class="art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-slate text-slate-700 border border-slate-200 hover:border-brand-navy transition">Tư vấn cửa Xingfa</button>
          <button type="button" onclick="filterArticles('kinh-nghiem', this)" class="art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-slate text-slate-700 border border-slate-200 hover:border-brand-navy transition">Kinh nghiệm chọn cửa</button>
          <button type="button" onclick="filterArticles('bao-gia-tt', this)" class="art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-slate text-slate-700 border border-slate-200 hover:border-brand-navy transition">Báo giá &amp; Thi công</button>
        </div>

        <!-- Lưới bài viết trang chủ -->
        <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Render từ JS -->
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 11. ĐỐI TÁC CỦA CHÚNG TÔI (6 ảnh đối tác từ Google Drive)                  -->
    <!-- ========================================================================= -->
    <section class="py-10 bg-brand-slate border-y border-slate-200/80">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            ĐỐI TÁC CỦA CHÚNG TÔI
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <div class="grid grid-cols-3 sm:grid-cols-6 gap-3 sm:gap-4">
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w500" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác cung cấp vật tư 1" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+1')">
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w500" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác cung cấp vật tư 2" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+2')">
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w500" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác cung cấp vật tư 3" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+3')">
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w500" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác cung cấp vật tư 4" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+4')">
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w500" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác cung cấp vật tư 5" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+5')">
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-xs">
            <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w500" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác cung cấp vật tư 6" class="max-h-full max-w-full object-contain" onerror="handleImgError(this, 'Doi+Tac+6')">
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================= -->
    <!-- 12. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK TRỰC TIẾP NGOÀI TRANG CHỦ         -->
    <!-- ========================================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white">
      <div class="pht-container">
        <div class="flatsome-title-wrap">
          <span class="flatsome-title-line"></span>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase tracking-wide text-center">
            BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE FACEBOOK
          </h2>
          <span class="flatsome-title-line right"></span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">

          <!-- Google Map ngoài trang chủ: 110 Đặng Huy Trứ, Phường Hòa Khánh, TP Đà Nẵng -->
          <div class="lg:col-span-7 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
            <div class="px-4 py-3 bg-brand-navy text-white flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                <svg class="w-4 h-4 text-brand-goldLight shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                <span>110 Đặng Huy Trứ, Phường Hòa Khánh, TP Đà Nẵng</span>
              </div>
              <a href="https://maps.google.com/?q=110+Đặng+Huy+Trứ,+Hòa+Khánh,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-goldLight hover:underline">
                Mở trên Google Maps &rarr;
              </a>
            </div>
            <div class="w-full flex-1 min-h-[280px] sm:min-h-[340px] bg-slate-100">
              <iframe
                title="Bản đồ Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương - 110 Đặng Huy Trứ, Hòa Khánh, Đà Nẵng"
                src="https://maps.google.com/maps?q=110+%C4%90%E1%BA%B7ng+Huy+Tr%E1%BB%A9,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
                allowfullscreen>
              </iframe>
            </div>
          </div>

          <!-- Fanpage Facebook ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
                <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
              </div>
              <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded-full">Đang hoạt động</span>
            </div>

            <!-- Khung Fanpage Card trực quan (thay link href bằng link Fanpage thực tế khi triển khai) -->
            <div class="flex-1 flex flex-col justify-between p-4 sm:p-5 bg-slate-50">
              <div>
                <div class="relative rounded-xl overflow-hidden bg-gradient-to-r from-brand-deep to-brand-navy p-4 text-white">
                  <div class="flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-white p-1.5 shrink-0 shadow">
                      <svg class="w-full h-full" viewBox="0 0 64 64" fill="none">
                        <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F4C81"/>
                        <rect x="6" y="6" width="52" height="52" rx="9" stroke="#C88A1E" stroke-width="2.5"/>
                        <path d="M14 27L32 14L50 27" stroke="#E5A93B" stroke-width="3" stroke-linecap="round"/>
                        <rect x="18" y="29" width="12" height="19" rx="1.5" fill="#FFFFFF"/>
                        <rect x="34" y="29" width="12" height="19" rx="1.5" fill="#E5A93B"/>
                      </svg>
                    </div>
                    <div class="min-w-0">
                      <h3 class="font-bold text-sm sm:text-[15px] leading-tight break-words">Nhôm Kính Phúc Hoàng Thương - Đà Nẵng</h3>
                      <p class="text-[11px] text-slate-200 mt-0.5">Công ty Xây dựng &amp; Cửa nhôm Xingfa • 4.8K người theo dõi</p>
                    </div>
                  </div>
                  <div class="mt-3.5 flex items-center gap-2">
                    <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-600 text-white text-xs font-semibold transition">
                      <span>Thích Trang</span>
                    </a>
                    <a href="https://m.me/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-white text-brand-navy hover:bg-slate-100 text-xs font-semibold transition">
                      <span>Nhắn Tin Tư Vấn</span>
                    </a>
                  </div>
                </div>

                <!-- Bài viết mới nhất trên Fanpage -->
                <div class="mt-4 bg-white rounded-xl border border-slate-200 p-3.5 space-y-2.5">
                  <div class="flex items-center justify-between text-xs text-slate-500">
                    <span class="font-bold text-slate-800">Nhôm Kính Phúc Hoàng Thương</span>
                    <span>Cập nhật mới</span>
                  </div>
                  <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
                    Hoàn thiện lắp đặt trọn bộ Cửa đi mở quay 4 cánh &amp; Cửa xếp trượt nhôm Xingfa nhập khẩu tem đỏ tại Hòa Khánh, Đà Nẵng. Miễn phí khảo sát, bảo hành chính hãng! Hotline: <strong>0905.479.773</strong>.
                  </p>
                  <div class="grid grid-cols-2 gap-2">
                    <img src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w500" data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-" alt="Công trình cửa nhôm Xingfa 4 cánh" class="w-full h-24 object-cover rounded-lg" onerror="handleImgError(this, 'Xingfa+4+Canh')">
                    <img src="https://drive.google.com/thumbnail?id=1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ&sz=w500" data-drive-id="1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ" alt="Công trình cửa xếp trượt Xingfa" class="w-full h-24 object-cover rounded-lg" onerror="handleImgError(this, 'Cua+Xep+Truot')">
                  </div>
                </div>
              </div>

              <div class="mt-3 pt-2 border-t border-slate-200 text-center">
                <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-[#1877F2] hover:underline">
                  Xem thêm hình ảnh thi công thực tế trên Fanpage &rarr;
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- ========================================================================= -->
  <!-- 13. FOOTER FLATSOME 4 CỘT (Có khoảng đệm dưới cho thanh liên hệ Mobile)    -->
  <!-- ========================================================================= -->
  <footer class="bg-brand-deep text-slate-300 pt-12 pb-20 sm:pb-8 border-t-4 border-brand-gold">
    <div class="pht-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none">
              <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F4C81"/>
              <rect x="6" y="6" width="52" height="52" rx="9" stroke="#C88A1E" stroke-width="2.5"/>
              <path d="M14 27L32 14L50 27" stroke="#E5A93B" stroke-width="3" stroke-linecap="round"/>
              <rect x="18" y="29" width="12" height="19" rx="1.5" fill="#FFFFFF"/>
              <rect x="34" y="29" width="12" height="19" rx="1.5" fill="#E5A93B"/>
            </svg>
            <div class="leading-tight">
              <div class="text-sm font-extrabold text-white">PHÚC HOÀNG THƯƠNG</div>
              <div class="text-[10px] font-semibold text-brand-goldLight uppercase tracking-wider">phuchoangthuong.com</div>
            </div>
          </div>
          <p class="text-xs font-bold text-white uppercase leading-relaxed">
            CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG
          </p>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><strong class="text-white">Địa chỉ:</strong> 110 Đặng Huy Trứ, Phường Hòa Khánh, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0905479773" class="text-brand-goldLight font-bold hover:underline">0905.479.773</a></li>
            <li><strong class="text-white">Website:</strong> phuchoangthuong.com</li>
            <li><strong class="text-white">Mã số thuế:</strong> 0402181444</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5 pb-2 border-b border-brand-gold/50 inline-block">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('1-canh')" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa 1 cánh</a></li>
            <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('2-canh')" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa 2 cánh</a></li>
            <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('3-canh')" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa 3 cánh</a></li>
            <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('4-canh')" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa 4 cánh</a></li>
            <li><a href="#cua-nhom-xingfa" onclick="selectProductCategory('5-canh')" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa 5 cánh</a></li>
            <li><a href="#cua-nhom-xingfa" class="hover:text-brand-goldLight transition">Cửa đi xếp trượt Xingfa</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5 pb-2 border-b border-brand-gold/50 inline-block">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#cua-nhom-xingfa" class="hover:text-brand-goldLight transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-goldLight transition">Cửa kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-goldLight transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-goldLight transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-goldLight transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-brand-goldLight transition">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5 pb-2 border-b border-brand-gold/50 inline-block">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs sm:text-[13px]">
            <li><a href="#gioi-thieu" class="hover:text-brand-goldLight transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-brand-goldLight transition">Công trình tiêu biểu Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-goldLight transition">Bảng báo giá cửa nhôm kính</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-goldLight transition">Tin tức &amp; Tư vấn kỹ thuật</a></li>
            <li><a href="#form-bao-gia" class="hover:text-brand-goldLight transition">Đăng ký khảo sát miễn phí</a></li>
            <li><a href="#lien-he" class="hover:text-brand-goldLight transition">Bản đồ &amp; Thông tin liên hệ</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <p>Copyright &copy; 2026 CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG. All rights reserved.</p>
        <p>Website: <span class="text-brand-goldLight font-medium">phuchoangthuong.com</span></p>
      </div>
    </div>
  </footer>

  <!-- ========================================================================= -->
  <!-- 14. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE - PC & MOBILE)       -->
  <!-- ========================================================================= -->

  <!-- Phiên bản Máy tính & Tablet: Cụm nút nổi dọc bên phải dưới -->
  <div class="hidden sm:flex fixed right-4 bottom-5 z-50 flex-col items-end gap-2.5">
    <!-- Facebook -->
    <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all hover:scale-105" aria-label="Facebook Phúc Hoàng Thương">
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Zalo -->
    <a href="https://zalo.me/0905479773" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all hover:scale-105" aria-label="Chat Zalo 0905.479.773">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Hotline -->
    <a href="tel:0905479773" class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-xl transition-all hover:scale-105" aria-label="Gọi Hotline 0905.479.773">
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.3" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="text-xs font-extrabold whitespace-nowrap">0905.479.773</span>
    </a>
  </div>

  <!-- Phiên bản Điện thoại: Thanh liên hệ 3 nút nổi bật cố định dưới đáy, không tràn viền -->
  <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(0,0,0,0.08)] grid grid-cols-3 gap-1.5 p-2">
    <a href="tel:0905479773" class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-red-600 text-white font-bold text-xs shadow-sm active:scale-95 transition">
      <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.3" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span>Hotline</span>
    </a>
    <a href="https://zalo.me/0905479773" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-[#0068FF] text-white font-bold text-xs shadow-sm active:scale-95 transition">
      <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-extrabold text-[8px] flex items-center justify-center shrink-0">Zalo</span>
      <span>Chat Zalo</span>
    </a>
    <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-xl bg-[#1877F2] text-white font-bold text-xs shadow-sm active:scale-95 transition">
      <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
      <span>Facebook</span>
    </a>
  </div>

  <!-- ========================================================================= -->
  <!-- 15. MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT                                -->
  <!-- ========================================================================= -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/60 p-4" onclick="closeModalOnOverlay(event)">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[88vh] overflow-y-auto shadow-2xl relative">
      <button type="button" onclick="closeDetailModal()" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-brand-navy hover:text-white text-slate-700 flex items-center justify-center transition" aria-label="Đóng hộp thoại">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
      <div id="detail-modal-body" class="p-5 sm:p-6"></div>
    </div>
  </div>

  <!-- ========================================================================= -->
  <!-- 16. JAVASCRIPT: DỮ LIỆU SẢN PHẨM, BÀI VIẾT, SLIDER, XỬ LÝ ẢNH DRIVE      -->
  <!-- ========================================================================= -->
  <script>
    /**
     * Xử lý fallback nhiều tầng cho ảnh Google Drive để đảm bảo hiển thị ổn định nhất:
     * 1) drive.google.com/thumbnail?id=...
     * 2) lh3.googleusercontent.com/d/...
     * 3) placehold.co (phòng trường hợp tệp chưa bật chia sẻ công khai)
     */
    function handleImgError(imgEl, label) {
      const stage = parseInt(imgEl.getAttribute('data-err-stage') || '0', 10);
      const driveId = imgEl.getAttribute('data-drive-id');
      if (stage === 0 && driveId) {
        imgEl.setAttribute('data-err-stage', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
      } else if (stage <= 1) {
        imgEl.setAttribute('data-err-stage', '2');
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/800x600/0F4C81/FFFFFF?text=' + (label || 'Phuc+Hoang+Thuong');
      }
    }

    /* ==================== DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA ==================== */
    const productsData = [
      {
        id: 'p1',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: 'mo-quay',
        wingKey: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.200.000 ₫',
        salePrice: '1.850.000 ₫',
        discount: '-16%',
        specs: 'Thanh nhôm Xingfa hệ 55 nhập khẩu dày 2.0mm, kính cường lực 8mm Hải Long/Việt Nhật, phụ kiện Kinlong đồng bộ, gioăng kép EPDM kín khít.',
        usage: 'Phù hợp cửa thông phòng, cửa ban công, cửa nhà vệ sinh, cửa sau nhà phố.'
      },
      {
        id: 'p2',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: 'mo-quay',
        wingKey: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.250.000 ₫',
        salePrice: '1.890.000 ₫',
        discount: '-16%',
        specs: 'Nhôm Xingfa tem đỏ Quảng Đông hệ 55 dày 2.0mm, khóa đa điểm chống trộm, bản lề 3D chịu lực cao, sơn tĩnh điện ngoài trời chống ăn mòn muối biển.',
        usage: 'Phù hợp cửa chính nhà phố vừa, cửa ra sân vườn, cửa ban công rộng.'
      },
      {
        id: 'p3',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: 'mo-quay',
        wingKey: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.300.000 ₫',
        salePrice: '1.950.000 ₫',
        discount: '-15%',
        specs: 'Nhôm Xingfa nhập khẩu hệ 55 dày 2.0mm, ép góc CNC ke góc 4mm chắc chắn, keo Dowcorning chống thấm nước tuyệt đối.',
        usage: 'Tối ưu không gian mở cho mặt tiền nhà phố, quán café, văn phòng.'
      },
      {
        id: 'p4',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: 'mo-quay',
        wingKey: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.350.000 ₫',
        salePrice: '1.980.000 ₫',
        discount: '-16%',
        specs: 'Cửa đi mặt tiền 4 cánh nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm - 10mm, bộ phụ kiện Kinlong chính hãng bảo hành 24 tháng.',
        usage: 'Lựa chọn hàng đầu cho cửa mặt tiền nhà phố, biệt thự, showroom sang trọng.'
      },
      {
        id: 'p5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xep-truot',
        wingKey: '5-canh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.500.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-16%',
        specs: 'Hệ nhôm Xingfa 63 chuyên dụng cho cửa xếp trượt 4 - 5 - 6 cánh, bánh xe treo trên và dẫn hướng dưới vận hành nhẹ nhàng, mở rộng đến 95% diện tích.',
        usage: 'Phù hợp mặt tiền rộng, biệt thự sân vườn, resort, hồ bơi, nhà hàng.'
      },
      {
        id: 'p6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'cua-so',
        wingKey: '2-canh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.100.000 ₫',
        salePrice: '1.750.000 ₫',
        discount: '-17%',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh chống gió định vị góc mở tối đa 45 độ, chống hắt mưa hiệu quả ngay cả khi trời mưa lớn tại Đà Nẵng.',
        usage: 'Phù hợp phòng ngủ, phòng làm việc, khách sạn cao tầng, chung cư.'
      }
    ];

    /* ==================== DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ ==================== */
    const articlesData = [
      {
        id: 'a1',
        category: 'tu-van',
        catLabel: 'Tư vấn cửa Xingfa',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
        excerpt: 'Phân tích khả năng chống gió bão, chống ăn mòn muối biển và độ kín nước của cửa nhôm Xingfa nhập khẩu tem đỏ.',
        content: 'Đà Nẵng có khí hậu nhiệt đới gió mùa ven biển, độ ẩm cao và thường xuyên chịu ảnh hưởng của gió bão. Cửa nhôm Xingfa nhập khẩu chính hãng với bề mặt sơn tĩnh điện cao cấp ngoài trời, cấu trúc khoang rỗng kết hợp gân gia cường và hệ gioăng EPDM giúp chống oxy hóa, chịu áp lực gió lên đến 1600 Pascal và ngăn nước mưa tràn vào nhà hiệu quả.'
      },
      {
        id: 'a2',
        category: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm chọn cửa',
        date: '12/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu chính hãng và hàng nhái',
        excerpt: 'Hướng dẫn kiểm tra mã QR tem đỏ, độ dày thanh profile 1.4mm - 2.0mm và màu ánh kim đặc trưng bên trong lõi nhôm.',
        content: 'Để tránh mua phải nhôm mỏng kém chất lượng, khách hàng cần kiểm tra 4 yếu tố: (1) Tem đỏ Quảng Đông in rõ nét, quét mã QR ra đúng thông tin nhà sản xuất; (2) Mặt cắt bên trong thanh nhôm có lớp mạ crom ánh kim sáng; (3) Độ dày đạt chuẩn 1.4mm cho cửa sổ và 2.0mm cho cửa đi; (4) Công nghệ ép góc thủy lực khít đều, không hở khe.'
      },
      {
        id: 'a3',
        category: 'bao-gia-tt',
        catLabel: 'Báo giá & Thi công',
        date: '05/11/2026',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        title: 'Báo giá cửa nhôm Xingfa trọn gói tại Đà Nẵng mới nhất 2026',
        excerpt: 'Cập nhật chi tiết cách tính diện tích m² cửa nhôm kính, đơn giá phụ kiện Kinlong và ưu đãi thi công trực tiếp tại xưởng.',
        content: 'Giá cửa nhôm Xingfa trọn gói được tính theo công thức: Tổng chi phí = (Diện tích cửa m² x Đơn giá nhôm kính) + Bộ phụ kiện tương ứng. Khi đặt gia công trực tiếp tại xưởng Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương (110 Đặng Huy Trứ, Hòa Khánh, Đà Nẵng), khách hàng được miễn phí khảo sát, vận chuyển và lắp đặt hoàn thiện.'
      },
      {
        id: 'a4',
        category: 'tu-van',
        catLabel: 'Tư vấn cửa Xingfa',
        date: '28/10/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        title: 'Kinh nghiệm thi công phòng tắm kính và cầu thang kính bền đẹp',
        excerpt: 'Lựa chọn độ dày kính cường lực 10mm - 12mm và bộ phụ kiện Inox 304 chống gỉ giúp không gian luôn sang trọng.',
        content: 'Phòng tắm kính và cầu thang kính giúp mở rộng tầm nhìn, tăng ánh sáng tự nhiên cho nhà phố hiện đại. Phúc Hoàng Thương khuyên dùng kính cường lực tối thiểu 10mm cho cabin tắm và 10mm - 12mm cho cầu thang, kết hợp phụ kiện bản lề, kẹp kính chuẩn Inox 304 và gioăng chắn nước chuyên dụng để vận hành bền bỉ theo thời gian.'
      }
    ];

    /* ==================== RENDER SẢN PHẨM (2 CỘT MOBILE, CÓ % GIẢM GIÁ GÓC TRÊN TRÁI) ==================== */
    function renderProducts(filter = 'all') {
      const grid = document.getElementById('products-grid');
      if (!grid) return;

      const list = filter === 'all'
        ? productsData
        : productsData.filter(p => p.category === filter || p.wingKey === filter);

      const finalList = list.length > 0 ? list : productsData;

      grid.innerHTML = finalList.map(item => `
        <div class="group bg-white rounded-xl border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition overflow-hidden flex flex-col">
          <!-- Khung ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal('${item.id}')">
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-red-600 text-white text-[11px] sm:text-xs font-extrabold shadow">
              ${item.discount}
            </span>
            <img
              src="https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800"
              data-drive-id="${item.driveId}"
              alt="${item.name}"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleImgError(this, 'Cua+Nhom+Xingfa')"
            >
          </div>

          <!-- Nội dung sản phẩm: Tên hiển thị đầy đủ, không cắt chữ, không tràn viền -->
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2.5">
            <div>
              <h3 onclick="openProductModal('${item.id}')" class="cursor-pointer text-[12.5px] sm:text-[14.5px] font-bold text-slate-800 group-hover:text-brand-navy leading-snug break-words">
                ${item.name}
              </h3>
              <!-- Giá gốc gạch ngang & Giá ưu đãi -->
              <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-[15px] font-extrabold text-red-600">${item.salePrice}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${item.oldPrice}</span>
              </div>
              <div class="text-[10.5px] sm:text-[11px] text-slate-500 mt-0.5">Đơn vị tính: VNĐ / m²</div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 pt-1">
              <button type="button" onclick="openProductModal('${item.id}')" class="w-full py-1.5 sm:py-2 px-2 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-light font-semibold text-[11px] sm:text-xs transition">
                Xem chi tiết
              </button>
              <a href="#form-bao-gia" onclick="prefillQuote('${item.name}')" class="w-full text-center py-1.5 sm:py-2 px-2 rounded-lg bg-brand-navy hover:bg-brand-gold text-white font-semibold text-[11px] sm:text-xs transition">
                Báo giá ngay
              </a>
            </div>
          </div>
        </div>
      `).join('');
    }

    function filterProducts(category, btnEl) {
      renderProducts(category);
      document.querySelectorAll('.prod-filter-btn').forEach(btn => {
        btn.className = 'prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition';
      });
      if (btnEl) {
        btnEl.className = 'prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition';
      }
    }

    function selectProductCategory(wingKey) {
      renderProducts(wingKey);
      const sec = document.getElementById('cua-nhom-xingfa');
      if (sec) sec.scrollIntoView({ behavior: 'smooth' });
    }

    /* ==================== RENDER BÀI VIẾT TRANG CHỦ ==================== */
    function renderArticles(category = 'all') {
      const grid = document.getElementById('articles-grid');
      if (!grid) return;

      const list = category === 'all'
        ? articlesData
        : articlesData.filter(a => a.category === category);

      grid.innerHTML = list.map(art => `
        <article class="group bg-white rounded-xl border border-slate-200 hover:border-brand-navy shadow-sm hover:shadow-md transition overflow-hidden flex flex-col">
          <div class="aspect-[16/10] bg-slate-100 overflow-hidden cursor-pointer" onclick="openArticleModal('${art.id}')">
            <img
              src="https://drive.google.com/thumbnail?id=${art.driveId}&sz=w800"
              data-drive-id="${art.driveId}"
              alt="${art.title}"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleImgError(this, 'Tin+Tuc+Nhom+Kinh')"
            >
          </div>
          <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
                <span class="font-semibold text-brand-gold">${art.catLabel}</span>
                <span>${art.date}</span>
              </div>
              <h3 onclick="openArticleModal('${art.id}')" class="cursor-pointer text-sm font-bold text-brand-navy group-hover:text-brand-gold leading-snug break-words">
                ${art.title}
              </h3>
              <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                ${art.excerpt}
              </p>
            </div>
            <div class="mt-3 pt-2.5 border-t border-slate-100">
              <button type="button" onclick="openArticleModal('${art.id}')" class="text-xs font-bold text-brand-navy hover:text-brand-gold transition">
                Đọc chi tiết &rarr;
              </button>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterArticles(category, btnEl) {
      renderArticles(category);
      document.querySelectorAll('.art-filter-btn').forEach(btn => {
        btn.className = 'art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-slate text-slate-700 border border-slate-200 hover:border-brand-navy transition';
      });
      if (btnEl) {
        btnEl.className = 'art-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition';
      }
    }

    /* ==================== MODAL CHI TIẾT SẢN PHẨM & BÀI VIẾT ==================== */
    function openProductModal(productId) {
      const item = productsData.find(p => p.id === productId);
      if (!item) return;
      const body = document.getElementById('detail-modal-body');
      body.innerHTML = `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden bg-slate-100 border border-slate-200 aspect-[4/3]">
            <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-red-600 text-white text-xs font-extrabold">${item.discount}</span>
            <img src="https://drive.google.com/thumbnail?id=${item.driveId}&sz=w1000" data-drive-id="${item.driveId}" alt="${item.name}" class="w-full h-full object-cover" onerror="handleImgError(this, 'San+Pham')">
          </div>
          <div class="space-y-3">
            <h3 class="text-lg font-extrabold text-brand-navy leading-snug">${item.name}</h3>
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-red-600">${item.salePrice}</span>
              <span class="text-sm text-slate-400 line-through">${item.oldPrice}</span>
              <span class="text-xs text-slate-500">/ m²</span>
            </div>
            <div class="text-xs sm:text-sm text-slate-600 space-y-2 leading-relaxed">
              <p><strong class="text-slate-800">Thông số kỹ thuật:</strong> ${item.specs}</p>
              <p><strong class="text-slate-800">Ứng dụng:</strong> ${item.usage}</p>
              <p><strong class="text-slate-800">Đơn vị thi công:</strong> Công ty TNHH Thương Mại và Sản Xuất Phúc Hoàng Thương (Đà Nẵng).</p>
            </div>
            <div class="pt-2 flex flex-wrap gap-2.5">
              <a href="tel:0905479773" class="flex-1 text-center py-2.5 px-4 rounded-xl bg-red-600 hover:bg-red-700 text-white font-bold text-xs sm:text-sm transition">
                Gọi 0905.479.773
              </a>
              <button type="button" onclick="closeDetailModal(); prefillQuote('${item.name}'); scrollToSection('form-bao-gia');" class="flex-1 py-2.5 px-4 rounded-xl bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs sm:text-sm transition">
                Nhận báo giá
              </button>
            </div>
          </div>
        </div>
      `;
      const modal = document.getElementById('detail-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function openArticleModal(articleId) {
      const art = articlesData.find(a => a.id === articleId);
      if (!art) return;
      const body = document.getElementById('detail-modal-body');
      body.innerHTML = `
        <div class="space-y-4">
          <div class="text-xs font-semibold text-brand-gold">${art.catLabel} • ${art.date}</div>
          <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy leading-snug">${art.title}</h3>
          <div class="rounded-xl overflow-hidden aspect-[16/9] bg-slate-100">
            <img src="https://drive.google.com/thumbnail?id=${art.driveId}&sz=w1000" data-drive-id="${art.driveId}" alt="${art.title}" class="w-full h-full object-cover" onerror="handleImgError(this, 'Tin+Tuc')">
          </div>
          <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-4 rounded-xl bg-brand-light border border-brand-navy/15 text-xs sm:text-sm text-brand-navy">
            <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ SẢN XUẤT PHÚC HOÀNG THƯƠNG</strong><br>
            Địa chỉ: 110 Đặng Huy Trứ, Phường Hòa Khánh, TP Đà Nẵng • Hotline: <a href="tel:0905479773" class="font-bold underline">0905.479.773</a>
          </div>
        </div>
      `;
      const modal = document.getElementById('detail-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function closeModalOnOverlay(event) {
      if (event.target.id === 'detail-modal') {
        closeDetailModal();
      }
    }

    /* ==================== 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT MOBILE ==================== */
    let currentSlide = 0;
    let slideInterval = null;

    function showSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.slider-dot');
      if (!slides.length) return;

      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        if (i === currentSlide) {
          slide.classList.add('active');
        } else {
          slide.classList.remove('active');
        }
      });

      dots.forEach((dot, i) => {
        if (i === currentSlide) {
          dot.classList.add('w-6', 'bg-brand-goldLight');
          dot.classList.remove('w-2', 'bg-white/50');
        } else {
          dot.classList.remove('w-6', 'bg-brand-goldLight');
          dot.classList.add('w-2', 'bg-white/50');
        }
      });
    }

    function nextSlide() {
      showSlide(currentSlide + 1);
      resetSlideTimer();
    }

    function prevSlide() {
      showSlide(currentSlide - 1);
      resetSlideTimer();
    }

    function goToSlide(idx) {
      showSlide(idx);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => showSlide(currentSlide + 1), 5000);
    }

    /* Hỗ trợ thao tác vuốt (swipe) chuyển banner trên điện thoại */
    function initBannerSwipe() {
      const slider = document.getElementById('hero-slider');
      if (!slider) return;
      let startX = 0;
      slider.addEventListener('touchstart', (e) => {
        startX = e.changedTouches[0].screenX;
      }, { passive: true });
      slider.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - startX;
        if (Math.abs(diff) > 45) {
          if (diff < 0) nextSlide();
          else prevSlide();
        }
      }, { passive: true });
    }

    /* ==================== MENU MOBILE & FORM YÊU CẦU BÁO GIÁ ==================== */
    function toggleMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const btn = document.getElementById('mobile-menu-btn');
      const iconOpen = document.getElementById('icon-menu-open');
      const iconClose = document.getElementById('icon-menu-close');
      const isHidden = menu.classList.contains('hidden');
      menu.classList.toggle('hidden');
      iconOpen.classList.toggle('hidden', isHidden);
      iconClose.classList.toggle('hidden', !isHidden);
      btn.setAttribute('aria-expanded', isHidden ? 'true' : 'false');
    }

    function closeMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      const btn = document.getElementById('mobile-menu-btn');
      const iconOpen = document.getElementById('icon-menu-open');
      const iconClose = document.getElementById('icon-menu-close');
      if (!menu.classList.contains('hidden')) {
        menu.classList.add('hidden');
        iconOpen.classList.remove('hidden');
        iconClose.classList.add('hidden');
        btn.setAttribute('aria-expanded', 'false');
      }
    }

    function toggleSubmenu(id) {
      const el = document.getElementById(id);
      const arrow = document.getElementById('arrow-' + id);
      if (el) el.classList.toggle('hidden');
      if (arrow) arrow.classList.toggle('rotate-180');
    }

    function scrollToSection(id) {
      const el = document.getElementById(id);
      if (el) el.scrollIntoView({ behavior: 'smooth' });
    }

    function prefillQuote(itemName) {
      const noteEl = document.getElementById('q-note');
      const catEl = document.getElementById('q-category');
      if (catEl) {
        const matched = Array.from(catEl.options).find(opt =>
          itemName.toLowerCase().includes(opt.value.toLowerCase())
        );
        if (matched) catEl.value = matched.value;
      }
      if (noteEl) {
        noteEl.value = 'Tôi cần tư vấn và nhận báo giá chi tiết hạng mục: ' + itemName;
      }
    }

    function handleQuoteSubmit(event) {
      event.preventDefault();
      try {
        const name = document.getElementById('q-name').value.trim();
        const phone = document.getElementById('q-phone').value.trim();
        const category = document.getElementById('q-category').value;
        const feedback = document.getElementById('quote-feedback');

        feedback.innerHTML = `Cảm ơn anh/chị <strong>${name}</strong>! Yêu cầu báo giá <strong>${category}</strong> đã được tiếp nhận. Bộ phận kỹ thuật Phúc Hoàng Thương sẽ gọi lại số <strong>${phone}</strong> trong ít phút (Hotline: 0905.479.773).`;
        feedback.classList.remove('hidden');
        document.getElementById('quote-form').reset();
      } catch (err) {
        console.error('Lỗi gửi form báo giá:', err);
      }
    }

    /* Khởi tạo toàn bộ giao diện khi trang tải xong */
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts('all');
      renderArticles('all');
      showSlide(0);
      resetSlideTimer();
      initBannerSwipe();
    });
  </script>
</body>
</html>
