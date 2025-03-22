<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blow Me Away</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* General Styles */
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #ffc8dd;
            color: #333;
        }

        /* Navigation Bar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(255, 255, 255, 0.9);
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            padding: 10px 15px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .logo a {
            font-size: 22px;
            font-weight: bold;
            text-decoration: none;
            color: #ffafcc;
            transition: 0.3s;
        }
        .logo a:hover {
            color: #a2d2ff;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 10px;
            padding: 0;
            margin: 0;
        }

        .nav-links li {
            display: inline-block;
        }

        .nav-links li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 8px 10px;
            transition: 0.3s;
        }

        .nav-links li a:hover {
            background: #ffafcc;
            border-radius: 5px;
            color: white;
        }

        /* Hero Section */
        .hero {
            height: 90vh;
            background: url('https://i.ibb.co/GwVJ4qM/head-img.jpg') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            color: white;
        }
        .hero .overlay {
            position: absolute;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }
        .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: #ffafcc;
            color: white;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        .hero .btn:hover {
            background: #ff79a6;
        }

        /* Doctors Section */
        .doctors {
            text-align: center;
            padding: 60px 20px;
            background: #ffafcc;
        }
        .doctor-list {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .doctor {
            background: white;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: 0.3s;
        }
        .doctor:hover {
            transform: scale(1.05);
        }

        /* Contact Form */
        .contact {
            padding: 60px 20px;
            text-align: center;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .form-group {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        label {
            font-weight: bold;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        textarea {
            resize: vertical;
        }
        .btn {
            padding: 12px;
            background: #ff79a6;
            color: white;
            font-size: 1rem;
            font-weight: bold;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ff4d7d;
        }

    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">
            <a href="#home">Blow Me Away</a>
        </div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#doctors">Doctors</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#appointment">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="overlay"></div>
        <div class="hero-content">
            <h1>Welcome to Blow Me Away</h1>
            <p>Your beauty, our passion.</p>
            <a href="#appointment" class="btn">Book an Appointment</a>
        </div>
    </section>

    <!-- Doctors Section -->
    <section id="doctors" class="doctors">
        <h2>Skin Surgeon Doctor</h2>
        <div class="doctor-list">
            <div class="doctor">
                <img src="https://img.freepik.com/premium-photo/indian-doctor-wearing-white-coat-with-stethoscope_85574-3676.jpg?w=2000" alt="Doctor 1">
                <h3>Prof. Dr. Shipra Maharana</h3>
                <p>Practicing medicine for over 18 years.</p>
            </div>
        </div>
    </section>

    <!-- Contact Form -->
    <section id="appointment" class="contact">
        <h2>Book An Appointment Now!</h2>
        <form class="contact-form" action="https://submit-form.com/a3Lyar1ru" method="POST">
            <div class="form-group">
                <label>Name*</label>
                <input type="text" name="name" required>
            </div>
            <div class="form-group">
                <label>Phone*</label>
                <input type="tel" name="phone" required>
            </div>
            <div class="form-group">
                <label>Email</label>
                <input type="email" name="email">
            </div>
            <div class="form-group">
                <label>Preferred Date*</label>
                <input type="date" name="date" required>
            </div>
            <div class="form-group">
                <label>Preferred Time*</label>
                <input type="time" name="time" required>
            </div>
            <div class="form-group">
                <label>Service Needed*</label>
                <select name="service" required>
                    <option value="">Select Service</option>
                    <option value="Hair Treatment">Hair Treatment</option>
                    <option value="Skin Care">Skin Care</option>
                    <option value="Facial">Facial</option>
                </select>
            </div>
            <div class="form-group">
                <label>Additional Notes</label>
                <textarea name="message" rows="4"></textarea>
            </div>
            <button type="submit" class="btn">Submit</button>
        </form>
    </section>

</body>
</html>
