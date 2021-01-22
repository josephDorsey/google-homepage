# google-homepage

Hello! This is my first mini-project. I am required to deconstruct an existing web page and rebuild it. The goal is to start thinking about how elements get placed on the page and roughly how they get styled and aligned. 

# 1/14/2021 Update 1

Made a couple of changes to html and css. First I added classes to the top buttons in the header div. Next, I changed the footer div to have a bottom of 0 to bring the nav bar to the bottom and gave it a colored background.

Also changed the value and type of the search and feeling lucky buttons. Now I need to fix their sizes and work on adding a line over the footer. Also attempting to add a box shadow on hover for the search bar.

# 1/14/2021 Update 2

Was able to fix the Google Search and Feeling lucky buttons, by changing their height and width and as well as adjusting their margin-left property. Fixed the issue with the border around the Google Search and Feeling lucky buttons, deleted the :hover code to it.

I still plan on working on the middle-content, but if there's time I will also work on the footer:

    -rounding out the search bar
    -adding a shadow element to the hover function of the search bar
    -how to put the magnifying glass and the input voice in the search bar

# 1/18/2021 Update 3

First let's address what was able to be worked on in this current update! 

1. I was able to round the search bar (.searchbar class)
    - rounded it to 20px;

2. I was able to add a shadow element to the hover function of the search bar (.searchbar:hover)
    - box-shadow: 0 4px 8px 0 rgba (136, 136, 136,0.2), 0 6px 20px 0 rgba (167, 167, 167, 0.19);

3. learned how to add the magnifying glass and input voice icon in the search bar
    
    -first I added two background images:
        1. url ("magnifying-glass-1976105_1280.png")
            - then I changed the background position to left center
  
        2. url ("googlemicrophone.png")
            - then I changed the background position to right center
    - made sure the background-repeat was set to:
      - no-repeat

4. Next I updated the #footer div, I changed the positioning on it and added a border-top.
    
    - I added left & right: 0;
    - had a min-width and max-width of 100% to stretch the footer on the bottom page
    - added a border-top
    - added green leaf icon to link on the footer

Also added a new link to CSS emojis in html

Ok thats the end of this update, here are the next things that I may try in the next update:

1. How to space out the buttons on the top on bottom rows to their own grid areas
2. Add the app drawer and profile photo emoji
3. How to bring the google logo and middle-content div to the center of the page

# 1/21/2021 Update 4

Fixed a lot in this update. I learned how to space out the buttons on the top and bottoms rows and to their own areas. I added the app drawer and profile picture to the links above. I also centered the google logo & searchbar  (or so I hope) to the center of the page.



There are a few things I would like to fix but that's perfectionism and I should be happy with how this has turned out so far! I feel like I really learned a lot about this project and I am looking forward to the next ones.