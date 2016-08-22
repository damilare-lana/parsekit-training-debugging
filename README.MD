# Debug a ParseKit Parser

This parser is broken, fix it. Use the ParseKit Tools debug package and the `-d` to debug the parser.

## Parsing Strategy

This parser attempts to extract the PRS table from the 2002 County Business Pattern Dataset from the US Census. 

## Installation & Usage
First install the required depedencies:

`pip install -r requirements.txt`

Finally to run the parser, execute:

`parsekit run -d --allow-unsafe`



## Datasource Notes

The data is stored in txt text format. 


## Contacts

Niger Little-Poole <niger.little-poole@enigma.io>