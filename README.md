Currency-Converter is a web application that allows users to convert one currency to another based on the latest exchange rates.
This application was built using Flask a python web framework that can handle the backend logic of the currency converter,HTML to structuring the web page
and CSS for styling and layout purpose.
first we install flask and then we create an HTML form with input fields for the amount to convert,the source currency and the target currency and we add a submit
button.
Then we style the html with css after that we define flask routes in another file to handle HTTP requests from the HTML form.
later on we use a currency exchange rate API to fetch the latest exchange rates and perform the conversion calculation in our flask route.
after that we returns the converted amount to the HTML template and display it to the user.

