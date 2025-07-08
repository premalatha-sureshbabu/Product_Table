# Product Table
## Date:
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
    <table cellspacing="5" cellpadding="5" border="3" bgcolor="lightpink">
        <caption>Product Details</caption>
        <thead bgcolor="Grey">
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Moisturizer</td>
                <td>800</td>
                <td>Hydrates and softens skin</td>
            </tr>
            <tr>
                <td>Sunscreen</td>
                <td>600</td>
                <td>Protects from UV rays</td>
            </tr>
            <tr>
                <td>Face Serum</td>
                <td>1200</td>
                <td>Brightens and nourishes skin</td>
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
    font-weight: bold;
}

thead {
    background-color: grey;
    color: white;
}

th, td {
    border: 2px solid #ddd;
    padding: 10px;
    text-align: center;
}

tr:nth-child(even) {
    background-color: #f9c2d1; 
}

tr:hover {
    background-color: #f1f1f1; 
}
```
## Output:
![Screenshot (62)](https://github.com/user-attachments/assets/d656a10e-888b-4e7a-bd8f-b94c05210049)

![Screenshot (64)](https://github.com/user-attachments/assets/fe8698c2-679a-4352-aa7c-73e167ddfa06)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
