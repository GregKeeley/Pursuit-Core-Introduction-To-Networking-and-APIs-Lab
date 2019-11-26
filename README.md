# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
https://catfact.ninja
{
  "breed": "string",
  "country": "string",
  "origin": "string",
  "coat": "string",
  "pattern": "string"
}
1. A list of 150 random users in English.
https://randomapi.com
{
  "invoiceID": "191125-PRV-74452",
  "date": "November 25, 2019 4:06 PM",
  "itemsPurchased": 1,
  "items": "beer",
  "card": "4532-4626-0427-1628",
  "total": "$9.45"
}

1. All the repos on Github with Pursuit their name
https://api.github.com

- How do we filter down to search terms within the API? 

1. All the JavaScript repos on Github with Pursuit in their name


1. All the Swift repos on Github with Pursuit in their name


1. A list of all Pokemon
https://pokeapi.co/api/v2/
{
"ability": "https://pokeapi.co/api/v2/ability/",
"berry": "https://pokeapi.co/api/v2/berry/",
"berry-firmness": "https://pokeapi.co/api/v2/berry-firmness/",
"berry-flavor": "https://pokeapi.co/api/v2/berry-flavor/",
...

1. A list of all items in Fortnite
(Store items) https://fortnite-api.theapinetwork.com/store/get
{
"lastUpdate": 1574726400,
"lanuage": "en",
"data": [
    {
        "itemId": "e67b4bc-bd9afae-5c95ae3-2ce6ce9",
        "lastUpdate": 1574726400,
        "store": {
            "isFeatured": true,
            "isRefundable": true,
            "cost": 1200,
            "occurrences": 0,
            "isNew": false
            }...
1. A list of all Game of Thrones Episodes.
https://api.got.show/doc/#api-EpisodeMap-GetAllEpisodesMap/
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 - https://catfact.ninja/breeds?limit=1
1. 301 - moved permanently (Most browsers should redirect correctly)
1. 400 - client side error. Can be fixed by correcting syntax or modifying code to resolve issue
1. 401 - Unauthorized request - Client needs to get correct, proper authorization to access API
1. 403 - Forbidden access - Client may be authorized, but there permissions do not allow access
1. 404 - the resource maybe available in the future, but currently cannot be mapped
1. 418 - "I'm a teapot, but you requested coffee"
1. 500  - Server side issue, only resolved by the server


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



