# ML6290_Group2

## • Structure (2#)

### - Group information (3#)

Xuan Zhao (xuanzhao@gwu.edu)

Suyash Shrivastava ([suyash65@gwu.edu](mailto:suyash65@gwu.edu))

Jiujiu Yang ([hello99yang@gwu.edu](mailto:hello99yang@gwu.edu))

### Clearly delineated sections

#### - Intended use (4#)

##### * Primary intended uses (1st & 2nd points: business values) (5#) 

* Intended to be used for bank systems to make a decision whether they lend to the mortgage applicants based on those lenders’ personal backgrounds, such as their standardized income, race, gender, etc.

##### * Primary intended users (3rd points)

* Particularly intended for those mortgage applicants who are planning to invest in real estate.

##### * Out-of-scope use cases (4th point, consider)



#### \* Training data 

* Home Mortgage Disclosure Act (HMDA) labeled data.
* The data is split into training data as 0.7, and validation data as 0.3.

* Train data rows = 112253, columns = 23

​		Validation data rows = 48085, columns = 23

* the meaning of all training data columns:
  * black: Applicants with black skin
  * asian:  Applicants with yellow skin
  * white: Applicants with white skin
  * amind: Applicants with **???**
  * hipac: **???**
  * hispanic: **???**
  * non_hispanic: **???**
  * male: 
  * term 360: Binary numeric input, whether the mortgage is a standard 360 month mortgage (1) or a different type of mortgage (0).

​		

