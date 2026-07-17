# Coffee Vending Machine Sales Report

This project is a Power BI report for a coffee vending machine sales dataset including line charts, a column chart, a donut chart, and a slicer. You can download and open `report.pbix` to view the report.

## Screenshots

The following is a screenshot of the report for all coffee types.

<img src="screenshot-1.png" alt="all-coffee-report" width=700>

The following is a screenshot of the report for espresso and americano only.

<img src="screenshot-2.png" alt="espresso-americano-report" width=700>

## Patterns and Insights

The most popular coffee types are:
1. Latte (~24.1% of sales)
2. Americano with Milk (~21.8% of sales)
3. Cappuccino (~15.6% of sales)

And the least popular coffee type is Espresso (~2.4% of sales).

Overall sales (sum of payments) increased from January (mid Winter), peaked in March (early Spring), and then dropped dramatically in April (mid Spring).
Overall sales decreased from May (late Spring) to July (mid Summer) and increased from July (mid Summer) to October (mid Fall).

Overall, sales tend to be lower in the warmest and coldest months.

The lowest non-zero sales occurred in the 6-7 o'clock time slot. The sales increased until it peaked in the 10-11 o'clock time slot, and started decreasing. The second-highest peak occurred in the 16-17 o'clock time slot. 

It appears that the highest sales in an hour occurred a little after the start and a little before the end of the workday.

The median of payment time slots is always in the 12-13 o'clock time slot to the 16-17 o'clock time slot range. The median increased from March (early Spring) and peaked in June (early Summer), then decreased and dipped in August (late Summer). The median hour increased from August (late Summer) to December (early Winter).

It appears that overall, the median of payment time slots is highest in the warmest and coldest months.

Using the slicer, we can see that Americano is visibly more popular in February (late Winter) and March (early Spring).


## Recommendations

Here are some recommendations based on the above patterns and insights:
- Considering the top 3 most popular drinks all include milk, it's important to make sure vending machines do not run out of milk.
- If we ever planned on reducing the number of coffee types served in our vending machines, removing the least popular coffee type, which is espresso, would be the most logical option.
- It's best to refill the vending machines between 11 pm and 6 am, which had zero sum of payments. 
- If we want to start any marketing campaigns, it can be a good option to focus on increasing sales in the coldest and warmest months, where sales seem to be lower than in other months.


## Attributions
The <a href="https://www.kaggle.com/">Kaggle</a> dataset used for this report
<a href="https://www.kaggle.com/datasets/ihelon/coffee-sales">Coffee Sales dataset</a> 
by <a href="https://www.kaggle.com/ihelon">Yaroslav Isaienkov</a> 
is licensed under <a href="https://creativecommons.org/publicdomain/zero/1.0/">CC0: Public Domain</a>.


