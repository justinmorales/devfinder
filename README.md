This project is designed to help me get familiar with Fullstack Java development.

With this project, I will build a web application.  
The web application with have a few goals.  
1. It will be used as a proof that I can build a web application with java scripting.  
2. I will then use a page as a resume of sorts to show off my projects and link to other social media.  
3. I will then branch the website into a more general purpose application where users can sign up and create a page
for themselves to show off their projects and link their git repos.

I will attempt to update and bugfix this web application a few times a week actively learning while searching
for employment.

If you would like to collaborate on this project or seeking to employ me, please contact me at

magagod2@gmail.com

-- *Justin Morales*

***

The following is just for learning/ personal purposes. I will be describing things in a way that make sense to me.

[Markdown Guide](https://www.markdownguide.org/basic-syntax/)  

[The ULTIMATE Guide to Spring Boot: Spring Boot for Beginners](https://www.youtube.com/watch?v=Nv2DERaMx-4)

### Maven commands
`./mvnw` (maven wrapper)

`./mvnw clean` (removes target folder with compiled files)

`./mvnw compile` (compiles the files in to a folder called targer)

`./mvnw test` (runs test folder code against the compiled code)

`./mvnw package` (packages the project into a jar or war)

`./mvnw verify` (makes sure everything is working nicely)

### Testing
To test the package its self to see that it is working we will take the jar file and run it with
the command

`java -jar PATHTOJARFILE.jar`

EXAMPLE\
`java -jar devfinder-0.0.1-SNAPSHOT.jar`  
`java -jar "target\devfinder-0.0.1-SNAPSHOT.jar"`

and it will run. At the moment of writing this, it is running on localhost:8080

***

### Common Application properties
[Spring Documentation](https://docs.spring.io/spring-boot/docs/3.2.2/reference/htmlsingle/index.html#appendix.application-properties)

In the file application.properties, you may configure different properties about your project as described in the 
Spring Documentation link. You may also rename the file to application.yml to write the config in a different format.
Be aware that the file application.properties in main and in test may be different.

For this project my main will be on port 8080 for now, while the test is on port 8081
written as\
`server.port = 8080`

If application.properties is empty then it will likely use default values.