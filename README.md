[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LXHgsJqg)
# INST377-Lab 3

# Name (Please Input your name): Mushfiq Rafee

# Comments: 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Rock-Paper-Scissors Page</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif; /* custom font-family */
            margin: 0;
            padding: 0;
        }

        /* Header & Footer */
        .header-footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin: 10px;
        }

        /* Navigation */
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: red;
        }

        /* Content Layout */
        .content {
            display: flex; /* makes sidebar + main in one line */
            margin: 20px;
        }

        /* Main Content */
        .main {
            width: 70%;
            padding: 20px;
            margin: 10px;
            background-color: #f0f0f0;
        }

        /* Sidebar */
        .sidebar {
            width: 30%;
            padding: 20px;
            margin: 10px;
            background-color: #ddd;
            transition: background-color 0.3s;
        }

        .sidebar:hover {
            background-color: #bbb; /* changes color on hover */
        }

        /* Form Styling */
        #name {
            width: 200px;
            transition: width 0.3s;
        }

        #name:focus {
            width: 300px;
        }

        input[type="submit"] {
            padding: 8px 15px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header-footer">
        <h1>Welcome to Rock-Paper-Scissors!</h1>
    </div>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="https://www.google.com" target="_blank">Google</a></li>
            <li><a href="https://www.wikipedia.org" target="_blank">Wikipedia</a></li>
            <li><a href="https://www.youtube.com" target="_blank">YouTube</a></li>
        </ul>
    </nav>

    <!-- Content -->
    <div class="content">
        <!-- Main Content -->
        <div class="main">
            <h2>Play the Game</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>

                <label for="choice">Choose:</label>
                <select id="choice" name="choice">
                    <option value="rock">Rock</option>
                    <option value="paper">Paper</option>
                    <option value="scissors">Scissors</option>
                </select><br><br>

                <input type="submit" value="Play">
            </form>
        </div>

        <!-- Sidebar -->
        <div class="sidebar">
            <h2>Rules</h2>
            <p>Rock beats Scissors</p>
            <p>Scissors beats Paper</p>
            <p>Paper beats Rock</p>
        </div>
    </div>

    <!-- Footer -->
    <div class="header-footer">
        <p>DJ is the UFC GOAT</p>
    </div>
</body>
</html>
