# 🛒 Shopping Cart - Spring Boot Application

A full-featured online shopping cart system built with **Spring Boot**, **Spring MVC**, **JPA**, and **MySQL**.

## 🚀 Features

- User Registration & Authentication
- Role-based Authorization
- Product Catalog with Image Upload
- Add to Cart / Remove from Cart
- Checkout Process
- Order History
- Admin Panel for Product Management
- Email Notifications

## 🧰 Tech Stack

| Layer       | Technology                         |
|-------------|-------------------------------------|
| Backend     | Spring Boot 3.2.3, Spring MVC       |
| Database    | MySQL (via Spring Data JPA)         |
| Security    | Spring Security                     |
| Mail        | JavaMailSender (Gmail SMTP)         |
| View Layer  | JSP (Java Server Pages)             |
| Build Tool  | Maven                               |
| Java Ver.   | Java 17                             |

## 🔧 Configuration

Update the `application.properties` file in:
```
src/main/resources/application.properties
```

### Example:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password

spring.mail.username=yourmail@gmail.com
spring.mail.password=your_email_password
```

⚠️ **Never commit real credentials.** Use environment variables or a `.env` loader in production.

---

## 🧪 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/shopping-cart-spring-boot.git
cd shopping-cart-spring-boot

# Build with Maven
mvn clean install

# Run the application
mvn spring-boot:run
```

App should now be running at `http://localhost:8080`

---

## 🛠️ Todo / Improvements

- Switch to Thymeleaf or React for frontend
- Add payment integration (Stripe/PayPal)
- Dockerize the application
- Add test coverage (JUnit + Mockito)

---

## 📬 Contact

**Aravind Varanasi**  
GitHub: [your-profile-link]  
Email: [your-email]

---

## 📝 License

This project is for educational and demonstration purposes only.
