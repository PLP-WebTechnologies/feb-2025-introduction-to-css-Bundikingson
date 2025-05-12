<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Introduction</title>
    <!-- Linking external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>
    
    <nav class="navigation">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section class="content-section">
            <h2>About This Project</h2>
            <p>This project demonstrates basic CSS styling techniques including selectors, colors, typography, and spacing.</p>
            
            <div class="image-container">
                <img src="https://via.placeholder.com/400x300" alt="Sample image">
                <p class="image-caption">A sample placeholder image with styling</p>
            </div>
        </section>
        
        <section class="content-section">
            <h2>CSS Features Used</h2>
            <ul>
                <li>External CSS linking</li>
                <li>Multiple selector types</li>
                <li>Color and typography</li>
                <li>Spacing with margins and padding</li>
                <li>Border styling</li>
            </ul>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 CSS Introduction Project</p>
    </footer>
</body>
</html>

/* Element Selector */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* ID Selector */
#main-header {
    background-color: #2c3e50;
    color: #ecf0f1;
    text-align: center;
    padding: 1.5rem;
    margin-bottom: 2rem;
}

/* Class Selector */
.navigation {
    background-color: #34495e;
    padding: 1rem 0;
}

.navigation ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 0;
}

.navigation li {
    margin: 0 1rem;
}

.navigation a {
    color: #ecf0f1;
    text-decoration: none;
    font-weight: bold;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    transition: background-color 0.3s ease;
}

.navigation a:hover {
    background-color: #2c3e50;
}

.content-section {
    background-color: white;
    margin: 1rem auto;
    padding: 2rem;
    width: 80%;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Image Styling */
.image-container {
    text-align: center;
    margin: 2rem 0;
}

.image-container img {
    border: 3px solid #3498db;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    max-width: 100%;
    height: auto;
}

.image-caption {
    font-style: italic;
    color: #7f8c8d;
    margin-top: 0.5rem;
}

/* Typography */
h1 {
    font-family: 'Georgia', serif;
    font-size: 2.5rem;
}

h2 {
    font-family: 'Georgia', serif;
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 0.5rem;
}

/* Footer Styling */
footer {
    background-color: #2c3e50;
    color: #ecf0f1;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
