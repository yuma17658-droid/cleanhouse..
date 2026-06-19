<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CleanHome - Dịch Vụ Dọn Dẹp Nhà Chuyên Nghiệp</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700;800&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- HEADER / NAVIGATION -->
    <header class="main-header">
        <div class="nav-container">
            <a href="#" class="logo">
                <span class="logo-icon">✨</span>
                <span class="logo-text">Clean<span>Home</span></span>
            </a>
            <nav class="nav-links">
                <a href="#problems" class="nav-link">Vấn Đề</a>
                <a href="#solution" class="nav-link">Giải Pháp</a>
                <a href="#process" class="nav-link">Quy Trình</a>
                <a href="#booking" class="nav-link">Đặt Lịch</a>
            </nav>
        </div>
    </header>

    <!-- SECTION 1: HERO -->
    <section class="hero-section">
        <div class="hero-container">
            <div class="hero-content">
                <div class="badge-container">
                    <span class="hero-badge">🏠 Dịch Vụ Dọn Dẹp Chuyên Nghiệp</span>
                </div>
                <h1 class="hero-title">
                    Tận Hưởng Cuối Tuần <span class="text-highlight">Thảnh Thơi</span>. 
                    Để Việc Dọn Nhà Cho Chúng Tôi.
                </h1>
                <p class="hero-subtitle">
                    Dịch vụ dọn dẹp nhà cửa chuyên nghiệp giúp bạn loại bỏ stress và lấy lại thời gian quý báu bên những người thân yêu của mình.
                </p>
                <div class="hero-actions">
                    <button class="btn btn-accent" onclick="scrollToBooking()">Đặt Lịch Dọn Dẹp Ngay</button>
                </div>
                <div class="hero-trust-info">
                    <span><i class="fas fa-check-circle"></i> Đặt lịch nhanh trong 60s</span>
                    <span><i class="fas fa-shield-alt"></i> Bảo hiểm dịch vụ 100%</span>
                </div>
            </div>
            <div class="hero-image-container">
                <div class="hero-image-wrapper">
                    <img src="https://images.unsplash.com/photo-1585399449821-3d86c313371b?w=500&h=500&fit=crop" alt="Gia đình hạnh phúc" class="hero-img">
                    <div class="floating-badge badge-success">
                        <div class="badge-icon">
                            <i class="fas fa-heart"></i>
                        </div>
                        <div class="badge-txt">
                            <h4>Thảnh Thơi</h4>
                            <p>Không lo việc nhà</p>
                        </div>
                    </div>
                    <div class="floating-badge badge-clean">
                        <div class="badge-icon">
                            <i class="fas fa-sparkles"></i>
                        </div>
                        <div class="badge-txt">
                            <h4>100% Sạch Thơm</h4>
                            <p>Chuẩn khách sạn 5 sao</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 2: THE PROBLEM -->
    <section class="problem-section" id="problems">
        <div class="container">
            <div class="section-header text-center">
                <span class="section-subtitle">Vấn Đề Của Bạn</span>
                <h2 class="section-title">Bạn đang kiệt sức trong chính ngôi nhà của mình?</h2>
                <p class="section-desc">
                    Sau một tuần làm việc mệt mỏi, cuối tuần lẽ ra là thời gian để bạn nghỉ ngơi. Nhưng đống bát đĩa, quần áo chưa giặt và sàn nhà bụi bặm lại đang vắt kiệt chút sức lực cuối cùng của bạn.
                </p>
            </div>

            <div class="problem-grid">
                <div class="problem-card">
                    <div class="problem-icon">
                        <i class="fas fa-head-side-virus"></i>
                    </div>
                    <h3>Stress Tột Độ</h3>
                    <p>Bạn luôn trong trạng thái chạy đua với thời gian. Việc dọn dẹp biến ngày nghỉ duy nhất trong tuần thành một gánh nặng không hồi kết.</p>
                </div>

                <div class="problem-card">
                    <div class="problem-icon">
                        <i class="fas fa-frown"></i>
                    </div>
                    <h3>Cảm Giác Có Lỗi</h3>
                    <p>Bạn dằn vặt vì những giờ phút lẽ ra được ngồi chơi xếp hình cùng con, hay ăn tối thảnh thơi cùng bạn đời lại bị thay thế bởi việc lau dọn.</p>
                </div>

                <div class="problem-card">
                    <div class="problem-icon">
                        <i class="fas fa-triangle-exclamation"></i>
                    </div>
                    <h3>Sự E Ngại, Xấu Hổ</h3>
                    <p>Bạn luôn nơm nớp lo sợ và tìm cách từ chối khéo mỗi khi bạn bè hay người thân muốn ghé thăm nhà đột xuất chỉ vì phòng khách bừa bộn.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 3: THE GUIDE / SOLUTION -->
    <section class="guide-section" id="solution">
        <div class="container">
            <div class="section-header text-center">
                <span class="section-subtitle">Người Đồng Hành Tin Cậy</span>
                <h2 class="section-title">Chúng Tôi Hiểu Nỗi Vất Vả Của Bạn</h2>
            </div>

            <div class="guide-grid" style="margin-top: 60px;">
                <div>
                    <p class="guide-intro">
                        Bạn không cần phải làm siêu nhân để gánh vác mọi thứ. Hơn 500+ gia đình tại thành phố đã tin tưởng giao lại gánh nặng việc nhà cho CleanHome để tận hưởng cuộc sống trọn vẹn hơn.
                    </p>

                    <div class="trust-list">
                        <div class="trust-item">
                            <div class="trust-icon">
                                <i class="fas fa-money-bill-wave"></i>
                            </div>
                            <div class="trust-text">
                                <h4>Cam Kết Hoàn Tiền 100%</h4>
                                <p>Nếu bạn không hài lòng với chất lượng dọn dẹp, chúng tôi sẽ hoàn tiền ngay lập tức.</p>
                            </div>
                        </div>

                        <div class="trust-item">
                            <div class="trust-icon">
                                <i class="fas fa-certificate"></i>
                            </div>
                            <div class="trust-text">
                                <h4>Nhân Viên Được Đào Tạo Chuyên Nghiệp</h4>
                                <p>Lý lịch rõ ràng, kiểm tra sức khỏe định kỳ và đào tạo kỹ thuật dọn dẹp chuẩn 5 sao.</p>
                            </div>
                        </div>

                        <div class="trust-item">
                            <div class="trust-icon">
                                <i class="fas fa-leaf"></i>
                            </div>
                            <div class="trust-text">
                                <h4>Hóa Chất An Toàn 100%</h4>
                                <p>Sử dụng các sản phẩm sinh học hữu cơ lành tính, bảo vệ sức khỏe trẻ nhỏ và thú cưng.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="video-container">
                    <div class="video-card">
                        <div class="video-overlay" onclick="toggleVideoPlayer(this)">
                            <div class="video-play-btn">
                                <i class="fas fa-play"></i>
                            </div>
                            <p class="video-tagline">Xem chia sẻ từ khách hàng thực tế</p>
                        </div>
                        <div class="custom-video-player">
                            <div class="video-avatar">👨‍👩‍👧‍👦</div>
                            <div class="video-dialogue">
                                <p>"Trước đây, cuối tuần của tôi là ác mộng với đống việc nhà chồng chất. Nhờ CleanHome, giờ tôi có thể dành thời gian chơi với con và thư giãn cùng gia đình. Thực sự rất tuyệt vời!"</p>
                            </div>
                            <div class="video-controls">
                                <button onclick="playVideo(this)"><i class="fas fa-play"></i></button>
                                <div class="video-progress">
                                    <div class="video-progress-bar"></div>
                                </div>
                                <span>0:15 / 0:30</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 4: THE PLAN -->
    <section class="plan-section" id="process">
        <div class="container">
            <div class="section-header text-center">
                <span class="section-subtitle">Quy Trình Đơn Giản</span>
                <h2 class="section-title">Ngôi Nhà Sạch Bóng Chỉ Với 3 Bước Đơn Giản</h2>
            </div>

            <div class="steps-grid">
                <div class="step-card">
                    <div class="step-num">01</div>
                    <h3>Đặt Lịch Nhận Báo Giá</h3>
                    <p>Điền thông tin căn hộ của bạn vào form chỉ mất đúng 1 phút để nhận báo giá chính xác.</p>
                </div>

                <div class="step-card">
                    <div class="step-num">02</div>
                    <h3>Chúng Tôi Dọn Dẹp</h3>
                    <p>Đội ngũ chuyên nghiệp của CleanHome đến đúng giờ, làm sạch tỉ mỉ mọi ngóc ngách.</p>
                </div>

                <div class="step-card">
                    <div class="step-num">03</div>
                    <h3>Tận Hưởng Không Gian</h3>
                    <p>Trở về ngôi nhà thơm mát, thư giãn uống trà và làm những việc bạn thực sự yêu thích.</p>
                </div>
            </div>

            <div class="plan-cta text-center">
                <button class="btn btn-accent" onclick="scrollToBooking()">Đặt Lịch Dọn Dẹp Ngay</button>
            </div>
        </div>
    </section>

    <!-- SECTION 5: COMPARISON -->
    <section class="comparison-section">
        <div class="container">
            <div class="section-header text-center">
                <span class="section-subtitle">Sự Lựa Chọn Của Bạn</span>
                <h2 class="section-title">Bạn Muốn Cuối Tuần Của Mình Diễn Ra Như Thế Nào?</h2>
            </div>

            <div class="comparison-grid">
                <div class="comparison-card">
                    <div class="card-badge bg-danger">
                        <i class="fas fa-times"></i> Tự Dọn Dẹp
                    </div>
                    <ul>
                        <li>
                            <i class="fas fa-circle-xmark"></i>
                            <span>Mất 4-6 tiếng cuối tuần cắm cúi lau chùi</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-xmark"></i>
                            <span>Đau lưng, mỏi gối và kiệt sức trước khi tuần mới bắt đầu</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-xmark"></i>
                            <span>Không có thời gian chơi với con hay đi hẹn hò</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-xmark"></i>
                            <span>Ngôi nhà vẫn không thể sạch sâu chuẩn khách sạn</span>
                        </li>
                    </ul>
                </div>

                <div class="comparison-card highlighted">
                    <div class="card-badge bg-success">
                        <i class="fas fa-check"></i> Chọn CleanHome
                    </div>
                    <ul>
                        <li>
                            <i class="fas fa-circle-check"></i>
                            <span>100% thời gian cuối tuần dành cho bản thân và gia đình</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-check"></i>
                            <span>Không gian sống sạch bóng, ngát hương hoa nhài tự nhiên</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-check"></i>
                            <span>Tinh thần sảng khoái, tràn đầy năng lượng tích cực</span>
                        </li>
                        <li>
                            <i class="fas fa-circle-check"></i>
                            <span>Nhân viên chuyên nghiệp làm hết mọi việc nặng nhọc</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 6: LEAD MAGNET -->
    <section class="booking-section">
        <div class="container">
            <div class="booking-grid">
                <div class="lead-card">
                    <div class="lead-icon">
                        <i class="fas fa-book"></i>
                    </div>
                    <h3>Chưa Sẵn Sàng Đặt Lịch Ngay?</h3>
                    <p>Hãy tải miễn phí cẩm nang của chúng tôi để biết cách giữ nhà cửa ngăn nắp chỉ với 15 phút mỗi ngày.</p>
                    <form class="lead-form" onsubmit="handleLeadSubmit(event)">
                        <input type="email" placeholder="Nhập Email của bạn..." required>
                        <button type="submit" class="btn btn-primary btn-block">
                            <i class="fas fa-download"></i> &nbsp; Tải Cẩm Nang Ngay
                        </button>
                        <div class="success-message" style="display: none;">
                            <i class="fas fa-check-circle"></i> Email đã được gửi!
                        </div>
                    </form>
                </div>

                <div class="booking-form-card" id="booking">
                    <h3>Đặt Lịch Dọn Nhà Nhanh</h3>
                    <p class="form-intro">Điền thông tin để nhận báo giá & xác nhận lịch ngay lập tức.</p>

                    <form class="booking-form" onsubmit="handleBookingSubmit(event)">
                        <div class="form-group">
                            <label for="name">Họ và Tên <span style="color: var(--danger);">*</span></label>
                            <input type="text" id="name" placeholder="Ví dụ: Nguyễn Văn A" required>
                        </div>

                        <div class="form-group">
                            <label for="phone">Số Điện Thoại <span style="color: var(--danger);">*</span></label>
                            <input type="tel" id="phone" placeholder="Ví dụ: 0912345678" required>
                        </div>

                        <div class="form-row">
                            <div class="form-group">
                                <label for="area">Diện Tích Nhà (m²) <span style="color: var(--danger);">*</span></label>
                                <select id="area" required onchange="updatePrice()">
                                    <option value="">-- Chọn diện tích --</option>
                                    <option value="50-80">50m² - 80m²</option>
                                    <option value="80-120">80m² - 120m²</option>
                                    <option value="120-150">120m² - 150m²</option>
                                    <option value="150+">150m² trở lên</option>
                                </select>
                            </div>

                            <div class="form-group">
                                <label for="date">Ngày Dọn Dẹp <span style="color: var(--danger);">*</span></label>
                                <input type="date" id="date" required>
                            </div>
                        </div>

                        <div class="price-estimator">
                            <span>Giá dự kiến:</span>
                            <strong id="priceDisplay">350.000đ</strong>
                        </div>

                        <button type="submit" class="btn btn-accent btn-block">
                            <i class="fas fa-calendar-check"></i> &nbsp; Xác Nhận Đặt Lịch
                        </button>
                    </form>

                    <div class="booking-success">
                        <div class="success-content">
                            <div class="success-icon">
                                <i class="fas fa-check"></i>
                            </div>
                            <h3>Đặt Lịch Thành Công!</h3>
                            <p>Chúng tôi đã nhận được yêu cầu của bạn. Nhân viên tư vấn của CleanHome sẽ gọi điện xác nhận trong 5 phút nữa.</p>
                            <button class="btn btn-primary" onclick="resetBooking()">Đặt Lịch Cho Ngày Khác</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="main-footer">
        <div class="footer-container">
            <div class="footer-brand">
                <a href="#" class="logo">
                    <span class="logo-icon">✨</span>
                    <span class="logo-text">Clean<span>Home</span></span>
                </a>
                <p>Dịch vụ dọn dẹp nhà cửa chuyên nghiệp, giúp bạn tận hưởng cuộc sống trọn vẹn hơn bên những người thân yêu.</p>
            </div>

            <div class="footer-contact">
                <h4>Liên Hệ</h4>
                <p>
                    <i class="fas fa-phone"></i>
                    <strong>Hotline:</strong> 1900 6789
                </p>
                <p>
                    <i class="fas fa-envelope"></i>
                    <strong>Email:</strong> support@cleanhome.example.com
                </p>
                <p>
                    <i class="fas fa-map-marker-alt"></i>
                    <strong>Địa Chỉ:</strong> TP. Hồ Chí Minh, Việt Nam
                </p>
            </div>
        </div>

        <div class="footer-bottom">
            <p>&copy; 2024 CleanHome. Tất cả quyền được bảo lưu.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
