# Jam session #1
"Web 1.0" 

In this session we go over how to make static web pages. I.e., what the web looked like in the 90s. 
We're going to take a trip down memory lane, starting with the early days of the internet. 
This will give you the basics and a good foundation. 
That way, you'll better understand and appreciate present-day tech when we get to it in a few sessions.


[![Jam Session #1](1-static-html-css.PNG)](https://www.youtube.com/watch?v=jgw1XBNY5Ko)

## Index

- 11.15 Start with local file HTML, open in browser 
- 13.44 Introduce HTML syntax
- 20:30 Make new page, link to other pages
- 30:50 `<div>`
- 37:34 separating content and style
- 40:10 CSS in `<head>`
- 42:31 changing body font
- 51:40 h1 h2 h3
- 56:16 # vs . (id vs class)
- 1:08:00 images
- 1:18:00 embed youtube video

## Code used in Jam Session #1

```
<html>
 <head>
  <style>
   body {
    font-family: helvetica;
    padding: 20px;
    font-size: 25px;
    text-align: center;
   }
   div {
     color: green;
   }
   .content {
     font-family: monospace;
     font-size: 30px;
     color: red;
   }

   a { 
     text-decoration: none;
   }
   a:hover {
     text-decoration: underline;
   }

   img {
     max-width: 400px;
     border: 5px solid black;
   }
   #bottom-image {
     border: 5px solid blue;
   }
  </style>
 </head>
 
 <body>
  <h1>Jam Session #1</h1>

  <div><b>HELLO EVERYBODY!</b></div>

  Check out my video:
  <iframe width="658" height="370" src="https://www.youtube.com/embed/hdWkpbPTpmE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  <img id="top-image" src="https://i.ytimg.com/vi/Yj7ja6BANLM/maxresdefault.jpg"></img>
  <img id="bottom-image" src="https://media.discordapp.net/attachments/498679536721068033/508511491817996288/Code.png?width=579&height=294"></img>

  <div id="my-stuff"> STUFF </div>

  <div class="content"> CONTENT 1 </div>

  <div class="content"> CONTENT 2 </div>

  <div><a href="page2.html">Click this to go to page 2</a></div>
  <div><a href="page3.html">Awesome page three ahead</a></div>
 </body>
</html>
```


Once you feel good about your local changes, it's time to put it up on the Internet. Then your website will be LIVE and visible by anyone from anywhere in the world!

## How to host your page live on the Internet (for free)
1. Make a Github account @ [github.com](https://github.com/) and sign in

2. Click to make a new repository:

   ![Make new repository](https://guides.github.com/features/pages/create-new-repo-button.png)
3. Give the repository the special name `username.github.io` (where “username” is your GitHub user name):

  ![Set special repository name](https://guides.github.com/features/pages/create-new-repo-screen.png)
  
4. That's it! Now any page you put in this repository will appear online. 
    For example, if you put your `hello.html` page in your `your_username.github.io` repository, it will appear online @ `http://your_username.github.io/hello.html` 
    
For more information, see [https://pages.github.com/](https://pages.github.com/) or [https://guides.github.com/features/pages/](https://guides.github.com/features/pages/)
   
