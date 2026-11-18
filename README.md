# Author: Nhlanhla Radebe

1. ER Components
Entity
An entity is a real-world object that we want to store information about in a database. In an online bookstore, a Book can be considered an entity because the store needs to keep information about every book itsells.

Relationship
A relationship shows how two entities are connected. In an online bookstore, a Customer places an Order. The action of placing an order is the relationship between the Customer and Order entities.

Attribute
An attribute describes a characteristic of an entity. For example, a Book entity may have attributes such as Book_ID, Title, Price and Author. These attributes provide details about the book.

2. Data Model Levels
Conceptual Data Model
The conceptual data model focuses on what information the system needs to store. It is usually created by business stakeholders and data architects to identify the main business objects and relationships without worrying about technical details.

Physical Data Model
The physical data model focuses on how the database will actually be built inside a specific database system such as PostgreSQL. It is normally created by database administrators and developers. It includes tables, data types, primary keys and foreign keys.

Difference
The conceptual model is concerned with the overall business view of the data, while the physical model focuses on the actual implementation of the database.

3. ER Mapping
Customer Entity
Attributes:

customer_id
first_name
last_name
email
Order Entity
Attributes:

order_id
order_date
total_amount
customer_id
Relationship
One customer can place many orders, but each order belongs to only one customer.

