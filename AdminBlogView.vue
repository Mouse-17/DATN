<template>
    <main>
        <section class="admin">
            <div class="container">
                <div class="row gx-0">
                    <!-- Bên trái -->
                    <div class="col-12 col-lg-3 col-md-6 p-0 mt-2 admin-left">
                        <img src="../../../public/img/user1.jpg" alt="" class="admin-avatar">
                        <h5>Admin</h5>
                        <RouterLink to="/admin" class=""><i class="bi bi-palette2"></i>Bảng điều khiển</RouterLink>
                        <RouterLink to="/admin/quanlidanhmuc"><i class="bi bi-inboxes-fill"></i>Quản lý danh mục</RouterLink>
                        <RouterLink to="/admin/quanlisanpham"><i class="bi bi-box2-fill"></i>Quản lý sản phẩm</RouterLink>
                        <RouterLink to="/admin/quanlinguoidung"><i class="bi bi-people-fill"></i>Quản lý người dùng</RouterLink>
                        <RouterLink to="/admin/quanlidonhang"><i class="bi bi-receipt-cutoff"></i>Quản lý đơn hàng</RouterLink>
                        <RouterLink to="/admin/quanlibinhluan"><i class="bi bi-chat-fill"></i>Quản lý bình luận</RouterLink>
                        <RouterLink to="/admin/quanlibaiviet"><i class="bi bi-book-fill"></i>Quản lý bài viết</RouterLink>
                        <RouterLink to="/admin/quanlidanhgia"><i class="bi bi-star-fill"></i>Quản lý đánh giá</RouterLink>
                        <div class="tienichadmin-left">
                            <a href="#"><i class="bi bi-gear"></i>CÀI ĐẶT</a>
                            <a href="#"><i class="bi bi-question-circle"></i>TRỢ GIÚP</a>
                            <a href="#"><i class="bi bi-info-circle"></i>THOÁT</a>
                        </div>
                    </div>

                    <!-- Bên phải -->
                    <div class="col-lg-9 admin-right">
                        <div class="header-container">
                            <div class="title-section">
                                <h5>Danh sách bài viết</h5>
                                <p class="text-muted">Xem và tìm kiếm bài viết</p>
                            </div>
                            <a href="adminaddbaiviet.html"><button class="add-post-button"><i class="bi bi-plus-lg"></i>Thêm bài viết</button></a>
                        </div>                    

                        <ul class="nav nav-tabs">
                            <li class="nav-item">
                                <a class="nav-link active" href="#">Tất cả bài viết</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Chưa đăng</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Xử lý bài viết</a>
                            </li>
                        </ul>

                        <div class="d-flex justify-content-between align-items-center mt-3 filter-search-container">
                            <button class="btn btn-lg btn-light">
                                <i class="bi bi-plus-lg"></i> Thêm điều kiện lọc
                            </button>
                            <div class="input-group search-box">
                                <input type="text" class="form-control" placeholder="Tìm kiếm">
                                <span class="input-group-text"><i class="bi bi-search"></i></span>
                            </div>
                        </div>

                        <table class="table table-bordered table-hover mt-3">
                            <thead class="table-dark">
                                <tr>
                                    <th class="input-head"><input type="checkbox"></th>
                                    <th>Tên bài viết</th>
                                    <th>Tiêu đề</th>
                                    <th>Tác giả</th>
                                    <th>Nội dung</th>
                                    <th>Trạng thái</th>
                                    <th>Hành động</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td class="input-head"><input type="checkbox"></td>
                                    <td>Cầu lông</td>
                                    <td>Cầu lông</td>
                                    <td>Nga</td>
                                    <td>Cầu lông có thể đổi luật tính điểm...</td>
                                    <td>Đang đăng</td>
                                    <td>
                                        <i class="bi bi-eye me-2"></i>
                                        <i class="bi bi-pencil-square me-2"></i>
                                        <i class="bi bi-trash"></i>
                                    </td>
                                </tr>
                                <tr>
                                    <td  class="input-head"><input type="checkbox"></td>
                                    <td>Bóng đá</td>
                                    <td>Bóng đá</td>
                                    <td>Minh</td>
                                    <td>Cầu lông có thể đổi luật tính điểm...</td>
                                    <td>Đang đăng</td>
                                    <td>
                                        <i class="bi bi-eye me-2"></i>
                                        <i class="bi bi-pencil-square me-2"></i>
                                        <i class="bi bi-trash"></i>
                                    </td>
                                </tr>
                                <tr>
                                    <td  class="input-head"><input type="checkbox"></td>
                                    <td>Bóng đá</td>
                                    <td>Bóng đá</td>
                                    <td>Minh</td>
                                    <td>Cầu lông có thể đổi luật tính điểm...</td>
                                    <td>Đang đăng</td>
                                    <td>
                                        <i class="bi bi-eye me-2"></i>
                                        <i class="bi bi-pencil-square me-2"></i>
                                        <i class="bi bi-trash"></i>
                                    </td>
                                </tr>
                                <tr>
                                    <td  class="input-head"><input type="checkbox"></td>
                                    <td>Bóng đá</td>
                                    <td>Bóng đá</td>
                                    <td>Minh</td>
                                    <td>Cầu lông có thể đổi luật tính điểm...</td>
                                    <td>Đang đăng</td>
                                    <td>
                                        <i class="bi bi-eye me-2"></i>
                                        <i class="bi bi-pencil-square me-2"></i>
                                        <i class="bi bi-trash"></i>
                                    </td>
                                </tr>
                                <!-- Thêm các dòng khác nếu cần -->
                            </tbody>
                        </table>

                        <div class="d-flex justify-content-between align-items-center mt-3">
                            <span>Cài đặt</span>
                            <nav class="pagination-container">
                                <ul class="pagination">
                                    <li class="page-item"><a class="page-link" href="#">«</a></li>
                                    <li class="page-item"><a class="page-link" href="#">1</a></li>
                                    <li class="page-item"><a class="page-link" href="#">2</a></li>
                                    <li class="page-item"><a class="page-link" href="#">3</a></li>
                                    <li class="page-item"><a class="page-link" href="#">»</a></li>
                                </ul>
                            </nav>
                        </div>  
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<style>
    .form-group {
        display: flex;
        gap: 20px;
        align-items: stretch;
        font-size: 28px;
    }

    .right-left, .right-right {
        flex: 1;
        display: flex;
        flex-direction: column;
    }
    label{
        font-size: 16px;
        margin-bottom: 5px;
    }
    .right-left label{
        margin-bottom: 5px;
    }
    .right-left input{
        margin-bottom: 10px;
    }
    #status, #essay-name, #essay-title, #writer-name {
        padding: 10px 5px;
    }
    .right-right textarea {
        flex: 1;
        height: 100%;
        padding: 5px;
    }
    h2
    {
        margin-bottom: 20px;
        font-weight: bolder;
        text-align: left;
    }
    .submit-btn {
        display: block;
        margin: 20px auto;
        padding: 15px 25px;
        background-color: #C99928;
        color: white;
        border: none;
        cursor: pointer;
        font-size: 18px;
        border-radius: 8px;
    }
</style>