# ict-pa3
pizzazaza
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>cool web form</title>
</head>
<body style="background-color:#191818"> 
    <!-- HERO SECTION -->
    <div class="hero-image">
        <img src="C:\Users\Isobel\Downloads\img_banner.png" alt="stupid banner">
            <div class="hero-text">
                <h1 style="color: #b25453">pizza-on-demand!</h1>
            </div>  
    </div>
        <p style="color:#b25453">our 12" wood-fired pizzas are available for delivery! build your own special, customized pizza!</p>
    <!-- FORM SECTION -->
    <form> 
        <fieldset>
            <legend style="color: #b25453">your info!</legend>
                <!-- NAME -->
                <label for="full-name" style="color:#b25453">name:</label>
                <input type="text"name="full-name" placeholder="enter your full name">
                <br>
                <br>
            <!-- ADDRESS -->
                <label for="address" style="color:#b25453">address:</label>
                <input type="text"name="address" placeholder="enter your address">
                <br>
                <br>
            <!-- CONTACT -->
                <label for="contact" style="color:#b25453">contact no.:</label>
                <input type="text"name="contact" placeholder="enter your phone number/contact">
                <br>
                <br>
            <!-- EMAIL -->
                <label for="email" style="color:#b25453">email:</label>
                <input type="text"name="email" placeholder="enter your email">
                <br>
                <br>
            <!-- MESSAGE -->
             <label style="color:#b25453">delivery requests</label>
             <br>
             <textarea placeholder="add delivery instructions"></textarea>

        </fieldset>
    </form>
    <form>
            <h3 style="color:#b25453">pizza specifications</h3>

        <fieldset>
            <legend style="color:#b25453">Pizza Specs</legend>
            <fieldset>
                <legend style="color:#b25453">crust <em>(choose one)</em></legend>
                <input type="radio"name="crust">
                <label style="color:#b25453">classic white</label>
                <br>
                <input type="radio"name="crust">
                <label style="color:#b25453">multigrain</label>
                <br>
                <input type="radio"name="crust">
                <label style="color:#b25453">stuffed cheese</label>
                <br>
                <input type="radio"name="crust">
                <label style="color:#b25453">gluten-free</label>
                <br>
            </fieldset>
                <br>
            <fieldset>
                <legend style="color:#b25453">topping <em>(choose as many as you want)</em></legend>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">red sauce</label>
                <br>
                 <input type="checkbox"name="topping">
                <label style="color:#b25453">white sauce</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">mozzarella cheese</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">parmesan cheese</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">pepperoni</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">ground beef</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">mushrooms</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">olives</label>
                <br>
                <input type="checkbox"name="topping">
                <label style="color:#b25453">pineapple</label>
                <br>
            </fieldset>
                <br>
            <fieldset>
                <legend style="color:#b25453">how many pizzas? <em>(please pay for all of them)</em></legend>
                <select>
                    <option value="1">1</option>
                    <option value="2">2</option>
                    <option value="3">3</option>
                    <option value="4">4</option>
                    <option value="5">5</option>
                    <option value="182">182</option>
                    <option value="21">21</option>
                    <option value="10">10</option>
                    <option value="27">27</option>
                </select>
            </fieldset>
                <br>
            <fieldset>
            <p style="color: #b25453">" sleepin' on your folks' porch again, dreamin! " 🎸</p>
            </fieldset>
        </fieldset>
        <br>
        <input type="submit" value="bring me my pizza peasant">
        <input type="reset"  value="start over again peasant">
    </form>
</body>
</html>
