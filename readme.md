![](images/person-holds-a-basket-full-of-groceries-in-a-supermarket.jpg)

In this project I used the K-means algorithm to cluster grocery items based on their transaction data.

**Items that are often purchases together can be placed in the same aisle or aisles closer to each other,
increasing sales!**

This used to be done by human experts, which would require **many years of experience** in the industry to
narrow things down. However, with the rise of big data and machine learning, why not
let AI do all the trick and hard work for you?

### A few examples:

- Low/non-fat diary cluster:

| | product_id | cluster | product_name |                                          aisle_id | department_id |    
|--------:|-----------:|-------------:|--------------------------------------------------:|--------------:|----|
|   1901  | 10         | 42372        | Pineapple on the Bottom Greek Yogurt              | 120           | 16 |
|   1902  | 10         | 33791        | Raspberry on the Bottom Nonfat Greek Yogurt       | 120           | 16 |
|   1903  | 10         | 48626        | Coconut Blended Greek Yogurt                      | 120           | 16 |
|   1904  | 10         | 44156        | Strawberry on the Bottom Nonfat Greek Yogurt      | 120           | 16 |
|   1905  | 10         | 33548        | Peach on the Bottom Nonfat Greek Yogurt           | 120           | 16 |
|   1906  | 10         | 7533         | Low-Fat Strawberry Banana on the Bottom Greek ... | 120           | 16 |
|   1907  | 10         | 38241        | Low-Fat Mango on the Bottom Greek Yogurt          | 120           | 16 |
|   1908  | 10         | 46817        | Non Fat Black Cherry on the Bottom Greek Yogurt   | 120           | 16 |
|   1909  | 10         | 23296        | Blueberry on the Bottom Nonfat Greek Yogurt       | 120           | 16 |

- Organic product cluster:

| | product_id | cluster | product_name |                      aisle_id | department_id |
|--------:|-----------:|-------------:|------------------------------:|--------------:|----|
|   1150  | 5          | 45066        | Honeycrisp Apple              | 24            | 4  |
|   1151  | 5          | 47209        | Organic Hass Avocado          | 24            | 4  |
|   1152  | 5          | 45007        | Organic Zucchini              | 83            | 4  |
|   1153  | 5          | 26604        | Organic Blackberries          | 24            | 4  |
|   1154  | 5          | 44359        | Organic Small Bunch Celery    | 83            | 4  |
|   1155  | 5          | 46979        | Asparagus                     | 83            | 4  |
|   1156  | 5          | 24184        | Red Peppers                   | 83            | 4  |
|   1157  | 5          | 28985        | Michigan Organic Kale         | 83            | 4  |
|   1158  | 5          | 40706        | Organic Grape Tomatoes        | 123           | 4  |

