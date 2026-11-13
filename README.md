<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH QUẢNG CÁO VINH DESIGN - Thiết Kế & Thi Công Bảng Hiệu Quảng Cáo Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH QUẢNG CÁO VINH DESIGN (vinhdesign.com) - Chuyên thiết kế, thi công bảng hiệu quảng cáo, chữ nổi Inox, Mica, đèn LED, cắt khắc CNC Laser, nội thất showroom tại Đà Nẵng. Hotline: 0901.149.099">
    <meta name="keywords" content="Vinh Design, vinhdesign.com, làm bảng hiệu Đà Nẵng, quảng cáo Đà Nẵng, chữ nổi inox Đà Nẵng, cắt CNC laser Đà Nẵng, K160/53 Trần Cao Vân">
    <link rel="canonical" href="https://vinhdesign.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://vinhdesign.com/">
    <meta property="og:site_name" content="vinhdesign.com - CÔNG TY TNHH QUẢNG CÁO VINH DESIGN">
    <meta property="og:title" content="CÔNG TY TNHH QUẢNG CÁO VINH DESIGN - Thi Công Quảng Cáo & Nội Thất Đà Nẵng">
    <meta property="og:description" content="Chuyên thiết kế & thi công bảng hiệu quảng cáo, chữ nổi Mica - Inox, mặt dựng Alu, cắt khắc CNC - Laser, in phun khổ lớn tại Đà Nẵng. Đ/c: K160/53 Trần Cao Vân, Thanh Khê, Đà Nẵng. Hotline: 0901.149.099">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w1200">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH QUẢNG CÁO VINH DESIGN - vinhdesign.com">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w200">

    <!-- Tailwind CSS & Font Awesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

    <style>
        /* Reset chống tràn viền và chống lệch sang phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f6f7f9;
            color: #222222;
            scroll-behavior: smooth;
        }

        /* Màu chủ đạo theo Logo Vinh Design & mẫu Phúc Lợi Việt */
        :root {
            --vinh-red: #c8102e;
            --vinh-red-dark: #9e0b22;
            --vinh-navy: #0e2545;
            --vinh-blue: #163b6d;
            --vinh-gold: #f59e0b;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh danh mục trên máy tính: từng tên danh mục viết liền trên 1 hàng (nowrap),
           chữ nhỏ gọn để nằm trên cùng 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy chữ */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 6px;
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 700;
            letter-spacing: 0.1px;
            padding: 7px 9px;
            border-radius: 4px;
            transition: all 0.2s ease;
            color: #ffffff;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            background-color: var(--vinh-red);
            color: #ffffff;
        }

        /* Danh mục nhanh ở trang chủ (nhỏ gọn, viết liền trên 1 hàng mỗi mục) */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 11px;
            border-radius: 5px;
            border: 1px solid #e2e8f0;
            background: #ffffff;
            color: #1e293b;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }
        .home-cat-pill:hover, .home-cat-pill.active {
            background: var(--vinh-red);
            color: #ffffff;
            border-color: var(--vinh-red);
        }

        /* Tiêu đề Section kiểu Flatsome / Phúc Lợi Việt */
        .section-title-wrap {
            border-bottom: 2px solid var(--vinh-red);
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            gap: 8px;
            margin-bottom: 14px;
        }
        .section-title-main {
            background: var(--vinh-red);
            color: #ffffff;
            font-weight: 700;
            font-size: 13.5px;
            padding: 8px 14px;
            text-transform: uppercase;
            letter-spacing: 0.2px;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
            display: inline-flex;
            align-items: center;
            gap: 7px;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 15px;
                padding: 9px 18px;
            }
        }

        /* Card sản phẩm / dự án đơn giản chuẩn Flatsome box, tên không bị cắt hay tràn chữ */
        .ux-product-box {
            background: #ffffff;
            border: 1px solid #e5e7eb;
            border-radius: 6px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: box-shadow 0.2s ease, transform 0.2s ease;
        }
        .ux-product-box:hover {
            box-shadow: 0 8px 20px rgba(14, 37, 69, 0.12);
            transform: translateY(-2px);
        }
        .ux-box-image {
            width: 100%;
            aspect-ratio: 4 / 3;
            background: #f1f5f9;
            overflow: hidden;
        }
        .ux-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.35s ease;
        }
        .ux-product-box:hover .ux-box-image img {
            transform: scale(1.04);
        }
        .ux-box-text {
            padding: 9px 10px 11px;
            display: flex;
            flex-direction: column;
            flex: 1;
            justify-content: space-between;
        }
        .ux-box-title {
            font-size: 13px;
            line-height: 1.42;
            font-weight: 700;
            color: #1e293b;
            white-space: normal !important;
            word-break: break-word !important;
            overflow: visible !important;
            display: block;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .ux-box-title {
                font-size: 14px;
            }
        }
        .ux-product-box:hover .ux-box-title {
            color: var(--vinh-red);
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 16, 46, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 16, 46, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 16, 46, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

<!-- ==========================================
     #WRAPPER CHUẨN FLATSOME UX BUILDER
     ========================================== -->
<div id="wrapper" class="w-full overflow-x-hidden">

    <!-- ==========================================
         HEADER (#header) - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN
         ========================================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        <!-- Topbar thông tin địa chỉ & website -->
        <div class="bg-[#0e2545] text-white text-[11.5px] py-1.5 border-b border-white/10">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 flex-wrap">
                    <span class="inline-flex items-center gap-1.5">
                        <i class="fa-solid fa-building text-amber-400"></i>
                        <strong class="tracking-wide">CÔNG TY TNHH QUẢNG CÁO VINH DESIGN</strong>
                    </span>
                    <span class="hidden sm:inline text-white/40">|</span>
                    <span class="inline-flex items-center gap-1 text-slate-200">
                        <i class="fa-solid fa-location-dot text-red-400"></i>
                        K160/53 Trần Cao Vân, Phường Thanh Khê, TP Đà Nẵng
                    </span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-slate-200">
                    <span class="inline-flex items-center gap-1">
                        <i class="fa-solid fa-globe text-amber-400"></i>
                        Website: <strong class="text-white">vinhdesign.com</strong>
                    </span>
                    <span class="inline-flex items-center gap-1">
                        <i class="fa-solid fa-clock text-emerald-400"></i>
                        Làm việc: T2 - CN (07:30 - 18:00)
                    </span>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm (Không có nút gọi ngay trên header) -->
        <div class="bg-white py-2.5 border-b border-slate-200">
            <div class="flatsome-container flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink-0 group">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-md border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
                        <img
                            src="https://lh3.googleusercontent.com/d/1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc"
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w400';"
                            alt="Logo Công Ty TNHH Quảng Cáo Vinh Design"
                            class="w-full h-full object-contain"
                        >
                    </div>
                    <div class="min-w-0">
                        <div class="text-[13px] sm:text-[15px] md:text-[17px] font-black text-[#c8102e] leading-tight tracking-tight uppercase truncate">
                            QUẢNG CÁO VINH DESIGN
                        </div>
                        <div class="text-[10.5px] sm:text-[11.5px] text-[#0e2545] font-medium truncate">
                            vinhdesign.com • Thiết Kế & Thi Công Quảng Cáo Đà Nẵng
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm trên máy tính -->
                <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input
                            id="searchInputDesktop"
                            type="text"
                            placeholder="Tìm bảng hiệu Alu, chữ nổi Inox, cắt CNC, hộp đèn..."
                            oninput="filterProductsBySearch(this.value)"
                            class="w-full pl-3.5 pr-9 py-1.5 text-[13px] border border-slate-300 rounded-md focus:outline-none focus:border-[#c8102e]"
                        >
                        <span class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </span>
                    </div>
                </div>

                <!-- Cam kết ngắn gọn trên máy tính (Không để nút gọi ngay tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-4 text-[12px] text-slate-700 shrink-0">
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-Compass-drafting text-[#c8102e] text-sm"></i>
                        <span>Khảo sát & Thiết kế 3D</span>
                    </div>
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-industry text-[#0e2545] text-sm"></i>
                        <span>Xưởng SX Trực Tiếp Đà Nẵng</span>
                    </div>
                </div>

                <!-- Nút mở menu Danh mục trên điện thoại -->
                <button
                    type="button"
                    onclick="toggleMobileMenu()"
                    aria-label="Mở danh mục"
                    class="lg:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded bg-[#0e2545] text-white text-xs font-bold shrink-0"
                >
                    <i class="fa-solid fa-bars"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>
        </div>

        <!-- Thanh Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng mỗi mục, nằm trên 1 hàng hoặc xuống hàng 2 nguyên cụm -->
        <nav class="hidden lg:block bg-[#0e2545] border-b-2 border-[#c8102e]">
            <div class="flatsome-container py-1">
                <div class="desktop-nav-list">
                    <a href="#top" class="desktop-nav-item active">
                        <i class="fa-solid fa-house text-[11px]"></i> TRANG CHỦ
                    </a>
                    <a href="#sec-gioi-thieu" class="desktop-nav-item">
                        GIỚI THIỆU
                    </a>
                    <a href="#sec-quang-cao" class="desktop-nav-item">
                        THI CÔNG QUẢNG CÁO
                    </a>
                    <a href="#sec-chu-noi" class="desktop-nav-item">
                        CHỮ NỔI MICA - INOX
                    </a>
                    <a href="#sec-cnc-laser" class="desktop-nav-item">
                        CẮT KHẮC CNC – LASER
                    </a>
                    <a href="#sec-noi-that" class="desktop-nav-item">
                        SHOWROOM NỘI NGOẠI THẤT
                    </a>
                    <a href="#sec-in-phun" class="desktop-nav-item">
                        IN PHUN KHỔ LỚN
                    </a>
                    <a href="#sec-du-an-da-nang" class="desktop-nav-item">
                        DỰ ÁN ĐÀ NẴNG
                    </a>
                    <a href="#sec-doi-tac" class="desktop-nav-item">
                        ĐỐI TÁC
                    </a>
                    <a href="#sec-bai-viet" class="desktop-nav-item">
                        TIN TỨC
                    </a>
                    <a href="#sec-bao-gia" class="desktop-nav-item">
                        BÁO GIÁ & LIÊN HỆ
                    </a>
                </div>
            </div>
        </nav>

        <!-- Thanh Danh Mục Điện Thoại (Cuộn ngang gọn đẹp + Drawer) -->
        <div class="lg:hidden bg-[#0e2545] border-b border-[#c8102e] px-2 py-1.5 overflow-x-auto no-scrollbar">
            <div class="flex items-center gap-1.5 w-max">
                <a href="#sec-quang-cao" class="text-[11px] font-bold text-white bg-[#c8102e] px-2.5 py-1 rounded whitespace-nowrap">Thi Công Quảng Cáo</a>
                <a href="#sec-chu-noi" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">Chữ Nổi Inox - Mica</a>
                <a href="#sec-cnc-laser" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">Cắt CNC – Laser</a>
                <a href="#sec-noi-that" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">Nội Thất Showroom</a>
                <a href="#sec-in-phun" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">In Phun Khổ Lớn</a>
                <a href="#sec-du-an-da-nang" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">Dự Án Đà Nẵng</a>
                <a href="#sec-bao-gia" class="text-[11px] font-medium text-white bg-white/10 px-2.5 py-1 rounded whitespace-nowrap">Báo Giá</a>
            </div>
        </div>

        <!-- Menu mở rộng trên điện thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg">
            <div class="p-3 space-y-2">
                <div class="relative">
                    <input
                        type="text"
                        placeholder="Tìm kiếm sản phẩm, dịch vụ..."
                        oninput="filterProductsBySearch(this.value)"
                        class="w-full pl-3 pr-8 py-1.5 text-xs border border-slate-300 rounded"
                    >
                    <i class="fa-solid fa-magnifying-glass absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-[#0e2545]">
                    <a href="#sec-quang-cao" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">1. Thi Công Quảng Cáo</a>
                    <a href="#sec-chu-noi" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">2. Chữ Nổi Quảng Cáo</a>
                    <a href="#sec-cnc-laser" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">3. Cắt Khắc CNC - Laser</a>
                    <a href="#sec-noi-that" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">4. Nội Thất Showroom</a>
                    <a href="#sec-in-phun" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">5. In Phun Khổ Lớn</a>
                    <a href="#sec-du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">6. Dự Án Đà Nẵng</a>
                    <a href="#sec-doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">7. Đối Tác Khách Hàng</a>
                    <a href="#sec-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:bg-red-50 hover:text-[#c8102e]">8. Yêu Cầu Báo Giá</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         MAIN CONTENT (#main)
         ========================================== -->
    <main id="main" class="w-full py-3 md:py-4 space-y-6">

        <!-- ==========================================
             SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             - Thiết kế riêng Banner Máy Tính (md:block) và Banner Điện Thoại (md:hidden)
             - Chữ bên trong ảnh được chỉnh nhỏ gọn, nằm gọn hoàn toàn trong khung, không tràn viền
             ========================================== -->
        <section class="section" id="top">
            <div class="flatsome-container">
                <div class="relative w-full rounded-lg overflow-hidden shadow-md border border-slate-200 bg-[#0e2545]">

                    <!-- ==================== BANNER MÁY TÍNH (CHỈ HIỂN THỊ TRÊN MÁY TÍNH >= 768px) ==================== -->
                    <!-- Cả 2 slide có chiều cao cố định bằng nhau h-[340px] lg:h-[380px] -->
                    <div id="desktopBannerWrapper" class="hidden md:block relative w-full h-[340px] lg:h-[380px] overflow-hidden">

                        <!-- SLIDE 1 MÁY TÍNH -->
                        <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-[#091931] via-[#0e2545] to-[#7f091d] flex items-center">
                            <div class="w-full h-full px-8 lg:px-12 py-6 grid grid-cols-12 gap-6 items-center">
                                <!-- Cột chữ bên trái: chữ nhỏ gọn, nằm trọn trong khung banner -->
                                <div class="col-span-7 text-white space-y-2.5 pr-2">
                                    <div class="inline-flex items-center gap-2 bg-[#c8102e] text-white text-[11px] font-bold px-3 py-1 rounded uppercase tracking-wider">
                                        <span>VINHDESIGN.COM • QUẢNG CÁO & NỘI THẤT ĐÀ NẴNG</span>
                                    </div>
                                    <h1 class="text-[20px] lg:text-[25px] font-black leading-snug uppercase text-white">
                                        CÔNG TY TNHH QUẢNG CÁO <span class="text-amber-400">VINH DESIGN</span>
                                    </h1>
                                    <p class="text-[13px] lg:text-[14px] text-slate-200 leading-relaxed max-w-xl">
                                        Chuyên thiết kế & thi công trọn gói: Mặt dựng Alu, Bảng hiệu Chữ nổi Inox - Mica đèn LED, Hộp đèn quảng cáo, Cắt khắc CNC - Laser & Nội thất Showroom tại TP. Đà Nẵng.
                                    </p>
                                    <div class="grid grid-cols-2 gap-2 pt-1 text-[12px] text-amber-300 font-semibold max-w-lg">
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-emerald-400"></i> Khảo sát & Thiết kế 3D miễn phí</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-emerald-400"></i> Gia công trực tiếp tại xưởng</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-emerald-400"></i> Thi công nhanh - Đúng tiến độ</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-emerald-400"></i> Bảo hành dài hạn 12 - 24 tháng</div>
                                    </div>
                                    <div class="pt-2 flex flex-wrap items-center gap-3 text-[12px]">
                                        <span class="bg-white/10 border border-white/20 px-3 py-1.5 rounded text-white font-semibold">
                                            <i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i> Hotline: <strong>0901.149.099</strong>
                                        </span>
                                        <span class="bg-white/10 border border-white/20 px-3 py-1.5 rounded text-slate-200">
                                            <i class="fa-solid fa-location-dot text-red-400 mr-1"></i> K160/53 Trần Cao Vân, P. Thanh Khê, TP. Đà Nẵng
                                        </span>
                                    </div>
                                </div>
                                <!-- Cột ảnh công trình thực tế bên phải -->
                                <div class="col-span-5 grid grid-cols-2 gap-2.5 h-[260px] lg:h-[290px]">
                                    <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                        <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w800';" alt="Công trình Vinh Design 1" class="w-full h-full object-cover">
                                    </div>
                                    <div class="grid grid-rows-2 gap-2.5 h-full">
                                        <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                            <img src="https://lh3.googleusercontent.com/d/1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL&sz=w800';" alt="Công trình Vinh Design 2" class="w-full h-full object-cover">
                                        </div>
                                        <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                            <img src="https://lh3.googleusercontent.com/d/1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D&sz=w800';" alt="Công trình Vinh Design 3" class="w-full h-full object-cover">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- SLIDE 2 MÁY TÍNH (Kích thước bằng hệt Slide 1) -->
                        <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#132a4a] via-[#1b3b66] to-[#9e0b22] flex items-center">
                            <div class="w-full h-full px-8 lg:px-12 py-6 grid grid-cols-12 gap-6 items-center">
                                <div class="col-span-7 text-white space-y-2.5 pr-2">
                                    <div class="inline-flex items-center gap-2 bg-amber-500 text-slate-950 text-[11px] font-extrabold px-3 py-1 rounded uppercase tracking-wider">
                                        <span>XƯỞNG GIA CÔNG QUẢNG CÁO & CNC LASER HIỆN ĐẠI</span>
                                    </div>
                                    <h2 class="text-[20px] lg:text-[25px] font-black leading-snug uppercase text-white">
                                        GIẢI PHÁP BẢNG HIỆU & <span class="text-amber-400">SHOWROOM CHUYÊN NGHIỆP</span>
                                    </h2>
                                    <p class="text-[13px] lg:text-[14px] text-slate-200 leading-relaxed max-w-xl">
                                        Hệ thống máy cắt CNC, Laser Fiber, máy uốn chữ Inox tự động và máy in phun khổ lớn đời mới. Đáp ứng mọi công trình bảng hiệu chuỗi cửa hàng, tòa nhà, doanh nghiệp tại Đà Nẵng.
                                    </p>
                                    <div class="grid grid-cols-2 gap-2 pt-1 text-[12px] text-amber-300 font-semibold max-w-lg">
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-star text-amber-400"></i> Chữ nổi Inox vàng gương, Mica LED</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-star text-amber-400"></i> Ốp mặt dựng Alu composite cao cấp</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-star text-amber-400"></i> Cắt khắc CNC - Laser chính xác cao</div>
                                        <div class="flex items-center gap-1.5"><i class="fa-solid fa-star text-amber-400"></i> Giá gốc tận xưởng - Không qua trung gian</div>
                                    </div>
                                    <div class="pt-2 flex flex-wrap items-center gap-3 text-[12px]">
                                        <span class="bg-[#c8102e] px-3 py-1.5 rounded text-white font-semibold">
                                            <i class="fa-solid fa-headset mr-1"></i> Tư vấn & Báo giá 24/7: <strong>0901.149.099</strong>
                                        </span>
                                        <span class="bg-white/10 border border-white/20 px-3 py-1.5 rounded text-slate-200">
                                            <i class="fa-solid fa-globe text-amber-400 mr-1"></i> Website: <strong>vinhdesign.com</strong>
                                        </span>
                                    </div>
                                </div>
                                <div class="col-span-5 grid grid-cols-2 gap-2.5 h-[260px] lg:h-[290px]">
                                    <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                        <img src="https://lh3.googleusercontent.com/d/1Y8AllqlCuU370XwJQ67sHapavPodpCwR" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y8AllqlCuU370XwJQ67sHapavPodpCwR&sz=w800';" alt="Công trình Vinh Design 4" class="w-full h-full object-cover">
                                    </div>
                                    <div class="grid grid-rows-2 gap-2.5 h-full">
                                        <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                            <img src="https://lh3.googleusercontent.com/d/1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z&sz=w800';" alt="Công trình Vinh Design 5" class="w-full h-full object-cover">
                                        </div>
                                        <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg h-full">
                                            <img src="https://lh3.googleusercontent.com/d/111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr&sz=w800';" alt="Công trình Vinh Design 6" class="w-full h-full object-cover">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- ==================== BANNER ĐIỆN THOẠI (THIẾT KẾ RIÊNG KHÁC VỚI MÁY TÍNH - CHỈ HIỂN THỊ < 768px) ==================== -->
                    <!-- Cả 2 slide điện thoại có kích thước bằng nhau tuyệt đối h-[225px], chữ nhỏ gọn nằm hoàn toàn trong khung -->
                    <div id="mobileBannerWrapper" class="block md:hidden relative w-full h-[225px] overflow-hidden">

                        <!-- SLIDE 1 ĐIỆN THOẠI -->
                        <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-br from-[#091931] via-[#0e2545] to-[#8a0c20] p-3 flex flex-col justify-between">
                            <div class="flex items-center justify-between gap-2">
                                <span class="bg-[#c8102e] text-white text-[9.5px] font-bold px-2 py-0.5 rounded uppercase">
                                    vinhdesign.com • Đà Nẵng
                                </span>
                                <span class="text-amber-300 text-[10px] font-bold">
                                    <i class="fa-solid fa-phone"></i> 0901.149.099
                                </span>
                            </div>

                            <div class="grid grid-cols-12 gap-2 items-center my-auto py-1">
                                <div class="col-span-7 space-y-1">
                                    <div class="text-[12.5px] font-black text-white uppercase leading-tight">
                                        CÔNG TY QUẢNG CÁO <span class="text-amber-400">VINH DESIGN</span>
                                    </div>
                                    <p class="text-[10.5px] text-slate-200 leading-snug">
                                        Thi công Bảng hiệu Alu, Chữ nổi Inox - Mica đèn LED, Cắt CNC Laser, Nội thất Showroom.
                                    </p>
                                    <div class="text-[10px] text-emerald-300 font-semibold">
                                        ✓ Miễn phí thiết kế • Giá tận xưởng
                                    </div>
                                </div>
                                <div class="col-span-5 h-[112px] rounded overflow-hidden border border-white/30">
                                    <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w600';" alt="Banner Mobile 1" class="w-full h-full object-cover">
                                </div>
                            </div>

                            <div class="text-[9.5px] text-slate-200 bg-black/25 px-2 py-1 rounded truncate">
                                <i class="fa-solid fa-location-dot text-red-400 mr-1"></i>Đ/c: K160/53 Trần Cao Vân, P. Thanh Khê, Đà Nẵng
                            </div>
                        </div>

                        <!-- SLIDE 2 ĐIỆN THOẠI (Kích thước bằng hệt Slide 1: h-[225px]) -->
                        <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-br from-[#132a4a] via-[#193863] to-[#9e0b22] p-3 flex flex-col justify-between">
                            <div class="flex items-center justify-between gap-2">
                                <span class="bg-amber-400 text-slate-950 text-[9.5px] font-extrabold px-2 py-0.5 rounded uppercase">
                                    Xưởng Sản Xuất Trực Tiếp
                                </span>
                                <span class="text-white text-[10px] font-bold">
                                    Hotline: 0901.149.099
                                </span>
                            </div>

                            <div class="grid grid-cols-12 gap-2 items-center my-auto py-1">
                                <div class="col-span-7 space-y-1">
                                    <div class="text-[12.5px] font-black text-amber-300 uppercase leading-tight">
                                        GIA CÔNG CHỮ NỔI & CẮT KHẮC CNC LASER
                                    </div>
                                    <p class="text-[10.5px] text-slate-100 leading-snug">
                                        Chữ Inox vàng gương, hộp đèn siêu mỏng, Pano, In bạt khổ lớn sắc nét bền đẹp.
                                    </p>
                                    <div class="text-[10px] text-amber-200 font-semibold">
                                        ✓ Bảo hành uy tín 12 - 24 tháng
                                    </div>
                                </div>
                                <div class="col-span-5 h-[112px] rounded overflow-hidden border border-white/30">
                                    <img src="https://lh3.googleusercontent.com/d/1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi&sz=w600';" alt="Banner Mobile 2" class="w-full h-full object-cover">
                                </div>
                            </div>

                            <div class="text-[9.5px] text-slate-200 bg-black/25 px-2 py-1 rounded truncate">
                                <i class="fa-solid fa-bolt text-amber-400 mr-1"></i>Thi công trọn gói nhanh chóng khắp TP. Đà Nẵng
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều khiển & Chấm chỉ báo Slide -->
                    <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="
                        absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-[#c8102e] text-white flex items-center justify-center text-xs transition">
                        <i class="fa-solid fa-chevron-left"></i>
                    </button>
                    <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="
                        absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-[#c8102e] text-white flex items-center justify-center text-xs transition">
                        <i class="fa-solid fa-chevron-right"></i>
                    </button>
                    <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" aria-label="Slide 1" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                        <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" aria-label="Slide 2" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             THANH DANH MỤC SẢN PHẨM DỊCH VỤ TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP TRÊN PC & MOBILE)
             ========================================== -->
        <section class="section">
            <div class="flatsome-container">
                <div class="bg-white border border-slate-200 rounded-lg p-3 shadow-xs">
                    <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2">
                        <button type="button" onclick="filterHomeCategory('all', this)" class="home-cat-pill active">
                            <i class="fa-solid fa-border-all text-[11px]"></i> Tất Cả Hạng Mục
                        </button>
                        <button type="button" onclick="filterHomeCategory('quang-cao', this)" class="home-cat-pill">
                            <i class="fa-solid fa-sign-hanging text-[11px]"></i> Thi Công Quảng Cáo
                        </button>
                        <button type="button" onclick="filterHomeCategory('chu-noi', this)" class="home-cat-pill">
                            <i class="fa-solid fa-font text-[11px]"></i> Chữ Nổi Quảng Cáo
                        </button>
                        <button type="button" onclick="filterHomeCategory('cnc-laser', this)" class="home-cat-pill">
                            <i class="fa-solid fa-wand-magic-sparkles text-[11px]"></i> CNC – Cắt Laser – Uốn Inox
                        </button>
                        <button type="button" onclick="filterHomeCategory('noi-that', this)" class="home-cat-pill">
                            <i class="fa-solid fa-store text-[11px]"></i> Showroom Nội Ngoại Thất
                        </button>
                        <button type="button" onclick="filterHomeCategory('in-phun', this)" class="home-cat-pill">
                            <i class="fa-solid fa-print text-[11px]"></i> In Phun Khổ Lớn
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 2: DỰ ÁN THI CÔNG QUẢNG CÁO TẠI ĐÀ NẴNG TIÊU BIỂU ĐÃ THỰC HIỆN
             - Sử dụng 14 ảnh thực tế từ Google Drive của khách hàng
             - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
             - Không gắn nhãn dán đè lên ảnh, tên sản phẩm hiển thị đầy đủ không tràn/cắt chữ
             ========================================== -->
        <section class="section" id="sec-du-an-da-nang">
            <div class="flatsome-container">
                <div class="section-title-wrap">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-award"></i>
                        <span>DỰ ÁN THI CÔNG QUẢNG CÁO TẠI ĐÀ NẴNG TIÊU BIỂU</span>
                    </h2>
                    <a href="#sec-bao-gia" class="text-xs font-bold text-[#0e2545] hover:text-[#c8102e] pr-1">
                        Nhận báo giá thi công <i class="fa-solid fa-arrow-right ml-1"></i>
                    </a>
                </div>

                <!-- Grid 2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính -->
                <div id="realProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">

                    <!-- Ảnh thực tế 1 -->
                    <div class="ux-product-box filter-item" data-cat="quang-cao">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w800';" alt="Thi Công Bảng Hiệu Mặt Dựng Alu Chữ Nổi Đèn LED Tại Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Bảng Hiệu Mặt Dựng Alu Chữ Nổi Đèn LED Tại Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Thanh Khê, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 2 -->
                    <div class="ux-product-box filter-item" data-cat="chu-noi">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL&sz=w800';" alt="Làm Bảng Hiệu Chữ Nổi Mica Gắn Đèn LED Sáng Chân Cao Cấp" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Làm Bảng Hiệu Chữ Nổi Mica Gắn Đèn LED Sáng Chân Cao Cấp</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Hải Châu, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 3 -->
                    <div class="ux-product-box filter-item" data-cat="chu-noi">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D&sz=w800';" alt="Thi Công Bộ Chữ Nổi Inox Vàng Gương & Logo Backdrop Văn Phòng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Bộ Chữ Nổi Inox Vàng Gương & Logo Backdrop Văn Phòng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Sơn Trà, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 4 -->
                    <div class="ux-product-box filter-item" data-cat="quang-cao">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1Y8AllqlCuU370XwJQ67sHapavPodpCwR" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y8AllqlCuU370XwJQ67sHapavPodpCwR&sz=w800';" alt="Thiết Kế Thi Công Bảng Hiệu Cửa Hàng Kinh Doanh Trọn Gói Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thiết Kế Thi Công Bảng Hiệu Cửa Hàng Kinh Doanh Trọn Gói Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Liên Chiểu, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 5 -->
                    <div class="ux-product-box filter-item" data-cat="noi-that">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z&sz=w800';" alt="Thi Công Bảng Hiệu & Trang Trí Nội Thất Showroom Chuyên Nghiệp" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Bảng Hiệu & Trang Trí Nội Thất Showroom Chuyên Nghiệp</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Cẩm Lệ, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 6 -->
                    <div class="ux-product-box filter-item" data-cat="quang-cao">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr&sz=w800';" alt="Thi Công Hộp Đèn Quảng Cáo & Biển Vẫy Đèn LED Siêu Sáng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Hộp Đèn Quảng Cáo & Biển Vẫy Đèn LED Siêu Sáng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Ngũ Hành Sơn, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 7 -->
                    <div class="ux-product-box filter-item" data-cat="cnc-laser">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi&sz=w800';" alt="Gia Công Cắt Khắc CNC Alu Mica & Uốn Chữ Kim Loại Tại Xưởng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Gia Công Cắt Khắc CNC Alu Mica & Uốn Chữ Kim Loại Tại Xưởng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Xưởng Vinh Design Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                    <!-- Ảnh thực tế 8 -->
                    <div class="ux-product-box filter-item" data-cat="quang-cao">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1r3p33KyzU2TSj-0uu0djN80W5D3DzCAb" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r3p33KyzU2TSj-0uu0djN80W5D3DzCAb&sz=w800';" alt="Lắp Đặt Hoàn Thiện Bảng Hiệu Quảng Cáo Nhà Hàng & Quán Cafe" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Lắp Đặt Hoàn Thiện Bảng Hiệu Quảng Cáo Nhà Hàng & Quán Cafe</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px] text-slate-600">
                                <span>Khu vực: Hải Châu, Đà Nẵng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Xem chi tiết</a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 3: DANH MỤC 1 - THI CÔNG QUẢNG CÁO TẠI ĐÀ NẴNG (GIỐNG WEB MẪU PHÚC LỢI VIỆT)
             ========================================== -->
        <section class="section" id="sec-quang-cao">
            <div class="flatsome-container">
                <div class="section-title-wrap">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-bullhorn"></i>
                        <span>THI CÔNG QUẢNG CÁO TẠI ĐÀ NẴNG</span>
                    </h2>
                    <a href="#sec-bao-gia" class="text-xs font-bold text-[#0e2545] hover:text-[#c8102e]">
                        Tư vấn báo giá: 0901.149.099
                    </a>
                </div>

                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1V6Mifok3cbzG9ZuvkkmwbTxPbkTgzd0Q" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1V6Mifok3cbzG9ZuvkkmwbTxPbkTgzd0Q&sz=w800';" alt="Thi Công Biển Quảng Cáo Chữ Nổi Alu Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Biển Quảng Cáo Chữ Nổi Alu Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Báo giá theo m²</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1U23eEyV0ftCJu1jmKHaQ2zNZ4RCmQQjY" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1U23eEyV0ftCJu1jmKHaQ2zNZ4RCmQQjY&sz=w800';" alt="Thi Công Biển Quảng Cáo Mica Đèn LED Tại Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Biển Quảng Cáo Mica Đèn LED Tại Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Thiết kế miễn phí</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1CN4IbPxP4f-zZ5rYhrL3UAGPDh4UsJ82" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CN4IbPxP4f-zZ5rYhrL3UAGPDh4UsJ82&sz=w800';" alt="Thi Công Biển Quảng Cáo Đồng – Inox Ăn Mòn Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Biển Quảng Cáo Đồng – Inox Ăn Mòn Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Độ bền cao</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1D9PTSQ_l4rpsTNTkOErRcuGyVL6XOf3q" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D9PTSQ_l4rpsTNTkOErRcuGyVL6XOf3q&sz=w800';" alt="Thi Công Biển Quảng Cáo Hộp Đèn & Màn Hình LED Full Color" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Biển Quảng Cáo Hộp Đèn & Màn Hình LED Full Color</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Bảo hành 12-24T</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 4: DANH MỤC 2 - CHỮ NỔI QUẢNG CÁO & CẮT KHẮC CNC – LASER
             ========================================== -->
        <section class="section" id="sec-chu-noi">
            <div class="flatsome-container">
                <div class="section-title-wrap" id="sec-cnc-laser">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-layer-group"></i>
                        <span>CHỮ NỔI QUẢNG CÁO & CẮT KHẮC CNC – LASER</span>
                    </h2>
                    <a href="#sec-bao-gia" class="text-xs font-bold text-[#0e2545] hover:text-[#c8102e]">
                        Gia công giá xưởng Đà Nẵng
                    </a>
                </div>

                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1nDp-DBnzLKslT45kGwiaKpzEkJfgJOFN" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nDp-DBnzLKslT45kGwiaKpzEkJfgJOFN&sz=w800';" alt="Uốn Chữ Kim Loại – Chữ Nổi Inox Vàng Bóng Chất Lượng Tại Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Uốn Chữ Kim Loại – Chữ Nổi Inox Vàng Bóng Chất Lượng Tại Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Inox 304 cao cấp</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1XY5tZIjt_raQmZwQkhYgWx6-LwqP0Caf" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XY5tZIjt_raQmZwQkhYgWx6-LwqP0Caf&sz=w800';" alt="Cắt Khắc CNC Alu, Mica Chữ Nổi & Vách Ngăn Trang Trí Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Cắt Khắc CNC Alu, Mica Chữ Nổi & Vách Ngăn Trang Trí Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Cắt lấy nhanh</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1t2jb9QU9ZZWUbMCut2ZHYDm8vvMyLNoi&sz=w800';" alt="Gia Công Cắt Khắc Laser Kim Loại, Biển Tên Công Ty, Biển Phòng Ban" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Gia Công Cắt Khắc Laser Kim Loại, Biển Tên Công Ty, Biển Phòng Ban</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Sắc nét từng chi tiết</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D&sz=w800';" alt="Cắt CNC Trên Gỗ Công Nghiệp MDF & Chữ Nổi Trang Trí Sự Kiện" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Cắt CNC Trên Gỗ Công Nghiệp MDF & Chữ Nổi Trang Trí Sự Kiện</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Giá gốc tại xưởng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 5: DANH MỤC 3 - THIẾT KẾ THI CÔNG NỘI – NGOẠI THẤT SHOWROOM & IN PHUN KHỔ LỚN
             ========================================== -->
        <section class="section" id="sec-noi-that">
            <div class="flatsome-container">
                <div class="section-title-wrap" id="sec-in-phun">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-store"></i>
                        <span>THIẾT KẾ THI CÔNG SHOWROOM NỘI NGOẠI THẤT & IN PHUN KHỔ LỚN</span>
                    </h2>
                    <a href="#sec-bao-gia" class="text-xs font-bold text-[#0e2545] hover:text-[#c8102e]">
                        Xem báo giá trọn gói
                    </a>
                </div>

                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1sqhZOPTmqylw2kywSSVb2Bb-5dBG8b3Z&sz=w800';" alt="Thiết Kế Thi Công Nội Thất Showroom, Shop Thời Trang & Mỹ Phẩm Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thiết Kế Thi Công Nội Thất Showroom, Shop Thời Trang & Mỹ Phẩm Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Trọn gói A-Z</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w800';" alt="Thi Công Quầy Lễ Tân, Backdrop Sảnh Văn Phòng Công Ty Tại Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi Công Quầy Lễ Tân, Backdrop Sảnh Văn Phòng Công Ty Tại Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Đẹp - Sang trọng</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1r3p33KyzU2TSj-0uu0djN80W5D3DzCAb" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r3p33KyzU2TSj-0uu0djN80W5D3DzCAb&sz=w800';" alt="In Bạt Hiflex Khổ Lớn, Pano Quảng Cáo Ngoài Trời, Băng Rôn Đà Nẵng" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">In Bạt Hiflex Khổ Lớn, Pano Quảng Cáo Ngoài Trời, Băng Rôn Đà Nẵng</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">Mực dầu bền màu</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>

                    <div class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=111ZSZBC2JJypYsSUoRSzf3QKaONHvDWr&sz=w800';" alt="In Ấn Decal Ô Tô, Decal Dán Kính, PP, Backlit Film & Standee Sự Kiện" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">In Ấn Decal Ô Tô, Decal Dán Kính, PP, Backlit Film & Standee Sự Kiện</h3>
                            <div class="pt-1 border-t border-slate-100 flex items-center justify-between text-[11.5px]">
                                <span class="text-slate-600">In nhanh lấy liền</span>
                                <a href="#sec-bao-gia" class="text-[#c8102e] font-bold">Liên hệ</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 6: QUY TRÌNH THỰC HIỆN DỰ ÁN (GIỐNG MẪU PHÚC LỢI VIỆT)
             ========================================== -->
        <section class="section" id="sec-gioi-thieu">
            <div class="flatsome-container">
                <div class="bg-white border border-slate-200 rounded-lg p-4 md:p-6">
                    <div class="text-center max-w-2xl mx-auto mb-5">
                        <h2 class="text-base md:text-lg font-black text-[#0e2545] uppercase">
                            QUY TRÌNH THI CÔNG QUẢNG CÁO TẠI VINH DESIGN ĐÀ NẴNG
                        </h2>
                        <p class="text-xs md:text-sm text-slate-600 mt-1">
                            Chuyên nghiệp – Minh bạch – Cam kết đúng tiến độ và chất lượng thẩm mỹ cao nhất
                        </p>
                    </div>
                    <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="w-8 h-8 rounded-full bg-[#c8102e] text-white font-bold text-xs flex items-center justify-center mb-2">01</div>
                            <h3 class="text-xs md:text-sm font-bold text-[#0e2545] mb-1">Tiếp Nhận & Khảo Sát</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">Liên hệ Hotline/Zalo <strong>0901.149.099</strong>. Kỹ thuật viên khảo sát đo đạc thực tế tận nơi tại Đà Nẵng.</p>
                        </div>
                        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="w-8 h-8 rounded-full bg-[#0e2545] text-white font-bold text-xs flex items-center justify-center mb-2">02</div>
                            <h3 class="text-xs md:text-sm font-bold text-[#0e2545] mb-1">Thiết Kế Demo & Báo Giá</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">Lên phương án thiết kế 2D/3D trực quan và gửi bảng báo giá chi tiết tối ưu chi phí cho khách hàng.</p>
                        </div>
                        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="w-8 h-8 rounded-full bg-[#c8102e] text-white font-bold text-xs flex items-center justify-center mb-2">03</div>
                            <h3 class="text-xs md:text-sm font-bold text-[#0e2545] mb-1">Sản Xuất & Thi Công</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">Gia công trực tiếp tại xưởng Vinh Design bằng máy CNC - Laser hiện đại và lắp đặt an toàn, tỉ mỉ.</p>
                        </div>
                        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="w-8 h-8 rounded-full bg-[#0e2545] text-white font-bold text-xs flex items-center justify-center mb-2">04</div>
                            <h3 class="text-xs md:text-sm font-bold text-[#0e2545] mb-1">Nghiệm Thu & Bảo Hành</h3>
                            <p class="text-xs text-slate-600 leading-relaxed">Bàn giao công trình sạch đẹp, nghiệm thu và kích hoạt chế độ bảo hành uy tín từ 12 – 24 tháng.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG QUẢNG CÁO)
             ========================================== -->
        <section class="section" id="sec-bai-viet">
            <div class="flatsome-container">
                <div class="section-title-wrap">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-newspaper"></i>
                        <span>TIN TỨC & BÀI VIẾT TƯ VẤN QUẢNG CÁO</span>
                    </h2>
                    <span class="text-xs font-medium text-slate-600">Cẩm nang bảng hiệu đẹp Đà Nẵng</span>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 md:gap-4">
                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w800';" alt="Báo Giá Làm Bảng Hiệu Quảng Cáo Tại Đà Nẵng Mới Nhất" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <h3 class="ux-box-title">Báo Giá Làm Bảng Hiệu Quảng Cáo Tại Đà Nẵng Trọn Gói Mới Nhất</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2">Tổng hợp bảng giá thi công mặt dựng Alu, chữ nổi Mica, chữ nổi Inox đèn LED và bạt Hiflex tại TP. Đà Nẵng.</p>
                            </div>
                            <a href="#sec-bao-gia" class="text-[11.5px] font-bold text-[#c8102e]">Đọc thêm →</a>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D8T7MCevopMo6dlbFwqTvhLY8tcCYQFL&sz=w800';" alt="Kinh Nghiệm Chọn Chất Liệu Làm Bảng Hiệu Bền Đẹp" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <h3 class="ux-box-title">Kinh Nghiệm Chọn Chất Liệu Bảng Hiệu Phù Hợp Thời Tiết Miền Trung</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2">Tư vấn chọn Alu ngoài trời, Inox 304 chống gỉ và LED Hàn Quốc chống nước bền bỉ cho cửa hàng tại Đà Nẵng.</p>
                            </div>
                            <a href="#sec-bao-gia" class="text-[11.5px] font-bold text-[#c8102e]">Đọc thêm →</a>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zYQKvWG_l1hg4tHfpmGzyC_Ti76Fz-3D&sz=w800';" alt="Xu Hướng Thiết Kế Chữ Nổi Đèn LED Sáng Chân Cho Showroom" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <h3 class="ux-box-title">Top Mẫu Chữ Nổi Inox Vàng Gương & Mica Sáng Chân Được Ưa Chuộng</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2">Giải pháp nâng tầm nhận diện thương hiệu sang trọng cho spa, thẩm mỹ viện, khách sạn và văn phòng công ty.</p>
                            </div>
                            <a href="#sec-bao-gia" class="text-[11.5px] font-bold text-[#c8102e]">Đọc thêm →</a>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://lh3.googleusercontent.com/d/1Y8AllqlCuU370XwJQ67sHapavPodpCwR" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y8AllqlCuU370XwJQ67sHapavPodpCwR&sz=w800';" alt="Ứng Dụng Cắt Khắc CNC Laser Trong Quảng Cáo Nội Thất" loading="lazy">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <h3 class="ux-box-title">Ứng Dụng Công Nghệ Cắt Khắc CNC – Laser Trong Quảng Cáo & Nội Thất</h3>
                                <p class="text-[11.5px] text-slate-600 leading-relaxed mb-2">Gia công vách ngăn CNC, cắt chữ nổi Mica, khắc laser kim loại độ chính xác cao tại xưởng Vinh Design.</p>
                            </div>
                            <a href="#sec-bao-gia" class="text-[11.5px] font-bold text-[#c8102e]">Đọc thêm →</a>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 8: DANH MỤC CÁC ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU
             ========================================== -->
        <section class="section" id="sec-doi-tac">
            <div class="flatsome-container">
                <div class="section-title-wrap">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-handshake"></i>
                        <span>ĐỐI TÁC & KHÁCH HÀNG CỦA VINH DESIGN</span>
                    </h2>
                    <span class="text-xs text-slate-600">Đồng hành cùng doanh nghiệp tại Đà Nẵng & Miền Trung</span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 md:gap-3">
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-hotel text-xl text-[#0e2545] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Hệ Thống Khách Sạn & Resort Đà Nẵng</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-utensils text-xl text-[#c8102e] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Chuỗi Nhà Hàng & Cafe Đà Nẵng</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-bag-shopping text-xl text-[#0e2545] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Showroom Thời Trang & Mỹ Phẩm</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-Graduation-cap text-xl text-[#c8102e] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Trung Tâm Anh Ngữ & Giáo Dục</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-hospital text-xl text-[#0e2545] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Phòng Khám, Nha Khoa & Spa</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3 text-center flex flex-col items-center justify-center min-h-[82px]">
                        <i class="fa-solid fa-building-shield text-xl text-[#c8102e] mb-1"></i>
                        <div class="text-xs font-bold text-slate-800">Doanh Nghiệp & Cơ Quan Đơn Vị</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 9: FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK + BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ
             ========================================== -->
        <section class="section" id="sec-bao-gia">
            <div class="flatsome-container">
                <div class="section-title-wrap">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-file-signature"></i>
                        <span>YÊU CẦU TƯ VẤN BÁO GIÁ – FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG</span>
                    </h2>
                    <span class="text-xs font-bold text-[#c8102e]">Hotline/Zalo: 0901.149.099</span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">

                    <!-- CỘT 1 (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                    <div class="lg:col-span-5 bg-white border border-slate-200 rounded-lg p-4 md:p-5 shadow-xs">
                        <div class="border-b border-slate-200 pb-2.5 mb-3">
                            <h3 class="text-sm md:text-base font-black text-[#0e2545] uppercase">
                                ĐĂNG KÝ NHẬN BÁO GIÁ NHANH
                            </h3>
                            <p class="text-xs text-slate-600 mt-0.5">
                                Quý khách điền thông tin bên dưới, Vinh Design sẽ liên hệ tư vấn & báo giá ngay trong 5 phút!
                            </p>
                        </div>

                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                                <input id="custName" type="text" required placeholder="Nhập họ và tên của bạn..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-[#c8102e]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="custPhone" type="tel" required placeholder="Ví dụ: 0901149099" class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-[#c8102e]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần tư vấn & báo giá *</label>
                                <select id="custService" class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded bg-white focus:outline-none focus:border-[#c8102e]">
                                    <option value="Làm bảng hiệu Alu - Chữ nổi">1. Làm bảng hiệu Alu - Chữ nổi trọn gói</option>
                                    <option value="Chữ nổi Inox - Mica đèn LED">2. Gia công Chữ nổi Inox - Mica đèn LED</option>
                                    <option value="Cắt khắc CNC - Laser">3. Cắt khắc CNC – Laser (Alu, Mica, Gỗ, Kim loại)</option>
                                    <option value="Thi công Nội thất Showroom">4. Thiết kế & Thi công Nội thất Showroom, Shop</option>
                                    <option value="In phun khổ lớn - Bạt Hiflex - Decal">5. In phun khổ lớn (Bạt Hiflex, Decal, PP, Pano)</option>
                                    <option value="Khác">6. Hạng mục quảng cáo khác</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ khảo sát / Yêu cầu chi tiết</label>
                                <textarea id="custNote" rows="3" placeholder="Nhập địa chỉ công trình tại Đà Nẵng, kích thước dự kiến hoặc yêu cầu cụ thể..." class="w-full px-3 py-2 text-xs md:text-sm border border-slate-300 rounded focus:outline-none focus:border-[#c8102e]"></textarea>
                            </div>
                            <button type="submit" class="w-full py-2.5 px-4 rounded bg-[#c8102e] hover:bg-[#9e0b22] text-white font-bold text-xs md:text-sm uppercase tracking-wide transition cursor-pointer">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                            </button>
                        </form>

                        <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs space-y-2">
                            <div class="font-bold"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Đã ghi nhận yêu cầu báo giá của quý khách!</div>
                            <div id="quoteSummaryText" class="text-slate-700"></div>
                            <div class="pt-1 flex flex-wrap gap-2">
                                <a href="https://zalo.me/0901149099" target="_blank" rel="noopener" class="inline-flex items-center gap-1 bg-blue-600 text-white px-3 py-1.5 rounded font-bold">
                                    <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo 0901.149.099
                                </a>
                                <a href="tel:0901149099" class="inline-flex items-center gap-1 bg-[#c8102e] text-white px-3 py-1.5 rounded font-bold">
                                    <i class="fa-solid fa-phone"></i> Gọi trực tiếp
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- CỘT 2 (3/12): ĐƯA FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-3 bg-white border border-slate-200 rounded-lg p-4 shadow-xs flex flex-col justify-between">
                        <div>
                            <div class="border-b border-slate-200 pb-2.5 mb-3 flex items-center justify-between">
                                <h3 class="text-sm font-black text-[#0e2545] uppercase">
                                    <i class="fa-brands fa-facebook text-blue-600 mr-1"></i> FANPAGE CHÍNH THỨC
                                </h3>
                            </div>

                            <!-- Khung Fanpage trực quan + Plugin kết nối trực tiếp tới ID 61566503873995 -->
                            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
                                <div class="relative h-28 bg-gradient-to-r from-[#0e2545] to-[#c8102e] p-3 flex items-end">
                                    <img src="https://lh3.googleusercontent.com/d/1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P_pTJsUjWs3J2dzGxZ2DGIWj1DADSSY7&sz=w600';" alt="Cover Fanpage Vinh Design" class="absolute inset-0 w-full h-full object-cover opacity-45">
                                    <div class="relative z-10 flex items-center gap-2.5">
                                        <img src="https://lh3.googleusercontent.com/d/1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w200';" alt="Logo Fanpage" class="w-12 h-12 rounded-md bg-white p-0.5 object-contain border border-white shadow">
                                        <div class="text-white">
                                            <div class="text-xs font-black leading-tight">CÔNG TY TNHH QUẢNG CÁO VINH DESIGN</div>
                                            <div class="text-[11px] text-amber-300 font-medium">Quảng cáo & Nội thất Đà Nẵng</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3 space-y-2 text-xs text-slate-700">
                                    <p class="leading-relaxed">
                                        Cập nhật hình ảnh thi công bảng hiệu thực tế hàng ngày tại Fanpage chính thức của Quảng Cáo Vinh Design.
                                    </p>
                                    <div class="text-[11.5px] space-y-1 text-slate-600">
                                        <div><i class="fa-solid fa-location-dot text-[#c8102e] w-4"></i> K160/53 Trần Cao Vân, Thanh Khê, Đà Nẵng</div>
                                        <div><i class="fa-solid fa-phone text-emerald-600 w-4"></i> 0901.149.099</div>
                                        <div><i class="fa-solid fa-globe text-blue-600 w-4"></i> vinhdesign.com</div>
                                    </div>
                                    <div class="pt-2 grid grid-cols-2 gap-2">
                                        <a href="https://www.facebook.com/profile.php?id=61566503873995" target="_blank" rel="noopener" class="bg-blue-600 hover:bg-blue-700 text-white text-center py-2 px-2 rounded font-bold text-[11.5px] flex items-center justify-center gap-1">
                                            <i class="fa-brands fa-facebook-f"></i> Xem Fanpage
                                        </a>
                                        <a href="https://www.facebook.com/profile.php?id=61566503873995" target="_blank" rel="noopener" class="bg-slate-200 hover:bg-slate-300 text-slate-800 text-center py-2 px-2 rounded font-bold text-[11.5px] flex items-center justify-center gap-1">
                                            <i class="fa-brands fa-facebook-messenger text-blue-600"></i> Nhắn Tin
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="mt-3 p-2.5 rounded bg-amber-50 border border-amber-200 text-[11.5px] text-slate-700">
                            <strong class="text-[#c8102e]">ƯU ĐÃI:</strong> Miễn phí 100% chi phí khảo sát & thiết kế file 2D/3D khi thi công trọn gói tại Vinh Design!
                        </div>
                    </div>

                    <!-- CỘT 3 (4/12): ĐƯA GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-4 bg-white border border-slate-200 rounded-lg p-4 shadow-xs flex flex-col justify-between">
                        <div>
                            <div class="border-b border-slate-200 pb-2.5 mb-3 flex items-center justify-between">
                                <h3 class="text-sm font-black text-[#0e2545] uppercase">
                                    <i class="fa-solid fa-map-location-dot text-[#c8102e] mr-1"></i> BẢN ĐỒ GOOGLE MAPS
                                </h3>
                                <a href="https://www.google.com/maps/search/?api=1&query=K160%2F53+Tr%E1%BA%A7n+Cao+V%C3%A2n%2C+Thanh+Kh%C3%AA%2C+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-[11px] font-bold text-blue-600 hover:underline">
                                    Mở bản đồ lớn ↗
                                </a>
                            </div>

                            <div class="rounded-lg overflow-hidden border border-slate-300 h-[250px] w-full bg-slate-100">
                                <iframe
                                    title="Bản đồ Công Ty TNHH Quảng Cáo Vinh Design - K160/53 Trần Cao Vân, Phường Thanh Khê, TP Đà Nẵng"
                                    src="https://maps.google.com/maps?q=K160/53%20Tr%E1%BA%A7n%20Cao%20V%C3%A2n,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                    width="100%"
                                    height="100%"
                                    style="border:0;"
                                    allowfullscreen=""
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>

                        <div class="mt-3 text-xs text-slate-700 space-y-1 bg-slate-50 p-2.5 rounded border border-slate-200">
                            <div class="font-bold text-[#0e2545]">CÔNG TY TNHH QUẢNG CÁO VINH DESIGN</div>
                            <div><i class="fa-solid fa-location-dot text-[#c8102e] mr-1"></i> <strong>Địa chỉ:</strong> K160/53 Trần Cao Vân, Phường Thanh Khê, TP Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone-volume text-emerald-600 mr-1"></i> <strong>Hotline/Zalo:</strong> <a href="tel:0901149099" class="font-bold text-[#c8102e]">0901.149.099</a></div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- ==========================================
         FOOTER (#footer) CHUẨN MẪU PHÚC LỢI VIỆT
         ========================================== -->
    <footer id="footer" class="w-full bg-[#0e2545] text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-[#c8102e]">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10">

                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img
                            src="https://lh3.googleusercontent.com/d/1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc"
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jN4Z8EZWSd_hwxhcOYLTSu3Q5iiDSRDc&sz=w300';"
                            alt="Logo Vinh Design Footer"
                            class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <div class="text-sm font-black text-white uppercase">CÔNG TY TNHH QUẢNG CÁO VINH DESIGN</div>
                            <div class="text-[11px] text-amber-400 font-semibold">Website: vinhdesign.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên Thiết kế & Thi công Bảng hiệu quảng cáo, Chữ nổi Inox - Mica, Mặt dựng Alu, Gia công Cắt khắc CNC - Laser, Nội thất Showroom và In phun khổ lớn.
                    </p>
                    <div class="text-xs space-y-1 text-slate-200">
                        <div><i class="fa-solid fa-location-dot text-red-400 w-4"></i> <strong>Địa chỉ:</strong> K160/53 Trần Cao Vân, Phường Thanh Khê, TP Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-amber-400 w-4"></i> <strong>Hotline 24/7:</strong> <a href="tel:0901149099" class="text-amber-300 font-bold">0901.149.099</a></div>
                        <div><i class="fa-solid fa-globe text-sky-400 w-4"></i> <strong>Website:</strong> vinhdesign.com</div>
                    </div>
                </div>

                <!-- Cột 2: Dịch vụ nổi bật -->
                <div class="space-y-2">
                    <h4 class="text-sm font-bold text-white uppercase border-b border-white/15 pb-1.5">DỊCH VỤ NỔI BẬT</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#sec-quang-cao" class="hover:text-amber-400">✅ Làm bảng hiệu và thi công quảng cáo trọn gói</a></li>
                        <li><a href="#sec-chu-noi" class="hover:text-amber-400">✅ Gia công chữ nổi Inox, chữ nổi Mica đèn LED</a></li>
                        <li><a href="#sec-cnc-laser" class="hover:text-amber-400">✅ Cắt khắc CNC – Laser trên Alu, Mica, Gỗ, Inox</a></li>
                        <li><a href="#sec-noi-that" class="hover:text-amber-400">✅ Thiết kế và thi công nội thất Showroom, Cửa hàng</a></li>
                        <li><a href="#sec-in-phun" class="hover:text-amber-400">✅ In phun khổ lớn Bạt Hiflex, Decal, PP, Pano</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách ưu đãi và bảo hành -->
                <div class="space-y-2">
                    <h4 class="text-sm font-bold text-white uppercase border-b border-white/15 pb-1.5">CHÍNH SÁCH ƯU ĐÃI & BẢO HÀNH</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li>• Miễn phí 100% phí khảo sát & thiết kế khi thi công</li>
                        <li>• Thi công trọn gói tất cả các hạng mục quảng cáo</li>
                        <li>• Sản phẩm sản xuất trực tiếp tại xưởng không qua trung gian</li>
                        <li>• Bảo hành từ 12 - 24 tháng tất cả các hạng mục sản phẩm</li>
                        <li>• Hỗ trợ bảo trì nhanh chóng tận nơi tại TP. Đà Nẵng</li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối mạng xã hội -->
                <div class="space-y-2.5">
                    <h4 class="text-sm font-bold text-white uppercase border-b border-white/15 pb-1.5">KẾT NỐI VỚI VINH DESIGN</h4>
                    <p class="text-xs text-slate-300">
                        Theo dõi Fanpage hoặc liên hệ trực tiếp qua Zalo để nhận mẫu bảng hiệu đẹp và báo giá ưu đãi nhất.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-1">
                        <a href="https://www.facebook.com/profile.php?id=61566503873995" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold inline-flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook-f"></i> Fanpage Facebook
                        </a>
                        <a href="https://zalo.me/0901149099" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-sky-500 hover:bg-sky-600 text-white text-xs font-bold inline-flex items-center gap-1.5">
                            <i class="fa-solid fa-comment-dots"></i> Chat Zalo
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-4 text-center text-xs text-slate-400">
                Copyright 2026 © <strong>CÔNG TY TNHH QUẢNG CÁO VINH DESIGN (vinhdesign.com)</strong> • Đ/c: K160/53 Trần Cao Vân, Phường Thanh Khê, TP Đà Nẵng • Hotline: 0901.149.099
            </div>
        </div>
    </footer>

</div>

<!-- ==========================================
     CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
     Tương thích hoàn hảo trên cả máy tính và điện thoại
     ========================================== -->
<div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
    <!-- Nút Facebook Fanpage -->
    <a
        href="https://www.facebook.com/profile.php?id=61566503873995"
        target="_blank"
        rel="noopener"
        title="Fanpage Công Ty TNHH Quảng Cáo Vinh Design"
        class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
    >
        <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm shrink-0">
            <i class="fa-brands fa-facebook-f"></i>
        </span>
        <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage Vinh Design</span>
        <span class="text-[11px] font-bold pr-0.5 sm:hidden">Facebook</span>
    </a>

    <!-- Nút Chat Zalo 0901.149.099 -->
    <a
        href="https://zalo.me/0901149099"
        target="_blank"
        rel="noopener"
        title="Chat Zalo 0901.149.099"
        class="flex items-center gap-2 bg-[#0068FF] hover:bg-sky-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
    >
        <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-black text-[11px] shrink-0">
            Zalo
        </span>
        <span class="text-xs font-bold pr-1 hidden sm:inline">Zalo: 0901.149.099</span>
        <span class="text-[11px] font-bold pr-0.5 sm:hidden">Zalo</span>
    </a>

    <!-- Nút Hotline 0901.149.099 -->
    <a
        href="tel:0901149099"
        title="Gọi ngay Hotline 0901.149.099"
        class="floating-pulse flex items-center gap-2 bg-[#c8102e] hover:bg-[#9e0b22] text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
    >
        <span class="w-7 h-7 rounded-full bg-white text-[#c8102e] flex items-center justify-center text-xs shrink-0">
            <i class="fa-solid fa-phone-volume"></i>
        </span>
        <span class="text-xs font-extrabold pr-1">0901.149.099</span>
    </a>
</div>

<!-- ==========================================
     JAVASCRIPT: TỰ ĐỘNG TRƯỢT 2 BANNER, LỌC DANH MỤC & XỬ LÝ FORM BÁO GIÁ
     ========================================== -->
<script>
    // 1. Tự động trượt 2 ảnh banner chuyên nghiệp (đồng bộ cả máy tính & điện thoại)
    let currentBannerIndex = 0;
    const totalBannerSlides = 2;
    let bannerTimer = null;

    function renderBannerSlide(index) {
        const desktopSlides = document.querySelectorAll('.banner-slide-desktop');
        const mobileSlides = document.querySelectorAll('.banner-slide-mobile');
        const dot0 = document.getElementById('bannerDot0');
        const dot1 = document.getElementById('bannerDot1');

        desktopSlides.forEach((slide, i) => {
            if (i === index) {
                slide.classList.remove('opacity-0', 'z-0');
                slide.classList.add('opacity-100', 'z-10');
            } else {
                slide.classList.remove('opacity-100', 'z-10');
                slide.classList.add('opacity-0', 'z-0');
            }
        });

        mobileSlides.forEach((slide, i) => {
            if (i === index) {
                slide.classList.remove('opacity-0', 'z-0');
                slide.classList.add('opacity-100', 'z-10');
            } else {
                slide.classList.remove('opacity-100', 'z-10');
                slide.classList.add('opacity-0', 'z-0');
            }
        });

        if (dot0 && dot1) {
            if (index === 0) {
                dot0.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                dot1.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
            } else {
                dot0.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
                dot1.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
            }
        }
    }

    function changeBannerSlide(step) {
        currentBannerIndex = (currentBannerIndex + step + totalBannerSlides) % totalBannerSlides;
        renderBannerSlide(currentBannerIndex);
        restartBannerAutoPlay();
    }

    function goToBannerSlide(index) {
        currentBannerIndex = index;
        renderBannerSlide(currentBannerIndex);
        restartBannerAutoPlay();
    }

    function restartBannerAutoPlay() {
        if (bannerTimer) clearInterval(bannerTimer);
        bannerTimer = setInterval(() => {
            currentBannerIndex = (currentBannerIndex + 1) % totalBannerSlides;
            renderBannerSlide(currentBannerIndex);
        }, 5000);
    }

    // 2. Đóng/mở menu danh mục trên điện thoại
    function toggleMobileMenu() {
        const drawer = document.getElementById('mobileMenuDrawer');
        if (drawer) {
            drawer.classList.toggle('hidden');
        }
    }

    // 3. Lọc danh mục nhanh ở trang chủ
    function filterHomeCategory(category, btnEl) {
        const pills = document.querySelectorAll('.home-cat-pill');
        pills.forEach(p => p.classList.remove('active'));
        if (btnEl) btnEl.classList.add('active');

        const items = document.querySelectorAll('#realProjectsGrid .filter-item');
        items.forEach(item => {
            const itemCat = item.getAttribute('data-cat');
            if (category === 'all' || itemCat === category) {
                item.style.display = 'flex';
            } else {
                item.style.display = 'none';
            }
        });
    }

    // 4. Tìm kiếm nhanh sản phẩm trên trang chủ
    function filterProductsBySearch(keyword) {
        const q = (keyword || '').trim().toLowerCase();
        const boxes = document.querySelectorAll('.ux-product-box');
        boxes.forEach(box => {
            const text = box.innerText.toLowerCase();
            box.style.display = (!q || text.includes(q)) ? 'flex' : 'none';
        });
    }

    // 5. Xử lý gửi form Yêu Cầu & Báo Giá trang chủ
    function submitQuoteForm(event) {
        event.preventDefault();
        const name = document.getElementById('custName').value.trim();
        const phone = document.getElementById('custPhone').value.trim();
        const service = document.getElementById('custService').value;
        const note = document.getElementById('custNote').value.trim();

        const summaryEl = document.getElementById('quoteSummaryText');
        const successBox = document.getElementById('quoteSuccessBox');

        if (summaryEl && successBox) {
            summaryEl.innerHTML = `Khách hàng: <strong>${name}</strong> (${phone})<br>Hạng mục: <strong>${service}</strong>${note ? '<br>Ghi chú: ' + note : ''}`;
            successBox.classList.remove('hidden');
        }
    }

    window.onload = function () {
        restartBannerAutoPlay();
    };
</script>
</body>
</html>
