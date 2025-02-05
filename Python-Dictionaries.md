## Dictionaries

[Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp) are used to store data values in key:value pairs. It is a collection which is ordered, changeable, but it does not allow duplicates. 
<br>

To use this, we would first give it a name then a curly bracket ```{}```. inside the ```{}``` is where we will store the key and value pairs. below is an example code:

```
## CountryAbbreviations is the name of the dictionary.
CountryAbbreviations = {

## key:value pair    
"UK":"United Kingdom",
"USA":"United States of America",
"SRB": "Serbia",

}

## To print a specific value in a dictionary, we would input it's key.
print(CountryAbbreviations.get("UK"))

## If you input an invalid key that is not available in the dictionary, it will print "invalid"
print(CountryAbbreviations.get("AUS", "Invalid Key"))
```



