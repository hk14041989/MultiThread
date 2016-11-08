# MultiThread
Example về Multi Thread:
+ Sử dụng BackgroundWorker để nhận lại kết quả khi chia thread chạy tính toán.
+ Khi click vào button Synchronous (same thread) là trường hợp chạy 1 luồng thông thường, chạy xong mới in ra kết quả
+ Khi click vào button Asynchronous (worker thread) là trường hợp chạy nhiều luồng, mỗi luồng khi tính toán ra kết quả thì sẽ gửi kết quả 
cho backgroundworker.
Chạy 2 trường hợp để thấy sự khác biệt giữa single thread và multi thread
