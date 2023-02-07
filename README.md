This system is a web-based tool that allows an organization to manage the process of recruiting and hiring developers. This system includes functionality such as programming challenges, receiving and reviewing the developer's codes, and making hiring decisions.

## How to Run the Project
<ol>
 <li>Clone this project on your own system: git clone https://github.com/maryamjavid/Software-Architecture.git</li>
 <li>Run your Docker</li>
 <li>Using Terminal or CMD (in the project's root directory), enter the codes respectivly:<br/>docker-compose build<br/>docker-compose up -d</li>
 <li>Now you need to add the SQL:
   <ul>
   <li>Clone the SQL file from this address: https://github.com/maryamjavid/MySQL.git</li>
   <li>Open the link of "phpmyadmin" on port 8001:80 from Docker Desktop<li>
   <li>Enter the username = php_docker  and  password = password</li>
   <li>Import the SQL file in php_docker database</li>
   </ul>
 </li>
 <li>Open your browser and enter your localhost address</li>
</ol>
## How to Use the Project
<strong>As a Developer:</strong>

## Description of Architecture
N-tire architecture is used in this web application. The application is divided into three layers: "Front-end", "Back-end", and "Database".
Despite keeping "Modularity" a little bit, this architecture keeps "Simplicity" and easy to understand codes.

## Programming Language
PHP is the programming language used for this IT system, and Laravel is the library.
