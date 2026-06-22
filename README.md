# Spring MVC Search Application

A simple web application built using **Spring MVC**, **JSP**, and **Bootstrap** that allows users to enter a search query and redirects them to Google search results using `RedirectView`.

## 🚀 Features

* User-friendly search interface
* Form handling with Spring MVC
* Query parameter binding using `@RequestParam`
* URL redirection using `RedirectView`
* Responsive UI with Bootstrap 5

## 🛠️ Technologies Used

* Java
* Spring MVC
* JSP
* Bootstrap 5
* Maven
* Apache Tomcat

## 📂 Project Structure

```
src
├── main
│   ├── java
│   │   └── controller
│   │       └── SearchController.java
│   ├── webapp
│   │   └── WEB-INF
│   │       └── views
│   │           └── index.jsp
│   └── resources
```

## ⚙️ How It Works

1. User enters a search query.
2. The request is sent to the Spring MVC controller.
3. `@RequestParam` retrieves the query value.
4. `RedirectView` redirects the user to:

```
https://www.google.com/search?q=<query>
```

## ▶️ Running the Application

1. Clone the repository:

```bash
git clone https://github.com/your-username/springmvc-search-app.git
```

2. Import the project into Eclipse.

3. Configure Apache Tomcat.

4. Run the application and open:

```
http://localhost:8080/springmvc-search-app/
```

## 👨‍💻 Author

**Vivek Chaudhari**

Learning and building Java Backend applications using Spring Framework.
