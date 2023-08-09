```java
package com.learning.tacocloud.controller;  
  
import org.springframework.stereotype.Controller;  
import org.springframework.web.bind.annotation.GetMapping;  
  
@Controller  
public class HomeController {  
	@GetMapping("/")  
	public String home() {  
		return "home";  
	}  
}
```

@Controller: Đánh dấu đây là Controller, giúp cho @ComponentScan có thể quét được, vào trong Spring Application Context và tạo ra 1 instance HomeController

Lưu ý: [[@Component @Controller @Service @Repository]]

