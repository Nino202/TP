
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment form</title>
    <link rel="stylesheet" href="stylepay.css">
</head>
<body>
    <div class="container">
    <form action="" >
        <h1 class="main_heading">Payment Form</h1>
        <p> Required Fields are followed by *</p>
        <h2>Contact Information</h2>
        <p>Name: *<input type="text" name="Name" placeholder="Niranjan Pawar" required></p>
        
        <fieldset>
            <legend>Gender * </legend>
            <p>
            Male <input type="radio" name="gender" id="gender" required>
            FeMale <input type="radio" name="gender" id="gender" required>
            Other <input type="radio" name="gender" id="gender" required>
            </p>
        </fieldset>
        <p>Address: <textarea name="address" id="address" cols="100" rows="8"></textarea></p>
        <p> Email: *<input type="email" name="email" id="email" required></p>
        <p>Pincode: *<input type="number" name="pincode" id="pincode" required></p>
        <h2>Payment Information</h2>
        <p>Card Type: *
            <select name="card_type" id="card_type" required>
                <option value="">--Select a card type--</option>
                <option value="VISA">visa</option>
                <option value="RUPAY">rupay</option>
                <option value="MASTERCARD">mastercard</option>
             </select>
        </p>
        <p>
            Card Number *<input type="number" name="card_number" required> 
        </p>
        <p>
            Expiration Date: *<input type="date" name="exp_date" id="exp_date" required>
        </p>
        <p>CVV  *<input type="password" name="cvv" id="cvv" required></p>
        <input type="submit" value="Pay Now">
      
    </form>
</div>
</body>
</html>
