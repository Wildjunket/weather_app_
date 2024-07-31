



<h1>weather_app_</h1>

<h3>Overview</h3>
weather_app_ is a React-based application designed to provide users with weather information and forecasts. This application includes various components such as Home, Summary, Header, and Footer, along with routes for different weather categories and blog posts.

<h3>Features</h3>

Home Page: Displays the main content and navigation.
Weather Summary: Shows detailed weather information for selected locations.
Header and Footer: Provides consistent navigation and information across all pages.
Weather Categories: Includes various categories for different weather types.
Blog Posts: Displays and manages blog content related to weather.
Technologies Used
React
React Router
Bootstrap
CSS

<h2>Method 1</h2>

Installation
To run this project locally, follow these steps:

Clone the repository

bash
Copy code
git clone https://github.com/yourusername/weather_app_.git
cd weather_app_
Install dependencies

bash
Copy code
npm install
Start the development server

bash
Copy code
npm start
The application will be available at http://localhost:3000.

<h2>Method 2</h2>
<p>this method is for the linux like Ec2 ubuntu Machine</p>

if you use jenkins the you need to integrate the jenkins or github or you can maualy add the code folder

the you go inside the code folder the run these command

sudo apt update
sudo apt install nodejs
sudo apt install npm
sudo npm install

now install Docker to run project on container

i provide a Docker file now crteate a image by using Dockerfile

Docker build . -t <imagename>
sudo Docker run -it --name <nameyouwant> -p 5173:5173 <imagename>

then the project run on the public ip of your ec2:5173  like this 


*Make sure you open the port in inbound rule 

Hope you enjoy the project
