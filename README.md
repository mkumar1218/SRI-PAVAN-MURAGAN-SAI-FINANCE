<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bike Showroom</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background: #333;
            padding: 15px;
            color: white;
        }
        .header img {
            width: 50px;
            height: auto;
        }
        .menu {
            display: flex;
        }
        .menu a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .menu a:hover {
            background: #555;
        }
        .container {
            padding: 20px;
        }
        .search-bar {
            margin-bottom: 20px;
        }
        input {
            padding: 10px;
            width: 300px;
            margin-right: 10px;
        }
        .bike-list {
            display: flex;
            flex-wrap: wrap;
        }
        .bike {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 5px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
            width: 250px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="bike-logo.png" alt="Bike Logo">
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">Bikes</a>
            <a href="#">EMI Plans</a>
            <a href="#">Contact</a>
        </div>
    </div>

    <div class="container">
        <div class="search-bar">
            <input type="text" placeholder="Search by number or bike number">
            <button>Search</button>
        </div>

        <div class="bike-list">
            <div class="bike">
                <h3>Bike Model 1</h3>
                <p>Price: ₹1,00,000</p>
                <p>EMI: ₹5,000/month</p>
            </div>
            <div class="bike">
                <h3>Bike Model 2</h3>
                <p>Price: ₹1,50,000</p>
                <p>EMI: ₹7,500/month</p>
            </div>
        </div>
    </div>
</body>
</html>
