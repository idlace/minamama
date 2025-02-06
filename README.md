<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Basic Website</title>
    <link rel="stylesheet" href="style.css">  </head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>This is a paragraph about me.  You can write whatever you want here.</p>
        </section>

        <section>
            <h2>My Projects</h2>
            <ul>
                <li>Project 1</li>
                <li>Project 2</li>
            </ul>
        </section>

         <section>
            <h2>Contact</h2>
            <form>
              <label for="name">Name:</label><br>
              <input type="text" id="name" name="name"><br>
              <label for="email">Email:</label><br>
              <input type="email" id="email" name="email"><br><br>
              <input type="submit" value="Submit">
            </form>
        </section>

    </main>

    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>

    <script src="script.js"></script> </body>
</html>
/* Basic Styling */
body {
    font-family: sans-serif;
    margin: 0; /* Remove default margins */
    padding: 0;
}

header {
    background-color: #f0f0f0; /* Light gray background */
    padding: 20px;
    text-align: center; /* Center the header text */
}

nav ul {
    list-style: none; /* Remove bullet points */
    padding: 0;
    margin: 0;
}

nav li {
    display: inline; /* Make list items horizontal */
    margin: 0 10px; /* Add some space between items */
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px; /* Add space between sections */
}

footer {
    background-color: #333; /* Darker background for footer */
    color: white;
    padding: 10px;
    text-align: center;
}

/* Style the form */
form {
  width: 300px;
  margin: 0 auto;
}

label, input[type="text"], input[type="email"] {
  display: block; /* Make labels and inputs stack */
  width: 100%;
  margin-bottom: 10px;
  box-sizing: border-box; /* Include padding and border in element's total width and height */
}// You can add JavaScript code here later.  For now, it's empty.
console.log("Hello from JavaScript!"); //This will log to the browser console.
