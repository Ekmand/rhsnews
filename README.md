# RHS News Website
Super dead simple website for our school news, just enough code to remove the nasty wix/editorx banner ;) Useful bit of code for getting around the wix branding restrictions. Just keep the code on the down low, or else I'll have to make something new ;)

## What's the fancy smancy code to remove the wix banner? 
So it's not really removing the wix banner, just making it not visible. Wix has a little vulnerability, and that is that they don't support iframe protection. That means that you can iframe literally any wix website you want, and throw it on a custom domain. No need to pay for the convienience of doing that through wix when you can do it yourself! Something I find myself using more and more when I don't wanna spend days coding a website, and just wanna throw something together real quick that works. 

## Step 1
I assume you know what an iframe is, but if not here's a litle definition. An iframe allows you to put a website inside your code. You can make it however big or small you want, and palce it anywehre on your page, or in our case, make it the entire page. 

The first thing that you'll do is start by adding the iframe tag `<iframe> </iframe>` 

## Step 2
Next You'll add the link you want like so `<iframe src="https://ekmand.dev" ></iframe>`

## Step 3
Now's the fun part, the styles that make this all work. `<iframe src="https://ekmand.dev" style="position:fixed; top:-57px; left:0px; bottom:0px; right:0px; width:100%; height:106%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;"></iframe>`
By setting the top to -57, it pushes the entire site up, leaving the wix banner just above, and with the height at 106, it allows for the website to fit on your entire screen. Without that, there would be a huge white bar at the bottom of the screen, and no one wants that ugly thing while browsing the web. And that's about it. If you really wanna make it look like it's a custom site, I recommend adding a favicon, and some meta elements like an og_image, an og_description, and an og_title. This will make your website so much more legit looking. Not only getting better SEO on google, but also giving platforms like discord a way to pull link previews (that's what the image and description that popo up are)

## step 4
That's it! Pretty simple right? Now of course you'll need to replace the ""https://ekmand.dev"" with your wix/editorx website url (the one that's user.editorx.com/yoursite) and that's really all you'll need to do. 

# You're done!!!
Love that bit of code? Doesn't it make your life so much easier? I know it sure makes making simple sites for me easy. Never wanna forget this bit of code? Hit the star, I'd appreciate it. 
