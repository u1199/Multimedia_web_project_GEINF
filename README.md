# Multimedia_web_project_GEINF
Visit Tokyo is an interactive tourism website designed to introduce users to Tokyo's culture, gastronomy, nature, and urban life. 

## Description of the page structure and multimedia elements
The page is structured as a single–page layout with a clear visual hierarchy.
At the top, there is a container (title_wrapper) with a background image, the main title “VISIT TOKYO”, an introductory text box about the city, and a carousel motion animation on the right-hand side, with a few Tokyo photos.
Below the background image that vanishes with a black gradient, a horizontal navigation bar allows the user to switch between the four categories: Culture, Gastronomy, Nature and Urban Life. When you enter the web, the Culture section is chosen by default.
The four categories are distributed the same way: A simple introduction at the top highlighting the important points, followed by a list of activities presented as reusable cards, each one including an image, title, short description, and price, along with the option to add it directly to the cart.
In addition, in the top-right of the page there is a cart icon and the number of elements in the cart; both, when pressed, open a dropdown menu that displays the selected items, each quantity, and the total price. There are also in-line buttons to increase or decrease an item quantity.
When pressed, the cart again hides from the screen. 
About the multimedia elements, I've created a edited video using Blender that can be found in the Gastronomy section, with its appropiate description. In the Nature category, I've pasted a photo edited with GIMP, where I applied some color corrections and wrote some text behind the photo buildings. And lastly, an audio explanation about the Urban Life in Tokyo. 

## Development process 
The website was developed step by step using React, starting with a basic page structure and progressively adding interactivity and content. I first created the main background with its gradients and format to make it possible to paste elements in front of it. At first it wasn't an easy task, as the elements started to paste after the background image and so on.
Once the layout was clear, I implemented the category system, allowing users to navigate through the different sections without reloading the page. Then, I created reusable components such as the ActivityCard, the carousel and the audio button, which helped avoid duplicated code and made the main file Webproject cleaner and more simple.
After that, I added the shopping cart logic, and when everything was right to me, I implemented some animations to make it look cleaner.

## Instructions to local run the website
If its the first time using react is important to have an actual version of Node.js. Then, to install all the necessary files use npm-install. After that, use npm install react-icons.
Also, as I've used the Carousel animation and the Audio Container, is very important to use npm install motion. Then, when everything is correctly done, npm start to see it at your Web Browser. 
