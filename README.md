# Data-Science-Assignment-2017
This repository will hold any raw data extracted from Donald Trump's public Twitter account information.

Should you wish to extract the data from these text files:

1. Download the file
2. Open it in python (while importing the json library)
3. Load the data as a string s
4. dictionary = json.loads(s)

Querying can be done as follows:

1. dictionary["data"][<put_index_here>][<put_search_tag_here>]

e.g. trump_friends["data"][0]["location"] will give you Sarah Sander's location in Washington DC, since she's the first entry.
