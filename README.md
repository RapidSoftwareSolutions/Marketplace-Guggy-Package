[![](https://scdn.rapidapi.com/RapidAPI_banner.png)](https://rapidapi.com/package/Guggy/functions?utm_source=RapidAPIGitHub_GuggyFunctions&utm_medium=button&utm_content=RapidAPI_GitHub)

# Guggy Package
Guggy is the leader in smart predictive GIFs.
* Domain: [Guggy](http://guggy.com)
* Credentials: apiKey

## How to get credentials: 
0. Request your apiKey at [Developers page](https://guggy.com/developers)



## Custom datatypes: 
 |Datatype|Description|Example
 |--------|-----------|----------
 |Datepicker|String which includes date and time|```2016-05-28 00:00:00```
 |Map|String which includes latitude and longitude coma separated|```50.37, 26.56```
 |List|Simple array|```["123", "sample"]``` 
 |Select|String with predefined values|```sample```
 |Array|Array of objects|```[{"Second name":"123","Age":"12","Photo":"sdf","Draft":"sdfsdf"},{"name":"adi","Second name":"bla","Age":"4","Photo":"asfserwe","Draft":"sdfsdf"}] ```
 

## Guggy.createGIFs
Get gifs based on sentence

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your apiKey from Guggy
| sentence| String     | Sentence to get your gifs
| lang    | String     | A two character ISO 639-1 language code that will direct Guggy to use a specific language when extracting context and trending content.

## Guggy.getTrendingGIFs
Get trending gifs

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your apiKey from Guggy
| lang  | String     | A two character ISO 639-1 language code that will direct Guggy to use a specific language when extracting context and trending content.

