# About the assignment

This is the weekend assignment for Lede progrram 2021.
We dealt with two APIs called "Weather API" and "Last.fm API", and created separate files.

## assignment details
---

**Weather API** 
https://www.weatherapi.com/
    
On Weather API, I wrote a code to see the current weather and forecast where I want to visit, Miami.  Details are below.

0) Import libraries

1) Make a request to the Weather API of Miami (Place I want to go)

2) Find the current wind speed, and how much warmer does it feel than it actually is

3) Request the API endpoint for moon-related information. Find how much of the moon will be visible on next Thursday

4) Culcurate the difference between the high and low temperatures today

5) Print out the next week's forecast. the high temperature for each day, and whether it's hot, warm, or cold

6) Print the hottest day in the next week, and the high temperature on that day

7) What's the weather looking like for the next 24+ hours in Miami, Florida

8) For the next 24-ish hours in Miami, what percent of the time is the temperature above 85 degrees

9) Learn about the API which shows history 


**Last.fm API** 
https://www.last.fm/api/intro 

On Last.fm API, I wrote a code to see the artists like Lil Jon. Details are below.

1)  Search for and print a list of 50 musicians with lil in their name, along with the number of listeners they have

2)  Print how many listeners my list have in totalImport the libraries/packages

3)  Show each artist's name and the URL to the extra-large image

4)  Find Lil Jon's mbid

5)  Find the artist's name and bio using their mbid

6)  Print every tag of that artist

7)  Find the mbids (again)

8)  Saving those mbids

9)  Printing our API urls

10)  Using the first three mbids, request the API urls and print the artist's name

11)  Using the first three mbids, request the API urls and print the artist's name and their tags

12)  Using the first ten mbids, print the artist's name and whether they're a rapper

13)  Find the percentage of "lil" results are rappers

## Something I learned in the process
---

1) for loop (again and again). I don't fall in love with for loop yet, but don't hate anymore.  

2) How to hide my API key. It's first time for me to hear ".env" file.

3) Sometimes, free API has limitation. Knowing the weather on Christmas day in 2010 is a wealthy option.

4) Sometimes, API is dead like extra-large photos. We should take care of it.

5) Miami is hot.

## Something I found challenging
---

1) Finding rappers is relatively easy, but printing rappers and non-rappers on the same list was challenging for me. 

2) When I put {API-KEY} in line to hide my API key. It didn't work at first. I realized I should use f-strings with {API_KEY} like I did on other lines .

3) Understanding Jupyter's characteristic comparing to VS code. Sometimes, I made Jupyter specific mistake.

4) Writing a cool README.
