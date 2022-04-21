# CSS-JS-CLOCK
#
# GOAL: Following along with JS-30 I want to create a css and javascript clock
#
#
# First I decided to create a box with a width and a height of 400px. I used a small border at first to see the size I wished
#
#
# Next I used flexbox to center the box so it would be in the center of the page.
#
#
# Now to change the square into a circle with a border radius property set with a 50% value
#
#
# I had to make the face of the clock relative and the hands absolute to be able to move them within the clock and not change the size of the hands
#
#
# Putting a transform of translate 5px on the clock face I was able to show the full length of the clock hands
#
#
# Noticed that the hands of the clock touch the inside edge of the circle when it rotated. Lowered the width to 49% and it seemed to have fixed it for now.
#
#
# Using the transition-timing-function I was able to get get a realistic ticking of the clock
#
#
# For the JavaScript I made each hand have its own variable. Created a function of setting the date. Learned about new Date(), getting seconds, minutes, and hours
#
#
# Also learned about the setInterval() function