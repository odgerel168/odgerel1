<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Old Facebook Layout - 2004</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        td {
            background-color: #f2f2f2;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e9f5f4;
        }
        header {
            background-color: #3b5998;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer {
            background-color: #3b5998;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .main-content {
            padding: 20px;
        }
        .profile-picture img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }
    </style>
</head>
<body>

<!-- Header Section (Тамга хэсэг) -->
<header>
    <h1>Welcome to Facebook 2004</h1>
</header>

<!-- Main Content Section -->
<table>
    <tr>
        <!-- Left Column: Profile Section -->
        <td width="25%" class="profile-section">
            <h2>Profile</h2>
            <div class="profile-picture">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Facebook_Logo_2023.png/1200px-Facebook_Logo_2023.png" alt="Profile Picture">
            </div>
            <p><strong>Name:</strong> John Doe</p>
            <p><strong>Location:</strong> Boston, MA</p>
        </td>

        <!-- Center Column: News Feed Section -->
        <td width="50%" class="news-feed">
            <h2>News Feed</h2>
            <table border="1">
                <tr>
                    <td><strong>Friend 1</strong></td>
                    <td>Just updated their status: "Having a great time in the park!"</td>
                </tr>
                <tr>
                    <td><strong>Friend 2</strong></td>
                    <td>Shared a photo: "Look at my new car!"</td>
                </tr>
                <tr>
                    <td><strong>Friend 3</strong></td>
                    <td>Commented on a post: "I totally agree with you!"</td>
                </tr>
            </table>
        </td>

        <!-- Right Column: Friend Suggestions Section -->
        <td width="25%" class="friend-suggestions">
            <h2>Friend Suggestions</h2>
            <ul>
                <li><a href="#">Friend 4</a></li>
                <li><a href="#">Friend 5</a></li>
                <li><a href="#">Friend 6</a></li>
            </ul>
        </td>
    </tr>
</table>

<!-- Footer Section (Доод хэсэг) -->
<footer>
    <p>&copy; 2004 Facebook. All rights reserved.</p>
</footer>

</body>
</html>
