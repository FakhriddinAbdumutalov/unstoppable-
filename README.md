<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fisrt real work</title>
   <link rel="stylesheet" href="style/style.css">
</head>
<body>
    <h1 class="title">HELLO WORLD</h1>
    <h2 class="subtitle" align="center">Good Evening</h2>
    <p id="paragraph" align="center">How are you dude</p>
    <p align="center">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.</p>
    <a href="https://google.com" id="google-link">google</a>
    <p>Grocery List</p>
    <img src="photos/newyorkimage.jpg" style="border: 10px solid black;">
    <ul>
        <li>Meat</li>
        <li>Eggs</li>
        <li>Milk</li>
        <li>Bread</li>
    </ul>
    <p>Grocery List Order</p>
    <ol>
        <li>Meat</li>
        <li>Eggs</li>
        <li>Milk</li>
        <li>Bread</li>
    </ol>
    <table>
        <thead>
            <tr>
                <td>Name</td>
                <td>Email</td>
                <td>Phone Number</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Jane Smith</td>
                <td>jane@gmail.com</td>
                <td>99890 332 09 94</td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <td>Jane Smith</td>
                <td>jane@gmail.com</td>
                <td>99897 727 81 78</td>
            </tr>
        </tbody>
    </table>
    <br>
    <hr>
    <!--  break  -->
    <img src="photo/style.JPG" width="200" alt="">
    <form action="">
        <label for="fname">
            First Name:
           <input type="text" name="fname" placeholder="First Name" id="fname">
        </label>
        <label for="age">
            Age:
           <input type="number" name="age" placeholder="Your Age" id="age" max="20" min="1">
        </label>
        <label for="password">
            First Name:
           <input type="password" name="password" placeholder="Your Password" id="password">
        </label>
        <br>
        <label for="gender">
            Is Married: <br>
           Yes<input type="radio" name="isMarried" id="isMarried">
           No<input type="radio" id="isMarried" name="isMarried">
        </label>
        <br>
        <label for="country">
            <select name="country" id="country">
                <option value="us">USA</option>
                <option value="uk">UK</option>
                <option value="uz">Uzbekistan</option>

            </select>
        </label>
        <textarea name="Description" id="description" cols="30" rows="10" maxlength="100"></textarea><button>Submit</button>
    </form>
    <p style="text-align: center; background-color: black; color: white; padding: 20px" >Copyright CityTech Tashkent</p>
    <footer></footer>
    <div class="container"></div>
    <div class="loader"><span></span></div>
</body>
</html>
