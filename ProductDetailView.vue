<template>
    <main>
        <section class="product-detail">
            <div class="container">
                <div class="row gx-0">
                    <div class="col-12 col-lg-6 p-0">
                        <div class="px-lg-2 px-3 d-flex gap-4">
                            <div class="product-thumnail">
                                <div class="custom-thumnail__box mb-3">
                                    <img src="../img/p1.png" alt="" class="img-fluid">
                                </div>
                                <div class="custom-thumnail__box mb-3">
                                    <img src="../img/p1.png" alt="" class="img-fluid">
                                </div>
                                <div class="custom-thumnail__box my-3">
                                    <img src="../img/p1.png" alt="" class="img-fluid">
                                </div>
                                <div class="custom-thumnail__box my-3">
                                    <img src="../img/p1.png" alt="" class="img-fluid">
                                </div>
                                <div class="custom-thumnail__box my-3">
                                    <img src="../img/p1.png" alt="" class="img-fluid">
                                </div>
                            </div>
                            <div class="flex-fill">
                                <img src="../img/p1.png" alt="" class="rounded-4">
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6 p-0">
                        <div class="product-info px-5">
                            <a href="#" class="category-bkdetail__link mt-2">TÊN DANH MỤC</a>
                            <h2 class="text-start productname my-2">Áo thun nam nữ thể thao</h2>
                            <p class="text-muted fs-4">Mã sản phẩm: SP001</p>
                            <p class="mt-4">
                                <del class="fs-4 me-3" style="color: var(--colortext3);">300.000đ</del> 
                                <strong style="color:var(--accent); font-size: 1.9rem;">250.000đ</strong>
                            </p>
                            <div class=" d-flex align-items-center gap-2 mt-2 mb-3">
                                <i class="bi bi-star-fill color-star"></i>
                                <p class="m-0 me-1 fs-3 fw-bold" style="color: var(--colortext1);">5.0</p>
                                <i class="bi bi-dot fs-2" style="color: var(--colortext2);"></i>
                                <a href="#" class="m-0 fs-4 fw-regular fst-italic rating-link-view">Đánh giá (10)</a>
                            </div>
                            <p class="product-desc">
                                Áo thun nam thể thao phối bo cổ được thiết kế năng động, trẻ trung, phù hợp cho 
                                các hoạt động hàng ngày và tập luyện. Chất liệu vải thoáng khí, co giãn tốt, mang 
                                lại cảm giác thoải mái khi vận động.
                            </p>
                            <h5 class="mt-4 fs-4">Màu sắc:</h5>
                            <div class="color-options mt-3">
                                <div style="background: #ddd;"></div>
                                <div style="background: #c4aead;"></div>
                            </div>
                            <h5 class="mt-4 fs-4">Size:</h5>
                            <div class="size-options mt-3">
                                <div class="fs-4">S</div>
                                <div class="fs-4">M</div>
                                <div class="fs-4">L</div>
                                <div class="fs-4">XL</div>
                                <div class="fs-4">XXL</div>
                            </div>
                            <div class="mt-4 d-flex align-items-center gap-4">
                                <div><input type="number" class="form-date product-quantity" name="quantity" value="1" id=""></div>
                                <a href="" class="btn-order">Thêm vào giỏ hàng</a>
                                <div class="d-flex align-items-center gap-1 btn-add-wishlist">
                                    <div><i class="bi bi-heart-fill fs-3"></i></div>
                                    <div><i class="bi bi-facebook fs-3"></i></div>
                                    <div><i class="bi bi-messenger fs-3"></i></div>
                                    <div><i class="bi bi-share fs-3"></i></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="detail-infor">
            <div class="container">
                <ul class="d-flex list-unstyled detail-infor__list">
                    <li class="detail-infor__desc-rating">Mô tả</li>
                    <li class="detail-infor__desc-rating">Đánh giá</li>
                </ul>
                <div id="desc-box">
                    <div class="row gx-0">
                        <div class="col-12 col-lg-7">
                            <div class="padding-custom">
                                <!-- <h2 class="fs-1 text-start my-3">Thông tin chi tiết</h2> -->
                                <div>
                                    <h3 class="fs-3 fw-semibold text-start">1. Giới thiệu sân cầu lông Kỳ Hòa</h3>
                                    <ul class="mt-3">
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Sân cầu lông Kỳ Hòa có quy mô 11 sân ngoài trời, nổi tiếng với không gian rộng rãi, 
                                            thoáng mát, view cực đẹp. Hệ thống chiếu sáng LED hiện đại được bố trí đều trên sân, 
                                            đảm bảo đủ ánh sáng cho việc chơi Pickleball cả ban ngày lẫn ban đêm. Mặt sân chất lượng, 
                                            đạt chuẩn quốc tế, luôn được vệ sinh sạch sẽ và đảm bảo độ bám tốt. Khu vực nghỉ ngơi 
                                            rộng rãi, đầy đủ tiện nghi, giúp người chơi thư giãn và thoải mái.
                                        </li>
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Ngoài ra, nơi đây có tích hợp nhiều dịch vụ giải trí khác vô cùng tiện lợi nếu dẫn con 
                                            em đi theo. Có cho thuê vợt và bóng Pickleball với giá cả hợp lý. Bãi giữ xe rộng rãi, 
                                            có thể chứa cả ô tô và xe máy. Trang thiết bị tại sân đều mới, sạch sẽ và đạt chuẩn. 
                                            Pickleball D-Joy còn tổ chức các lớp học Pickleball cơ bản, giúp người chơi dễ tiếp cận 
                                            bộ môn này, đồng thời rèn luyện kỹ năng và nâng cao trình độ. Những người đến chơi tại đây 
                                            đều rất hòa đồng, thân thiện và tỏ ra hài lòng với trải nghiệm tại sân.
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <h3 class="fs-3 fw-semibold text-start">2. Giá thuê sân cầu lông Kỳ Hòa</h3>
                                    <ul class="mt-3">
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Dao động từ 140.000đ - 290.000đ/giờ tuỳ theo giờ chơi. 
                                        </li>
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Giá có thể thay đổi theo tình hình giờ giấc thực tế, nếu bạn muốn biết thêm chi tiết giá đặt sân, 
                                            các bạn có thể liên hệ hotline hoặc Zalo của sân để được tư vấn nhé.
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <h3 class="fs-3 fw-semibold text-start">3. Các dịch vụ tiện ích của sân</h3>
                                    <ul class="mt-3">
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Khu vực nghỉ ngơi rộng rãi và đầy đủ tiện nghi, giúp người chơi thư giãn thoải mái sau khi vận động.
                                        </li>
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Có cho thuê vợt và bóng Pickleball với giá cả hợp lý, tiện lợi cho những ai chưa trang bị sẵn.
                                        </li>
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Bãi giữ xe rộng rãi có thể chứa cả ô tô và xe máy, đảm bảo an toàn.
                                        </li>
                                        <li style="color: var(--colortext2); font-size: 1.5rem; line-height: 2.4rem; text-align: justify;">
                                            Cổ chức các lớp học Pickleball cơ bản, giúp người chơi dễ dàng tiếp cận bộ môn này, rèn luyện kỹ năng và nâng cao trình độ.
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-lg-5">
                            <div class="ps-5 pe-lg-0 pe-3 detail-infor__thumnail">
                                <div class="my-2"><img src="../img/p1.png" alt="" class="img-fluid"></div>
                                <div class="my-2"><img src="../img/p1.png" alt="" class="img-fluid"></div>
                                <div class="my-2"><img src="../img/p1.png" alt="" class="img-fluid"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="comment-box">
                    <div class="row gx-0 justify-content-between mt-5">
                        <div class="col-6">
                            <div class="comment-box__rating mt-4">
                                <div class="d-flex align-items-center justify-content-between gap-3">
                                    <h1 class="m-0 fw-semibold" style="font-size: 3.2rem;">5.0</h1>
                                    <div>
                                        <div class="d-flex align-items-center gap-2 mb-3">
                                            <i class="bi bi-star-fill fs-2 color-star"></i>
                                            <i class="bi bi-star-fill fs-2 color-star"></i>
                                            <i class="bi bi-star-fill fs-2 color-star"></i>
                                            <i class="bi bi-star-fill fs-2 color-star"></i>
                                            <i class="bi bi-star-fill fs-2 color-star"></i>
                                        </div>
                                        <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3);">
                                            10 đánh giá
                                        </p>
                                    </div>
                                </div>
                                <hr style="color: var(--colortext3);">
                                <div class="d-flex align-items-center justify-content-between my-4 mt-5">
                                    <h3 style="width:5%; font-size: 2rem;">5</h3>
                                    <i class="bi bi-star-fill fs-3 color-star"></i>
                                    <div class="bkdt__percent-rating">
                                        <div class="bkdt__percent-rating-child percent100"></div>
                                    </div>
                                    <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3); width: 90px;">
                                        10 đánh giá
                                    </p>
                                </div>
                                <div class="d-flex align-items-center justify-content-between my-4">
                                    <h3 style="width:5%; font-size: 2rem;">4</h3>
                                    <i class="bi bi-star-fill fs-3 color-star"></i>
                                    <div class="bkdt__percent-rating">
                                        <div class="bkdt__percent-rating-child"></div>
                                    </div>
                                    <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3); width: 90px;">
                                        0 đánh giá
                                    </p>
                                </div>
                                <div class="d-flex align-items-center justify-content-between my-4">
                                    <h3 style="width:5%; font-size: 2rem;">3</h3>
                                    <i class="bi bi-star-fill fs-3 color-star"></i>
                                    <div class="bkdt__percent-rating">
                                        <div class="bkdt__percent-rating-child"></div>
                                    </div>
                                    <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3); width: 90px;">
                                        0 đánh giá
                                    </p>
                                </div>
                                <div class="d-flex align-items-center justify-content-between my-4">
                                    <h3 style="width:5%; font-size: 2rem;">2</h3>
                                    <i class="bi bi-star-fill fs-3 color-star"></i>
                                    <div class="bkdt__percent-rating">
                                        <div class="bkdt__percent-rating-child"></div>
                                    </div>
                                    <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3); width: 90px;">
                                        0 đánh giá
                                    </p>
                                </div>
                                <div class="d-flex align-items-center justify-content-between my-4">
                                    <h3 style="width:5%; font-size: 2rem;">1</h3>
                                    <i class="bi bi-star-fill fs-3 color-star"></i>
                                    <div class="bkdt__percent-rating">
                                        <div class="bkdt__percent-rating-child"></div>
                                    </div>
                                    <p class="fs-4 fst-italic m-0 text-end" style="color: var(--colortext3); width: 90px;">
                                        0 đánh giá
                                    </p>
                                </div>

                                <p class="my-5 py-2 fs-3" style="color: var(--colortext2);">Dựa trên 10 đánh giá đến từ khách hàng</p>
                            </div>
                        </div>
                        <div class="col-5">
                            <div style="background-color: var(--white); border-radius: 12px; box-shadow: 0 0 16px var(--shadow2);">
                                <h2 class="m-0 fs-2 fw-semibold text-start" style="padding: 24px;">Tất cả bình luận</h2>
                                <div class="comment-box__comment-content mt-1">
                                    <div class="px-5">
                                        <div class="d-flex gap-4 flex-fill">
                                            <div class="bkdt__comment-user">
                                                <img src="../img/user1.jpg" alt="" class="img-fluid rounded-circle">
                                            </div>
                                            <div>
                                                <div class="">
                                                    <h3 class="fs-3 text-start m-0">Han Truong (张昕)</h3>
                                                    <div class="d-flex align-items-center gap-3">
                                                        <div class="d-flex align-items-center gap-1 mb-1">
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                        </div>
                                                        <i class="bi bi-dot fs-4" style="color: var(--colortext2);"></i>
                                                        <p class="m-0 fs-4 hidden-text" style="color: var(--colortext3);">18 tháng 2, 2025</p>
                                                        <div class="flex-fill">
                                                            <i class="bi bi-hand-thumbs-up-fill fs-2 color-star"></i>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <p class="m-0 mt-2" style="color: var(--colortext1); font-size: 1.5rem; line-height: 2rem;">Sân cầu lông rộng rãi, thoáng mát, mặt sân đạt chuẩn giúp di chuyển linh hoạt.</p>
                                                </div>

                                            </div>
                                        </div>
                                        <hr style="color: var(--colortext3); margin: 24px 0 20px 0;">
                                    </div>
                                    <div class="px-5">
                                        <div class="d-flex gap-4 flex-fill">
                                            <div class="bkdt__comment-user">
                                                <img src="../img/user1.jpg" alt="" class="img-fluid rounded-circle">
                                            </div>
                                            <div>
                                                <div class="">
                                                    <h3 class="fs-3 text-start m-0">Han Truong (张昕)</h3>
                                                    <div class="d-flex align-items-center gap-3">
                                                        <div class="d-flex align-items-center gap-1 mb-1">
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                        </div>
                                                        <i class="bi bi-dot fs-4" style="color: var(--colortext2);"></i>
                                                        <p class="m-0 fs-4 hidden-text" style="color: var(--colortext3);">18 tháng 2, 2025</p>
                                                        <div class="flex-fill">
                                                            <i class="bi bi-hand-thumbs-up-fill fs-2 color-star"></i>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <p class="m-0 mt-2" style="color: var(--colortext1); font-size: 1.5rem; line-height: 2rem;">Sân cầu lông rộng rãi, thoáng mát, mặt sân đạt chuẩn giúp di chuyển linh hoạt.</p>
                                                </div>

                                            </div>
                                        </div>
                                        <hr style="color: var(--colortext3); margin: 24px 0 20px 0;">
                                    </div>
                                    <div class="px-5">
                                        <div class="d-flex gap-4 flex-fill">
                                            <div class="bkdt__comment-user">
                                                <img src="../img/user1.jpg" alt="" class="img-fluid rounded-circle">
                                            </div>
                                            <div>
                                                <div class="">
                                                    <h3 class="fs-3 text-start m-0">Han Truong (张昕)</h3>
                                                    <div class="d-flex align-items-center gap-3">
                                                        <div class="d-flex align-items-center gap-1 mb-1">
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                        </div>
                                                        <i class="bi bi-dot fs-4" style="color: var(--colortext2);"></i>
                                                        <p class="m-0 fs-4 hidden-text" style="color: var(--colortext3);">18 tháng 2, 2025</p>
                                                        <div class="flex-fill">
                                                            <i class="bi bi-hand-thumbs-up-fill fs-2 color-star"></i>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <p class="m-0 mt-2" style="color: var(--colortext1); font-size: 1.5rem; line-height: 2rem;">Sân cầu lông rộng rãi, thoáng mát, mặt sân đạt chuẩn giúp di chuyển linh hoạt.</p>
                                                </div>

                                            </div>
                                        </div>
                                        <hr style="color: var(--colortext3); margin: 24px 0 20px 0;">
                                    </div>
                                    <div class="px-5">
                                        <div class="d-flex gap-4 flex-fill">
                                            <div class="bkdt__comment-user">
                                                <img src="../img/user1.jpg" alt="" class="img-fluid rounded-circle">
                                            </div>
                                            <div>
                                                <div class="">
                                                    <h3 class="fs-3 text-start m-0">Han Truong (张昕)</h3>
                                                    <div class="d-flex align-items-center gap-3">
                                                        <div class="d-flex align-items-center gap-1 mb-1">
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                            <i class="bi bi-star-fill fs-4 color-star"></i>
                                                        </div>
                                                        <i class="bi bi-dot fs-4" style="color: var(--colortext2);"></i>
                                                        <p class="m-0 fs-4 hidden-text" style="color: var(--colortext3);">18 tháng 2, 2025</p>
                                                        <div class="flex-fill">
                                                            <i class="bi bi-hand-thumbs-up-fill fs-2 color-star"></i>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div>
                                                    <p class="m-0 mt-2" style="color: var(--colortext1); font-size: 1.5rem; line-height: 2rem;">Sân cầu lông rộng rãi, thoáng mát, mặt sân đạt chuẩn giúp di chuyển linh hoạt.</p>
                                                </div>

                                            </div>
                                        </div>
                                        <hr style="color: var(--colortext3); margin: 24px 0 20px 0;">
                                    </div>
                                </div>
                                <form action="" class="p-5 pt-2">
                                    <input type="text" class="form-date d-block w-100" placeholder="Viết bình luận...">
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="popular-y mx-lg-auto mx-2">
            <div class="container">
                <div class="d-flex justify-content-between align-items-center mb-2 px-2">
                    <h1 class="title-section">ĐỀ XUẤT CHO BẠN</h1>
                    <a href="" class="seemore">
                        <div>Xem thêm</div>
                        <i class="bi bi-caret-right-fill"></i>
                    </a>
                </div>
                <div class="row gx-0">
                    <div class="col-12 col-lg-3 col-md-6 p-0">
                        <div class="product my-3">
                            <a href="#" class="link-img-p">
                                <img src="../img/p1.png" alt="" class="img-fluid">
                            </a>
                            <div class="product-infor">
                                <a href="#" class="m-0 title-product fs-3">Áo thun Unisex phối bo cổ</a>
                                <div class="d-flex align-items-center gap-2 pt-1 pb-2">
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill fs-5 color-star-gray"></i>
                                    <p class="text-rating m-0 ms-3 fs-4">(4/5)</p>
                                </div>
                                <div class="text-location py-2">
                                    <p class="m-0">Áo thun nam thể thao phối bo cổ được thiết kế năng động, trẻ trung</p>
                                </div>
                                <div class="d-flex align-items-center gap-2 text-location">
                                    <i class="bi bi-eye"></i>
                                    <p class="custom-open m-0">Lượt xem: 230</p>
                                </div>
                                <div class="price d-flex align-items-end gap-4">
                                    <p class="m-0">240.000đ</p>
                                    <del>320.000đ</del>
                                </div>
                            </div>
                            <div class="atc-love-box">
                                <a href="" class="atc-love"><i class="bi bi-heart-fill"></i></a>
                                <a href="" class="atc-love atc-icon"><i class="bi bi-cart-fill"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-3 col-md-6 p-0">
                        <div class="product my-3">
                            <a href="#" class="link-img-p">
                                <img src="../img/p1.png" alt="" class="img-fluid">
                            </a>
                            <div class="product-infor">
                                <a href="#" class="m-0 title-product fs-3">Áo thun Unisex phối bo cổ</a>
                                <div class="d-flex align-items-center gap-2 pt-1 pb-2">
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill fs-5 color-star-gray"></i>
                                    <p class="text-rating m-0 ms-3 fs-4">(4/5)</p>
                                </div>
                                <div class="text-location py-2">
                                    <p class="m-0">Áo thun nam thể thao phối bo cổ được thiết kế năng động, trẻ trung</p>
                                </div>
                                <div class="d-flex align-items-center gap-2 text-location">
                                    <i class="bi bi-eye"></i>
                                    <p class="custom-open m-0">Lượt xem: 230</p>
                                </div>
                                <div class="price d-flex align-items-end gap-4">
                                    <p class="m-0">240.000đ</p>
                                    <del>320.000đ</del>
                                </div>
                            </div>
                            <div class="atc-love-box">
                                <a href="" class="atc-love"><i class="bi bi-heart-fill"></i></a>
                                <a href="" class="atc-love atc-icon"><i class="bi bi-cart-fill"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-3 col-md-6 p-0">
                        <div class="product my-3">
                            <a href="#" class="link-img-p">
                                <img src="../img/p1.png" alt="" class="img-fluid">
                            </a>
                            <div class="product-infor">
                                <a href="#" class="m-0 title-product fs-3">Áo thun Unisex phối bo cổ</a>
                                <div class="d-flex align-items-center gap-2 pt-1 pb-2">
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill fs-5 color-star-gray"></i>
                                    <p class="text-rating m-0 ms-3 fs-4">(4/5)</p>
                                </div>
                                <div class="text-location py-2">
                                    <p class="m-0">Áo thun nam thể thao phối bo cổ được thiết kế năng động, trẻ trung</p>
                                </div>
                                <div class="d-flex align-items-center gap-2 text-location">
                                    <i class="bi bi-eye"></i>
                                    <p class="custom-open m-0">Lượt xem: 230</p>
                                </div>
                                <div class="price d-flex align-items-end gap-4">
                                    <p class="m-0">240.000đ</p>
                                    <del>320.000đ</del>
                                </div>
                            </div>
                            <div class="atc-love-box">
                                <a href="" class="atc-love"><i class="bi bi-heart-fill"></i></a>
                                <a href="" class="atc-love atc-icon"><i class="bi bi-cart-fill"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-3 col-md-6 p-0">
                        <div class="product my-3">
                            <a href="#" class="link-img-p">
                                <img src="../img/p1.png" alt="" class="img-fluid">
                            </a>
                            <div class="product-infor">
                                <a href="#" class="m-0 title-product fs-3">Áo thun Unisex phối bo cổ</a>
                                <div class="d-flex align-items-center gap-2 pt-1 pb-2">
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill color-star fs-5"></i>
                                    <i class="bi bi-star-fill fs-5 color-star-gray"></i>
                                    <p class="text-rating m-0 ms-3 fs-4">(4/5)</p>
                                </div>
                                <div class="text-location py-2">
                                    <p class="m-0">Áo thun nam thể thao phối bo cổ được thiết kế năng động, trẻ trung</p>
                                </div>
                                <div class="d-flex align-items-center gap-2 text-location">
                                    <i class="bi bi-eye"></i>
                                    <p class="custom-open m-0">Lượt xem: 230</p>
                                </div>
                                <div class="price d-flex align-items-end gap-4">
                                    <p class="m-0">240.000đ</p>
                                    <del>320.000đ</del>
                                </div>
                            </div>
                            <div class="atc-love-box">
                                <a href="" class="atc-love"><i class="bi bi-heart-fill"></i></a>
                                <a href="" class="atc-love atc-icon"><i class="bi bi-cart-fill"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>