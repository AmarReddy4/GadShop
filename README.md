# GadShop -- Gadget Shop Frontend

A front-end gadget shop web application built as a course project (2016). Features a product gallery homepage, user sign-up and login forms, about us and contact us pages, all styled with Bootstrap 3 and organized with reusable JSP header/footer includes.

## Tech Stack

- **Frontend:** JSP, Bootstrap 3, jQuery
- **Build:** Maven 3, WAR packaging
- **Server:** Apache Tomcat (or any Servlet 2.3+ container)

## Project Structure

```
GadShop/Gadgets/
├── pom.xml
└── src/main/webapp/
    ├── index.jsp            # Homepage with product image gallery
    ├── Login.jsp            # Login form with image carousel
    ├── SignUp.jsp           # Registration form
    ├── AboutUs.jsp          # About page
    ├── ContactUs.jsp        # Contact page
    ├── Common-Header.jsp    # Shared navbar header
    ├── Common-Footer.jsp    # Shared footer
    └── WEB-INF/
        └── web.xml
```

## Prerequisites

- Java 7+
- Maven 3

## Build and Run

```bash
cd GadShop/Gadgets
mvn clean package
# Deploy the WAR from target/Gadgets.war to Tomcat
```
