#java #multithreading

Có 2 loại Thread trong Java:
- [[User Thread]]: 
	- Thread được tạo từ ứng dụng bởi người dùng. 
	- Chúng là thread có độ ưu tiên cao (high priority).
	- JVM sẽ không ngừng thực thi cho đến khi nào User Thread được xử lý hoàn toàn. 
	- Chương trình sẽ kết thúc nếu User Thread thực thi xong.
- [[Daemon Thread]]: Thread chạy ngầm dùng để bổ trợ cho User Thread
	- Là thread chạy ngầm dưới ứng dụng (background task).
	- Hầu hết là những thread do JVM tạo ra dùng để xử lý các công vụ như dọn dẹp (Garbage Collection)
	- Là những Thread có độ ưu tiên thấp
	- JVM sẽ không đợi những Daemon Thread thực thi xong, và chúng chỉ kết thúc khi User Thread hoàn thành
	- JVM vẫn sẽ kết thúc quá trình chạy cho dù Daemon Thread vẫn còn chạy


