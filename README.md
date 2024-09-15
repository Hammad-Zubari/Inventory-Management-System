# Inventory-Management-System

Domain:
The inventory management system will cater to businesses across various domains such as retail, manufacturing, warehousing, and distribution. It will provide functionalities to track and manage inventory levels, streamline purchasing processes, optimize stock replenishment, and generate reports for informed decision-making.

Granularity:
The system will offer granular control over inventory items, allowing users to manage individual products, batches, or serialized items. It will facilitate tracking at the SKU level, enabling users to monitor stock movement accurately and efficiently.
The "category" table serves as a classification system for products, grouping them based on common characteristics or types. Each "product" belongs to a specific category and is uniquely identified by a product ID. "Customers" interact with the system by placing "orders," which are recorded in the respective table. Each order may contain multiple "order details," specifying the quantity and specific products ordered. The "order detail" table acts as a bridge between the "order" and "product" tables, linking each order to the products it contains.

