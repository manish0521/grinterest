# gridterest
A tutorial on how to make a photo album using CSS Grid.

Hey everyone!

Today we're going to be playing with photos. A LOT. You'll spend some time picking photos, but you'll spend most of your time arranging them. Welcome to... Grinterest!

### Steps

* First thing's first: make a commit for each of these steps. Make an "initial commit" commit now!
* Pick a theme and pick 25 photos from the internet for it. Unsplash.com can help with this! Feel free to spend a little time and have a little fun with the selection process. Obviously not too much time, though! Try to spend less than half an hour on this.
* Using CSS Grid, and only CSS Grid--implement a blank Holy Grail. This was a whole thing before, but it's going to be a little easier with Grid! **For this project, and in general, it's a really really good idea to have a set size, in px, for your container div.** Which, in this case, is the content area. Make it a nice square. You can use relative sizes if you want for the other areas.
* What's going to go IN our Holy Grail? Put some words (and/or more images?) that fit your theme in your heading, footing, and sidebar. We'll be putting the photos you grabbed in our content section. As to your navbar, put a link with no destination in there. We'll be filling it in later.
* Now let's do that thing I mentioned: add all 25 photos to the main section. Do the images look well laid out? Unless you got ahead of yourself, probably not! We can fix that, though.
* Now, if you're doing this with a partner, switch who's driving! Make a commit marked: "initial commit with new driver".
* Put the photos in a 5x5 grid of evenly-sized squares. This won't look good either, because some photos will not be squares. (If you picked all perfectly square photos for some reason, pick at least 5 that aren't!)
* Now try putting the landscape-orientation photos in their own row(s), and the portrait-orientation in their own row(s). If you don't have a multiple of 5 of each (again, weird if you do), there are two simple solutions to having squares and rectangles intermixed.
* The first is to center the square images within each rectangle. Do this for the landscape row(s). If your particular grid solution already did this for you, you're done!
* The second solution is to streeeeeetch the square images. Do this for the portrait row(s). Again, if your particular grid solution already did this for you, you're done!
* Now for the better solution: put the squares all in their own rows or columns, and leave the rectangles in their respective rows and columns. You will very likely have to do a fair bit of work to make this happen, but it'll look _real nice_. Think about what portion of the container each row and column should take up. Then make it so!