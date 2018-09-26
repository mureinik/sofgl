# sofgl.github.io
##### SOFGL - StackOverFlow Flair Generator for Linkedin.   

**Happy Braging**

### Introduction:-  
_SOFGL is a hack which allows you to show your StackOverflow flair on linkedin like you see in [this](https://www.linkedin.com/in/vipul-bhardwaj-172a50145/) profiles media_.

### How to do it:-  
Step 1:- Fork or clone this repo.     
Step 2:- Open index.html file, there you see in the _div.container_, this div contains an image tag which is getting your flair from StackOverflow, change the _<user-id-number>_ to your user id.             
Step 3:- Open the index.html file in your browser, you should see your flair from StackOverflow.          
Step 4:- Make this available online.(Using github pages is a nice option).         
After this step, you should have a url which shows this page with your flair, something like [this](https://vipulbhj.github.io/) if you are using github pages.         


**_Now comes the fun part_**, we are going to use a free available public thumbnail RESTAPI(I am going to use _thumbnail.ws_ but you can use whatever you want).     


Go to [_thumbnail.ws_](https://thumbnail.ws/), and Sign Up to create a new account. After you are done creating a new account, they will mail you your api key and an example on how to use there api which will look something like _https://api.thumbnail.ws/api/ab1ee68a2153c70e75c72efaeb6f8dc5b2b088f17056/thumbnail/get?url=https://thumbnail.ws/&width=480_.      

See that there is a parameter called url, this is where the magic happens. Go ahead change that to any website you want. Here is what happens when I replace it with [Facebook.com](https://api.thumbnail.ws/api/ab1ee68a2153c70e75c72efaeb6f8dc5b2b088f17056/thumbnail/get?url=https://fb.com/&width=480).                   

Hope you all have guessed the next step, use this API and replace the url with the url where your flair is hosted. Then use this big url in the media section of your linkedin profile.          

Here is an example of what it might look like _https://api.thumbnail.ws/api/ab1ee68a2153c70e75c72efaeb6f8dc5b2b088f17056/thumbnail/get?url=https://vipulbhj.github.io/&width=480_      
I encourage you to experiment more with this.      

**And there you have it,_If you like this hack, do make sure to like it and share it_**                

P.S :- Instead of using any thumbnail service you can make your own. If you are using JS, then check out Phantom.js which is a good starting point for this.


**Happy Braging**
