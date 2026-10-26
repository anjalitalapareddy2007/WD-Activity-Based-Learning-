
<!DOCTYPE html>
<html>
<head>
    <title>Digital Library</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f2f5f9;
        }

        header {
            background-color: #203864;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #162747;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
        }

        section {
            padding: 20px;
        }

        input, select {
            padding: 10px;
            margin: 5px;
            border: 1px solid #aaa;
            border-radius: 5px;
        }

        /* Book cards using CSS Grid */
        .book-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
        }

        .book {
            background-color: white;
            padding: 15px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 2px 6px #ccc;
        }

        .book img {
            width: 120px;
            height: 160px;
            object-fit: cover;
        }

        .available {
            color: green;
            font-weight: bold;
        }

        .borrowed {
            color: red;
            font-weight: bold;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background-color: white;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: #203864;
            color: white;
        }

        footer {
            background-color: #203864;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 5px;
            }

            table {
                font-size: 12px;
            }

            th, td {
                padding: 6px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>📚 Digital Library</h1>
    <p>Discover, Read and Learn</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#books">Books</a>
    <a href="#catalog">Catalog</a>
    <a href="#rules">Library Rules</a>
</nav>

<section id="home">
    <h2>Welcome to Our Library</h2>
    <p>Explore books from different categories and find your
       favorite books easily.</p>
</section>

<section id="books">
    <h2>Search and Filter Books</h2>

    <input type="text" id="search"
           placeholder="Search book or author..."
           oninput="filterBooks()">

    <select id="category" onchange="filterBooks()">
        <option value="all">All Categories</option>
        <option value="Programming">Programming</option>
        <option value="Science">Science</option>
        <option value="Novel">Novel</option>
    </select>

    <select id="availability" onchange="filterBooks()">
        <option value="all">All Availability</option>
        <option value="Available">Available</option>
        <option value="Borrowed">Borrowed</option>
    </select>

    <div class="book-container">

        <div class="book" data-category="Programming"
             data-status="Available">
            <img src="https://placehold.co/120x160/203864/ffffff?text=Python"
                 alt="Python book cover">
            <h3>Python Basics</h3>
            <p>Author: John Smith</p>
            <p>Category: Programming</p>
            <p class="available">Available</p>
        </div>

        <div class="book" data-category="Science"
             data-status="Borrowed">
            <img src="https://placehold.co/120x160/287271/ffffff?text=Science"
                 alt="Science book cover">
            <h3>Our Universe</h3>
            <p>Author: David Brown</p>
            <p>Category: Science</p>
            <p class="borrowed">Borrowed</p>
        </div>

        <div class="book" data-category="Novel"
             data-status="Available">
            <img src="https://placehold.co/120x160/9b4d60/ffffff?text=Novel"
                 alt="Novel book cover">
            <h3>Dream World</h3>
            <p>Author: Emily Rose</p>
            <p>Category: Novel</p>
            <p class="available">Available</p>
        </div>

        <div class="book" data-category="Programming"
             data-status="Borrowed">
            <img src="https://placehold.co/120x160/775da6/ffffff?text=HTML"
                 alt="HTML book cover">
            <h3>HTML and CSS</h3>
            <p>Author: Mark Lee</p>
            <p>Category: Programming</p>
            <p class="borrowed">Borrowed</p>
        </div>

    </div>
</section>

<section id="catalog">
    <h2>Book Catalog</h2>

    <table>
        <tr>
            <th>Book ID</th>
            <th>Book Name</th>
            <th>Author</th>
            <th>Category</th>
            <th>Status</th>
        </tr>

        <tr>
            <td>101</td>
            <td>Python Basics</td>
            <td>John Smith</td>
            <td>Programming</td>
            <td>Available</td>
        </tr>

        <tr>
            <td>102</td>
            <td>Our Universe</td>
            <td>David Brown</td>
            <td>Science</td>
            <td>Borrowed</td>
        </tr>

        <tr>
            <td>103</td>
            <td>Dream World</td>
            <td>Emily Rose</td>
            <td>Novel</td>
            <td>Available</td>
        </tr>

        <tr>
            <td>104</td>
            <td>HTML and CSS</td>
            <td>Mark Lee</td>
            <td>Programming</td>
            <td>Borrowed</td>
        </tr>
    </table>
</section>

<section id="rules">
    <h2>Library Rules</h2>
    <ul>
        <li>Keep the library clean and quiet.</li>
        <li>Return books on time.</li>
        <li>Handle books carefully.</li>
        <li>Do not damage or lose books.</li>
        <li>Return books to the correct place.</li>
    </ul>
</section>

<footer>
    <p>© 2026 Digital Library Management System</p>
</footer>

<script>
    function filterBooks() {
        let search = document.getElementById("search")
            .value.toLowerCase();

        let category = document.getElementById("category").value;
        let status = document.getElementById("availability").value;

        let books = document.querySelectorAll(".book");

        books.forEach(function(book) {
            let text = book.innerText.toLowerCase();

            let matchSearch = text.includes(search);
            let matchCategory = category === "all" ||
                book.dataset.category === category;
            let matchStatus = status === "all" ||
                book.dataset.status === status;

            if (matchSearch && matchCategory && matchStatus) {
                book.style.display = "block";
            } else {
                book.style.display = "none";
            }
        });
    }
</script>

</body>
</html>
