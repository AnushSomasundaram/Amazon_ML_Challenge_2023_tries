### Data Cleaning

- Filter out the HTML
- Try and extract the values (inches, feet, meters, size, etc)
- Take care of NaN values in DESCRIPTION
- Remove unicode characters
- Remove stopwords
- Remove product description not relevant to size because size matters here

### Data
- A total of 3314 unique PRODUCT_TYPE_ID


### Fun

look into depth?

checking if inch present:
- inch
- in
- digits"
- seperated by x
- seperated by *

if inch present:
- If 3 values present, take middle. multiply by 100
- If 2 values present, take second. multiply by 100

if mm present:
- multiply by 10. goto cm case

if cm present:
- convert to inch, multiply by 100
-
