# First we are gonna create the element at the top to represent our header
* So i create new <div> with class header and i put there the search bar
* The header is gonna have 3 sections: left, middle and right, so first i create 3 <div>
* Search bar will be in the middle section

# Next we are gonna take care of margin 
* I set margin in body to 0, so it will set all margins in all directions to 0

# Now i can start styling the header
* I add height to the header and i get into 55px in the header class

# Next i gonna positions all 3 sections
* Now our sections are aligned vertically, that's because <div> by default is display-block
* To create horizontal layout i change header container to flexbox
* So i change display in header class to flex and the flex-direction to row
* Now the sections take only as much space as they need to 

# Then to create our auto-resizing middle section we are gonna use flex property
* The right and left sections will gonna have pre-define width, so when we resize the page it don't change it's width
* The fixed width of our left-section will be 150px
* The middle section will be stretch, so i change flex to 1
* And the right-section fixed width is 200px

# Next i gonna add spacing on the left and right side of the middle section
* I add margin to the left 70px and to the right 35px
