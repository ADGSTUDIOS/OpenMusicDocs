# Welcome to OpenMusic Docs

## Introduction

this is an Open Source Project which allows you to host your music (.mp3, .ogg) and have it stream cross platform with zero restrictions. Allows for full personalization this project is yours to bootstrap from.

### How does it work?
- Basically you are deploying a web server which exposes your links to the audio files/cover art and OpenMusic will take care of everything else for you.

- You just have to fill in an array of tracks with your data linking to your files and thats it OpenMusic will sort you out.

- This Web App is cross platform you can get your own Streaming Service for Free 🤑 you can host this repo on your GitHub account (on GitHub pages for free 🤑) by forking the repository [Link to Repo](https://github.com/ADGSTUDIOS/OpenMusic/) 


- The Web App handles `Nth` amount of songs provided that you keep each .mp3 under 100MB on GitHub 
if you serve it on Nginx server etc you can store any size audio files as you need.

### Updates / Contributions

- fixes for missing artworks should be replaced with onerror event - to change `src` to `nomusicicon.png`
- an update will be provided in the future to fix UI glitches and also add more functionality to the app. - Feel free to hit us with a Pull Request (its free real estate ...)
- have ideas for Chromecast, Notification Bar Controls, Sliding Music Control bars etc ... i'm too busy working on other projects (if i have a spare break ill work on this project) if your build it i will commend your and put your name in the credits!
- Python Script to auto build library (finding music and photos from directory)- Array for `script.js` (coverart and music)

### Tech Stack
![StackPhoto](./static/stack.png)

### File Structure

    assets      # Consists of all Website files consisting of CSS,SCSS,fonts,images and JavaScript folders consisting files which builds up the web player.
    index.html  # The Web Player front end html file.
    ...         # Other (song files / cover artwork) folders can be added!
