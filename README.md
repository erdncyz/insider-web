# Insider Test Automation Project

A comprehensive Selenium WebDriver test automation solution for testing QA (Quality Assurance) positions on the Insider company's career website.

## 🚀 Features

- **Page Object Model (POM)** design pattern implementation
- **Modern Selenium WebDriver 4.15.0** with latest features
- **Automatic ChromeDriver management** via WebDriverManager
- **Optimized element locators** using XPath and CSS selectors
- **Clean and maintainable code** following best practices

## 📋 Test Requirements

1. **Homepage Verification**: Visit https://useinsider.com/ and verify the Insider home page is opened
2. **Career Page Navigation**: Select "Company" menu → "Careers" and verify career page elements
3. **QA Department Access**: Navigate to QA department page and click "See all QA jobs"
4. **Job Filtering**: Filter jobs by location (Istanbul, Turkey) and department (Quality Assurance)
5. **Application Verification**: Verify "View Role" button redirects to Lever application form

## 🛠️ Technologies Used

- **Java 11** - Main programming language
- **Selenium WebDriver 4.15.0** - Web automation framework
- **JUnit 4** - Test framework
- **Maven** - Dependency management
- **WebDriverManager** - Automatic driver management

## 📁 Project Structure

```
insider-selenium/
├── src/test/java/
│   ├── base/BaseTest.java           # Base test class
│   ├── objects/                     # Page objects
│   │   ├── HomePage.java           # Homepage interactions
│   │   ├── CareersPage.java        # Careers page
│   │   ├── QAPage.java             # QA department
│   │   └── OpenPositionPage.java   # Job listings
│   └── test_scenarios/
│       └── VerifyQAJobs.java       # Main test scenario
├── pom.xml                         # Maven configuration
└── README.md                       # Project documentation
```

## ⚡ Quick Start

### Prerequisites
- Java 11 or higher
- Maven 3.6 or higher
- Chrome browser

### Installation
```bash
git clone https://github.com/erdncyz/insider-selenium.git
cd insider-selenium
mvn clean install
```

### Run Tests
```bash
mvn test
```

## 📊 Project Status

- **Version**: 1.0.0
- **Status**: Production Ready
- **Test Coverage**: Core functionality implemented

## 👨‍💻 Developer

**Erdinç Yılmaz**
- **Phone**: +90 551 435 34 03
- **Email**: erdncyz@gmail.com

## 🔗 Links

- **Repository**: [insider-selenium](https://github.com/erdncyz/insider-selenium.git)
- **Documentation**: [insider.html](insider.html)

---

*This project demonstrates modern test automation best practices using Selenium WebDriver and Page Object Model design pattern.* 