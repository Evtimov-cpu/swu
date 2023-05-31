<!DOCTYPE html>
<html>
<head>
    <title>Github Side Menu</title>
    <style>
        /* Define the styles for the side menu */
        .sidebar {
            position: fixed;
            left: 0;
            top: 0;
            height: 100%;
            width: 200px;
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        /* Style the menu items */
        .sidebar a {
            display: block;
            margin-bottom: 10px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        /* Add a hover effect */
        .sidebar a:hover {
            background-color: #555;
        }

        /* Style the active menu item */
        .sidebar a.active {
            background-color: #555;
        }

        /* Add some space for the content */
        .content {
            margin-left: 200px;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>

    <!-- Add your main content here -->
    <div class="content">
        <h1>Welcome to My GitHub Repository</h1>
        <p>This is the main content of your repository.</p>
    </div>
</body>
</html>

