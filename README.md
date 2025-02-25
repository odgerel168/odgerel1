<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook - 2004 Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e9f5f4;
            margin: 0;
            padding: 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #4c69b6;
            color: white;
            font-weight: bold;
        }
        td {
            background-color: #f0f0f0;
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
        .profile-picture img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }
        .news-feed {
            background-color: #ffffff;
            padding: 15px;
            margin-top: 20px;
        }
        .news-feed h2 {
            color: #3b5998;
        }
        .friend-suggestions {
            background-color: #ffffff;
            padding: 15px;
            margin-top: 20px;
        }
        .friend-suggestions ul {
            list-style-type: none;
            padding-left: 0;
        }
        .friend-suggestions ul li {
            padding: 10px 0;
        }
        .friend-suggestions ul li a {
            color: #3b5998;
            text-decoration: none;
        }
        .friend-suggestions ul li a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<!-- Header Section (Тамга хэсэг) -->
<header>
    <h1>Facebook</h1>
    <p>Welcome to Facebook - 2004</p>
</header>

<!-- Main Content Section -->
<table>
    <tr>
        <!-- Left Column: Profile Section -->
        <td width="20%" valign="top" class="profile-section">
            <h2>Profile</h2>
            <div class="profile-picture">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Facebook_Logo_2023.png/1200px-Facebook_Logo_2023.png" alt="Profile Picture">
            </div>
            <p><strong>Name:</strong> John Doe</p>
            <p><strong>Location:</strong> Boston, MA</p>
            <p><a href="#">Edit Profile</a></p>
        </td>

        <!-- Center Column: News Feed Section -->
        <td width="60%" valign="top" class="news-feed">
            <h2>News Feed</h2>
            <table border="1" width="100%" cellspacing="0">
                <tr>
                    <td><strong>Friend 1</strong></td>
                    <td>Just updated their status: "Having a great time at the beach!"</td>
                </tr>
                <tr>
                    <td><strong>Friend 2</strong></td>
                    <td>Shared a photo: "Look at my new car!"</td>
                </tr>
                <tr>
                    <td><strong>Friend 3</strong></td>
                    <td>Commented on a post: "I totally agree with you!"</td>
                </tr>
                <tr>
                    <td><strong>Friend 4</strong></td>
                    <td>Joined a new group: "Music Lovers"</td>
                </tr>
            </table>
        </td>

        <!-- Right Column: Friend Suggestions Section -->
        <td width="20%" valign="top" class="friend-suggestions">
            <h2>Friend Suggestions</h2>
            <ul>
                <li><a href="#">Friend 5</a></li>
                <li><a href="#">Friend 6</a></li>
                <li><a href="#">Friend 7</a></li>
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
