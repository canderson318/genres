# Genres
I extracted the ISRC codes for every song in my saved songs and put them into a csv file with tunemymusic.com. With that I made a dataframe and applied a function for each
song code that searches the Last.FM API for artist information and iterates through the json response to pull out the genre information and print it to a new field. 
