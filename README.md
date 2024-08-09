<h1> Syoft NodeJS Assignment </h1> 

<h2> About: </h2>

<p> The task is all about to test your backend skills, as well as to check your coding style/architecture. We would judging your code based on readability, reusability and robustness of your code. </p>

<h2> Technologies to Use: </h2>

- **Server-side Framework**: Node.js
- **Authentication**: JWT or any token system you prefer.

<h2> Your task consists you developing three end/api points  </h2>
<ul>
 <li> Register </li>
 <li> Login </li>
 <li> Product CRUD </li>
</ul>


<h2> Register: </h2>
<p>	Create a post call with fields like username, email, password, role(enum with fields admin, manager & staff). If it is valid response return 201 status with user created message </p>

<h2> Login: </h2>
<p>		Create a post call with fields like email & password. If he is valid user return 200 status along with a JWT token or any token system your familiar with. The main aim of token is to authorise user for crud operations.
</p>

 
<h2> Product: </h2>
<p>	The product model will have fields like title, description & inventory count. All the CRUD(Create, Read, Update & Delete) API’s should require token in header to perform actions. If no token provided return status 400 with Token not provided message.
</p>
<ul>
   <li> Product Creation can be accessed with admin token only </li>
   <li> Product Get can be accessed with admin, manager token only  </li>
   <li> Product Update can be accessed with admin, manager token only  </li>
   <li> Product Delete can be accessed with admin token only  </li>
   <li> Staff will not have any CRUD rights </li>
</ul>
