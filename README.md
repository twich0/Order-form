<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Order Form</title>
</head>

<body>

<header>
<h1>Order Form</h1>
<p>Kindly proceed with order registration by filling the details.</p>
</header>

<main>

<form method="POST" action="https://formspree.io/f/xpqyzodz">

<fieldset>
<legend>Personal info</legend>

<label for="full-name">Name (required):</label>
<input type="text" id="full-name" name="name" placeholder="e.g., Twich Zema" required size="30">
<br><br>

<label for="phone">Phone number (required):</label>
<input type="tel" id="phone" name="phone" placeholder="+1-555-777-9999" required size="20">
<br><br>

<label for="address">Delivery address (required):</label>
<input type="text" id="address" name="address" placeholder="Franklin Park NY 08823" required>
<br><br>

<label for="items">Item ordered:</label>
<input type="text" id="items" name="brand" size="25">
<br><br>

<label for="size">Size (required):</label>
<input type="text" id="size" name="size" placeholder="Large" required size="7">

</fieldset>

<br>

<fieldset>
<legend>Shipping and Tracking info</legend>

<p>Please select how you will like to ship</p>

<input type="checkbox" name="shipping" value="standard"> Standard shipping<br>
<input type="checkbox" name="shipping" value="expedited"> Expedited shipping<br>
<input type="checkbox" name="shipping" value="overnight"> Overnight shipping<br>

</fieldset>

<br>

<fieldset>
<legend>Payment Method</legend>

<label for="payment">How will you proceed with payment?</label>

<select name="payment" id="payment">
<option value="zelle">Zelle</option>
<option value="paypal">Paypal</option>
<option value="crypto">Crypto</option>
<option value="etransfer">E-transfer</option>
<option value="bank" selected>Bank payment</option>
</select>

</fieldset>

<br>

<label for="comments">Additional Comments:</label><br>

<textarea id="comments" name="comments" rows="5" cols="30"></textarea>

<br><br>

<button id="submit" type="submit">Submit</button>

</form>

</main>

</body>
</html>
