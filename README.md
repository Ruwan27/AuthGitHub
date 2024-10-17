1. Steps to Register:

Go to GitHub Developer Settings.
Under OAuth Apps, click on New OAuth App.
Fill out the required information:
Application Name: Give your application a name (e.g., "My Spring App").
Homepage URL: Enter the homepage URL of your app (for development, you can use http://localhost:8080).
Authorization Callback URL: This is the URL GitHub will redirect to after authentication. Use http://localhost:8080/login/oauth2/code/github for local development.
After registering, GitHub will provide you with a Client ID and Client Secret. You will need both for your Spring Boot application.

2. Configure Spring Boot Application
Add the client-id and client-secret to your application.properties or application.yml file.
