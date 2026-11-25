<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>ĐẠI PHÁT WINDOWS | Cửa Nhôm Xingfa & Kính Cường Lực TP Huế - Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TRÁCH NHIỆM HỮU HẠN MỘT THÀNH VIÊN XÂY DỰNG SẢN XUẤT ĐẠI PHÁT WINDOWS - Chuyên sản xuất, thi công cửa nhôm Xingfa chính hãng, cửa nhựa lõi thép, cửa kính cường lực, cầu thang kính, phòng tắm kính tại TP Huế và Đà Nẵng. Hotline: 0763.743.456.">

    <!-- =========================================================
         META THUMBNAIL CHIA SẺ LIÊN KẾT (OPEN GRAPH / ZALO / FB)
         Lưu ý: Khi đưa lên WordPress/Flatsome, tải file logo lên
         và cập nhật đường dẫn ảnh logo thật vào thuộc tính content
         ========================================================= -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="ĐẠI PHÁT WINDOWS - daiphatwindows.com">
    <meta property="og:url" content="https://daiphatwindows.com/">
    <meta property="og:title" content="ĐẠI PHÁT WINDOWS | Cửa Nhôm Xingfa, Kính Cường Lực Uy Tín Huế - Đà Nẵng">
    <meta property="og:description" content="CÔNG TY TNHH MTV XÂY DỰNG SẢN XUẤT ĐẠI PHÁT WINDOWS - TDP Thuỷ Phú, Phường Hóa Châu, TP Huế. Hotline: 0763.743.456.">
    <meta property="og:image" content="https://daiphatwindows.com/wp-content/uploads/logo-daiphat-windows-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Công ty TNHH MTV Xây Dựng Sản Xuất Đại Phát Windows">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="ĐẠI PHÁT WINDOWS | daiphatwindows.com">
    <meta name="twitter:description" content="Chuyên sản xuất thi công Cửa Nhôm Xingfa, Cửa Kính Cường Lực tại TP Huế & Đà Nẵng - 0763.743.456">
    <meta name="twitter:image" content="https://daiphatwindows.com/wp-content/uploads/logo-daiphat-windows-thumbnail.png">
    <link rel="icon" type="image/svg+xml" href="https://daiphatwindows.com/wp-content/uploads/favicon-daiphat-windows.svg">

    <!-- Font Inter & Tailwind CSS CDN -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình màu sắc đồng bộ theo Logo Đại Phát Windows -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#082A4A',      /* Xanh Navy đậm - viền & footer */
                            primary: '#0B3D6B',   /* Xanh kiến trúc chủ đạo theo logo */
                            mid: '#155E9F',       /* Xanh dương trung bình */
                            light: '#EBF4FC',     /* Nền xanh nhạt tinh tế */
                            accent: '#D97706',    /* Vàng đồng sang trọng từ logo */
                            accentHover: '#B45309',
                            sale: '#DC2626',      /* Đỏ nhãn giảm giá góc trái sản phẩm */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* =========================================================
           QUY CHUẨN CHỐNG TRÀN VIỀN & BỐ CỤC 95% TRÊN MÁY TÍNH
           ========================================================= */
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
            -webkit-font-smoothing: antialiased;
        }

        /* Container chuẩn UX Builder: Mobile 100% có padding, Desktop đúng 95% chiều ngang */
        .dp-container {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 640px) {
            .dp-container {
                padding-left: 18px;
                padding-right: 18px;
            }
        }

        @media (min-width: 1024px) {
            .dp-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* =========================================================
           MENU MÁY TÍNH: CHỮ GỌN TRÊN 1 HÀNG, KHÔNG XUỐNG DÒNG TÊN MỤC
           ========================================================= */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 4px;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        .desktop-nav-item {
            position: relative;
            flex-shrink: 0;
        }

        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            white-space: nowrap; /* Tuyệt đối không bẻ dòng trong tên danh mục */
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: -0.01em;
            color: #0B3D6B;
            padding: 8px 7px;
            border-radius: 6px;
            transition: all 0.2s ease;
            text-decoration: none;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 9px 10px;
            }
        }

        @media (min-width: 1440px) {
            .desktop-nav-link {
                font-size: 13.5px;
                padding: 9px 12px;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-link.active {
            color: #D97706;
            background-color: #EBF4FC;
        }

        /* Dropdown Flatsome gọn gàng */
        .desktop-submenu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #FFFFFF;
            border: 1px solid #E2E8F0;
            border-top: 3px solid #D97706;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 14px 30px rgba(8, 42, 74, 0.14);
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.22s ease;
            z-index: 60;
            padding: 6px 0;
            list-style: none;
        }

        .desktop-nav-item:hover > .desktop-submenu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .desktop-submenu a {
            display: block;
            padding: 9px 16px;
            font-size: 13px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            text-decoration: none;
            transition: background-color 0.15s ease, color 0.15s ease;
        }

        .desktop-submenu a:hover {
            background-color: #EBF4FC;
            color: #0B3D6B;
            font-weight: 600;
        }

        /* =========================================================
           HERO BANNER 2 SLIDE BẰNG KÍCH THƯỚC NHAU - KHÔNG MẤT CHỮ
           ========================================================= */
        .banner-grid-stage {
            display: grid;
            grid-template-columns: 1fr;
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 14px;
            background-color: #082A4A;
        }

        .banner-slide {
            grid-area: 1 / 1;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
            transition: opacity 0.65s ease, visibility 0.65s ease;
            position: relative;
            display: flex;
            align-items: center;
        }

        .banner-slide.is-active {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
            z-index: 2;
        }

        /* =========================================================
           TIÊU ĐỀ SECTION CHUẨN FLATSOME
           ========================================================= */
        .flatsome-heading {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            margin-bottom: 1.5rem;
        }

        .flatsome-heading::before,
        .flatsome-heading::after {
            content: "";
            height: 2px;
            flex: 1;
            max-width: 90px;
            background: linear-gradient(90deg, transparent, #CBD5E1, #0B3D6B);
        }

        .flatsome-heading::after {
            background: linear-gradient(90deg, #0B3D6B, #CBD5E1, transparent);
        }

        /* =========================================================
           HIỆU ỨNG NÚT LIÊN HỆ NỔI (ZALO, FACEBOOK, HOTLINE)
           ========================================================= */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.55); }
            70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }

        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Ngăn ảnh sản phẩm làm vỡ khung trên mọi màn hình */
        img {
            max-width: 100%;
            display: block;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- =================================================================
         1. TOP BAR THÔNG TIN (KHÔNG CHỨA THANH CHỈNH SỬA UXBUILDER)
         ================================================================= -->
    <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
        <div class="dp-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1 text-slate-200">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-brand-accent"></i>
                    <span>TDP Thuỷ Phú, Phường Hóa Châu, TP Huế</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-brand-accent"></i>
                    <span>Làm việc: 07:30 - 21:00 (Tất cả các ngày)</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-slate-200">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-brand-accent"></i>
                    <span>daiphatwindows.com</span>
                </span>
                <span class="inline-flex items-center gap-1.5 font-semibold text-amber-300">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>0763.743.456</span>
                </span>
            </div>
        </div>
    </div>

    <!-- =================================================================
         2. HEADER CHÍNH: LOGO GỌN NHỎ + MENU 1 HÀNG (KHÔNG ĐỂ NÚT GỌI NGAY)
         ================================================================= -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="dp-container py-2 flex items-center justify-between gap-2">
            <!-- Logo công ty chuyên nghiệp, thiết kế gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 no-underline group" aria-label="Đại Phát Windows Trang chủ">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Đại Phát Windows">
                    <!-- Khung cửa nhôm kiến trúc -->
                    <rect x="4" y="4" width="56" height="56" rx="12" fill="#0B3D6B"/>
                    <rect x="8.5" y="8.5" width="47" height="47" rx="8.5" stroke="#D97706" stroke-width="2.2"/>
                    <!-- 4 ô cửa sổ cách điệu ánh sáng -->
                    <path d="M16 17H30V30H16V17Z" fill="#FFFFFF"/>
                    <path d="M34 17H48V30H34V17Z" fill="#38BDF8" fill-opacity="0.9"/>
                    <path d="M16 34H30V47H16V34Z" fill="#E0F2FE"/>
                    <path d="M34 34H48V47H34V34Z" fill="#D97706"/>
                    <!-- Đường cắt góc nhôm tinh tế -->
                    <path d="M32 13V51M13 32H51" stroke="#0B3D6B" stroke-width="2.6"/>
                    <path d="M18 20L27 28" stroke="#0B3D6B" stroke-width="1.6" stroke-linecap="round" opacity="0.35"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary group-hover:text-brand-mid transition-colors whitespace-nowrap">
                        ĐẠI PHÁT <span class="text-brand-accent">WINDOWS</span>
                    </div>
                    <div class="text-[9.5px] sm:text-[10px] font-semibold uppercase tracking-wider text-slate-500 whitespace-nowrap">
                        Nhôm Xingfa &amp; Kính Cường Lực
                    </div>
                </div>
            </a>

            <!-- Menu Máy Tính: 9 danh mục viết liền 1 hàng gọn đẹp, không xuống dòng tên danh mục -->
            <nav class="hidden lg:block flex-1 min-w-0" aria-label="Danh mục chính">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')" class="desktop-nav-link">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <ul class="desktop-submenu">
                            <li><a href="#san-pham" onclick="filterProducts('xingfa-1-canh')">Cửa nhôm xingfa 1 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('xingfa-2-canh')">Cửa nhôm xingfa 2 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('xingfa-3-canh')">Cửa nhôm xingfa 3 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('xingfa-4-canh')">Cửa nhôm xingfa 4 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('xingfa-5-canh')">Cửa nhôm xingfa 5 cánh</a></li>
                        </ul>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#san-pham" onclick="filterProducts('cua-kinh-cuong-luc')" class="desktop-nav-link">Cửa kính cường lực</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" class="desktop-nav-link">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <ul class="desktop-submenu">
                            <li><a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')">Cửa nhôm xingfa</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('cua-nhua-loi-thep')">Cửa nhựa lõi thép</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('cua-kinh-tu-dong')">Cửa kính tự động</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')">Cầu thang kính</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')">Kính ốp bếp</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('phong-tam-kinh')">Phòng tắm kính</a></li>
                        </ul>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- Nút mở Menu Mobile (Không đặt nút Gọi ngay trên Header) -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition-colors" aria-label="Mở danh mục trang web">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>
    </header>

    <!-- =================================================================
         DRAWER MENU ĐIỆN THOẠI (CHUẨN FLATSOME OFF-CANVAS)
         ================================================================= -->
    <div id="mobileDrawerOverlay" class="fixed inset-0 bg-slate-900/60 z-50 hidden transition-opacity"></div>
    <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
        <div class="flex items-center justify-between px-4 py-3.5 bg-brand-primary text-white">
            <span class="font-bold text-sm tracking-wide uppercase">Danh mục Đại Phát Windows</span>
            <button id="closeMobileDrawer" type="button" class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center hover:bg-white/25" aria-label="Đóng menu">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto py-2 px-3">
            <ul class="space-y-1 text-sm font-semibold text-slate-700">
                <li><a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light text-brand-primary">Trang chủ</a></li>
                <li><a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Giới thiệu</a></li>

                <!-- Submenu Mobile: Cửa nhôm xingfa -->
                <li class="border-t border-slate-100 pt-1">
                    <button type="button" onclick="toggleMobileSubmenu('sub-xingfa', this)" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-brand-light text-left">
                        <span>Cửa nhôm xingfa</span>
                        <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                    </button>
                    <ul id="sub-xingfa" class="hidden pl-4 mt-1 space-y-1 text-xs font-medium text-slate-600 border-l-2 border-brand-accent/40 ml-3">
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-1-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-2-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-3-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-4-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-5-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa 5 cánh</a></li>
                    </ul>
                </li>

                <li><a href="#san-pham" onclick="filterProducts('cua-kinh-cuong-luc')" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Cửa kính cường lực</a></li>

                <!-- Submenu Mobile: Sản phẩm -->
                <li class="border-t border-slate-100 pt-1">
                    <button type="button" onclick="toggleMobileSubmenu('sub-sanpham', this)" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-brand-light text-left">
                        <span>Sản phẩm</span>
                        <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                    </button>
                    <ul id="sub-sanpham" class="hidden pl-4 mt-1 space-y-1 text-xs font-medium text-slate-600 border-l-2 border-brand-accent/40 ml-3">
                        <li><a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhôm xingfa</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-nhua-loi-thep')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa nhựa lõi thép</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-kinh-tu-dong')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cửa kính tự động</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Cầu thang kính</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Kính ốp bếp</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-brand-light">Phòng tắm kính</a></li>
                    </ul>
                </li>

                <li class="border-t border-slate-100 pt-1"><a href="#cong-trinh" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Công trình</a></li>
                <li><a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Báo giá</a></li>
                <li><a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Tin tức</a></li>
                <li><a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-light">Liên hệ</a></li>
            </ul>
        </div>
        <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-brand-primary">ĐẠI PHÁT WINDOWS</div>
            <div>TDP Thuỷ Phú, Phường Hóa Châu, TP Huế</div>
            <div class="font-semibold text-brand-accent">Hotline: 0763.743.456</div>
        </div>
    </aside>

    <!-- =================================================================
         3. HERO BANNER 2 ẢNH TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         - Hình ảnh & chữ nằm trọn trong khung banner, cách xa viền
         - Tự co giãn thông minh đảm bảo không mất chữ trên Mobile & PC
         ================================================================= -->
    <section id="trang-chu" class="pt-3 pb-6 sm:pt-4 sm:pb-8 bg-slate-50">
        <div class="dp-container">
            <div id="heroBanner" class="banner-grid-stage shadow-lg border border-slate-200">

                <!-- BANNER SLIDE 1 -->
                <div class="banner-slide is-active" data-slide="0">
                    <!-- Ảnh nền thật từ dự án + lớp phủ xanh kiến trúc -->
                    <img
                        src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w1400"
                        onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Dai Phat Windows')"
                        alt="Cửa nhôm Xingfa nhập khẩu Đại Phát Windows"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-[#06223D]/95 via-[#0B3D6B]/88 to-[#0B3D6B]/65"></div>

                    <!-- Khung nội dung cách xa viền (px-10 sm:px-16 lg:px-20 py-10 sm:py-14) -->
                    <div class="relative z-10 w-full px-10 sm:px-16 lg:px-20 py-9 sm:py-12 lg:py-14">
                        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <div class="inline-block px-3 py-1 rounded-full bg-brand-accent/20 border border-brand-accent/60 text-amber-300 text-[11px] sm:text-xs font-semibold tracking-wide">
                                    ĐẠI PHÁT WINDOWS • HUẾ &amp; ĐÀ NẴNG
                                </div>
                                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight text-white">
                                    CỬA NHÔM XINGFA CHÍNH HÃNG &amp; KÍNH CƯỜNG LỰC CAO CẤP
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                    Trực tiếp sản xuất &amp; thi công cửa nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ. Cam kết chuẩn kỹ thuật, cách âm cách nhiệt vượt trội, bảo hành dài hạn.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-[11px] sm:text-xs text-slate-100 pt-1 max-w-lg">
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-amber-400"></i><span>Khảo sát tận nơi miễn phí</span></div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-amber-400"></i><span>Giá xưởng tiết kiệm đến 20%</span></div>
                                </div>
                                <div class="flex flex-wrap items-center gap-2.5 pt-2">
                                    <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm shadow-md transition-colors">
                                        <i class="fa-solid fa-file-invoice-dollar"></i>
                                        <span>Nhận báo giá ngay</span>
                                    </a>
                                    <a href="#san-pham" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition-colors">
                                        <span>Xem mẫu cửa</span>
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh minh họa nằm gọn bên trong banner trên Desktop -->
                            <div class="hidden lg:block lg:col-span-5">
                                <div class="p-2.5 rounded-xl bg-white/10 border border-white/25 backdrop-blur-sm shadow-2xl">
                                    <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-brand-dark">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-=w1000"
                                            onerror="handleDriveImgError(this, '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-', 'Cua Nhom Xingfa 4 Canh')"
                                            alt="Cửa đi quay mở 4 cánh nhôm Xingfa Đại Phát Windows"
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                    <div class="mt-2.5 flex items-center justify-between text-xs text-white px-1">
                                        <span class="font-semibold">Cửa Nhôm Xingfa Quảng Đông</span>
                                        <span class="text-amber-300 font-bold">Bảo hành 5 năm</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- BANNER SLIDE 2 (KÍCH THƯỚC & BỐ CỤC TƯƠNG ĐƯƠNG TUYỆT ĐỐI) -->
                <div class="banner-slide" data-slide="1">
                    <img
                        src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1400"
                        onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'Du An Dai Phat Windows')"
                        alt="Thi công dự án khách sạn resort Đại Phát Windows"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-[#06223D]/95 via-[#0B3D6B]/88 to-[#0B3D6B]/65"></div>

                    <div class="relative z-10 w-full px-10 sm:px-16 lg:px-20 py-9 sm:py-12 lg:py-14">
                        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <div class="inline-block px-3 py-1 rounded-full bg-brand-accent/20 border border-brand-accent/60 text-amber-300 text-[11px] sm:text-xs font-semibold tracking-wide">
                                    NHÀ THẦU NHÔM KÍNH CHUYÊN NGHIỆP
                                </div>
                                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight text-white">
                                    THI CÔNG TRỌN GÓI KHÁCH SẠN, BIỆT THỰ &amp; NHÀ PHỐ MIỀN TRUNG
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                    Hơn 150+ công trình lớn tại TP Huế &amp; Đà Nẵng: Cửa nhôm Xingfa, cửa kính tự động, cầu thang kính, phòng tắm kính, kính ốp bếp thẩm mỹ và bền bỉ trước gió bão.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-[11px] sm:text-xs text-slate-100 pt-1 max-w-lg">
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-amber-400"></i><span>Thi công đúng tiến độ 100%</span></div>
                                    <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-amber-400"></i><span>Hotline tư vấn: 0763.743.456</span></div>
                                </div>
                                <div class="flex flex-wrap items-center gap-2.5 pt-2">
                                    <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm shadow-md transition-colors">
                                        <i class="fa-solid fa-building-circle-check"></i>
                                        <span>Xem dự án tiêu biểu</span>
                                    </a>
                                    <a href="#bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition-colors">
                                        <span>Bảng báo giá mới</span>
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh dự án nằm gọn bên trong banner trên Desktop -->
                            <div class="hidden lg:block lg:col-span-5">
                                <div class="p-2.5 rounded-xl bg-white/10 border border-white/25 backdrop-blur-sm shadow-2xl">
                                    <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-brand-dark">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w1000"
                                            onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Du An Khach San Ruby Light')"
                                            alt="Dự án khách sạn Ruby Light Đà Nẵng"
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                    <div class="mt-2.5 flex items-center justify-between text-xs text-white px-1">
                                        <span class="font-semibold">Dự án Khách sạn &amp; Resort 4 Sao</span>
                                        <span class="text-amber-300 font-bold">Huế – Đà Nẵng</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Trái / Phải đặt sát mép ngoài vùng chữ -->
                <button type="button" id="bannerPrev" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button type="button" id="bannerNext" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" class="banner-dot w-7 h-2 rounded-full bg-brand-accent transition-all" data-index="0" aria-label="Chuyển tới banner 1"></button>
                    <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-index="1" aria-label="Chuyển tới banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         4. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, TỐI ƯU PC & MOBILE)
         ================================================================= -->
    <section id="danh-muc-san-pham" class="py-8 sm:py-10 bg-white">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Danh mục sản phẩm nổi bật
                </h2>
            </div>

            <!-- 2 cột trên điện thoại, 3 cột trên tablet, 6 cột 1 hàng gọn đẹp trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Danh mục 1: Cửa nhôm xingfa -->
                <a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w600"
                            onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Cua Nhom Xingfa')"
                            alt="Cửa nhôm Xingfa"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Cửa nhôm Xingfa
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 2: Cửa nhựa lõi thép -->
                <a href="#san-pham" onclick="filterProducts('cua-nhua-loi-thep')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w600"
                            onerror="handleDriveImgError(this, '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', 'Cua Nhua Loi Thep')"
                            alt="Cửa nhựa lõi thép"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Cửa nhựa lõi thép
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 3: Cửa kính tự động -->
                <a href="#san-pham" onclick="filterProducts('cua-kinh-tu-dong')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w600"
                            onerror="handleDriveImgError(this, '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', 'Cua Tu Dong')"
                            alt="Cửa kính tự động"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Cửa kính tự động
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 4: Cầu thang kính -->
                <a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w600"
                            onerror="handleDriveImgError(this, '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', 'Cau Thang Kinh')"
                            alt="Cầu thang kính"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Cầu thang kính
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 5: Kính ốp bếp -->
                <a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w600"
                            onerror="handleDriveImgError(this, '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', 'Kinh Op Bep')"
                            alt="Kính ốp bếp"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Kính ốp bếp
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 6: Phòng tắm kính -->
                <a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="group block bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition-all overflow-hidden">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w600"
                            onerror="handleDriveImgError(this, '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', 'Phong Tam Kinh')"
                            alt="Phòng tắm kính"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-2.5 text-center bg-slate-50 group-hover:bg-brand-primary transition-colors">
                        <h3 class="text-xs font-bold uppercase text-brand-primary group-hover:text-white leading-tight">
                            Phòng tắm kính
                        </h3>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- =================================================================
         5. SẢN PHẨM NỔI BẬT (2 CỘT TRÊN MOBILE, CÓ GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI)
         ================================================================= -->
    <section id="san-pham" class="py-8 sm:py-12 bg-slate-50 border-y border-slate-200/80">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Sản phẩm cửa nhôm Xingfa &amp; kính cường lực
                </h2>
            </div>

            <!-- Bộ lọc danh mục gọn gàng theo chuẩn Flatsome -->
            <div id="productFilterTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                <button type="button" onclick="filterProducts('all')" data-filter="all" class="prod-tab active px-3 py-1.5 rounded-lg text-xs font-semibold border border-brand-primary bg-brand-primary text-white transition-colors">
                    Tất cả nổi bật
                </button>
                <button type="button" onclick="filterProducts('cua-nhom-xingfa')" data-filter="cua-nhom-xingfa" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Cửa nhôm Xingfa
                </button>
                <button type="button" onclick="filterProducts('cua-nhua-loi-thep')" data-filter="cua-nhua-loi-thep" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Cửa nhựa lõi thép
                </button>
                <button type="button" onclick="filterProducts('cua-kinh-cuong-luc')" data-filter="cua-kinh-cuong-luc" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Cửa kính cường lực
                </button>
                <button type="button" onclick="filterProducts('cua-kinh-tu-dong')" data-filter="cua-kinh-tu-dong" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Cửa kính tự động
                </button>
                <button type="button" onclick="filterProducts('cau-thang-kinh')" data-filter="cau-thang-kinh" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Cầu thang kính
                </button>
                <button type="button" onclick="filterProducts('kinh-op-bep')" data-filter="kinh-op-bep" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Kính ốp bếp
                </button>
                <button type="button" onclick="filterProducts('phong-tam-kinh')" data-filter="phong-tam-kinh" class="prod-tab px-3 py-1.5 rounded-lg text-xs font-semibold border border-slate-300 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary transition-colors">
                    Phòng tắm kính
                </button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên PC -> Tên sản phẩm hiển thị đủ chữ, không bị tràn -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4 lg:gap-5">
                <!-- Được render tự động bằng JavaScript từ dữ liệu sản phẩm thật -->
            </div>
        </div>
    </section>

    <!-- =================================================================
         6. GIỚI THIỆU CÔNG TY & CAM KẾT CHẤT LƯỢNG (THEO MẪU NGỌC HÂN WINDOW)
         ================================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
        <div class="dp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-start">
                <!-- Cột giới thiệu -->
                <div class="lg:col-span-7 space-y-4">
                    <div class="inline-block text-xs font-bold uppercase tracking-wider text-brand-accent">
                        Về chúng tôi
                    </div>
                    <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary leading-snug">
                        CÔNG TY TNHH MTV XÂY DỰNG SẢN XUẤT ĐẠI PHÁT WINDOWS
                    </h2>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>Đại Phát Windows</strong> là đơn vị uy tín hàng đầu chuyên thiết kế, sản xuất và thi công lắp đặt tổng thể các hạng mục nhôm kính tại <strong>TP Huế, Đà Nẵng và khu vực Miền Trung</strong>. Với hệ thống máy móc gia công hiện đại cùng đội ngũ kỹ thuật viên giàu kinh nghiệm, chúng tôi mang đến các dòng sản phẩm đạt chuẩn chất lượng quốc tế: <em>Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa nhựa lõi thép uPVC, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.</em>
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Với phương châm <strong>“Cửa Đẹp Cho Mọi Nhà – Bền Vững Cùng Thời Gian”</strong>, Đại Phát Windows luôn chú trọng từng đường keo, góc ép, hệ phụ kiện đồng bộ chính hãng và chính sách bảo hành tận tâm nhằm kiến tạo không gian sống sang trọng, hiện đại và an toàn tuyệt đối.
                    </p>

                    <!-- 4 chỉ số năng lực Flatsome -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
                        <div class="p-3.5 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">150+</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Dự án hoàn thành</div>
                        </div>
                        <div class="p-3.5 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">50+</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Kỹ thuật viên</div>
                        </div>
                        <div class="p-3.5 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">100+</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Mẫu cửa cao cấp</div>
                        </div>
                        <div class="p-3.5 rounded-xl bg-brand-light border border-brand-primary/10 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">100%</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Khách hàng hài lòng</div>
                        </div>
                    </div>
                </div>

                <!-- Cột bảng cam kết dịch vụ (tương tự bảng ưu đãi của web mẫu) -->
                <div class="lg:col-span-5">
                    <div class="rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                        <div class="bg-brand-primary text-white px-5 py-3.5 font-bold text-sm uppercase tracking-wide flex items-center gap-2">
                            <i class="fa-solid fa-shield-halved text-brand-accent"></i>
                            <span>Cam kết dịch vụ tại Đại Phát Windows</span>
                        </div>
                        <div class="divide-y divide-slate-200 text-xs sm:text-sm bg-white">
                            <div class="flex items-center justify-between px-4 py-3 gap-3">
                                <span class="font-semibold text-slate-700"><i class="fa-solid fa-check text-emerald-600 mr-2"></i>Hotline tư vấn</span>
                                <a href="tel:0763743456" class="font-bold text-brand-accent hover:underline">0763.743.456</a>
                            </div>
                            <div class="flex items-center justify-between px-4 py-3 gap-3 bg-slate-50/70">
                                <span class="font-semibold text-slate-700"><i class="fa-solid fa-check text-emerald-600 mr-2"></i>Khảo sát &amp; lắp đặt</span>
                                <span class="font-semibold text-brand-primary text-right">Đo đạc miễn phí tận công trình</span>
                            </div>
                            <div class="flex items-center justify-between px-4 py-3 gap-3">
                                <span class="font-semibold text-slate-700"><i class="fa-solid fa-check text-emerald-600 mr-2"></i>Ưu đãi trực tiếp</span>
                                <span class="font-semibold text-brand-sale text-right">Giảm ngay 10% – 20% giá xưởng</span>
                            </div>
                            <div class="flex items-center justify-between px-4 py-3 gap-3 bg-slate-50/70">
                                <span class="font-semibold text-slate-700"><i class="fa-solid fa-check text-emerald-600 mr-2"></i>Chế độ bảo hành</span>
                                <span class="font-semibold text-brand-primary text-right">Thanh nhôm 5 năm • Phụ kiện 2 năm</span>
                            </div>
                            <div class="flex items-center justify-between px-4 py-3 gap-3">
                                <span class="font-semibold text-slate-700"><i class="fa-solid fa-check text-emerald-600 mr-2"></i>Chất lượng vật tư</span>
                                <span class="font-semibold text-brand-primary text-right">100% Nhôm Xingfa &amp; Kính chuẩn</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         7. BẢNG BÁO GIÁ THAM KHẢO CỬA NHÔM XINGFA MỚI NHẤT
         ================================================================= -->
    <section id="bao-gia" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200/80">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Bảng báo giá cửa nhôm Xingfa mới nhất
                </h2>
            </div>

            <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs sm:text-sm">
                        <thead>
                            <tr class="bg-brand-primary text-white">
                                <th class="py-3 px-4 font-bold w-12 text-center">STT</th>
                                <th class="py-3 px-4 font-bold">Hạng mục hệ cửa Nhôm Xingfa nhập khẩu tem đỏ</th>
                                <th class="py-3 px-4 font-bold">Độ dày nhôm</th>
                                <th class="py-3 px-4 font-bold text-right">Đơn giá ưu đãi (VNĐ/m²)</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200">
                            <tr class="hover:bg-brand-light/40">
                                <td class="py-3 px-4 text-center font-semibold">1</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa sổ mở hất 1 cánh / 2 cánh nhôm Xingfa hệ 55</td>
                                <td class="py-3 px-4 text-slate-600">1.4 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">1.850.000 ₫</td>
                            </tr>
                            <tr class="hover:bg-brand-light/40 bg-slate-50/50">
                                <td class="py-3 px-4 text-center font-semibold">2</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi mở quay 1 cánh nhôm Xingfa hệ 55</td>
                                <td class="py-3 px-4 text-slate-600">2.0 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">1.950.000 ₫</td>
                            </tr>
                            <tr class="hover:bg-brand-light/40">
                                <td class="py-3 px-4 text-center font-semibold">3</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi mở quay 2 cánh / 3 cánh nhôm Xingfa hệ 55</td>
                                <td class="py-3 px-4 text-slate-600">2.0 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">2.050.000 ₫</td>
                            </tr>
                            <tr class="hover:bg-brand-light/40 bg-slate-50/50">
                                <td class="py-3 px-4 text-center font-semibold">4</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi mở quay 4 cánh / 5 cánh nhôm Xingfa hệ 55</td>
                                <td class="py-3 px-4 text-slate-600">2.0 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">2.100.000 ₫</td>
                            </tr>
                            <tr class="hover:bg-brand-light/40">
                                <td class="py-3 px-4 text-center font-semibold">5</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa đi mở xếp trượt nhôm Xingfa hệ 63</td>
                                <td class="py-3 px-4 text-slate-600">2.0 – 3.0 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">2.250.000 ₫</td>
                            </tr>
                            <tr class="hover:bg-brand-light/40 bg-slate-50/50">
                                <td class="py-3 px-4 text-center font-semibold">6</td>
                                <td class="py-3 px-4 font-semibold text-slate-800">Cửa kính cường lực bản lề sàn 10mm – 12mm</td>
                                <td class="py-3 px-4 text-slate-600">Kính 10-12 mm</td>
                                <td class="py-3 px-4 text-right font-bold text-brand-sale">850.000 ₫</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="px-4 py-3 bg-brand-light/60 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
                    <span>* Đơn giá tham khảo đã bao gồm kính an toàn 6.38mm / cường lực 8mm, gioăng EPDM, keo ép góc. Chưa gồm phụ kiện Kinlong theo bộ.</span>
                    <a href="#form-bao-gia" class="font-bold text-brand-primary hover:text-brand-accent underline">Đăng ký nhận báo giá chi tiết theo bản vẽ &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         8. CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG & HUẾ (6 DỰ ÁN THỰC TẾ)
         ================================================================= -->
    <section id="cong-trinh" class="py-10 sm:py-12 bg-white border-t border-slate-200/80">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Các dự án nổi bật tại Đà Nẵng &amp; Huế
                </h2>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <!-- Dự án 1 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w800"
                            onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'My Son Heritage Resort')"
                            alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Khách sạn &amp; Resort • Miền Trung</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Cung cấp và lắp đặt đồng bộ hệ cửa nhôm Xingfa nhập khẩu, vách kính cường lực chịu lực gió lớn cho toàn khu nghỉ dưỡng.
                        </p>
                    </div>
                </article>

                <!-- Dự án 2 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy=w800"
                            onerror="handleDriveImgError(this, '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy', 'Khach San Goden Line')"
                            alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Khách sạn • Đà Nẵng</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Hạng mục mặt dựng nhôm kính, cửa đi ban công Xingfa cách âm chuẩn khách sạn và cabin phòng tắm kính cường lực.
                        </p>
                    </div>
                </article>

                <!-- Dự án 3 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w800"
                            onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Khach San Ruby Light')"
                            alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Khách sạn • Đà Nẵng &amp; Huế</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            DỰ ÁN KHÁCH SẠN RUBY LIGHT
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Thi công trọn gói cửa sổ mở hất, cửa đi mở quay nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển và cửa kính sảnh.
                        </p>
                    </div>
                </article>

                <!-- Dự án 4 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w800"
                            onerror="handleDriveImgError(this, '1za_IJpAm850uulT6IuhBsk1THb3LuPuc', 'Raon Da Nang Beach Hotel')"
                            alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Khách sạn ven biển • Đà Nẵng</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Hệ thống cửa kính tự động sảnh chính, vách kính hộp cách âm và hệ cửa nhôm kính đồng bộ toàn tòa nhà ven biển.
                        </p>
                    </div>
                </article>

                <!-- Dự án 5 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64=w800"
                            onerror="handleDriveImgError(this, '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64', 'Khach San Jolia')"
                            alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Khách sạn căn hộ • Đà Nẵng</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Lắp đặt cửa đi lùa nhôm Xingfa, lan can cầu thang kính cường lực và toàn bộ vách tắm kính sang trọng cho khu căn hộ.
                        </p>
                    </div>
                </article>

                <!-- Dự án 6 -->
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt=w800"
                            onerror="handleDriveImgError(this, '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt', 'Khach San Soho')"
                            alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4">
                        <div class="text-[11px] font-semibold text-brand-accent uppercase mb-1">Boutique Hotel • Đà Nẵng</div>
                        <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                            THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
                        </h3>
                        <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                            Thi công vách mặt dựng kính phản quang, cửa nhôm kính cao cấp chuẩn thẩm mỹ kiến trúc hiện đại bàn giao vượt tiến độ.
                        </p>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =================================================================
         9. FORM YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ NGAY TRÊN TRANG CHỦ
         ================================================================= -->
    <section id="form-bao-gia" class="py-10 sm:py-12 bg-brand-primary text-white">
        <div class="dp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <!-- Thông tin hỗ trợ bên trái -->
                <div class="lg:col-span-5 space-y-4">
                    <div class="inline-block px-3 py-1 rounded-full bg-white/10 text-amber-300 text-xs font-semibold uppercase tracking-wide">
                        Hỗ trợ kỹ thuật 24/7
                    </div>
                    <h2 class="text-xl sm:text-2xl font-extrabold leading-tight">
                        ĐĂNG KÝ NHẬN BÁO GIÁ &amp; KHẢO SÁT MIỄN PHÍ
                    </h2>
                    <p class="text-sm text-slate-200 leading-relaxed">
                        Để lại thông tin công trình của quý khách, kỹ sư của <strong>Đại Phát Windows</strong> sẽ gọi lại tư vấn phương án cửa tối ưu nhất và gửi bảng dự toán chi tiết trong vòng 15 phút.
                    </p>
                    <div class="space-y-2.5 text-sm pt-1">
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-phone-volume text-brand-accent mt-1"></i>
                            <span>Hotline / Zalo: <strong class="text-amber-300">0763.743.456</strong></span>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-1"></i>
                            <span>Xưởng &amp; Văn phòng: TDP Thuỷ Phú, Phường Hóa Châu, TP Huế</span>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-globe text-brand-accent mt-1"></i>
                            <span>Website: daiphatwindows.com</span>
                        </div>
                    </div>
                </div>

                <!-- Form gửi yêu cầu bên phải -->
                <div class="lg:col-span-7">
                    <form id="quoteRequestForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-xl space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="qName" class="block text-xs font-bold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                                <input id="qName" name="name" type="text" required placeholder="Nhập họ tên của bạn..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                                <input id="qPhone" name="phone" type="tel" required placeholder="Ví dụ: 0763.743.456" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="qCategory" class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                                <select id="qCategory" name="category" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20">
                                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1 - 5 cánh, xếp trượt)</option>
                                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                                    <option value="Cầu thang kính">Cầu thang kính</option>
                                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    <option value="Thi công trọn gói công trình">Thi công trọn gói nhà phố / khách sạn</option>
                                </select>
                            </div>
                            <div>
                                <label for="qLocation" class="block text-xs font-bold text-slate-700 mb-1">Địa điểm công trình</label>
                                <input id="qLocation" name="location" type="text" placeholder="TP Huế, Đà Nẵng, Quảng Trị..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20">
                            </div>
                        </div>

                        <div>
                            <label for="qNote" class="block text-xs font-bold text-slate-700 mb-1">Kích thước dự kiến / Yêu cầu cụ thể</label>
                            <textarea id="qNote" name="note" rows="3" placeholder="Nhập số lượng bộ cửa, kích thước hoặc yêu cầu khảo sát tận nhà..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-3">
                            <button type="submit" class="w-full sm:w-auto px-6 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm shadow-md transition-colors inline-flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Gửi yêu cầu báo giá ngay</span>
                            </button>
                            <span class="text-xs text-slate-500">Bảo mật thông tin khách hàng 100%</span>
                        </div>

                        <!-- Thông báo gửi thành công thay thế alert() -->
                        <div id="quoteSuccessBox" class="hidden p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium">
                            <i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i>
                            <span id="quoteSuccessText">Đã tiếp nhận yêu cầu báo giá! Bộ phận kỹ thuật Đại Phát Windows sẽ liên hệ với bạn trong ít phút.</span>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         10. DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ
         ================================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-12 bg-slate-50">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Tin tức &amp; Kiến thức nhôm kính
                </h2>
            </div>

            <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Render từ danh sách bài viết bên dưới -->
            </div>
        </div>
    </section>

    <!-- =================================================================
         11. ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC CUNG CẤP)
         ================================================================= -->
    <section class="py-8 sm:py-10 bg-white border-t border-slate-200/80">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Đối tác của chúng tôi
                </h2>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" onerror="handleDriveImgError(this, '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk', 'Doi Tac 1')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 1" class="max-h-full max-w-full object-contain">
                </div>
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" onerror="handleDriveImgError(this, '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq', 'Doi Tac 2')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 2" class="max-h-full max-w-full object-contain">
                </div>
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" onerror="handleDriveImgError(this, '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn', 'Doi Tac 3')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 3" class="max-h-full max-w-full object-contain">
                </div>
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" onerror="handleDriveImgError(this, '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT', 'Doi Tac 4')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 4" class="max-h-full max-w-full object-contain">
                </div>
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" onerror="handleDriveImgError(this, '1SDcarhnX0yypmqdbawICjYBRtFnKngn-', 'Doi Tac 5')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 5" class="max-h-full max-w-full object-contain">
                </div>
                <div class="h-20 sm:h-24 p-3 rounded-xl border border-slate-200 bg-white flex items-center justify-center hover:border-brand-primary transition-colors">
                    <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" onerror="handleDriveImgError(this, '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg', 'Doi Tac 6')" alt="Đối tác cung cấp nhôm kính Đại Phát Windows 6" class="max-h-full max-w-full object-contain">
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         12. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY NGOÀI TRANG CHỦ
         ================================================================= -->
    <section id="lien-he" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200/80">
        <div class="dp-container">
            <div class="flatsome-heading">
                <h2 class="text-base sm:text-xl font-extrabold uppercase tracking-tight text-brand-primary text-center">
                    Bản đồ chỉ đường &amp; Fanpage Facebook
                </h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Cột Google Map địa chỉ TDP Thuỷ Phú, Phường Hóa Châu, TP Huế -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-brand-primary text-white flex flex-wrap items-center justify-between gap-2">
                        <div class="text-xs sm:text-sm font-bold flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                            <span>Bản đồ đến xưởng Đại Phát Windows</span>
                        </div>
                        <a href="https://maps.google.com/?q=TDP+Thuy+Phu,+Phuong+Hoa+Chau,+TP+Hue" target="_blank" rel="noopener" class="text-[11px] font-semibold text-amber-300 hover:underline">
                            Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                        </a>
                    </div>
                    <div class="flex-1 min-h-[280px] sm:min-h-[340px] w-full bg-slate-200">
                        <iframe
                            title="Bản đồ Công ty Đại Phát Windows - TDP Thuỷ Phú, Phường Hóa Châu, TP Huế"
                            src="https://maps.google.com/maps?q=Thuy%20Phu,%20Hoa%20Chau,%20Hue,%20Vietnam&t=&z=14&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                    <div class="px-4 py-2.5 text-xs text-slate-600 bg-slate-50 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <span><strong>Địa chỉ:</strong> TDP Thuỷ Phú, Phường Hóa Châu, TP Huế</span>
                        <span><strong>SĐT:</strong> <a href="tel:0763743456" class="font-bold text-brand-primary">0763.743.456</a></span>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook đưa ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
                        <div class="text-xs sm:text-sm font-bold flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-base"></i>
                            <span>Fanpage Facebook chính thức</span>
                        </div>
                        <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded-full">Đang hoạt động</span>
                    </div>

                    <!-- Khung giao diện Fanpage Facebook chuẩn đẹp & tương thích mọi trình duyệt -->
                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <!-- Cover + Avatar Fanpage -->
                        <div class="rounded-xl overflow-hidden border border-slate-200">
                            <div class="relative h-28 bg-brand-dark overflow-hidden">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w800"
                                    onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Fanpage Dai Phat Windows')"
                                    alt="Ảnh bìa Fanpage Đại Phát Windows"
                                    class="w-full h-full object-cover opacity-50"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                        <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="4" y="4" width="56" height="56" rx="12" fill="#0B3D6B"/>
                                            <rect x="8.5" y="8.5" width="47" height="47" rx="8.5" stroke="#D97706" stroke-width="2.2"/>
                                            <path d="M16 17H30V30H16V17Z" fill="#FFFFFF"/>
                                            <path d="M34 17H48V30H34V17Z" fill="#38BDF8"/>
                                            <path d="M16 34H30V47H16V34Z" fill="#E0F2FE"/>
                                            <path d="M34 34H48V47H34V34Z" fill="#D97706"/>
                                        </svg>
                                    </div>
                                    <div class="min-w-0 text-white">
                                        <div class="text-sm font-bold leading-tight truncate">Đại Phát Windows - Cửa Nhôm Xingfa</div>
                                        <div class="text-[11px] text-slate-200">5.8K lượt thích • 6.2K người theo dõi</div>
                                    </div>
                                </div>
                            </div>

                            <!-- Bài đăng mới nhất trên Fanpage -->
                            <div class="p-3.5 bg-slate-50 space-y-2.5">
                                <div class="flex items-center justify-between text-[11px] text-slate-500">
                                    <span class="font-semibold text-brand-primary">Cập nhật công trình mới nhất</span>
                                    <span>Hôm nay</span>
                                </div>
                                <p class="text-xs text-slate-700 leading-relaxed">
                                    Hoàn thiện lắp đặt trọn gói cửa nhôm Xingfa tem đỏ nhập khẩu &amp; cầu thang kính cường lực cho biệt thự tại TP Huế. Ưu đãi giảm giá trực tiếp tại xưởng - Gọi ngay 0763.743.456 để được đo đạc miễn phí!
                                </p>
                                <div class="grid grid-cols-3 gap-1.5">
                                    <img src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-=w400" onerror="handleDriveImgError(this, '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-', 'Cong trinh 1')" alt="Ảnh công trình 1" class="aspect-square w-full object-cover rounded-md">
                                    <img src="https://lh3.googleusercontent.com/d/17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR=w400" onerror="handleDriveImgError(this, '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR', 'Cong trinh 2')" alt="Ảnh công trình 2" class="aspect-square w-full object-cover rounded-md">
                                    <img src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w400" onerror="handleDriveImgError(this, '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', 'Cong trinh 3')" alt="Ảnh công trình 3" class="aspect-square w-full object-cover rounded-md">
                                </div>
                            </div>
                        </div>

                        <!-- Nút tương tác Fanpage -->
                        <div class="grid grid-cols-2 gap-2.5">
                            <a href="https://www.facebook.com/" target="_blank" rel="noopener" class="py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold text-center transition-colors inline-flex items-center justify-center gap-1.5">
                                <i class="fa-solid fa-thumbs-up"></i>
                                <span>Thích Fanpage</span>
                            </a>
                            <a href="https://zalo.me/0763743456" target="_blank" rel="noopener" class="py-2.5 px-3 rounded-lg bg-brand-light hover:bg-blue-100 text-brand-primary text-xs font-bold text-center transition-colors inline-flex items-center justify-center gap-1.5 border border-brand-primary/20">
                                <i class="fa-solid fa-comment-dots"></i>
                                <span>Nhắn tin tư vấn</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =================================================================
         13. FOOTER CHUẨN FLATSOME 4 CỘT (CÓ KHOẢNG TRỐNG ĐÁY CHO MOBILE BAR)
         ================================================================= -->
    <footer class="bg-brand-dark text-slate-300 pt-10 pb-24 lg:pb-8 border-t-4 border-brand-accent">
        <div class="dp-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect x="4" y="4" width="56" height="56" rx="12" fill="#0B3D6B"/>
                            <rect x="8.5" y="8.5" width="47" height="47" rx="8.5" stroke="#D97706" stroke-width="2.2"/>
                            <path d="M16 17H30V30H16V17Z" fill="#FFFFFF"/>
                            <path d="M34 17H48V30H34V17Z" fill="#38BDF8"/>
                            <path d="M16 34H30V47H16V34Z" fill="#E0F2FE"/>
                            <path d="M34 34H48V47H34V34Z" fill="#D97706"/>
                        </svg>
                        <div class="text-white font-extrabold text-sm leading-tight">
                            ĐẠI PHÁT <span class="text-brand-accent">WINDOWS</span>
                        </div>
                    </div>
                    <p class="text-xs font-bold text-white leading-relaxed">
                        CÔNG TY TRÁCH NHIỆM HỮU HẠN MỘT THÀNH VIÊN XÂY DỰNG SẢN XUẤT ĐẠI PHÁT WINDOWS
                    </p>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-0.5"></i>
                            <span>Địa chỉ: TDP Thuỷ Phú, Phường Hóa Châu, TP Huế</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-brand-accent"></i>
                            <span>Hotline: <a href="tel:0763743456" class="font-bold text-amber-300 hover:underline">0763.743.456</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-brand-accent"></i>
                            <span>Website: daiphatwindows.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h3 class="text-white font-bold text-xs uppercase tracking-wider mb-3 pb-2 border-b border-white/15">
                        Cửa nhôm Xingfa
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-1-canh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa 1 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-2-canh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa 2 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-3-canh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa 3 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-4-canh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('xingfa-5-canh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa 5 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa đi xếp trượt Xingfa</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h3 class="text-white font-bold text-xs uppercase tracking-wider mb-3 pb-2 border-b border-white/15">
                        Danh mục sản phẩm
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('cua-nhom-xingfa')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhôm Xingfa chính hãng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-nhua-loi-thep')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa nhựa lõi thép uPVC</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-kinh-cuong-luc')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa kính cường lực</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cua-kinh-tu-dong')" class="hover:text-amber-300 transition-colors">&rsaquo; Cửa kính tự động</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="hover:text-amber-300 transition-colors">&rsaquo; Cầu thang kính cường lực</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="hover:text-amber-300 transition-colors">&rsaquo; Kính ốp bếp &amp; Phòng tắm kính</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ trợ khách hàng -->
                <div>
                    <h3 class="text-white font-bold text-xs uppercase tracking-wider mb-3 pb-2 border-b border-white/15">
                        Liên kết nhanh
                    </h3>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition-colors">&rsaquo; Giới thiệu công ty</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-300 transition-colors">&rsaquo; Công trình Huế &amp; Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-300 transition-colors">&rsaquo; Báo giá thi công mới nhất</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition-colors">&rsaquo; Tin tức &amp; Tư vấn chọn cửa</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition-colors">&rsaquo; Đăng ký khảo sát miễn phí</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright 2026 &copy; Bản quyền thuộc về <strong class="text-white">ĐẠI PHÁT WINDOWS (daiphatwindows.com)</strong></div>
                <div>Thiết kế chuẩn Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- =================================================================
         14. NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Trên Máy tính: Cụm nút nổi gọn đẹp góc dưới bên phải
         - Trên Điện thoại: Thanh liên hệ 3 nút chạm mượt cố định đáy màn hình
         ================================================================= -->
    <!-- Phiên bản Máy tính (Desktop) -->
    <div class="hidden lg:flex fixed right-4 bottom-6 z-40 flex-col items-end gap-2.5">
        <a href="https://zalo.me/0763743456" target="_blank" rel="noopener" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <a href="https://www.facebook.com/" target="_blank" rel="noopener" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-all">
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs"></i>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <a href="tel:0763743456" class="hotline-pulse flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-xl transition-all">
            <i class="fa-solid fa-phone-volume w-6 h-6 rounded-full bg-white text-brand-accent flex items-center justify-center text-xs"></i>
            <span class="text-xs font-extrabold whitespace-nowrap">0763.743.456</span>
        </a>
    </div>

    <!-- Phiên bản Điện thoại & Tablet (Mobile Bottom Bar - không gây tràn viền) -->
    <div class="lg:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-[0_-4px_15px_rgba(0,0,0,0.08)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a href="https://zalo.me/0763743456" target="_blank" rel="noopener" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#0068FF] text-white text-xs font-bold active:scale-95 transition-transform">
                <span class="font-extrabold">Zalo</span>
            </a>
            <a href="https://www.facebook.com/" target="_blank" rel="noopener" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#1877F2] text-white text-xs font-bold active:scale-95 transition-transform">
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>
            <a href="tel:0763743456" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-brand-accent text-white text-xs font-extrabold active:scale-95 transition-transform">
                <i class="fa-solid fa-phone-volume"></i>
                <span>0763.743.456</span>
            </a>
        </div>
    </div>

    <!-- =================================================================
         15. MODAL XEM NHANH SẢN PHẨM & ĐỌC CHI TIẾT BÀI VIẾT
         ================================================================= -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-slate-900/70 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="detailModalBody" class="p-5 sm:p-6"></div>
        </div>
    </div>

    <!-- =================================================================
         JAVASCRIPT: XỬ LÝ ẢNH DRIVE, SLIDER, LỌC SẢN PHẨM, FORM & MODAL
         ================================================================= -->
    <script>
        /**
         * Xử lý fallback tự động cho ảnh Google Drive để luôn hiển thị mượt mà
         */
        function handleDriveImgError(imgEl, driveId, fallbackLabel) {
            const step = parseInt(imgEl.dataset.fallbackStep || '0', 10);
            if (step === 0) {
                imgEl.dataset.fallbackStep = '1';
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
            } else if (step === 1) {
                imgEl.dataset.fallbackStep = '2';
                imgEl.src = 'https://placehold.co/800x600/0B3D6B/FFFFFF?text=' + encodeURIComponent(fallbackLabel || 'Dai Phat Windows');
            }
        }

        /**
         * Danh sách sản phẩm thật của Đại Phát Windows (đồng bộ tên sản phẩm, giá, giảm giá % & ảnh Drive)
         */
        const PRODUCTS = [
            {
                id: 'p1',
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-1-canh'],
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: 2450000,
                salePrice: 1950000,
                discount: 20,
                unit: '₫/m²',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính an toàn 6.38mm hoặc cường lực 8mm, phụ kiện Kinlong chính hãng đồng bộ, bảo hành 5 năm.'
            },
            {
                id: 'p2',
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-2-canh'],
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: 2480000,
                salePrice: 2050000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Nhôm Xingfa tem đỏ Quảng Đông hệ 55 dày 2.0mm, gioăng kép EPDM kín nước tuyệt đối, thích hợp cửa mặt tiền nhà phố & ban công.'
            },
            {
                id: 'p3',
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-3-canh'],
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: 2500000,
                salePrice: 2080000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Thiết kế mở quay 3 cánh sang trọng, thanh nhôm định hình gân gia cường chịu gió bão lên đến 1600 Pascal, khóa đa điểm chống trộm.'
            },
            {
                id: 'p4',
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-4-canh'],
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: 2550000,
                salePrice: 2100000,
                discount: 18,
                unit: '₫/m²',
                specs: 'Mẫu cửa chính 4 cánh được ưa chuộng nhất cho nhà phố & biệt thự. Ép góc thủy lực kín khít, sơn tĩnh điện bền màu trên 15 năm.'
            },
            {
                id: 'p5',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-5-canh'],
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: 2700000,
                salePrice: 2250000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Cửa đi xếp trượt gấp 4 – 5 – 6 cánh hệ 63 cao cấp, mở rộng tối đa không gian sân vườn, hồ bơi, khách sạn và showroom.'
            },
            {
                id: 'p6',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: 'cua-nhom-xingfa',
                subcats: ['cua-nhom-xingfa', 'xingfa-2-canh'],
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: 2250000,
                salePrice: 1850000,
                discount: 18,
                unit: '₫/m²',
                specs: 'Cửa sổ mở hất chống hắt mưa hiệu quả cho khí hậu TP Huế - Đà Nẵng, bản lề chữ A inox 304 và thanh chống gió an toàn.'
            },
            {
                id: 'p7',
                name: 'Cửa nhựa lõi thép uPVC cách âm cao cấp',
                category: 'cua-nhua-loi-thep',
                subcats: ['cua-nhua-loi-thep'],
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                originalPrice: 2100000,
                salePrice: 1750000,
                discount: 17,
                unit: '₫/m²',
                specs: 'Thanh nhựa uPVC lõi thép gia cường mạ kẽm, cách âm cách nhiệt vượt trội, không cong vênh mối mọt, phù hợp phòng ngủ & văn phòng.'
            },
            {
                id: 'p8',
                name: 'Cửa kính cường lực tự động trượt 2 cánh',
                category: 'cua-kinh-tu-dong',
                subcats: ['cua-kinh-tu-dong', 'cua-kinh-cuong-luc'],
                driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                originalPrice: 26500000,
                salePrice: 22500000,
                discount: 15,
                unit: '₫/bộ',
                specs: 'Motor tự động cảm biến mắt thần siêu êm, kính cường lực 10mm - 12mm an toàn tuyệt đối cho khách sạn, ngân hàng, siêu thị.'
            },
            {
                id: 'p9',
                name: 'Cầu thang kính cường lực tay vịn gỗ',
                category: 'cau-thang-kinh',
                subcats: ['cau-thang-kinh', 'cua-kinh-cuong-luc'],
                driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                originalPrice: 1650000,
                salePrice: 1380000,
                discount: 16,
                unit: '₫/md',
                specs: 'Kính cường lực 10mm - 12mm kết hợp trụ inox 304 và tay vịn gỗ căm xe / gỗ sồi sang trọng, giúp không gian nhà luôn thoáng sáng.'
            },
            {
                id: 'p10',
                name: 'Kính ốp bếp cường lực sơn màu chịu nhiệt',
                category: 'kinh-op-bep',
                subcats: ['kinh-op-bep', 'cua-kinh-cuong-luc'],
                driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                originalPrice: 980000,
                salePrice: 820000,
                discount: 16,
                unit: '₫/md',
                specs: 'Kính cường lực 8mm sơn hấp nhiệt màu sắc đa dạng, chống bám dầu mỡ, dễ dàng vệ sinh lau chùi, liền mạch không mạch vữa.'
            },
            {
                id: 'p11',
                name: 'Phòng tắm kính cường lực vách ngăn hiện đại',
                category: 'phong-tam-kinh',
                subcats: ['phong-tam-kinh', 'cua-kinh-cuong-luc'],
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                originalPrice: 1250000,
                salePrice: 990000,
                discount: 21,
                unit: '₫/m²',
                specs: 'Kính cường lực 10mm trong suốt, phụ kiện inox 304 chống rỉ sét tuyệt đối, gioăng từ ngăn nước bắn ra ngoài hiệu quả.'
            },
            {
                id: 'p12',
                name: 'Cửa kính cường lực bản lề sàn 2 cánh',
                category: 'cua-kinh-cuong-luc',
                subcats: ['cua-kinh-cuong-luc'],
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                originalPrice: 1150000,
                salePrice: 920000,
                discount: 20,
                unit: '₫/m²',
                specs: 'Kính cường lực 10mm – 12mm kết hợp bản lề thủy lực VVP Thái Lan / Hafele Đức, thẩm mỹ tối đa cho mặt tiền cửa hàng và văn phòng.'
            }
        ];

        /**
         * Danh sách bài viết kiến thức nhôm kính trang chủ
         */
        const NEWS_ARTICLES = [
            {
                id: 'n1',
                tag: 'Tư vấn nhôm kính',
                date: '20/11/2026',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu mưa bão TP Huế & Đà Nẵng không?',
                excerpt: 'Phân tích khả năng chống thấm nước, chịu áp lực gió bão 1600Pa và độ bền lớp sơn tĩnh điện của cửa nhôm Xingfa tại miền Trung.',
                content: 'Khí hậu miền Trung (đặc biệt tại TP Huế và Đà Nẵng) có đặc thù nắng nóng gay gắt vào mùa hè và mưa bão kéo dài vào mùa đông. Cửa nhôm Xingfa nhập khẩu tem đỏ được thiết kế khoang rỗng kết hợp các đường gân gia cường chịu lực, đi kèm hệ gioăng kép EPDM kín khít và rãnh thoát nước thông minh hướng ra ngoài giúp ngăn nước mưa tạt vào nhà tuyệt đối, không bị cong vênh hay rỉ sét như các loại cửa thông thường.'
            },
            {
                id: 'n2',
                tag: 'Kinh nghiệm chọn cửa',
                date: '15/11/2026',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                title: 'Cửa nhôm Xingfa có tốt hơn cửa gỗ và cửa nhựa lõi thép không?',
                excerpt: 'So sánh chi tiết độ bền, khả năng cách âm, tính thẩm mỹ và chi phí bảo trì giữa cửa nhôm Xingfa, cửa gỗ tự nhiên và cửa nhựa uPVC.',
                content: 'So với cửa gỗ truyền thống dễ bị co ngót, mối mọt khi gặp độ ẩm cao và cửa nhựa lõi thép có thể ố vàng sau nhiều năm ngoài nắng, cửa nhôm Xingfa nổi bật với tuổi thọ hàng chục năm, màu sắc hiện đại (ghi xám, đen tuyền, nâu cà phê, vân gỗ), trọng lượng nhẹ giúp giảm tải trọng công trình và đặc biệt rất dễ lau chùi bảo dưỡng.'
            },
            {
                id: 'n3',
                tag: 'Tiết kiệm năng lượng',
                date: '10/11/2026',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                title: 'Cửa nhôm kính Xingfa giúp cách âm, tiết kiệm điện điều hòa như thế nào?',
                excerpt: 'Sự kết hợp giữa profile nhôm đa khoang, keo ép góc chuyên dụng và kính hộp giúp giảm tới 30% điện năng làm mát cho ngôi nhà.',
                content: 'Nhờ công nghệ ép góc tự động bằng máy thủy lực và hệ phụ kiện Kinlong khóa đa điểm ép chặt cánh cửa vào khung bao, cửa nhôm Xingfa hạn chế tối đa sự thất thoát hơi lạnh từ điều hòa ra bên ngoài, đồng thời giảm thiểu tiếng ồn xe cộ ở các tuyến đường lớn, mang lại không gian nghỉ ngơi yên tĩnh.'
            },
            {
                id: 'n4',
                tag: 'Báo giá & Thi công',
                date: '05/11/2026',
                driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                title: 'Cách tính diện tích và báo giá cửa nhôm Xingfa chuẩn xác không phát sinh',
                excerpt: 'Hướng dẫn khách hàng cách dự toán chi phí làm cửa nhôm Xingfa trọn gói theo m² cửa cộng bộ phụ kiện đồng bộ chính hãng.',
                content: 'Công thức chuẩn để tính giá 1 bộ cửa nhôm Xingfa = (Chiều rộng x Chiều cao) x Đơn giá 1m² theo hệ cửa + Đơn giá bộ phụ kiện Kinlong tương ứng. Tại Đại Phát Windows, toàn bộ chi phí khảo sát, thiết kế bản vẽ và vận chuyển lắp đặt tại TP Huế được hỗ trợ tối đa, báo giá minh bạch ngay từ đầu và cam kết không phát sinh.'
            }
        ];

        function formatVND(num) {
            return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.');
        }

        /**
         * Render danh sách sản phẩm - Tối ưu 2 cột Mobile, tên sản phẩm không bị tràn/cắt chữ
         */
        function renderProducts(filterKey) {
            const grid = document.getElementById('productGrid');
            if (!grid) return;

            let filtered = PRODUCTS;
            if (filterKey === 'all') {
                // Mặc định hiển thị 8 sản phẩm nổi bật (6 mẫu Xingfa thật + 2 mẫu bán chạy) cho cân đối 2 cột Mobile & 4 cột PC
                filtered = PRODUCTS.slice(0, 8);
            } else {
                filtered = PRODUCTS.filter(p => p.subcats.includes(filterKey) || p.category === filterKey);
            }

            if (filtered.length === 0) {
                filtered = PRODUCTS.slice(0, 6);
            }

            grid.innerHTML = filtered.map(item => `
                <article class="group bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-lg transition-all overflow-hidden flex flex-col">
                    <!-- Ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-brand-sale text-white text-[11px] sm:text-xs font-extrabold shadow-sm">
                            -${item.discount}%
                        </span>
                        <img
                            src="https://lh3.googleusercontent.com/d/${item.driveId}=w700"
                            onerror="handleDriveImgError(this, '${item.driveId}', '${item.name}')"
                            alt="${item.name}"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>

                    <!-- Thông tin sản phẩm: Tên sản phẩm đầy đủ, không cắt chữ trên điện thoại 2 cột -->
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                                ${item.name}
                            </h3>
                        </div>

                        <div class="space-y-2 pt-1">
                            <!-- Giá gốc gạch ngang & Giá khuyến mãi nổi bật -->
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-[13px] sm:text-base font-extrabold text-brand-sale">
                                    ${formatVND(item.salePrice)} ${item.unit}
                                </span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                                    ${formatVND(item.originalPrice)} ₫
                                </span>
                            </div>

                            <!-- Nút hành động -->
                            <div class="grid grid-cols-2 gap-1.5">
                                <button type="button" onclick="openProductModal('${item.id}')" class="py-1.5 px-2 rounded-lg border border-brand-primary/30 text-brand-primary hover:bg-brand-light text-[11px] sm:text-xs font-semibold transition-colors">
                                    Xem nhanh
                                </button>
                                <button type="button" onclick="selectProductForQuote('${item.name.replace(/'/g, "\\'")}')" class="py-1.5 px-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-[11px] sm:text-xs font-semibold transition-colors">
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Lọc sản phẩm theo danh mục & đồng bộ trạng thái tab
         */
        function filterProducts(filterKey) {
            renderProducts(filterKey);

            // Cập nhật trạng thái nút Tab
            const tabs = document.querySelectorAll('.prod-tab');
            tabs.forEach(tab => {
                const isMatch = tab.dataset.filter === filterKey ||
                    (filterKey.startsWith('xingfa-') && tab.dataset.filter === 'cua-nhom-xingfa');
                if (isMatch) {
                    tab.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary');
                    tab.classList.remove('bg-white', 'text-slate-700', 'border-slate-300');
                } else {
                    tab.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary');
                    tab.classList.add('bg-white', 'text-slate-700', 'border-slate-300');
                }
            });
        }

        /**
         * Render danh mục bài viết trang chủ
         */
        function renderNews() {
            const grid = document.getElementById('newsGrid');
            if (!grid) return;

            grid.innerHTML = NEWS_ARTICLES.map(art => `
                <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/${art.driveId}=w700"
                            onerror="handleDriveImgError(this, '${art.driveId}', 'Tin Tuc Dai Phat')"
                            alt="${art.title}"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-3">
                        <div>
                            <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
                                <span class="font-semibold text-brand-accent">${art.tag}</span>
                                <span>${art.date}</span>
                            </div>
                            <h3 class="text-sm font-bold text-brand-primary leading-snug group-hover:text-brand-accent transition-colors">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <button type="button" onclick="openNewsModal('${art.id}')" class="self-start text-xs font-bold text-brand-primary hover:text-brand-accent inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        /**
         * Modal xem nhanh sản phẩm
         */
        function openProductModal(productId) {
            const item = PRODUCTS.find(p => p.id === productId);
            if (!item) return;

            const body = document.getElementById('detailModalBody');
            body.innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
                    <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[4/3]">
                        <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-brand-sale text-white text-xs font-extrabold">-${item.discount}%</span>
                        <img
                            src="https://lh3.googleusercontent.com/d/${item.driveId}=w900"
                            onerror="handleDriveImgError(this, '${item.driveId}', '${item.name}')"
                            alt="${item.name}"
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="space-y-3">
                        <div class="text-xs font-bold uppercase text-brand-accent">Sản phẩm chính hãng Đại Phát Windows</div>
                        <h3 class="text-lg font-extrabold text-brand-primary leading-snug">${item.name}</h3>
                        <div class="flex items-baseline gap-2.5">
                            <span class="text-xl font-extrabold text-brand-sale">${formatVND(item.salePrice)} ${item.unit}</span>
                            <span class="text-sm text-slate-400 line-through">${formatVND(item.originalPrice)} ₫</span>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${item.specs}</p>
                        <div class="pt-2 flex flex-col gap-2">
                            <button type="button" onclick="closeDetailModal(); selectProductForQuote('${item.name.replace(/'/g, "\\'")}')" class="w-full py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm transition-colors">
                                Yêu cầu báo giá mẫu cửa này
                            </button>
                            <a href="tel:0763743456" class="w-full py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-bold text-sm text-center transition-colors">
                                Gọi tư vấn nhanh: 0763.743.456
                            </a>
                        </div>
                    </div>
                </div>
            `;
            showDetailModal();
        }

        /**
         * Modal đọc chi tiết bài viết
         */
        function openNewsModal(articleId) {
            const art = NEWS_ARTICLES.find(a => a.id === articleId);
            if (!art) return;

            const body = document.getElementById('detailModalBody');
            body.innerHTML = `
                <div class="space-y-4">
                    <div class="flex items-center gap-3 text-xs text-slate-500">
                        <span class="px-2.5 py-0.5 rounded-full bg-brand-light text-brand-primary font-bold">${art.tag}</span>
                        <span>Ngày đăng: ${art.date}</span>
                    </div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand-primary leading-snug">${art.title}</h3>
                    <div class="aspect-[16/9] w-full rounded-xl overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/${art.driveId}=w900"
                            onerror="handleDriveImgError(this, '${art.driveId}', 'Tin Tuc')"
                            alt="${art.title}"
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
                    <div class="p-4 rounded-xl bg-brand-light border border-brand-primary/15 text-xs sm:text-sm text-slate-700">
                        <strong>Liên hệ tư vấn miễn phí:</strong> CÔNG TY TNHH MTV XÂY DỰNG SẢN XUẤT ĐẠI PHÁT WINDOWS – TDP Thuỷ Phú, Phường Hóa Châu, TP Huế • Hotline: <a href="tel:0763743456" class="font-bold text-brand-accent">0763.743.456</a>.
                    </div>
                </div>
            `;
            showDetailModal();
        }

        function showDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /**
         * Chọn sản phẩm và cuộn mượt xuống Form báo giá trang chủ
         */
        function selectProductForQuote(productName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = 'Tôi cần báo giá sản phẩm: ' + productName;
            }
            const section = document.getElementById('form-bao-gia');
            if (section) {
                section.scrollIntoView({ behavior: 'smooth' });
            }
        }

        /**
         * Điều khiển Drawer Menu Điện thoại
         */
        function openMobileDrawer() {
            document.getElementById('mobileDrawerOverlay').classList.remove('hidden');
            document.getElementById('mobileDrawer').classList.remove('-translate-x-full');
        }

        function closeMobileDrawer() {
            document.getElementById('mobileDrawerOverlay').classList.add('hidden');
            document.getElementById('mobileDrawer').classList.add('-translate-x-full');
        }

        function toggleMobileSubmenu(id, btn) {
            const sub = document.getElementById(id);
            const icon = btn.querySelector('i');
            if (sub) {
                sub.classList.toggle('hidden');
                if (icon) icon.classList.toggle('rotate-180');
            }
        }

        /**
         * Điều khiển 2 Banner Tự Trượt chuyên nghiệp (có hỗ trợ vuốt cảm ứng mobile)
         */
        function initHeroBanner() {
            const slides = document.querySelectorAll('#heroBanner .banner-slide');
            const dots = document.querySelectorAll('#heroBanner .banner-dot');
            const prevBtn = document.getElementById('bannerPrev');
            const nextBtn = document.getElementById('bannerNext');
            const bannerStage = document.getElementById('heroBanner');
            let currentIndex = 0;
            let autoTimer = null;

            function showSlide(index) {
                currentIndex = (index + slides.length) % slides.length;
                slides.forEach((s, i) => s.classList.toggle('is-active', i === currentIndex));
                dots.forEach((d, i) => {
                    if (i === currentIndex) {
                        d.classList.add('w-7', 'bg-brand-accent');
                        d.classList.remove('w-2.5', 'bg-white/50');
                    } else {
                        d.classList.remove('w-7', 'bg-brand-accent');
                        d.classList.add('w-2.5', 'bg-white/50');
                    }
                });
            }

            function startAuto() {
                stopAuto();
                autoTimer = setInterval(() => showSlide(currentIndex + 1), 5000);
            }

            function stopAuto() {
                if (autoTimer) clearInterval(autoTimer);
            }

            if (prevBtn) prevBtn.addEventListener('click', () => { showSlide(currentIndex - 1); startAuto(); });
            if (nextBtn) nextBtn.addEventListener('click', () => { showSlide(currentIndex + 1); startAuto(); });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    showSlide(parseInt(dot.dataset.index, 10));
                    startAuto();
                });
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại
            let touchStartX = 0;
            bannerStage.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            bannerStage.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    if (diff < 0) showSlide(currentIndex + 1);
                    else showSlide(currentIndex - 1);
                    startAuto();
                }
            }, { passive: true });

            startAuto();
        }

        /**
         * Khởi chạy toàn bộ tính năng sau khi tải trang
         */
        window.addEventListener('DOMContentLoaded', function () {
            renderProducts('all');
            renderNews();
            initHeroBanner();

            // Sự kiện mở/đóng menu điện thoại
            document.getElementById('mobileMenuBtn').addEventListener('click', openMobileDrawer);
            document.getElementById('closeMobileDrawer').addEventListener('click', closeMobileDrawer);
            document.getElementById('mobileDrawerOverlay').addEventListener('click', closeMobileDrawer);
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', closeMobileDrawer);
            });

            // Đóng modal khi bấm nền tối
            document.getElementById('detailModal').addEventListener('click', function (e) {
                if (e.target === this) closeDetailModal();
            });

            // Xử lý gửi form báo giá trang chủ (không dùng alert)
            const quoteForm = document.getElementById('quoteRequestForm');
            quoteForm.addEventListener('submit', function (e) {
                e.preventDefault();
                const name = document.getElementById('qName').value.trim();
                const phone = document.getElementById('qPhone').value.trim();
                const cat = document.getElementById('qCategory').value;
                const successBox = document.getElementById('quoteSuccessBox');
                const successText = document.getElementById('quoteSuccessText');

                if (successBox && successText) {
                    successText.textContent = `Cảm ơn anh/chị ${name}! Yêu cầu báo giá "${cat}" (SĐT: ${phone}) đã được gửi tới Đại Phát Windows. Kỹ thuật viên sẽ liên hệ lại sớm nhất.`;
                    successBox.classList.remove('hidden');
                }
                quoteForm.reset();
            });
        });
    </script>
</body>
</html>
