Spring Application Context: hay container, dùng để quản lý component cho application
Bean: Các component
Depedency Injection: 


Cấu trúc Project Spring Boot:
mvnw and mvnw.cmd: Dùng để build dự án bằng Maven dù không có Maven
main/resources/aplication.properties
main/resources/static: Bỏ hình ảnh, nội dung tĩnh vào đây
main/resources/template:

Các depedencies có "starter": Bản thân chúng không phải thư viện, chúng là tập hợp của nhiều depedencies khác nhau.
Lợi ích
- Không cần khai báo nhiều dependencies
- Tên dễ nhớ cho mục đích sử dụng
- Tương thích phiên bản Spring Boot đang chạy

@SpringBootApplication: Tập hợp của 3 annotation:
- @SpringBootConfiguration: Chỉ định class này là configuration class (Mặc dù class này có thể không có config)
- @EnableAutoConfiguration
- @ComponentScan: Cho phép class này có thể scan @Component, @Service, @Controller được đinh nghĩa ở nơi khác

### Các bước chạy của hàm main() trong Spring Boot

```java
SpringApplication.run(TacoCloudApplication.class, args);
```

Gọi hàm static run() của SpringApplication, khởi tạo Spring Boot Context




@SpringBootTest: Annotation gọi JUnit để "bootstrap" ứng dụng Spring


[[Test API MVC với @WebMvcTest]]
[[Xử lý web request trong Spring Boot]]
