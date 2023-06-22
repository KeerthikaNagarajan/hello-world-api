# Create an API to print HELLO WORLD
## AIM:
To create an API to print HELLO WORLD using Springboot.
## ALGORITHM:
1. Create a new Spring Boot project using your preferred development environment (e.g., IntelliJ, Eclipse, or Spring Initializr).
2. Create a new Java class, such as HelloController, and annotate it with @RestController. This annotation indicates that this class will handle incoming HTTP requests and provide responses.
3. Within the HelloController class, create a method annotated with @GetMapping (or @RequestMapping) to handle HTTP GET requests. For example, you can create a method called sayHello().
4. Return a simple string message, such as "Hello, World!".
5. Start the Spring Boot application, which will launch an embedded web server.
## PROGRAM:
```java
package com.hello.world;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@SpringBootApplication
@RestController

public class WorldApplication {

	public static void main(String[] args) {
		SpringApplication.run(WorldApplication.class, args);
	}
		@GetMapping("/")
		public String HelloWorld()
	{
			return "Hello World";
		}
	}

```
## OUTPUT:
<img width="521" alt="image" src="https://github.com/KeerthikaNagarajan/hello-world-api/assets/93427089/65077939-f516-42ef-b0f7-e9cdc7682663">

## RESULT:
To create an API to print HELLO WORLD using Springboot was successfully done.


