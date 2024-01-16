# ZeroCool-FreeTv-Frontend
A frontend for watching free tv and movies.

zeroCools FreeTv Frontend is a frontend designed for free television servers like vidsrc. Many streaming services use sketchy servers to stream television. After one of my favorite sites, kk01, was shut down, I thought to get my shows directly from the source. A common source these sites use is vidsrc. I have no idea who runs or where it's hosted but they have so many shows it's insane.

# How to use our frontend

Get the source of the movie or show of your choice. I get mine from luga tv. What I do is look through the javascript, and aboout halfway from the bottom you'll find the source.
You'll know you have the right one when it has the season and episode next to it, "1-1" in our case.

Here's an example of it should look like this:

https://vidsrc.xyz/embed/tt2861424/1-1

Once you have the src, remove the 1-1, the episode and season part.
Next!
Copy and paste your show like it is below to add it to the list.

"<li><a onclick="changeSrc('https://vidsrc.xyz/embed/tt2861424/');">Rick And Morty</a></li>"

The above peice of html code is for rick and morty. Just chance the vidsrc url to the url for your show, change the name, and you should be good to go!

Ya know... it only just occured to me that this could be ever so slightly illegal. fuck da police!
