# Tempo Goal Tracking App
This application is the repository for the Tempo Goal Tracking Web application.

## Requirements:
 - Java JDK 14.0.1
 - Maven 3.x.x (compiled with 3.6.3)

### To run locally:
 - have a database ready locally.
 - update application.properties with port, username and password information.
 - run command `mvn clean install` to install dependancies.
 - run command `mvn spring-boot:run` to run program.

## Release Notes 0.0.3:
 - Header now has dropdown links to index and create pages for both tags and goals.
 - These can be reached using "/", "/create" (for goals) and "/tags" "/tags/create" respectively.
 - Tags and Goals create pages are now functional.
 - Formatted basic CRUD pages, not all currently functional.
 - Can now Edit goals
 - Can associate tags with goals
 - Goals now have due dates
 - Optimized and added unit testing.
 
