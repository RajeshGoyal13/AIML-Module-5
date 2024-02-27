#  “Will a customer accept the coupon?” 
The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. The link for Python file used for this is 

## Understand the data:

The first step for this assignemnt was to understand the data. Looked into the attributes of the data.

<img width="1002" alt="Screenshot 2024-02-26 at 9 39 01 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/1d337de9-8533-4616-a23f-4d2a29e672af">

* There were total 26 columns but many of the columns have data as Objects, and there were few columns which have some missing data.

Data columns (total 26 columns):

<img width="459" alt="Screenshot 2024-02-26 at 9 34 29 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/142a786e-b3f8-469d-9754-67b29d7807db">



Also some of the values have range or commas. It was important to make the data readable and understandable. So , approach taken was to replace the ranges to average value e.g. 1 to 3 range was replaced with 2, so that data can be simplified. Also changed the data into numeric for most of the attributes.

## Analyze the data:

 First created the bar chart to visulaize how the coupons are distributed.Below chart shows, maximum Coffe House has the coupons data and then Restaurant <20.

  <img width="782" alt="Screenshot 2024-02-27 at 5 30 16 PM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/a298d393-b252-41e9-87db-e8fba9aee801">

### Investigating the Bar Coupons
+ To investigate the data only related to Bar coupons, created a new data frame. The data looked like:
  
<img width="1001" alt="Screenshot 2024-02-27 at 5 36 31 PM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/c05eff39-4c99-4432-b5fe-ae6d97477fe5">

+ The investigation found that Proportion of accepted Bar coupons is : 41%. so it means almost 59 % drivers going to bar donot accept the coupon.
+ The acceptance rate for those who went to a bar 3 or fewer times a month was 33 % while those who went more was 20 %. So, it shows that drivers who go less to bar in a month, has the more probability to accept the coupon.
+ The acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry: 19.69
+ The acceptance rates between those drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed is : 19.48
+ The acceptance rates between those drivers who go to bars more than once a month and are under the age of 30 is : 12.34
+ The acceptance rates between those drivers who go to cheap restaurants more than 4 times a month and income is less than 50K is : 7.68

Finding for Bar coupons : Looking at the above aceptance rates, we can hypothesize that the drivers who go to bars more than once a month and  that were not a kid, and were not widowed are more likely to accept the bar coupon as compared to those drivers who go to bars more than once a month and are under the age of 30.

### Investigating the Bar Coupons (Similar to Bar coupons, investigated the Coffee House coupon group.)
+ To investigate the data only related to Bar coupons, created a new data frame. The data looked like:
  
<img width="1001" alt="Screenshot 2024-02-27 at 6 05 38 PM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/ce028cfa-4f1e-4679-9816-2e38ae329506">

+ The investigation shows that Male drivers who went alone are going to accept Coffe house coupons more than the Female Drivers.
+ But Male drivers who went with friends are going to accept Coffe house coupons less than the Female Drivers.

# Final findings across whole data frame
+ Histogram of Coupon Accepted without/with Passengers shows that drivers going alone accept the coupons more than the ones who goes with kids or partners.
  
<img width="850" alt="Screenshot 2024-02-26 at 11 53 47 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/77516147-7289-4347-83d8-f6dc7dc5e273">
+ Histogram of Coupons accepted based on Marital Status across various outlets shows that drivers who are single or are married  accept the coupons more than the ones who are widowed or divorced.

<img width="850" alt="Screenshot 2024-02-26 at 11 54 20 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/4ace3c07-d6e5-4f58-85ca-8346f4940eda">

<img width="850" alt="Screenshot 2024-02-26 at 11 54 48 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/9c1b4be9-7fdb-4ea5-a4f4-0e252561f631">

<img width="850" alt="Screenshot 2024-02-26 at 11 55 14 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/f2323b78-ce84-498d-ad3d-07a63b2ad18c">

<img width="867" alt="Screenshot 2024-02-26 at 11 55 27 AM" src="https://github.com/RajeshGoyal13/AIML-Module-5/assets/161057282/b46d0915-f117-4be8-ba5a-649a79eff502">
