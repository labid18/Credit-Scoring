# Credit-Scoring
### Context
The original dataset contains 1000 entries with 20 categorial/symbolic attributes prepared by Prof. Hofmann. In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes. The link to the original dataset can be found below.

### Content
It is almost impossible to understand the original dataset due to its complicated system of categories and symbols. Thus, I wrote a small Python script to convert it into a readable CSV file. Several columns are simply ignored, because in my opinion either they are not important or their descriptions are obscure. <br/><br/>The selected attributes are:

Age (numeric) <br/>
Sex (text: male, female) <br/>
Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled) <br/>
Housing (text: own, rent, or free) <br/>
Saving accounts (text - little, moderate, quite rich, rich) <br/>
Checking account (numeric, in DM - Deutsch Mark) <br/>
Credit amount (numeric, in DM) <br/>
Duration (numeric, in month) <br/>
Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others) <br/>
