# Authentication with Okta Integration

This project demonstrates how to integrate Okta for OAuth2 authentication in a Spring Boot application. It includes configuration files and controllers to enable secure authentication and authorization.

## Table of Contents
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Contributions](#contributions)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Key Features

1. **Security Configuration (`SecurityConfig.java`):**
   - Configures Spring Security to handle authentication and authorization.
   - Sets up OAuth2 login with Okta.
   - Defines custom logout behavior to redirect users to Okta's logout endpoint.

2. **Controller for Home Page (`HomeController.java`):**
   - Handles requests to the home page ("/").
   - Retrieves the currently authenticated user principal using `@AuthenticationPrincipal`.
   - Returns the name of the view template for rendering the home page.

## Technologies Used

- Spring Boot
- Spring Security
- Thymeleaf (for server-side HTML templating)
- Okta (for OAuth2 authentication)

## How to Run

1. Clone the repository to your local machine.
2. Set up your Okta account and configure the application properties (`application.properties` or `application.yml`) with your Okta issuer URL and client ID.
3. Run the Spring Boot application.
4. Access the application through a web browser.

## Contributions

Contributions to enhance security features, improve code quality, or add additional functionality are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

## Acknowledgements

Special thanks to the developers of Spring Security and Okta for providing robust authentication and authorization solutions.
