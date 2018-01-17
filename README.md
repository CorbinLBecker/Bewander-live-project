# Bewander-live-project
Worked on a Live website. Here are most of my code I contributed


SMALLER CHANGES FOLDER
In the Smaller Changes Folder I have a simple changes that were mostly good for learning how to navigate through a solution of that size. There consists of a css styling change when you hover over the amount of likes and it went from displaying the names in a oversized box to more of the bootstrap looking pill shape. 

I also made a javascript alert in an else statement if someone clicked to add a picture but no picture was selected.

Lastly I fixed a link directing to a wrong area.

COMMENTS DROPDOWN FOLDER
This story I made it so the comments displayed on the modul were limited to 5 with a see more comments link. The drop down link displayed the rest of the comments. First I used .Take(5) on line 10 to only display the first 5 comments. Then used the same large method for posting a comment, wrapped it in a div called #PostFive and had the div's css styled to display: none. Then inside the div back on the viewpage instead of take(5), I had skip(5). Between the two large code blocks I have a nice link there for more comments to be displayed. There is some Javascript attached to the link that is triggered to display the div when clicked. 


CHATBOX PROFILE PIC FOLDER
Getting a profile image to display on the chatbox nav. I was working within the chatbox view for this story. They already had the other users profile name displayed at the very top of the name through html action method so I was hoping that I would be able to find a similar way to connect the nav picture like so. Which Is what you see on like 8 is me using razor syntax to calll an html action. I’m calling the method LilMessagePic which was repurposed code that you see your own profile picture in the top right of the website. I tweaked that method so that it was pulling from the target user as oppose to your own user and displaying a picture with all the nice styling in place.

A LITTLE MORE JQUERY FOLDER
This was a simple enough story. When adding a comment on a post module, instead of the onclick event with the add button I was trying to make it so you could hit the enter button and get the same effect. Eventually landing with the code displayed.
Probably not the most impressive mix of javascript and jquery although I battled with a bit longer than Im willing to admit. After eventually deciding the code was working through a process of console.print debugging  scenarios  I changed the .keypressed to .keydown event action . lo and behold it is functioning!
