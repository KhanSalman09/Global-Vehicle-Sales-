# Global-Vehicle-Sales-
After finishing the EDA let's see what we have.

We have 558837 rows and 16 columns at first after importing the data. These 16 columns have 5 integer type columns and rest 11 are object or we can say string type columns.

As per the statistical analysis we can say that the Manheim Market Report (MMR) and Selling Price are quite close. The max of odometer is 999999 which seems very high but it is not impossible.

We have some cars manufactured in 1982 this might result as having some Vintage Cars in the dataset.

There are lots of missing values in dataset. Transmission has the highest missing values about 13% which is quite high. Other than this Make, Model, Trim, Body, and Condition have 1%-2% missing values. Besides these other have less than 1% missing values.

We have Year and Sale date columns which should be of datetime data type but they are in int and object type so we'll convert them.

The condition column have values such as 45, 59, 34 etc but this is not correct as it is a column which should have values between 1-5 as rating.

The 'Color' and 'Interior' columns has data point with values '-' which replaced by 'Multicolor' as we don't want to add more values to a particular color.

'Body' column values have some inconsistensies like Sedan, sedan or SUV, suv.

Ford, Chevrolet, Nissan, Toyota, and Dodge are the top 5 brands by the count.

Sedan and SUV are the top 2 body types used in cars.
