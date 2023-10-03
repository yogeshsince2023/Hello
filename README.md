# Hello
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms - Lets learn it</title>
</head>

<body>
    <h1>Form to apply for Sigma Web Development course - TA </h1>
    <form action="post">
        <div>
            <label for="username">Enter your Username</label>
            <input type="text" id="username" name="username" placeholder="Enter your username" autofocus>
        </div>
        <div>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
        </div>

        <div>
            <input type="checkbox" id="subscribe" name="subscribe" value="yes">
            <label for="subscribe">Subscribe to newsletter</label>
        </div>
        <div>
            <label for="comment">Enter your comment</label>
            <br>
            <textarea id="comment" name="comment" rows="4" cols="50"></textarea>
        </div>

        <div>
            <select name="fruits">
                <option value="apple">Apple</option>
                <option value="banana">Banana</option>
                <option value="cherry">Cherry</option>
          </select>
        </div>
    </form>
</body>

</html>
