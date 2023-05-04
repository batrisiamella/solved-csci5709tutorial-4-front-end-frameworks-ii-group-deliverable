Download Link: https://assignmentchef.com/product/solved-csci5709tutorial-4-front-end-frameworks-ii-group-deliverable
<br>



<strong>Learning Outcomes:                                                                                                                      </strong>

<ul>

 <li>Continue to work with the Front-End framework/library of your choice (i.e., the one you have decided to use for your project).</li>

 <li>Understand how routing and calls are made in the Front-End framework/library you have chosen (i.e., Angular or React).</li>

 <li>Work individually, and within your group, to create a simple interactive site.</li>

</ul>

<strong>Instructions: </strong>

<ul>

 <li>Create a login page with just two fields: Email and password</li>

 <li>Hit this API on login submit with the provided credentials</li>

</ul>

POST – <u>https://tutorial4-api.herokuapp.com/api/users/login</u> body data:

{

“email” : “<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d3b9bcbda0bdbca493a4b6a0a7b6a1bca0fdb0bcbe">[email protected]</a>”,

“password” : “<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="35727558500553415d47055b5000">[email protected]</a>” }

Email and password should be accepted from frontend form and sent as a POST request body data.

<ul>

 <li>On successful login, user should be redirected to profile listing page and should display a list of users fetched from this API:</li>

</ul>

GET – <u>https://tutorial4-api.herokuapp.com/api/users/</u>

Users should either be displayed as a list or grid items. Display the images from the API as well.

<ul>

 <li>Clicking on any user (item/card) should open a profile detail page. The API for this is:</li>

</ul>

GET – <u>https://tutorial4-api.herokuapp.com/api/users/:id</u>

parameter expected is the user id passed as id

<ul>

 <li>Display the user profile details from the API on the profile detail page.</li>

 <li>Along with this; implement an input search box on the profile listing page which would filter out users based on Firstname or Lastname.</li>

</ul>