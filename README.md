# Product Table
## Date:07.07.2025
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
</head>
<body>
    <table cellspacing="5" cellpadding="5" border="3" bgcolor="red">
        <caption>Product Details</caption>
        <thead bgcolor="grey">
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>450000</td>
                <td>High-speed performance</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>499</td>
                <td>Budget friendly with great features</td>
            </tr>
            <tr>
                <td>Headphones</td>
                <td>1500</td>
                <td>Noise cancellation and clear sound</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## Style code:
```
table {
    width: 70%;
    margin: 20px auto; 
}
caption {
    font-size: 1.5em;
    margin-bottom: 10px;
}
thead {
    background-color: cyan;
    color: pink;
}

th, td {
    border: 2px solid white;
    padding: 10px;
    text-align: center;
}

tr:nth-child(even) {
    background-color: orange; 
}

tr:hover {
    background-color: white; 
}
```
## Output:
![image](https://github.com/user-attachments/assets/7ae5dc0c-cdca-431c-911e-c1ece987478a)
![image](https://github.com/user-attachments/assets/afb78923-9ba3-4ab0-a9fb-0bacc226d4c5)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
