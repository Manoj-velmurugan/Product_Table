# Product Table
## Date: 07/07/2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Table</title>
  </head>
  <body>
    <table border="1" cell>
      <h1>Product Listed</h1>
      <thead>
        <tr>
          <th>Product Name</th>
          <th>Product Price</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Laptop</td>
          <td>₹45,000</td>
          <td>High-speed performance</td>
        </tr>
        <tr>
          <td>Phone</td>
          <td>₹35000</td>
          <td>Gaming segment</td>
        </tr>
        <tr>
          <td>Earbuds</td>
          <td>₹5000</td>
          <td>Dolby Atmos</td>
        </tr>
        <tr>
          <td>Smartwatch</td>
          <td>₹7000</td>
          <td>AI Enabled smartwatch</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

## Output:
![image](https://github.com/user-attachments/assets/455337cd-b2f8-46dd-ae59-fc60f2c66521)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
