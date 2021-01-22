<body>
<h1 style="color:blue"> Hotel Rooms Booking System for hotel "YOUR HOME" </h1>

<h3>Introduction</h3>
<p> APIs simple hotel booking system which equips the manager with the following functionalities</p>
<ul>
  <li>Check for availability of rooms between certain dates</li>
  <li>Book a room for a certain customer for a certain time period if it is available</li>
</ul>
<p>Constraints</p>
There is only one type of room and the booking is being made for a single person only.

<h3>Tech Stack</h3>
<ul>
  <li>Backend - NodeJS, ExpressJS for API's</li>
  <li>Database - MongoDB</li>
</ul>

<h3>Installations</h3>

Install node js and Postman <br>

Clone the repository using<br>
>git clone ................................... <br>
>cd ................................ <br>

Install the dependencies using<br>
>npm install -r requirements.txt <br>

Connect to the database <br>
>Connect to your own MongoDB by changing the url in .env file accordingly <br>

Note: <i>For database MongoDB Atlas which is the global cloud database service was used</i><br>

Start the server<br>
>npm start<br>

Verify the deployment by navigating to your server address in your preferred browser<br>
>localhost:3000<br>

<h3>Routes</h3>
/booking <br>
/checkAvailability <br>

<h3>Example request</h3>
<ul>
  <li>
    To see details of all the bookings make a GET request to <br>
    > http://localhost:3000/bookings/
  </li>
  <li>
    To make a new booking make a POST request to <br>
    > http://localhost:3000/bookings/
    <br><small>Note:<i> A booking is made only if the requested room is available</i></small>
  </li>
  <li>
    To scheck the availabe rooms in a certain date range make a GET request in the following format http://localhost:3000/checkAvailability/<from-date>/<to-date><br>
    > http://localhost:3000/checkAvailability/2020-05-12/2020-12-25
  </li>
</ul>
<p> Mention about postman and mongoDB cloud </p>
</body>
