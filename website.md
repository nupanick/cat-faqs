# Making A Live Website: FAQ/Walkthrough (PC)
_*Version 0.1, By Nick "Nupa" Lamicela.*_

I am making this guide because I was having trouble finding a good one. When I search for information on how to make a website, most of what I find involves using some sort of pre-fab website service like Blogspot or Wordpress or whatever, or it has some sort of vague not-immediately-actionable concepts like "you'll need to buy a hostname at some point" and so on. This guide isn't like those -- by the time you've finished reading this, you should be able to set up a website, from scratch, without buying *anything.* This guide assumes the following:
- You have a computer that is connected to the internet.
- You know how to edit text files.
- You're not afraid to learn some old-school stuff.

Also, for those of you who know what these words mean, I'll be using HTML, CSS, JavaScript, PHP, and Apache. I know these tools are "old" now, but they're what the web was built on so I'm convinced they're worth learning.

## Overview
A website is made up of a **client** and **server**, and the server is further made up of the **host** and the **backend.** I'm going to cheat a little and make up my own terms for this, since "server" can refer to like two or three different things and I don't want to have to explain that every time.
- When I talk about the *body* of the site, I mean everything that appears directly in the browser. This is your text, images, and any code that runs on the user's end.
- When I talk about the *heart* of the site, I mean all the heavy lifting done by the server to actually "serve" content to the user.
- When I talk about the *soul* of the site, I mean any additional code or scripting that runs on the server even if no users are visiting it.

Users can tinker with the client, adding or removing code as they wish, since it all exists on their machine when they visit your website. Most users won't do this, but keep it in mind. _(Move this to a better place)_

When you start making a website, you can start from either end. If you start from the client, or "front end", you'll begin by designing the look and feel of your website. Images, text, buttons, and the way they're laid out on the page. It won't be "live" until you set up a server to host it on, but you can always do that later.

If you start from the server, or "back end", you'll begin by getting your computer connected to the real internet, where other people can see your work. 
