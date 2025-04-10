<html>
<head>
    <title>Simple Multimedia Page</title>
    <style>
        body { font-family: Arial; max-width: 800px; margin: 0 auto; }
        section { margin: 20px 0; }
    </style>
</head>
<body>
    <h1>My Simple Page</h1>
<!-- Audio -->
    <section>
        <h2>Music Player</h2>
        <audio controls>
            <source src="music.mp3" type="audio/mpeg">
        </audio>
    </section>
<!-- Video -->
    <section>
        <h2>Video Player</h2>
        <video width="400" controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </section<!-- Simple Form -->
    <section>
        <h2>Sign Up</h2>
        <form>
            <label>Name: <input type="text" required></label><br>
            <label>Email: <input type="email" required></label><br>
            <label>Password: <input type="password" required minlength="6"></label><br>
            <button>Submit</button>
        </form>
    </section>
<!-- Image -->
    <section>
        <h2>Photo</h2>
        <img src="photo.jpg" alt="Beautiful landscape" width="300">
    </section>
<!-- Simple Table -->
    <section>
        <h2>Prices</h2>
        <table border="1">
            <tr>
                <th>Item</th>
                <th>Price</th>
            </tr>
            <tr>
                <td>Book</td>
                <td>R15</td>
            </tr>
            <tr>
                <td>Pen</td>
                <td>R5</td>
            </tr>
        </table>
    </section>
<!-- Lists -->
    <section>
        <h2>My Lists</h2>
        <h3>To Do:</h3>
        <ul>
            <li>Buy groceries</li>
            <li>Call mom</li>
        </ul>
        
        <h3>Steps:</h3>
        <ol>
            <li>Wake up</li>
            <li>Brush teeth</li>
        </ol>
    </section>
</body>
</html>
