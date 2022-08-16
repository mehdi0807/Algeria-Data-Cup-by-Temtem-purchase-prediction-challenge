# Algeria-Data-Cup-by-Temtem-purchase-prediction-challenge
### About
The data contains all orders made on the shopping app from January 1st 2021 upto February 15th, 2021. The data contains 29774 order. Both train and test set contains order during the same period (1/1/2021), test set has exactly the same structure as train set except for the target class column “Purchase Again” which is only included in the train set clearly.

Note that one order can contain multiple order items and is made by only one customer. Each order item is a row in the dataset.

### Variable definitions :

- Order ID: ID of the order
- Order Status: whether an order has been Completed, rejected or another status.
- Category Name: Category name of each product that has been ordered
- Product Name: Name of each product that has been ordered (in French)
- Quantity: Quantity of the product in an order.
- Unit Price: unit price of the product.
- Total Price: Unit Price*Quantity of an order item
- Subtotal: Total of the whole order (sum of total price for each order item).
- Payment Method: Method of payment of the order, ex : cash or by card for example.
- Customer ID: ID of the customer who made the order.
- Merchant: ID of the seller/merchant of the product (order item).
- Order Time: The exact date & time when the order has been made.
- Customer Country: country of customer, “Algeria” mostly.
