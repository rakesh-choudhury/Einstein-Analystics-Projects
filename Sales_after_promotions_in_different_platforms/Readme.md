## Links to the document:
https://docs.google.com/document/d/1sLjzkDYLQh5M-1VvAeyIWzT8TTbf9C0UY25CfDvETtw/edit?usp=sharing
https://codelabs-preview.appspot.com/?file_id=1sLjzkDYLQh5M-1VvAeyIWzT8TTbf9C0UY25CfDvETtw#0

### About the dataset:
The dataset talks about the different sales based on different marketing factors such as TV Marketing and Radio Marketing. It also has the data on adstock models which can help us to use it for getting different insights in the visualisation. 
The following is the description of the test dataset:

base_sales &rarr Sales without ad spending </br>
tv_Sales_1 ==> Sales with TV spending + adstock model 1 </br>
temp ==> Temperature (normalized) </br>
tv_spend==> Spending on TV ads </br>
week==> Week number </br>
adstock_TV_1==> Adstock contribution for model 1 </br>
tv_Sales_2==> Sales with TV spending + adstock model 2 </br>
tv_Radio_Sales_1==> Sales with TV spending + Radio spending + adstock model 1 </br>
tv_Radio_Sales_2==> Sales with TV spending + Radio spending + adstock model 2 </br>
radioSpend==> Spending on Radio ads</br>
tv_Sales_2_Adstock==> Adstock contribution for model 2</br>
tv_Radio_Sales_1_Adstock==> Adstock contribution for model 3</br>
tv_Radio_Sales_2_Adstock==> Adstock contribution for model 4</br>



### Steps for the Assignment 3 part 1
1. Reading the file into the pandas dataframe
2. Calculating the value of sales done by the TV ads.
3. Took the average of the two tv sales with two different ad stocks and put the final value on the 
4. Similarly for the Radio TV as sales the average of the two different sales associated with two different ad stocks were taken.
5. Finally the dataframe was written to csv and downloaded into the local system.
### Steps for the Assignment 3 part 2
1. The csv was loaded in another notebook so that TV ad expenditure along with base sales vs TV ad sales can plotted in the same graph axes.
2. Similarly the other graph was plotted so that Radio ad expenditure could be seen with base base sales + Radio and TV as expenditure altogether.

#### Observation 1:
The maximum amount of sales occur from week 200 to 260 with the max amount of base sale being 1,222 for the week 223.
The minimum sales occur in the week range 1 to 50, with the least amount of base sale and sales after TV spending being 989 and 987 respectively for week 38.
#### Observation 2:
The sales have definitely increased when compared to the base sales.
The max increase in sales is of about 3.2% for week 201 after spending on TV ads and the min increase in sales is of about 1.68% for week 102 after spending on TV ads.
The amount of money spent on TV ads is not linearly proportional to the increase in the sales. Upon comparing week 201 and 150, money spent on TV ads for week 150 is more than the money spent on TV ads for week 201, but still the gains are more for week 201
#### Observation 3:
We can observe  that the sales figures rose initially but then again dropped, pointing out that there are adstock effects for TV ad spending.
A similar pattern is seen for sales between the weeks 200 and 205, where we find that until the TV ad spending is reduced and then again increased, the increase in sales tapers off.
#### Observation 4:
The increase in sales is not directly proportional to the amount of money spent on radio ads.
When compared to the base sales, the figures rise after spending is done on the radio ads.
The sales actually fell by 0.169% for week 253 whereas, the maximum increase in sales after radio spending is about 3.02% for week 201.
#### Observation 5:
We find sales between the weeks 40 and 45 that had initially improved, again increase after a small dip at week 43 after spending on ads and have not tapered off or remained constant.
Similarly, between weeks 195 and 200, the sales increase initially at week 196, then it goes down for week 198 and finally rises for week 200 before tapering off.
