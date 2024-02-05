# Vehicle Data Analysis

This is a dataset from a company who deals in selling of second-hand cars. Features in this data set are - Car_Name, Year, Selling_Price,	Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, Owner.

I haved Microsoft Excel to clean, visualize and analyze the data.

## View of the Excel dashboard:

![Screenshot 2024-02-05 143546](https://github.com/kanishkagargg/Vehicle-Data-Set-Excel/assets/140965958/45b83732-1782-4a20-9c7e-482911239454)

## Cleaning involved: 
  1.	Name of the cars should start with capital letters. Hence made a new column for it.
  2.	Outlier - There is one scooty called Activa 3g which covered 5L kms , runs on petrol, is automatic and was from 2008. This is not possible for a scooty to cover this much of distance. I moved it to the end    of the row so that I could avoid it in calculations and not removing that entry at all.
  3.	There is a name of a car called 800 and from 2003. This could be Alto 800.
  4. Added two columns called kms bins (to convert categorical from continuous) and pp-sp which is present price - selling price.

## Key Findings:
  1.	This data could be of a business who deals in selling second-hand cars.
  2.	Total 301 cars are listed out of which only 98 are of unique brand.
  3.	There are more manual cars than automatic cars. Manual cars comprises of 87% of the total cars listed.
  4.	65% of the cars are sold through another dealer involved, while 35% sold are directly from individuals.
  5.	Maximum car uses petrol (79%), then comes diesel cars (20%) and only 2 cars uses CNG.
  6.	Average kms run by diesel is 50k, by CNG is 42k (from only 2 cars) and by petrol 33k.
  7.	Maximum car uses petrol (79%), then comes diesel cars (20%) and only 2 cars uses CNG.
  8.	Maximum cars covered distance of 10k-50k. 
  9.	70% cars are manual and runs on petrol.
  10.	Maximum cars listed are from 2013-17 (72%).
  11.	Maximum change in prices happens to those cars who are from 2010 and 2015.
  12.	Average present prices of all the cars driven between 70-80k is the highest. But the sum of present prices is highest for those cars who ran between 40-50k. This is because there are 11 cars under 70-80k      slab and 47 vehicles in 40-50k slab. Hence, average goes down in 40-50k slab.

