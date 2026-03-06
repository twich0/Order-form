<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Order Form</title>
  </head>
  <body>
    <header>
      <h1>Order Form</h1>
      <p>
        Kindly proceed with order registration by filling the details.
      </p>
    </header>
    <main>
      <form method="POST" action="https://formspree.io/f/xpqyzodz">
        <fieldset>
          <legend>Personal info</legend>
          <label for="full-name">Name (required):</label>
          <input type="text" id="full-name" name="name" placeholder="e.g., Twich Zema" required size="30">

          <label for="phone number">Phone number (required):</label>
          <input
            placeholder="+1-555-777-9999"
            required
            id="phone number"
            type="phone number"
            name="phone number"
            size="20"
          />
          <label for="delivery address">Delivery address (required):</label>
          <input type="text" id="address" name="address" placeholder="Franklin Park NY 08823"/>
          
          <label for="item ordered">Item ordered (name):</label>
          <input type="text" id="items" name="brand" size="25"/>

          <label for="size">Size (required):</label>
          <input type="numbers" placeholder="Large" size="7">
        
   
        </fieldset>

        <fieldset>
          <legend>
            Shipping and Tracking info
          </legend> 
            <!-- Checkboxes -->
  <p>Please select how you will like to ship</p>

  <input type="checkbox" name="topic" value="html"> Standard shipping<br>
  <input type="checkbox" name="topic" value="css"> Expeditory shipping<br>
  <input type="checkbox" name="topic" value="javascript"> Overnight shipping<br><br>
           
          
   
          
        </fieldset>

        <fieldset>
          <legend>



          <label for="Payments">How will you proceed with payment?</label>

          <select name="food" id="food">
            <option value="Zelle">Zelle</option>
            <option value="Cashapp">Paypal</option>
            <option value="Crypto">Crypto</option>
            <option value="E-transfer">E-transfer</option>
            <option selected value="Bank payment">Bank payment</option>
          </select>
        </fieldset>
                  <!-- Textarea -->
  <label for="comments">Additional Comments:</label><br>
  <textarea id="comments" name="comments" rows="5" cols="30"></textarea>
  <br><br>

  <!-- Submit button -->
  <button id="submit" type="submit">Submit</button>
      </form>
    </main>
  </body>
</html>
