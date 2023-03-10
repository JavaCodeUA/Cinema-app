:movie_camera: Cinema app :framed_picture: :dark_sunglasses:
## PROJECT DESCRIPTION  :octocat: :
> App represents a cinema booking system!
>
>It allows you to create cinema-hall, movies and register users and store them in DB. 
>
>There is also a possibility to add tickets to your shopping cart and complete the orders !

## FEATURES π‘ :
* Registration π
* Authentication π
* App have roles with different rights - admin/user π / π€
* Create, update cinema-hall/movie session/movies/users/orders π’οΈ
* Display list off all available movies for purchase in different cinema-halls π
* Add ticket to shopping cart for chosen movies and buy it πΈ

## PROJECT STRUCTURE π :
>**Project use 3-tier Architecture:**

>* Controller layer - gives user control under web-application (depends on his role)
>* Service layer - holds all business logic.
>* DAO layer - is responsible for communicating with the database by using CRUD methods.

## TECHNOLOGIES π§¬ :
* Spring MVC
* Spring Security
* MySQL
* Hibernate
* Tomcat (9.0.50)

## INSTRUCTIONS FOR LAUNCHING THE PROJECT πΊοΈ :
1. Fork my repository
2. git clone
3. Edit db.properties file
4. set the necessary parameters:
    ```
    db.driver=YOUR_DRIVER
    db.url=YOUR_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
    ```
5. Install Tomcat
6. Add Tomcat server to configuration
7. Run project



