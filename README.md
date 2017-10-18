## Website Performance Optimization portfolio project
I've optimized a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.
And below it's what I did with this project.

#### Part 1: Optimize PageSpeed Insights score for index.html

1- go to https://www.python.org/downloads/ and download python and install it
2-go to https://ngrok.com/download and place the downloaded file in your project folder
3-open gitbash or the command line and navigate to the project folder directory 
4-type in this command to start a live server for your project : # On Mac and Linux: python -m SimpleHTTPServer 8080
5- now if you open localhost:8080 you should see your website
6-open the ngrok file after placing it in the project directory and type in the following: if you are using mac then cd to project file and type ./ngrok http 8080
7- It will then give you a live link that you can use and paste in pagespeed insights to checkout how your optimization is working


#### Part 2: Optimize Frames per Second in pizza.html
- move "queryselector" out if loop
- write " requestAnimationFrame" method to tell the browser that you wish to perform an animation and requests that the browser call a specified function to update an animation before the next repaint. The method takes a callback as an argument to be invoked before the repaint.


### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Optimizing CSS](http://www.cssdrive.com/index.php/main/csscompressor/ "")
* [Optimizing JavaScript](https://closure-compiler.appspot.com/home "javascript")
* [Google Font API](https://css-tricks.com/snippets/css/basics-of-google-font-api/ "")
* <a href="https://tinypng.com/">Optimize images</a>

### Resources
- <a href="https://discussions.udacity.com/">Udacity Discussion Forum </a>
- <a href="https://stackoverflow.com/">stackoverflow </a>
- <a href="https://discussions.udacity.com/">1:1 session with a mentor</a>




