/* General Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
    margin: 0;
    padding: 20px;
}

header {
    text-align: center;
    margin-bottom: 30px;
}

h1 {
    color: #d35400;
    font-size: 2.5em;
}

h2 {
    color: #e67e22;
    font-size: 2em;
    margin-bottom: 15px;
}

p {
    font-size: 1.1em;
    line-height: 1.6;
}

/* Table Styling */
table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 30px;
    background-color: #fff;
    border: 2px solid #e67e22;
}

th, td {
    padding: 12px;
    text-align: left;
    border-bottom: 1px solid #ddd;
}

th {
    background-color: #e67e22;
    color: white;
}

tr:hover {
    background-color: #f5f5f5;
}

/* Link Styling */
a {
    color: #d35400;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunrise Café</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Sunrise Café</h1>
        <p>Welcome to Sunrise Café, located in the heart of downtown. We offer a cozy ambiance, fresh ingredients, and a menu crafted with love. Established in 2010, we pride ourselves on serving the best breakfast, lunch, and drinks in town!</p>
    </header>

    <!-- Menu Section -->
    <section>
        <h2>Our Menu</h2>
        <table>
            <thead>
                <tr>
                    <th>Category</th>
                    <th>Item</th>
                    <th>Price</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Breakfast</td>
                    <td>Pancakes</td>
                    <td>$5.99</td>
                </tr>
                <tr>
                    <td>Lunch</td>
                    <td>Grilled Chicken</td>
                    <td>$8.99</td>
                </tr>
                <tr>
                    <td>Drinks</td>
                    <td>Fresh Lemonade</td>
                    <td>$2.99</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Contact Section -->
    <section>
        <h2>Contact Us</h2>
        <p>Address: 123 Main Street, Downtown, Cityville<br>
           Phone: (123) 456-7890<br>
           Email: info@sunrisecafe.com</p>
        <a href="https://www.google.com/maps" target="_blank">Find us on Google Maps</a>
    </section>
</body>
</html>
