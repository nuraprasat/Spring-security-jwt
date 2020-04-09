# Spring-security-jwt
Simple spring boot application with spring security and jwt token

## Getting Started
To run a project, First clone it
```
git clone https://github.com/nuraprasat/Spring-security-jwt.git
```

### Running
After cloning just run the below class to SpringSecurityJwtApplication.java


###Post Man - 

To generate the JWT token, Hit the below URL with username and password in postman, This will give the JWT token
```
POST:http://localhost:8080/authenticate
Body: Application/JSON 
{
	"username":"foo",
	"password":"foo"
}
```
