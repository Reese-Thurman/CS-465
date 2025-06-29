# CS-465
Full Stack Development
1. Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
> The full stack project used both Angular and Express HTML for front end development. However, the technologies had different structures as the Angular project structure was noticeably more complex relative to Express HTML. Although Angular is more complex, the project structure is modular and has separate folders for different components and services. It also uses TypeScript. In contrast, the Express HTML page is much simpler, uses the MVC architecture structure, and primarily uses HTML, CSS, and JavaScript to display data.
> The full stack project also incorporates SPA functionality. The primary advantages of SPA functionality include faster navigation and reduced server load. Some of the disadvantages of SPA functionality are longer initial load times and more complex code. SPAs can update content dynamically without reloading the page, unlike simple web application interactions. The current project uses SPA to allow users to dynamically update travel information without refreshing the browser.
2. Why did the backend use a NoSQL MongoDB database?
> The backend uses a NoSQL MongoDB database because it stores data in a flexible format that works well with applications similar to the travel booking website. Unlike relational databases, MongoDB doesn't require a fixed schema, making it easier to handle changes in the structure of travel data as the project evolves.
3. How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
> JSON is a readable data format used for storing and exchanging data. It serves as the bridge between frontend and backend development because it allows data to be sent and received in a format both sides can understand. It is not a scripting language like Javascript. 
> In the travel booking website, MongoDB stores travel data in JSON format. When the frontend needs to display trips, it makes a request to the backend, which retrieves the travel information from MongoDB and the JSON data is sent to the frontend. 
4. Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
> Originally, the travel booking webpage was static, with all trip details hardcoded in the frontend. To improve functionality, I refactored the project to connect it to a backend using MongoDB. This allowed travel data to be stored in a database and dynamically loaded onto the site, making it easier to manage and expand.
> There are several major benefits that comes from reusable UI components. Reusable UI components are more efficient, consistent, and easier to maintain compared to nonmodular UI components.
5. Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
> In a full stack web application, methods refer to HTTP request types like GET or POST and they define the action the client side is asking the server to perform. Endpoints are the URLs that handle these methods. For example, in the travel booking website, a GET request to /api/trips would retrieve a list of trips from the database.
> Security is a critical component to a web app, especially when dealing with user data. The travel booking website uses JSON Web Tokens (JWTs) to secure the app. This means that only users with valid tokens can access protected endpoints.
I tested the endpoints using Postman, which allowed me to simulate requests and verify that the backend responded correctly. 
6. How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
> This course helped me move closer to my goal of becoming a software developer. One of the most valuable takeaways from the class was gaining a solid understanding of both front-end and back-end development, which are essential skills for any aspiring software engineer.
> This course taught me the fundamentals of JavaScript and HTML, which are the building blocks of web development. I also learned how to connect a front-end interface with a back-end server using Node.js and Express, and how to store and retrieve data using MongoDB. This class truly gave me a clearer understanding of how modern web applications are built and function.






