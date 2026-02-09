This project is a static website developed using HTML5 and CSS and basic Javascript. It includes Home, About, Services, and Contact pages connected through a common navigation bar. The website is fully responsive and works across mobile, tablet, and desktop screens using Flexbox and CSS Grid. No frameworks or libraries were used.

project demonstrates a simple and clear authentication system built with a minimal backend. Users log in using their email and password, with basic client-side validation to ensure correct input before the request is sent to the server. 

The backend verifies the credentials using either a hardcoded user or a stored record and, upon successful authentication, allows access to a protected page.

If the user is not authenticated, access is denied and they are redirected back to the login page or shown an unauthorized error.

The tech stack we used are node.js and express and mongodb for database.

 Protected routes are secured using authentication middleware, which checks whether the user is logged in before serving restricted content. 
