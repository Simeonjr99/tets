<?php
session_start();

// Database connection configuration
$servername = "localhost";
$username = "your_username";
$password = "your_password";
$dbname = "bnantubox";

// Create connection
$conn = new mysqli($servername, $username, $password, $dbname);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

$error = '';

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $username = $_POST['username'];
    $password = md5($_POST['password']); // Hashing the password

    $query = "SELECT * FROM users WHERE username='$username' AND password='$password'";
    $result = mysqli_query($conn, $query);

    if ($result && mysqli_num_rows($result) == 1) {
        $_SESSION['login_user'] = $username;
        header("location: dashboard.php"); // Redirect to user dashboard
    } else {
        $error = "Your Login Name or Password is invalid";
    }
}
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BnantuBox</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }

        header {
            background-color: #000;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #ff6600;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #000;
            padding: 10px 0;
            text-align: center;
        }

        button {
            background-color: #ff6600;
            border: none;
            color: #fff;
            padding: 10px 20px;
            cursor: pointer;
        }

        button:hover {
            background-color: #e65c00;
        }

        form {
            margin: 20px auto;
            padding: 20px;
            background-color: #222;
            border-radius: 5px;
            width: 300px;
        }

        form label, form input {
            display: block;
            margin: 10px 0;
        }

        form input {
            width: calc(100% - 22px);
            padding: 10px;
            border: 1px solid #444;
            border-radius: 3px;
            background-color: #333;
            color: #fff;
        }

        .logo {
            margin-bottom: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
        }

        @media (max-width: 480px) {
            main {
                padding: 10px;
            }

            form {
                width: 100%;
                padding: 10px;
            }
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            console.log("BnantuBox script loaded.");
        });
    </script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Series</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="logo">
            <img src="logo.jpg" alt="BnantuBox Logo" width="200"> <!-- Replace with your logo -->
        </div>
        <h1>Welcome to BnantuBox</h1>
        <p>Your favorite streaming platform!</p>

        <form method="POST" action="">
            <label>Username:</label>
            <input type="text" name="username" required>
            <label>Password:</label>
            <input type="password" name="password" required>
            <button type="submit">Login</button>
        </form>
        
        <?php
        if (!empty($error)) {
            echo '<p style="color: red;">' . $error . '</p>';
        }
        ?>
    </main>
    <footer>
        <p>&copy; 2024 BnantuBox. All rights reserved.</p>
    </footer>
</body>
</html>
