# CurrentWeatherApp
A react CurrentWeatherApp where the user can choose the city and see the weather through the API for 5 days

Here's the Deploy link where you can have a look of the website : https://reactcurrentweatherwebsite.netlify.app/


I created reusable functional or class-based components using JSX. This allowed me to modularize my code and reuse components throughout my application.

I utilized props to pass data between components. By passing data through props, I was able to customize the behavior and appearance of my components based on the data they received.

To manage dynamic behavior within my components, I made use of state and lifecycle methods or hooks. State allowed me to store and update data within a component, while lifecycle methods or hooks enabled me to perform certain actions at specific stages of a component's lifecycle.

To fetch data from the Yahoo Weather API and handle potential errors gracefully, I utilized methods like fetch or libraries like Axios. I ensured that my application didn't break if there were issues with the API request.

To incorporate user input, I implemented a form where users could enter their city. On form submission, I fetched the current weather for that city using the Yahoo Weather API and displayed it to the user.

To provide a smooth user experience, I used conditional rendering. For example, I displayed a loading message while the API data was being fetched, giving users feedback that the data was being processed.

If the API returned an array of data, I rendered this data as a list in my application. I made sure to correctly use keys, which helped React identify and efficiently update the list items.

Lastly, I implemented basic routing in my application using React Router. This allowed me to navigate between different pages or components based on the URL, providing a seamless user experience.
