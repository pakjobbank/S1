# S1
Main page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Pak Job Bank – Your Trusted Source for Latest Jobs in Pakistan. Find Government Jobs, Private Jobs, PPSC/FPSC, Army, Police, Teaching Jobs, and Internships daily.">
    <meta name="keywords" content="Pakistan Jobs, Today Jobs in Pakistan, Govt Jobs 2025, Pak Job Bank, FPSC Jobs, PPSC Jobs, Army Jobs, Police Jobs, Teaching Jobs, Internship Jobs">
    <meta name="author" content="Pak Job Bank">
    <title>Pak Job Bank – Latest Jobs in Pakistan</title>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

    <!-- CSS Styles -->
    <style>
        /* Reset & Basic Styling */
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }
        body { line-height: 1.6; color: #333; background-color: #f9f9f9; }
        a { text-decoration: none; color: inherit; }
        img { max-width: 100%; height: auto; }

        /* Header */
        header { background-color: #006400; color: #fff; padding: 15px 0; }
        header .container { display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: auto; padding: 0 20px; }
        header nav a { margin: 0 15px; font-weight: 500; color: #fff; }
        header nav a:hover { color: #00bfff; }

        /* Hero Section */
        .hero { background-color: #00bfff; color: #fff; text-align: center; padding: 80px 20px; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 20px; }
        .hero p { font-size: 1.2rem; margin-bottom: 30px; }
        .hero .btn { background-color: #006400; color: #fff; padding: 12px 30px; border-radius: 5px; font-weight: 500; transition: 0.3s; }
        .hero .btn:hover { background-color: #004d00; }

        /* Main Sections */
        .container { max-width: 1200px; margin: auto; padding: 20px; }
        h2.section-title { color: #006400; margin-bottom: 20px; text-align: center; }

        /* Job Cards */
        .job-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .job-card { background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 3px 6px rgba(0,0,0,0.1); }
        .job-card h3 { color: #006400; margin-bottom: 10px; }
        .job-card p { margin-bottom: 8px; font-size: 0.95rem; }
        .job-card a { display: inline-block; margin-top: 10px; background-color: #00bfff; color: #fff; padding: 8px 15px; border-radius: 5px; font-weight: 500; }
        .job-card a:hover { background-color: #0095cc; }

        /* Search Bar */
        .search-bar { text-align: center; margin-bottom: 40px; }
        .search-bar input { width: 60%; max-width: 400px; padding: 10px 15px; border-radius: 5px; border: 1px solid #ccc; }
        .search-bar button { padding: 10px 20px; background-color: #006400; color: #fff; border: none; border-radius: 5px; margin-left: 10px; cursor: pointer; }
        .search-bar button:hover { background-color: #004d00; }

        /* Footer */
        footer { background-color: #006400; color: #fff; text-align: center; padding: 20px; margin-top: 40px; }
        footer a { color: #fff; margin: 0 10px; font-size: 1.2rem; }
        footer a:hover { color: #00bfff; }

        /* Responsive */
        @media(max-width:768px) {
            .hero h1 { font-size: 2rem; }
            .search-bar input { width: 80%; }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <h2>Pak Job Bank</h2>
            </div>
            <nav>
                <a href="#">Home</a>
                <a href="#">Latest Jobs</a>
                <a href="#">Government Jobs</a>
                <a href="#">Private Jobs</a>
                <a href="#">PPSC/FPSC</a>
                <a href="#">Forces Jobs</a>
                <a href="#">Banking Jobs</a>
                <a href="#">About</a>
                <a href="#">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Pak Job Bank – Your Trusted Source for Latest Jobs in Pakistan</h1>
        <p>Stay updated with the latest Government Jobs, Private Jobs, PPSC/FPSC, Army, Police, Teaching Jobs, and Internship Opportunities in Pakistan.</p>
        <a href="#latest-jobs" class="btn">View Latest Jobs</a>
    </section>

    <!-- Search Section -->
    <section class="search-bar">
        <input type="text" placeholder="Search jobs by title, department, or category...">
        <button>Search</button>
    </section>

    <!-- Latest Jobs Section -->
    <section id="latest-jobs" class="container">
        <h2 class="section-title">Latest Jobs</h2>
        <div class="job-list">
            <!-- Example Job Card -->
            <div class="job-card">
                <h3>Assistant Manager – Banking Department</h3>
                <p><strong>Department:</strong> Banking</p>
                <p><strong>Vacancies:</strong> 5</p>
                <p><strong>Qualifications:</strong> MBA Finance / Relevant Degree</p>
                <p><strong>Age Limit:</strong> 25-35 years</p>
                <p><strong>Last Date:</strong> 30 November 2025</p>
                <a href="#">Apply Now</a>
                <a href="#" style="background-color:#006400;">Download PDF</a>
            </div>

            <div class="job-card">
                <h3>Teacher – Government School</h3>
                <p><strong>Department:</strong> Education</p>
                <p><strong>Vacancies:</strong> 10</p>
                <p><strong>Qualifications:</strong> B.Ed / M.Ed</p>
                <p><strong>Age Limit:</strong> 22-40 years</p>
                <p><strong>Last Date:</strong> 5 December 2025</p>
                <a href="#">Apply Now</a>
                <a href="#" style="background-color:#006400;">Download PDF</a>
            </div>
            <!-- Add more job cards dynamically -->
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Pak Job Bank | All Rights Reserved</p>
        <div>
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-linkedin-in"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </footer>

</body>
</html>
