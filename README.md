# Startup Names

Project of Epiphyte blog, from Greg Sherrid.

Data from [notpeter/crunchbase-data](https://github.com/notpeter/crunchbase-data).

## Setup

```
# One time
virtualenv -p python3.6 env
source env/bin/activate
pip install -r requirements.txt
python -m spacy download en_core_web_sm

# Each new tab
source env/bin/activate
```

If you want to generate examples, you'll also need to download corpora:

## License

This code is free to use under the terms of the MIT license. 
Data from Crunchbase available under the Creative Commons Attribution-NonCommercial License.
[See more](https://github.com/notpeter/crunchbase-data/blob/master/LICENSE).