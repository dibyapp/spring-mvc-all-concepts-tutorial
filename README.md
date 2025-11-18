# 🌐 Spring MVC - Complete Tutorial Repository

<div align="center">

![Spring MVC](https://img.shields.io/badge/Spring%20MVC-5.2.5-brightgreen?logo=spring)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.3.0-brightgreen?logo=springboot)
![Spring Security](https://img.shields.io/badge/Spring%20Security-5.3.2-success?logo=springsecurity)
![Java](https://img.shields.io/badge/Java-1.8-orange?logo=java)
![Maven](https://img.shields.io/badge/Maven-Build-red?logo=apachemaven)
![License](https://img.shields.io/badge/License-MIT-blue)

**Master Spring MVC with 44+ hands-on projects covering every concept from basics to enterprise patterns**

*From your first MVC app to production-ready web applications with security, validation, and batch processing*

[Getting Started](#-getting-started) • [Project Catalog](#-project-catalog) • [Learning Path](#-learning-path) • [Contributing](#-contributing)

</div>

---

## 📖 Table of Contents

- [About This Repository](#-about-this-repository)
- [Why This Repository?](#-why-this-repository)
- [What You'll Learn](#-what-youll-learn)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
- [Project Catalog](#-project-catalog)
  - [Basic MVC Applications](#1-basic-mvc-applications)
  - [100% Code-Driven (No XML)](#2-100-code-driven-no-xml)
  - [CRUD Operations](#3-crud-operations)
  - [Form Handling & Validation](#4-form-handling--validation)
  - [Spring Security](#5-spring-security)
  - [Session Management](#6-session-management)
  - [Spring Boot MVC](#7-spring-boot-mvc)
  - [Advanced Features](#8-advanced-features)
- [Learning Path](#-learning-path)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Configuration Approaches](#-configuration-approaches)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)

---

## 🎯 About This Repository

This repository is your **complete guide to Spring MVC** with **44+ independent Maven projects** demonstrating every aspect of building web applications with Spring Framework. From rendering your first JSP page to implementing enterprise-grade security and batch processing, this repository covers it all.

### 🎓 Perfect For:

- **Beginners** learning Spring MVC from scratch
- **Developers** migrating from traditional Spring MVC to Spring Boot
- **Teams** looking for reference implementations and best practices
- **Interview Preparation** - covers common Spring MVC interview topics
- **Architects** evaluating different configuration approaches
- **Full-Stack Developers** building Java web applications

---

## 💡 Why This Repository?

### ✨ What Makes This Special?

| Feature | Description |
|---------|-------------|
| 🎯 **Progressive Learning** | 44 projects organized from basic to advanced |
| 🔄 **Multiple Config Styles** | XML, Annotations, Java Config, and Spring Boot |
| 🏗️ **Production Patterns** | Layered architecture, security, validation, file handling |
| 📚 **Comprehensive Coverage** | Every Spring MVC concept with working examples |
| 🧩 **Problem-Solution Format** | Real problems (like double-posting) with multiple solutions |
| 🚀 **Modern & Legacy** | Traditional Spring MVC + Modern Spring Boot |
| 💼 **Real-World Projects** | Employee management, patient registration, login systems |
| 🔒 **Security Focus** | 7 security projects with different authentication methods |

---

## 📚 What You'll Learn

<details open>
<summary><b>Core Spring MVC Concepts</b></summary>

- ✅ DispatcherServlet configuration and lifecycle
- ✅ Controllers (@Controller, ParameterizableViewController, AbstractController)
- ✅ Handler Mappings (SimpleUrlHandlerMapping, RequestMappingHandlerMapping)
- ✅ View Resolvers (InternalResourceViewResolver, TilesViewResolver)
- ✅ Request Mapping (@RequestMapping, @GetMapping, @PostMapping, @PathVariable)
- ✅ Model & ModelAndView
- ✅ @ModelAttribute for data binding
- ✅ Form Tag Libraries
- ✅ Request/Session/Application scopes
</details>

<details open>
<summary><b>Advanced MVC Features</b></summary>

- ✅ Form Controllers (SimpleFormController pattern)
- ✅ Data Binding and Type Conversion
- ✅ Validation (JSR-303/Hibernate Validator & Programmatic)
- ✅ @InitBinder for custom property editors
- ✅ Reference Data handling
- ✅ Session Management (@SessionAttributes, Flash Attributes, HttpSession)
- ✅ File Upload/Download (MultipartResolver)
- ✅ Exception Handling
- ✅ Interceptors
- ✅ Two-Container Architecture (Parent-Child contexts)
</details>

<details open>
<summary><b>Spring Security Integration</b></summary>

- ✅ Form-based Authentication
- ✅ Database Authentication
- ✅ Properties File Authentication
- ✅ LDAP Authentication
- ✅ Password Encryption (BCrypt)
- ✅ Method-level Security
- ✅ Custom Login Pages
</details>

<details open>
<summary><b>Enterprise Features</b></summary>

- ✅ Spring Boot MVC Applications
- ✅ Internationalization (i18n)
- ✅ Apache Tiles Integration
- ✅ Pagination
- ✅ Spring Batch Processing
- ✅ Connection Pooling (HikariCP)
- ✅ Layered Architecture (Controller → Service → DAO)
- ✅ CRUD Operations with Spring JDBC
</details>

---

## 🔧 Prerequisites

Before you begin, ensure you have:

- ☕ **Java JDK 1.8** or higher
- 📦 **Apache Maven 3.x**
- 🌐 **Apache Tomcat 9.x** or any Servlet 4.0+ container
- 🛠️ **IDE** (IntelliJ IDEA Ultimate, Eclipse IDE for Enterprise Java, or VS Code with extensions)
- 🗄️ **Oracle Database** (optional - only for JDBC/CRUD examples)
- 📖 Basic understanding of:
  - Java and OOP
  - Servlets & JSP
  - HTML/CSS
  - Spring Core concepts

---

## 🚀 Getting Started

### Quick Start (Non-Boot Projects)

```bash
# Clone the repository
git clone https://github.com/dibyapp/spring-mvc-all-concepts-tutorial.git

# Navigate to a project
cd spring-mvc-all-concepts-tutorial/Annotations-ShowHomePage

# Build the project
mvn clean package

# Deploy the WAR file to Tomcat
cp target/ProjectName.war $TOMCAT_HOME/webapps/

# Start Tomcat and access
# http://localhost:8080/ProjectName
```

### Quick Start (Spring Boot Projects)

```bash
# Navigate to a Boot project
cd spring-mvc-all-concepts-tutorial/Boot-ShowHomePage

# Run with Maven
mvn spring-boot:run

# Access at http://localhost:8080
```

### Running in IDE

1. **Import** as Maven project
2. **Configure** Tomcat server (for non-Boot projects)
3. **Deploy** and run on server
4. **Access** via browser at `http://localhost:8080`

---

## 📁 Project Catalog

### 1️⃣ Basic MVC Applications

Get started with Spring MVC fundamentals.

| Project | Concept | Configuration |
|---------|---------|---------------|
| `ShowingHomePage` | Basic MVC setup | XML |
| `Annotations-ShowHomePage` | Basic with annotations | Annotations + XML |
| `Boot-ShowHomePage` | Basic with Boot | Spring Boot |
| `FrontController` | Front Controller pattern | XML |
| `WishApp-PVC` | ParameterizableViewController | XML |
| `WishApp-AC` | AbstractController | XML |
| `WishApp-UFVC` | UrlFilenameViewController | XML |
| `WishApp-ServiceClass` | Service layer integration | Annotations |

**💡 Key Learning:** Understand MVC architecture, DispatcherServlet, and basic request handling.

---

### 2️⃣ 100% Code-Driven (No XML)

Modern Spring MVC without any XML configuration.

| Project | Concept | Key Classes |
|---------|---------|-------------|
| `100Percent-CodeDriven-MVC-Application` | Pure Java config | WebApplicationInitializer |
| `100Percent-AbstractAnnoConfigDispServlet` | Modern initialization | AbstractAnnotationConfigDispatcherServletInitializer |
| `100Percent-LoginApp-SFC` | Login with Java config | SimpleFormController pattern |
| `100Percent-LoginApp-SFC-ORM` | Login with ORM | Java config + ORM |
| `100Percent-Security-Authentication` | Security without XML | Java-based security config |

**💡 Key Learning:** Build Spring MVC apps with zero XML using `WebApplicationInitializer` and `@Configuration`.

**Example:**
```java
public class MyWebAppInitializer implements WebApplicationInitializer {
    @Override
    public void onStartup(ServletContext servletContext) {
        // Register Spring config
        AnnotationConfigWebApplicationContext context =
            new AnnotationConfigWebApplicationContext();
        context.register(AppConfig.class);

        // Register DispatcherServlet
        DispatcherServlet servlet = new DispatcherServlet(context);
        ServletRegistration.Dynamic registration =
            servletContext.addServlet("dispatcher", servlet);
        registration.setLoadOnStartup(1);
        registration.addMapping("/");
    }
}
```

---

### 3️⃣ CRUD Operations

Complete Create, Read, Update, Delete functionality.

| Project | Features | Tech Stack |
|---------|----------|------------|
| `Annotations-MiniProject-CURD` | Employee CRUD | Spring MVC + JDBC + JSP |
| `Boot-CURD-Operations` | Modern CRUD | Spring Boot + JDBC |
| `Annotations-Project-AllEmployeeList-AC` | Employee listing | AbstractController |
| `XML-Project-AllEmployeeList-AC` | Employee listing (XML) | XML configuration |

**💡 Key Learning:** Build full-featured data management systems with Spring JDBC.

**Features:**
- ➕ Create new records with form validation
- 📋 List all records with pagination support
- ✏️ Update existing records
- 🗑️ Delete records with confirmation
- 🔍 Search and filter functionality

---

### 4️⃣ Form Handling & Validation

Master form processing, data binding, and validation.

| Project | Concept | Validation Type |
|---------|---------|-----------------|
| `Annotations-SimpleFormController-CoronaRegistration` | Basic form handling | Patient registration |
| `Annotations-SFC-Corona-SessionFormScope` | Session-scoped forms | Multi-page form |
| `Form Validation-Annotations-SFC` | JSR-303 validation | Annotation-based (@NotNull, @Size) |
| `Form Validation-Programatic-SFC` | Custom validation | Programmatic Validator |
| `Annotations-InitBinder` | Custom property editors | Type conversion |
| `Annotations-ReferenceData-SFC` | Dropdown data | Reference data population |
| `Annotations-Project-AbstractCommandController` | Command pattern | AbstractCommandController |

**💡 Key Learning:** Handle forms professionally with proper validation and error handling.

**Validation Example:**
```java
public class Patient {
    @NotNull(message = "Name is required")
    @Size(min = 2, max = 50, message = "Name must be between 2-50 characters")
    private String name;

    @NotNull(message = "Age is required")
    @Min(value = 1, message = "Age must be positive")
    @Max(value = 120, message = "Age must be realistic")
    private Integer age;

    @Email(message = "Invalid email format")
    private String email;
}

@PostMapping("/register")
public String registerPatient(@Valid @ModelAttribute Patient patient,
                              BindingResult result) {
    if (result.hasErrors()) {
        return "registration-form";
    }
    // Process registration
    return "redirect:/success";
}
```

---

### 5️⃣ Spring Security

Secure your web applications with multiple authentication strategies.

| Project | Authentication Type | Description |
|---------|-------------------|-------------|
| `Security-MVC-WishApp` | In-memory authentication | Basic security setup |
| `Security-MVC-Database-Authentication` | Database authentication | User credentials in DB |
| `Security-MVC-PropertiesFile-Authentication` | Properties file | External configuration |
| `Security-MVC-LDAP-Authentication` | LDAP integration | Enterprise directory |
| `Security-MVC-Encryption` | Password encryption | BCrypt hashing |
| `Security-NonMVC-Application` | Standalone security | Security without MVC |
| `Boot-Security-WishApp` | Spring Boot Security | Auto-configured security |

**💡 Key Learning:** Implement production-ready authentication and authorization.

**Security Configuration Example:**
```java
@Configuration
@EnableWebSecurity
public class SecurityConfig extends WebSecurityConfigurerAdapter {

    @Override
    protected void configure(HttpSecurity http) throws Exception {
        http
            .authorizeRequests()
                .antMatchers("/", "/home", "/public/**").permitAll()
                .antMatchers("/admin/**").hasRole("ADMIN")
                .anyRequest().authenticated()
            .and()
            .formLogin()
                .loginPage("/login")
                .defaultSuccessUrl("/dashboard")
                .permitAll()
            .and()
            .logout()
                .logoutSuccessUrl("/")
                .permitAll();
    }

    @Bean
    public PasswordEncoder passwordEncoder() {
        return new BCryptPasswordEncoder();
    }
}
```

---

### 6️⃣ Session Management

Handle sessions properly and avoid common pitfalls.

| Project | Problem Solved | Solution Approach |
|---------|---------------|-------------------|
| `SFC-DoublePostingProblem-RedirectToGetMode` | Double posting | PRG (Post-Redirect-Get) pattern |
| `SFC-DoublePostingProblem-SessionScope-HttpSession` | Form data persistence | HttpSession |
| `SFC-DoublePostingProblem-SessionScope-FlashAttribute` | One-time data transfer | Flash Attributes |

**💡 Key Learning:** Prevent duplicate form submissions and manage session state effectively.

**The Double-Posting Problem:**
When users refresh after form submission, data gets submitted again! 😱

**Solution 1: Redirect After Post (PRG Pattern)**
```java
@PostMapping("/submit")
public String handleSubmit(@ModelAttribute FormData data) {
    service.save(data);
    return "redirect:/success"; // Redirect instead of forward
}
```

**Solution 2: Flash Attributes**
```java
@PostMapping("/submit")
public String handleSubmit(@ModelAttribute FormData data,
                          RedirectAttributes redirectAttrs) {
    service.save(data);
    redirectAttrs.addFlashAttribute("message", "Success!");
    return "redirect:/success";
}
```

---

### 7️⃣ Spring Boot MVC

Modern Spring MVC with auto-configuration and embedded servers.

| Project | Feature | Description |
|---------|---------|-------------|
| `Boot-ShowHomePage` | Basic Boot MVC | Minimal Spring Boot web app |
| `Boot-CURD-Operations` | CRUD with Boot | Zero XML CRUD application |
| `Boot-LoginApplication` | Login system | Authentication without XML |
| `Boot-ListLanguages` | Data listing | Display collections |
| `Boot-Pagination` | Paginated results | Large dataset handling |
| `Boot-Security-WishApp` | Security with Boot | Auto-configured security |

**💡 Key Learning:** Build Spring MVC apps faster with Spring Boot's conventions.

**Benefits of Spring Boot:**
- 🚀 **Zero Configuration**: No XML, minimal annotations
- 📦 **Embedded Server**: No need to deploy to external Tomcat
- ⚡ **Auto-Configuration**: Smart defaults for common scenarios
- 🔧 **DevTools**: Hot reload for faster development
- 📊 **Production-Ready**: Actuator endpoints for monitoring

---

### 8️⃣ Advanced Features

Enterprise-grade features for production applications.

| Project | Feature | Technology |
|---------|---------|------------|
| `Annotations-FileUploading-FileDownloading` | File handling | MultipartResolver, Commons FileUpload |
| `TilesFramework-TwoColumnLayout` | Layout management | Apache Tiles 3.0 |
| `Internationalization-MVC-webapp` | Multi-language support | MessageSource, ResourceBundles |
| `Batch-Database-CVS` | Batch processing | Spring Batch + CSV |
| `Batch-POC-CustomRWs` | Custom readers/writers | Spring Batch processors |
| `WishApp-ServiceClass-TwoContainers` | Parent-Child contexts | Hierarchical containers |

**💡 Key Learning:** Build enterprise applications with advanced Spring features.

#### File Upload Example:
```java
@PostMapping("/upload")
public String handleFileUpload(@RequestParam("file") MultipartFile file) {
    if (!file.isEmpty()) {
        String filename = file.getOriginalFilename();
        byte[] bytes = file.getBytes();
        // Save file logic
        return "redirect:/upload/success";
    }
    return "upload-form";
}
```

#### Internationalization Example:
```java
// messages_en.properties
welcome.message=Welcome to our application!

// messages_hi.properties
welcome.message=हमारे एप्लिकेशन में आपका स्वागत है!

// messages_fr.properties
welcome.message=Bienvenue dans notre application!
```

---

## 🗺️ Learning Path

### 🌱 Beginner Track (Start Here!)

**Week 1: Spring MVC Basics**
```
1. ShowingHomePage
   ↓
2. Annotations-ShowHomePage
   ↓
3. Boot-ShowHomePage
   ↓
4. WishApp-PVC
```

**Week 2: Forms & Data Binding**
```
1. Annotations-SimpleFormController-CoronaRegistration
   ↓
2. Form Validation-Annotations-SFC
   ↓
3. Annotations-InitBinder
```

**Week 3: CRUD Operations**
```
1. Annotations-MiniProject-CURD
   ↓
2. Boot-CURD-Operations
```

### 🚀 Intermediate Track

**Focus Areas:**
- 100% Code-Driven applications (no XML)
- Session management patterns
- File upload/download
- Spring Security basics
- Spring Boot MVC applications

**Recommended Projects:**
1. `100Percent-CodeDriven-MVC-Application`
2. `SFC-DoublePostingProblem-RedirectToGetMode`
3. `Annotations-FileUploading-FileDownloading`
4. `Security-MVC-Database-Authentication`
5. `Boot-Pagination`

### 🎓 Advanced Track

**Master These:**
- All Spring Security variations (7 projects!)
- Apache Tiles framework
- Spring Batch processing
- Two-container architecture
- LDAP authentication
- Custom validation and property editors

**Expert Projects:**
1. `Security-MVC-LDAP-Authentication`
2. `Security-MVC-Encryption`
3. `TilesFramework-TwoColumnLayout`
4. `Batch-Database-CVS`
5. `WishApp-ServiceClass-TwoContainers`

---

## 🛠️ Tech Stack

### Core Technologies

```yaml
Spring Framework: 5.2.5.RELEASE
  - Spring MVC
  - Spring Core (IoC, DI)
  - Spring JDBC
  - Spring Security: 5.3.2.RELEASE
  - Spring Batch: 4.2.2.RELEASE

Spring Boot: 2.3.0.RELEASE

Java: 1.8
Maven: 3.x
Servlet API: 4.0.1
```

### View Layer

```yaml
JSP: JavaServer Pages
JSTL: 1.2
Apache Tiles: 3.0.8
Spring Form Tags
```

### Database & Persistence

```yaml
Spring JDBC: 5.2.5
Oracle JDBC: ojdbc6, ojdbc8
HikariCP: 3.4.5 (Connection Pooling)
```

### Additional Libraries

```yaml
Lombok: 1.18.12
AspectJ: 1.9.5
Commons FileUpload: 1.4
Commons IO: 2.6
```

---

## 📂 Project Structure

### Repository Organization

```
spring-mvc-all-concepts-tutorial/
├── Basic MVC Apps/
│   ├── ShowingHomePage/
│   ├── Annotations-ShowHomePage/
│   └── Boot-ShowHomePage/
│
├── Code-Driven (No XML)/
│   ├── 100Percent-CodeDriven-MVC-Application/
│   ├── 100Percent-AbstractAnnoConfigDispServlet/
│   └── 100Percent-Security-Authentication/
│
├── CRUD Operations/
│   ├── Annotations-MiniProject-CURD/
│   └── Boot-CURD-Operations/
│
├── Form Handling/
│   ├── Annotations-SimpleFormController-CoronaRegistration/
│   ├── Form Validation-Annotations-SFC/
│   └── Form Validation-Programatic-SFC/
│
├── Security/
│   ├── Security-MVC-Database-Authentication/
│   ├── Security-MVC-Encryption/
│   └── Boot-Security-WishApp/
│
└── Advanced Features/
    ├── Annotations-FileUploading-FileDownloading/
    ├── TilesFramework-TwoColumnLayout/
    └── Batch-Database-CVS/
```

### Typical Web Project Structure

```
ProjectName/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/com/dib/
│   │   │   ├── controller/         # MVC Controllers
│   │   │   ├── service/            # Business logic
│   │   │   ├── dao/                # Data access
│   │   │   ├── dto/                # Data transfer objects
│   │   │   ├── bo/                 # Business objects
│   │   │   ├── validator/          # Custom validators
│   │   │   ├── config/             # Java configurations
│   │   │   └── security/           # Security configs
│   │   │
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   └── messages*.properties
│   │   │
│   │   └── webapp/
│   │       ├── WEB-INF/
│   │       │   ├── web.xml         # Deployment descriptor
│   │       │   ├── spring/
│   │       │   │   └── dispatcher-servlet.xml
│   │       │   └── views/          # JSP files
│   │       │       ├── home.jsp
│   │       │       ├── list.jsp
│   │       │       └── form.jsp
│   │       │
│   │       └── resources/
│   │           ├── css/
│   │           ├── js/
│   │           └── images/
│   │
│   └── test/
└── target/
    └── ProjectName.war
```

---

## ⚙️ Configuration Approaches

This repository demonstrates **4 different configuration approaches** for the same concepts:

### 1. XML-Based Configuration (Traditional)

```xml
<!-- dispatcher-servlet.xml -->
<beans>
    <context:component-scan base-package="com.dib" />

    <bean class="org.springframework.web.servlet.view.InternalResourceViewResolver">
        <property name="prefix" value="/WEB-INF/views/" />
        <property name="suffix" value=".jsp" />
    </bean>
</beans>
```

**Pros:** Externalized config, no recompilation needed
**Cons:** Verbose, type-safety issues

---

### 2. Annotation-Based Configuration

```java
@Controller
@RequestMapping("/employee")
public class EmployeeController {

    @Autowired
    private EmployeeService service;

    @GetMapping("/list")
    public String listEmployees(Model model) {
        model.addAttribute("employees", service.getAllEmployees());
        return "employee-list";
    }
}
```

**Pros:** Less verbose, cleaner code
**Cons:** Still needs some XML (web.xml, dispatcher-servlet.xml)

---

### 3. 100% Java-Based Configuration (No XML)

```java
@Configuration
@EnableWebMvc
@ComponentScan("com.dib")
public class WebConfig implements WebMvcConfigurer {

    @Bean
    public ViewResolver viewResolver() {
        InternalResourceViewResolver resolver =
            new InternalResourceViewResolver();
        resolver.setPrefix("/WEB-INF/views/");
        resolver.setSuffix(".jsp");
        return resolver;
    }
}

public class MyWebInitializer
    extends AbstractAnnotationConfigDispatcherServletInitializer {

    @Override
    protected Class<?>[] getRootConfigClasses() {
        return new Class[] { RootConfig.class };
    }

    @Override
    protected Class<?>[] getServletConfigClasses() {
        return new Class[] { WebConfig.class };
    }

    @Override
    protected String[] getServletMappings() {
        return new String[] { "/" };
    }
}
```

**Pros:** Type-safe, refactoring-friendly, modern
**Cons:** Longer setup initially

---

### 4. Spring Boot (Auto-Configuration)

```java
@SpringBootApplication
public class Application {
    public static void main(String[] args) {
        SpringApplication.run(Application.class, args);
    }
}

@Controller
public class HomeController {
    @GetMapping("/")
    public String home() {
        return "home"; // maps to templates/home.html
    }
}
```

**Pros:** Minimal config, fastest setup, embedded server
**Cons:** Less control over auto-configuration

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create!

### How to Contribute

1. 🍴 **Fork** the repository
2. 🌿 **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. ✍️ **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 **Push** to the branch (`git push origin feature/AmazingFeature`)
5. 🔃 **Open** a Pull Request

### Contribution Ideas

- 📝 **Add REST API examples** using @RestController
- 🎨 **Modernize frontend** with Thymeleaf instead of JSP
- 🆕 **Spring 6 & Boot 3** migration examples
- ✅ **Add unit & integration tests** with MockMvc
- 🐛 **Fix bugs** or improve existing examples
- 📚 **Enhance documentation** with diagrams
- 🌐 **Add WebSocket** examples
- 🔄 **Add reactive examples** with Spring WebFlux
- 🎯 **Add microservices** patterns
- 🐳 **Add Docker** configurations

---

## 👨‍💻 Author

**Dibyaprakash Pradhan**

- GitHub: [@dibyapp](https://github.com/dibyapp)
- Repository: [spring-mvc-all-concepts-tutorial](https://github.com/dibyapp/spring-mvc-all-concepts-tutorial)

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use for learning and education
- ✅ Use in personal and commercial projects
- ✅ Modify and distribute
- ✅ Create derivative works

---

## ⭐ Star History

If this repository helped you master Spring MVC, please give it a ⭐!

[![Star History Chart](https://api.star-history.com/svg?repos=dibyapp/spring-mvc-all-concepts-tutorial&type=Date)](https://star-history.com/#dibyapp/spring-mvc-all-concepts-tutorial&Date)

---

## 🙏 Acknowledgments

- **Spring Framework Team** for the incredible framework
- **Apache Software Foundation** for Tiles and Commons libraries
- **Open-source community** for continuous inspiration
- **All contributors** who help improve this repository

---

## 📚 Related Resources

### Other Tutorial Repositories
- 🌸 [Spring Core Concepts](https://github.com/dibyapp/spring-core-all-concepts-tutorial) - Master Spring IoC and DI
- 🔄 [Spring Boot Advanced](https://github.com/dibyapp) - More Spring Boot examples

### Official Documentation
- 📖 [Spring Framework Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/)
- 📖 [Spring MVC Reference](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
- 📖 [Spring Security Reference](https://docs.spring.io/spring-security/reference/)
- 📖 [Spring Boot Reference](https://docs.spring.io/spring-boot/docs/current/reference/html/)

---

## 📞 Support

### Found This Helpful?

- ⭐ **Star** this repository
- 🍴 **Fork** and contribute
- 📢 **Share** with developers learning Spring MVC
- 🐛 **Report** bugs via issues
- 💡 **Suggest** new examples or improvements

### Need Help?

- 📖 Check existing examples for similar patterns
- 💬 Open an issue for questions
- 📧 Contact through GitHub

---

## 📊 Repository Stats

- 📁 **44+ Projects** covering every Spring MVC concept
- 🔧 **4 Configuration Styles** (XML, Annotations, Java Config, Spring Boot)
- 🔒 **7 Security Projects** with different authentication methods
- 🌐 **i18n Support** for building multi-language apps
- 📦 **Spring Batch** integration for enterprise processing
- 🎯 **100% Working Code** - all examples tested and functional

---

<div align="center">

### 🌐 Master Spring MVC One Project at a Time 🚀

**Build Production-Ready Web Applications with Confidence**

Made with ❤️ by the Spring Developer Community

[![GitHub stars](https://img.shields.io/github/stars/dibyapp/spring-mvc-all-concepts-tutorial?style=social)](https://github.com/dibyapp/spring-mvc-all-concepts-tutorial/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/dibyapp/spring-mvc-all-concepts-tutorial?style=social)](https://github.com/dibyapp/spring-mvc-all-concepts-tutorial/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/dibyapp/spring-mvc-all-concepts-tutorial?style=social)](https://github.com/dibyapp/spring-mvc-all-concepts-tutorial/watchers)

**[⬆ Back to Top](#-spring-mvc---complete-tutorial-repository)**

</div>
