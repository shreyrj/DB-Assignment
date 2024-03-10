1) Product Entity: Product entity represents individual products
   Product catogary Entity: This entity represents categories that products can belong to.
   In this relationship, many products can belong to a single category. This means that multiple rows in the "Product" table can have the same value in the column representing the category ID, linking them to the 
   same category in the "Product_Category" table. Each product belongs to one category, but each category can have multiple products associated with it. This is represented by a many-to-one relationship between the 
   "Product" and "Product_Category" entities.
2) To ensure that each product in the "Product" table has a valid category assigned to it, you can implement a foreign key constraint.
