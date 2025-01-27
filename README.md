<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Clothing Store</title>
</head>
<body>
    <h1>Online Clothing Store</h1>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password"><br><br>

        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone"><br><br>

        <label>Size:</label>
        <input type="checkbox" id="small" name="size" value="Small">
        <label for="small">Small</label>
        <input type="checkbox" id="medium" name="size" value="Medium">
        <label for="medium">Medium</label>
        <input type="checkbox" id="large" name="size" value="Large">
        <label for="large">Large</label><br><br>

        <label for="color">Favorite Color:</label>
        <input type="color" id="color" name="color"><br><br>

        <label for="quantity">Quantity:</label>
        <input type="number" id="quantity" name="quantity" min="1"><br><br>

        <label for="delivery">Delivery Date:</label>
        <input type="date" id="delivery" name="delivery"><br><br>

        <label for="design">Upload Design:</label>
        <input type="file" id="design" name="design"><br><br>

        <label for="comments">Comments:</label><br>
        <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br><br>

        <button type="reset">Reset</button>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
