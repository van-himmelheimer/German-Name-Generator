# German-Name-Generator

A (very) simple name generator for German names. 

It uses lists of the most common German family names and of popular male/female first names which I got somewhere from Wikipedia, I think. (Warning: the first names may be rather old fashioned.)

* a list with over 3000 common German family names
* lists with more than 100 of the most frequent male/female first names

This script is several years old, I just uploaded it to have something on my github account :)

## Usage:
From the command line:
```bash
# this yields a single name (randomly male or female)
python german-name-generator.py

#this yields 10 names (randomly male or female)
python german-name-generator.py any 10

#this yields 5 (3) male (female) names
python german-name-generator.py m 5
python german-name-generator.py w 3
```

From a python script:
```python
import german-name-generator as namegen

namegen.get_random_name("any")
namegen.get_random_name("m")
namegen.get_random_name("w")

```
