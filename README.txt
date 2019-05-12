---------------Welcome to the SpringBoot Facebook login demo---------------

1. Clone the project using "https://github.com/shanakaweerasinghe/SpringBoot_SocialLogin.git"

2. Make Sure to provide generated Facebook App ID and App Secret for connection factory as shown below on "SocialFacebookController.java" class, which can be found under "src/main/java/com/samle/controllers/" directory.
           "private FacebookConnectionFactory factory = new FacebookConnectionFactory("<App ID>","<App Secret>");"
           
3. Build the project using "mvn package" command.

4. Navigete to the "target/" directory of the project and run the "spring-boot-social-login-0.0.1-SNAPSHOT.jar" file 
using "java -jar spring-boot-social-login-0.0.1-SNAPSHOT.jar" command.

5. Once application is started, navigate to "http://localhost:8080" url with new browser window.

6. Click the login with FaceBook link to authenticate through Facebook and retrieve user information with obteined 
Access token.
