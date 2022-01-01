## Adding Music to directory - locally on Website

create any folder name in this demo we made a folder called `songs`

our directory looks this now

    /assets
        ... All webfiles
    index.html  
    /songs

in songs folder add all your `.mp3` and `.ogg` music files to this folder - NB in GitHub Pages make sure your file sizes are less than 100MB otherwise you got a big issue else if you have GitHub LFS you can go ahead.

in this demo we will add one song file

called `OhWonderSharkIlleniumRemix.mp3`

our directory looks this now

    /assets    
        ... All webfiles
    index.html  
    /songs
        OhWonderSharkIlleniumRemix.mp3

## Auto Build Support
TODO - a python script to build and find music/covers in your directory and inject the JavaScript Payload to make life easier.

## Adding Music to the library/app

Once you got your music added to the places the app now needs to recognise the library you added.

we will work in the file `/assets/js/script.js` for now - (This is our main music controller logic)

in `line 20` or any other line find the `tracks` variable

it should be an array with dictionary values inside of it

example of syntax in `script.js` for the library of songs

    tracks= [{
        "name": "name of song",
        "cover": "link to artwork/directory to artwork"
        "source": "link to raw .mp3 or .ogg file"
    }]

in this demo we add `OhWonderSharkIlleniumRemix.mp3` to the app so our syntax will be

    tracks = [{
                "name": "Oh Wonder - Shark (Illenium Remix)",
                "cover": "https://i1.sndcdn.com/artworks-000094845967-6wb79s-t500x500.jpg",
                "source": "./songs/OhWonderSharkIlleniumRemix.mp3"
    }]

if you noticed carefully young padawan you can see we used the local music file from the website repo and the cover from a Web URL from `SoundCloud`


if you understand this carefully proceed to the next step young padawan.