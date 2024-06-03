# summer-Internship
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.top-bar {
    background-color: #f8f8f8;
    text-align: left;
    padding: 10px 20px;
}

.top-bar a {
    margin-left: 10px;
    text-decoration: none;
    color: #333;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 20px;
    color: black;
}

.header h1 {
    margin: 0;
}

.header nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
}

.header nav ul li {
    margin-left: 20px;
}

.header nav ul li a {
    color: black;
    text-decoration: none;
   
}

.search-bar input {
    padding: 5px;
}

main {
    padding: 20px;
}

.portfolio {
    text-align: center;
}

.portfolio h2 {
    margin-top: 0;
    margin-right:1300px;
}

.filters button {
    margin: 5px;
    padding: 10px 20px;
    background-color: #eee;
    border: none;
    cursor: pointer;
}

.portfolio-grid {
    display: block;
    gap: 20px;
}



footer {
    background-color: #f8f8f8;
    padding: 20px;
    text-align: center;
}

.footer-content {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 20px;
}

.footer-column {
    flex: 1;
    min-width: 200px;
}

.recent-projects {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.recent-projects img {
    max-width: 48%;
    height: auto;
}
</style>
<body>
    <header>
    <div>
   <!-- <nav style="margin-right:1100px;margin-left: 10px;text-decoration: none;color: #333; background-color: #f8f8f8;text-align: right; padding: 10px 20px;">-->
       <div class="top-bar" style="margin-right:0px;background-color:#5D8AA8;">
            <a href="#">My Account</a>
            <a href="#">Buy Here</a>
            <a href="#">Your Cart: $0.00</a>
        </div>
        <div class="search-bar" style="margin-top:0px;margin-left:1300px;">
             <input type="text" placeholder="Search">
        </div>
        </div>
        <div class="header">
            <h1>Virtue</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section class="portfolio">
            <h2 margin-right:1000px>Portfolio</h2>
            <div class="filters" style="margin-left:600px;">
                <button>All</button>
                <button>Design</button>
                <button>Photography</button>
                <button>Video</button>
            </div>
            <div class="portfolio-grid" style="display:flex; margin-left:300px;">
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 1.png" width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 2.webp" width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 3.png"  width="300" height="300"></div>
            </div>
            <div class="portfolio-grid" style="display:flex; margin-left:300px;">
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 4.jpg"  width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 5.jpg"  width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 6.jpg"  width="300" height="300"></div>
            </div>
            <div class="portfolio-grid" style="display:flex; margin-left:300px;">
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 7.jpg" width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 8.jpg" width="300" height="300"></div>
                <div class="portfolio-item"><img src="C:\Users\merit\Downloads\im 9.jpg" width="300" height="300"></div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content" style="background-color:grey;">
            <div class="footer-column">
                <h3>Virtue Theme</h3>
                <p>Duis iaculis pretium fermentum. Duis at placerat lacus, non luctus dui. Nunc vel enim eu eros congue laoreet. Nunc mollis dui sed consequat cursus. Sed vel nulla mi.</p>
            </div>
            <div class="footer-column">
                <h3>Social</h3>
                <p>

                    <h3>Contact Us</h3>
                    <p>Phone: 444-555-9999</p>
                    <p>Email: info@kadencethemes.com</p>
                </p>
            </div>
       
            <div class="footer-column">
                <h3>Recent Projects</h3>
                <div class="recent-projects" style="display:flex;">
                    <img src="C:\Users\merit\Downloads\im 1.png" height="100" width="80">
                    <img src="C:\Users\merit\Downloads\im 2.webp" height="100" width="80">
                    <img src="C:\Users\merit\Downloads\im 3.png" height="100" width="80">
                </div>
                <div class="recent-projects" style="display:flex;">
                    <img src="C:\Users\merit\Downloads\im 4.jpg"height="100" width="80" >
                    <img src="C:\Users\merit\Downloads\im 5.jpg" height="100" width="80" >
                    <img src="C:\Users\merit\Downloads\im 6.jpg" height="100" width="80" >
                </div>
            </div>
            <div class="footer-column">
                <h3>Resources</h3>
                <p>
                    <p> Home </p>
                    <p> Cart </p>
                    <p> Contact Us </p>
                    <p>Staff</p>
                    <p> My Account </p>
                </p>
            </div>
        </div>
    </footer>
</body>
</html>
