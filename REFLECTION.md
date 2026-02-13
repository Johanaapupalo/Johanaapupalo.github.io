1. Describe the path an HTTP Request takes from a browser to your GitHub Pages site.
The browser first finds the server address, the Github address. Then the browser connects to github computer using the address and asks for the website files, in this case it would be the index.html and styles.css. Then then GitHub Pages sends back the websites files, and finally the browser reads the files and displays the website in the screen.

2. We discussed Docker Containers in class. Explain how a Docker Container differs from the
environment provided by GitHub Pages.
when we want o use different version of diffrent packages, we can use Docker to make continers and each containers has its own version of the whole sytem and folders. We use this because when we work with someone and want them to have access to the same set up, then we sent an image (all the libraries needed) so that they can have your version installed into their computer very quickly. While github pages is a file server that only delivers static website files, unlike Docker it can not run backend code, host API's or have full control over the server enviroment.
3. AI Attribution: If you used GenAI (ChatGPT, Claude, etc.) to help write code, you must
include the prompt you used and explain one logic error the AI made that you had to fix
manually
"there are bullet points on my nav, how do I get rid of those?" I used this promt to figure out how I could avoid having the bullet points in the selection section and it suggested me to create  
nav ul{
    list-style-type: none;
    margin:0;
    padding:0;
    overflow:hidden;
 }
 by adding list-style-typ: none;
  I was able to get rid of the bullet points, which where there by defoult beacause I used ul. There was no no logic error that I noticed, but i did have to ask what everything meant to fully understand what it was suggesting and why.