# AJAX_TYPE_AHEAD

I Created what I like to call a type of head feature 
where I've got a list of cities and states with their
population in it when I type something in like new it's 
going to show me everything that matches the word new like 
new york, new jersey. If I type in Boston or west it's going 
to show me every single city and state that matches whatever 
I've typed in along with the corresponding population now this 
data is going to be coming in from an external Source what I've 
done is I just went on GitHub here and I found a cities.json file 
which will include the city name the state name as well as the population 
that we have here and I put that into a URL so first thing that we need to 
do is actually go and fetch this data which is a huge array and then once 
that data is back whenever someone types into the specific box we're going 
to filter that array down to a subset of all of the ones that either the city 
name or the state name will match. 
