## Website Performance Optimization portfolio project
In this portfolio project an example site has to get optimized for speed using multiple techniques. 
The project consists of two parts, in which each part some explanation will be given in how to get the project up and running.

To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html
The following steps are run in order to get the PageSpeed Insights score for index.html:
1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely. Make sure to also  connect your account to Ngrok by running the authentication command

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok authtoken <YOUR-AUTHENTICATION-TOKEN>
  $> ./ngrok http 8080
  ```

1. Copy the public URL in Ngrok and run it in PageSpeed Insights to see the score.

#### Part 2: Optimize Frames per Second in pizza.html
Two main modifications have been made in view/js/main.js to make the ```pizza.html``` page run smoothly.

##### Resizing pizzas in less than 5 ms

##### Optimizations for 60fps

