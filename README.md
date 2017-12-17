# Example application with spring-boot [CLI]

If you want to quick start without prior knowledge of java developement then looks at [Generate Spring Application](https://start.spring.io/)
Or you can generate product with CLI with [SDKMAN](http://sdkman.io/).

Steps to follow for CLI (Mac/terminal)

1. curl -s "https://get.sdkman.io" | bash
2. sdk install springboot
3. spring --version (verify installation)
4. sdk ls springboot (List Spring Boot Version)
5. Create app.groovy
    ```
    @RestController
    class ThisWillActuallyRun {
    
        @RequestMapping("/")
        String home() {
            "Hello World!"
        }
    }  
    ``` 

6. spring run app.groovy
7. Open http://localhost:8080 in browser.
 

