# Instagram Clone

### Table of Contents:
1. <a href="#details">Project Details</a> 
2. <a href="#application">Application</a>
3. <a href="#screenshots">Screenshots</a>
4. <a href="#steps">Steps to run after Clone</a>
5. <a href="#acknowledgements">Acknowledgements</a>

---
### <a name="details"> 1. Project Details</a>
Social media can be very influential on society in both positive and negative ways. It gives people a way to stay in touch with people who live far away. In this project ,we have created a replica of the Instagram App which is a social networking service.  Instagram Clone is a website which lets people share fun, interesting and informative content.
The user has to register to the website so that he/she can view his/her feed and connect to people. Laravel includes built-in authentication and session services which are typically accessed via the Auth and Session facades. The frontend user interface of the website is developed using **HTML5, CSS, Javascript and Bootstrap**. The backend is developed using Laravel PHP framework which controls the functionality of the routes and various controllers. This system stores all the information in a MYSQL Database. It stores data of the users, the posts, the profile details and the following and the followers.

On starting the server, the first task is the User Authentication. If the user is not registered he is asked to Sign In first and then Login to his account .Upon Logging in, the user is taken to his account page. Where he can view his Followers, the people Following him and the number of posts. The user can edit his profile at any time. He can also Add a new post to make his profile look perfect. 


---

### <a name="application"> 2. Application</a>
Instagram Clone is a system where people can connect with each other by sharing pictures or by following other users. You can give a different look or feel to your images, using them to convey your desired mood and message. It is a user-friendly website where users can post pictures, follow other users, search for friends or family, like other posts, scroll through the explore page for fun and many more. The user can also give his/her own feedback.

---

### <a name="screenshots"> 3. Screenshots</a>
> Main page where user can Register/Login <br><br>
![image](https://user-images.githubusercontent.com/58616834/102899471-ef8e6c80-4490-11eb-84c0-b6b274a60000.png)

> Profile Page <br><br>
![image](https://user-images.githubusercontent.com/58616834/102899516-092fb400-4491-11eb-9282-5352b03816f6.png)

> Home Page where the logged in user can see the posts of his followers <br><br>
![image](https://user-images.githubusercontent.com/58616834/102899171-89a1e500-4490-11eb-968d-9eda09f2cb23.png)

> Explore Page <br><br>
![image](https://user-images.githubusercontent.com/58616834/102899281-b0601b80-4490-11eb-88a7-b865207ba6f2.png)


---

### <a name="steps"> 4. Steps to run after Clone</a>
- Open the project in Command prompt, cd into the project and run ``composer install``
- To install the npm dependencies, run ``npm install``
- Rename '.env.example' to '.env'
- Generate an app encryption key by running this command ``php artisan key:generate``
- Create an empty database and add the details in the '.env' file
- Migrate the database by ``php artisan migrate``
- Run ``php artisan serve`` to test the project.

---

### <a name="acknowledgements"> 5. Acknowledgements</a>
- <a href="https://github.com/katerebello">Kate Rebello</a>
- <a href="https://github.com/clare0901">Clare Rebello</a>
- <a href="https://github.com/rebeccadias">Rebecca Dias</a>


[![WhatsApp Image 2020-10-13 at 7 04 51 PM](https://user-images.githubusercontent.com/72509723/95880997-b7cebe80-0d95-11eb-8934-1d4577546a52.jpeg)](http://issb.sfit.ac.in/)
<div align="center">
  <a href="https://www.instagram.com/ieeesfit/" target="_blank"><img src="https://img.icons8.com/fluent/48/000000/instagram-new.png"/></a>
  <a href="https://www.facebook.com/ieeesfitstudentbranch/" target="_blank"><img src="https://img.icons8.com/fluent/48/000000/facebook-new.png"/></a>
  <a href="mailto: ieeesfitsb@gmail.com" target="_blank"><img src="https://img.icons8.com/fluent/48/000000/gmail.png"/></a>
  <a href="https://discord.gg/HfpvkzE" target="_blank"><img src="https://img.icons8.com/color/48/000000/discord-new-logo.png"/></a>
</div>
