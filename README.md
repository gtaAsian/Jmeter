<div class="content">
    <h1>BÁO CÁO KIỂM THỬ HIỆU SUẤT JMETER</h1>
    <ol>
        <p><strong>Tên Dự Án:</strong> loadTesting of APIs</p>
        <p><strong>Ngày Kiểm Thử:</strong> 27/05/2024</p>
        <p><strong>Người Kiểm Thử:</strong> Giang Thành An</p>
        <p><strong>1. Mục Tiêu Kiểm Thử:</strong> Sử dụng Jmeter để kiểm tra hiệu năng trang WEB</p>
        <p><strong>2. Môi Trường Kiểm Thử:</strong> Jmeter.</p>
        <p><strong>3. Phương Pháp Kiểm Thử:</strong> Kiểm thử tự động và thủ công trên phần mềm Jmeter.</p>
        4.
         <strong>Kịch Bản Kiểm Thử lần 1:</strong>
            <ul>
            <li><p>Tên Kịch Bản: Kiểm thử cơ bản của 1 trang WEB</p></li>
            <li><p>Mục Đích: Test năng hoạt động của một trang web và phần mềm Jmeter</p></li>
            <li><p>HTTP request: www.simplilearn.com</p></li>
            <li><p>Tham Số: Resouces, Business</p></li>
            <li><p>Number of thread (user): 1</p></li>
            <li><p>Ramp-up period ( seconds): 1</p></li>
            <li><p>Loop-count : 1</p></li>
            <li><p>Kết Quả Mong Đợi: Gửi yêu cầu thành công</p></li>
            <li><p>Kết Quả Thực Tế: Đã gửi yêu cầu thành công</p></li>
            <li><p>Trạng Thái: Thành công</p></li>
            <li><p>Kết quả sau khi test:</p></li>
            <img width="1680" alt="Ảnh màn hình 2024-05-27 lúc 14 13 45" src="https://github.com/gtaAsian/Jmeter/assets/170786444/e9529079-f7f6-43e0-818d-535dc613f8c2">
            <li><p>Thời gian phản hồi trung bình: 8 giây</p></li>
            <li><p>Tỷ lệ yêu cầu thành công: 100%</p></li>
            </ul>
        <strong>Kịch Bản Kiểm Thử lần 2:</strong>
            <ul>
            <li><p>Tên Kịch Bản: Kiểm thử cơ bản của 1 trang WEB</p></li>
            <li><p>Mục Đích: Test năng hoạt động của một trang web khi thay đổi biến số</p></li>
            <li><p>HTTP request: www.simplilearn.com</p></li>
            <li><p>Tham Số: Resouces, Business</li>
            <li><p>Number of thread (user): 10</p></li>
            <li><p>Ramp-up period ( seconds): 2</p></li>
            <li><p>Loop-count : 10</p></li>
            <li><p>Kết Quả Mong Đợi: Gửi yêu cầu thành công</p></li>
            <li><p>Kết Quả Thực Tế: Đã gửi yêu cầu thành công</p></li>
            <li><p>Trạng Thái: Thành công</p></li>
            <li><p>Kết quả sau khi test:</p></li>
            <img width="1680" alt="Ảnh màn hình 2024-05-27 lúc 14 15 15" src="https://github.com/gtaAsian/Jmeter/assets/170786444/27faca0c-1cec-49be-82cc-068c472e6a80">
            <li><p>Thời gian phản hồi trung bình: vô hạn</p></li>
            <li><p>Tỷ lệ yêu cầu thành công: 100%</p></li>
            </ul>
