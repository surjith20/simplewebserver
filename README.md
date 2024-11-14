# EX01 Developing a Simple Webserver
## Date: 25/9/2024

## AIM:
To develop a simple webserver to display the configuration details of my laptop.


## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Specification</title>
    <style>
        body{
            background-color: #ecffc4fe;
        }
        table {
            width: 30%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px;
            border: 1px solid #000;
            text-align: left;
        }
        td:first-child::after {
            content: ":";
            margin-left: 5px;
        }
        h2{
            text-align: center;
        }
    </style>
</head>
<body>
    <h2>Laptop Specifications</h2>
<table class="specifications-table">
    <tr>
        <th>Specification</th>
        <th>Details</th>
    </tr>
    <tr>
        <td>Brand</td>
        <td>HP</td>
    </tr>
    <tr>
        <td>Model</td>
        <td>HP Pavilion</td>
    </tr>
    <tr>
        <td>Processor</td>
        <td>Intel Core i5 11th Gen</td>
    </tr>
    <tr>
        <td>RAM</td>
        <td>8 GB</td>
    </tr>
    <tr>
        <td>Storage</td>
        <td>512 GB</td>
    </tr>

    
    <tr>
        <td>Graphics</td>
        <td>Integrated</td>
    </tr>
    <tr>
        <td>Display</td>
        <td>15.6 Inches</td>
    </tr>
    <tr>
        <td>Battery Life</td>
        <td>Up to 10 hours</td>
    </tr>
    <tr>
        <td>Operating System</td>
        <td>Windows 11</td>
    </tr>
    <tr>
        <td>Special Feature</td>
        <td>Anti Glare Screen</td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT:

![ex1](https://github.com/user-attachments/assets/dcc29c80-9b0c-48cc-979e-667219c07021)


## RESULT:
The program for implementing simple webserver is executed successfully.
