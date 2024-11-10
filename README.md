
<html>
<head>
    <title>Penina Fernanda Agapa - Profile</title>
    <!-- Link ke Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f8ff;
            color: #374a63;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%; /* Buat lingkaran */
            object-fit: cover;
            display: block;
            margin: 0 auto 15px;
        }
        h1 {
            margin: 10px 0 5px;
            font-size: 26px;
            color: #374a63;
        }
        section {
            background-color: #ffffff;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(55, 74, 99, 0.1);
            display: none; /* Awalnya tersembunyi */
        }
        button {
            display: block;
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            background-color: #374a63;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #2c3c51;
        }
        .contact-info p {
            display: flex;
            align-items: center;
            margin: 5px 0;
        }
        .contact-info i {
            margin-right: 10px;
            color: #374a63;
        }
        .contact-info a {
            text-decoration: none;
            color: #374a63;
        }
    </style>
</head>
<body>
    <header>
        <img src="C:\Users\Lenovo\Pictures\WhatsApp Image 2023-11-27 at 11.51.32_7d43b533.jpg" alt="Penina Fernanda Agapa" class="profile-pic">
        <h1>Penina Fernanda Agapa</h1>
        <p>Student at Universitas Dinamika</p>
    </header>

    <button onclick="toggleSection('overview')">Overview</button>
    <section id="overview">
        <p>I am currently pursuing a Bachelor's degree in Information Systems at Universitas Dinamika. I possess a solid foundation in Microsoft Office, design skills with Canva, and experience in basic web development (HTML and basic CSS). Additionally, I have English language proficiency.</p>
    </section>

    <button onclick="toggleSection('achievements')">Achievements</button>
    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <li>Recipient of the Papua Superior Student Scholarship from the Central Papua Provincial Government.</li>
            <li>Assisted in teaching and creating websites for residents of Airlangga Village, Surabaya.</li>
            <li>Registered international guests for the World Bonsai Convention Event.</li>
        </ul>
    </section>

    <button onclick="toggleSection('contact')">Contact Information</button>
    <section id="contact" class="contact-info">
        <h2>Contact Information</h2>
        <p><i class="fas fa-envelope"></i>Email: peninanandaagapa@gmail.com</p>
        <p><i class="fas fa-phone"></i>Phone: 0812-4760-4318</p>
        <p><i class="fas fa-map-marker-alt"></i>Location: Semolowaru Selatan IX No. 1, Surabaya</p>
        <p><i class="fab fa-instagram"></i>Instagram: <a href="https://www.instagram.com/nnpx21" target="_blank">@nnpx21</a></p>
    </section>

    <script>
        function toggleSection(sectionId) {
            var section = document.getElementById(sectionId);
            section.style.display = section.style.display === "none" ? "block" : "none";
        }
    </script>
</body>
</html>
