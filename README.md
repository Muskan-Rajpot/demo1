<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nature & Responses</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#wildlife">Wildlife</a></li>
                <li><a href="#forests">Forests</a></li>
                <li><a href="#oceans">Oceans</a></li>
                <li><a href="#responses">User Responses</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h1>Welcome to the Nature & Responses Website</h1>
        <p>Explore the wonders of nature, and share your thoughts and experiences!</p>
        <div class="nature-images">
            <img src="picture/nature123.avif" alt="Nature Image 1">
            <img src="picture/nature2.avif" alt="Nature Image 2">
        </div>
    </section>

    <section id="responses">
        <h2>Share Your Nature Experience</h2>
        <form action="submit_response.php" method="post">
            <textarea name="response" placeholder="What is your favorite nature memory?" required></textarea>
            <button type="submit">Submit Response</button>
        </form>
    </section>

    <footer>
        <p>© 2026 Nature & Responses | Connect with us on social media!</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    padding: 20px;
}

header nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 20px;
    margin: 20px;
}

h1, h2 {
    color: #2E8B57;
}

.nature-images img {
    width: 48%;
    margin: 1%;
    border-radius: 10px;
}

textarea {
    width: 100%;
    height: 100px;
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

# demo1
