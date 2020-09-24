# BigMart_Sales_Prediction

| Variable	                    | Description                                                                                 |
  -------------------           | ---------------------------------------------------------------------------------------------
|Item_Identifier	              |  Unique product ID                                                                          |
|Item_Weight	                  |  Weight of product                                                                          |
|Item_Fat_Content	              |  Whether the product is low fat or not                                                      |
|Item_Visibility	              |  The % of total display area of all products in a store allocated to the particular product |
|Item_Type	                    |  The category to which the product belongs                                                  |
|Item_MRP	                      |  Maximum Retail Price (list price) of the product                                           | 
|Outlet_Identifier	            |  Unique store ID                                                                            |
|Outlet_Establishment_Year	    |  The year in which store was established                                                    |
|Outlet_Size	                  |  The size of the store in terms of ground area covered                                      |
|Outlet_Location_Type	          |  The type of city in which the store is located                                             |
|Outlet_Type	                  |  Whether the outlet is just a grocery store or some sort of supermarket                     |
|Item_Outlet_Sales	            |  Sales of the product in the particular store. This is the outcome variable to be predicted.|

These are the variables we will use to predict the number of sales.
We have achieved an RMSE score of 1089 on k fold cv split and 1031 on test set.
