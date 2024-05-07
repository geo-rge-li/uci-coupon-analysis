# uci-coupon-analysis
analysis of couponing habits based on a dataset

### Conclusion

Based on the data, the acceptance rate for those with an income lower than 50k is higher than those with an income greater than 50k. This is based on the following stats: 
- Bar coupons acceptance rate for those who visit the bar more than once a month, go to cheap restaurants more than 4 times a month, and have an income less than 50K:  0.7716535433070866
- Carry Away coupons acceptance rate for those who have an income less than 50K:  0.7530966143682907
- Carry Away coupons acceptance rate for those who have an income greater than 50K:  0.7294429708222812

- This trend can be seen in the following visualizations:
![bar_coupons_cheap_restaurants.png](images/bar_coupons_cheap_restaurants.png)
![carry_away_income.png](images/carry_away_income.png)

Having a kid as a passenger reduces the acceptance rate. Based on the following stats:
- Bar coupons acceptance rate for those who visit the bar more than once a month and do not have a child passenger and do not have an occupation in farming, fishing, or forestry:  0.7094339622641509
- Bar coupons acceptance rate for those who visit the bar more than once a month and have a child passenger  0.38095238095238093
- Carry Away coupons acceptance rate for those who do have a child passenger:  0.6971830985915493
- Carry Away coupons acceptance rate for those who do not have a child passenger:  0.7404115996258185

Visualizations for the carry away acceptance rate based on having a child passenger:
![carry_away_kids.png](images/carry_away_kids.png)
![carry_away_no_kids.png](images/carry_away_no_kids.png)

Stats about age show that it appears younger folks are more accepting of coupons:
- Carry Away coupons acceptance rate for those who are 21-31 years old or older than 50:  0.7400744416873449
- Carry Away coupons acceptance rate for others:  0.7320359281437125
- Bar coupons acceptance rate for those who visit the bar more than once a month and are over 30:  0.639344262295082
- Bar coupons acceptance rate for those who visit the bar more than once a month and are under 30:  0.7195121951219512

Overall, those who frequent the places more than 1 once a month are more likely to accept a coupon for those places. Based on the following stats:
- Carry Away coupons acceptance rate for those who go to Carry Away more than once a month:  0.7475117862755369
- Carry Away coupons acceptance rate for those who go to Carry Away less than once a month:  0.6873315363881402

So to summarize, having a kid as a passenger seems to negatively impact acceptance rate. Having a lower income seems to increase the acceptance rate and younger folks are more likely to accept a coupon.