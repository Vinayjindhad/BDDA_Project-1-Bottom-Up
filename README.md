# BDDA_Project-1-Bottom-Up


Objective:
The goal of this project is to design a comprehensive and robust database schema for the Myntra e-commerce platform using the bottom-up approach. This approach focuses on defining and integrating the most granular elements first, building up to a complete database structure that meets the operational needs of the platform.

Steps Involved:
Entity Identification:

The project begins by identifying key entities relevant to the Myntra platform. These entities represent core components of the business and include:
Customer: Information about customers.
Product: Details of the products sold on the platform.
Order: Records of customer orders.
OrderItem: Items included in each order.
Category: Product categories.
Brand: Information about product brands.
Review: Customer reviews of products.
Attribute Definition:

For each entity, relevant attributes are defined. These include:
Customer: CustomerID, Name, Email, Address, PhoneNumber, etc.
Product: ProductID, Name, Description, Price, StockQuantity, CategoryID, BrandID, etc.
Order: OrderID, CustomerID, OrderDate, TotalAmount, etc.
OrderItem: OrderItemID, OrderID, ProductID, Quantity, Price, etc.
Category: CategoryID, CategoryName, etc.
Brand: BrandID, BrandName, etc.
Review: ReviewID, ProductID, CustomerID, Rating, Comment, ReviewDate, etc.
